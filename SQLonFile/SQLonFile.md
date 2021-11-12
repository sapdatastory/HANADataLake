# SQL on File 예제

```shell
GRANT ROLE HDL_FILES_SERVICE_ADMIN TO USER1 WITH ADMIN OPTION;
--REVOKE ADMIN OPTION FOR ROLE HDL_FILES_SERVICE_ADMIN FROM USER1;


SELECT srvname FROM sysserver S 
	WHERE upper(S.srvclass) = 'FILES_SERVICE'

SELECT srvname FROM sysserver S 
	WHERE upper(S.srvclass) = 'FILES_SERVICE' 
	AND upper(S.srvname)= 'MY_SOF_SERVER';


--1. Create the server.
CREATE REMOTE SERVER MY_SOF_SERVER CLASS 'FILES_SERVICE'
	READ ONLY value 'on' ;
--DROP SERVER MY_SOF_SERVER;
--CALL sp_remote_schemas('MY_SOF_SERVER');


--2. Create the schema.
CREATE SCHEMA Factory IN FILES_SERVICE;
--DROP SCHEMA Factory IN FILES_SERVICE;


--3. Create the SQL on Files table.
CREATE TABLE IF NOT EXISTS Factory.nation 
(
	n_nationkey int,
	n_name char(25),
	n_regionkey int,
	n_comment char(152)
) IN FILES_SERVICE 
;
--DROP TABLE Factory.nation IN FILES_SERVICE;

--4. Create the virtual table.
CREATE EXISTING TABLE nation
(
	n_nationkey int,
	n_name char(25),
	n_regionkey int,
	n_comment char(152)
) AT 'MY_SOF_SERVER..Factory.nation';
--DROP TABLE nation;


--5. Add one or more datasources to the SQL on Files table.
ALTER TABLE Factory.nation IN FILES_SERVICE ADD DATASOURCE AS DS1 
CSV(webhdfs('hdlfs:///nation.tbl') )
ENCODING 'UTF_8';

ALTER TABLE Factory.nation IN FILES_SERVICE 
	DROP DATASOURCE ALL;

--List Table
CALL sp_remote_tables('MY_SOF_SERVER', null);
--List Virtual Table
SELECT * 
	FROM SYSPROXYTAB p,
		SYSTAB t, 
		SYSSERVER s 
	WHERE t.object_id = p.table_object_id
		AND s.srvid = p.srvid 
		AND upper(s.srvclass) = 'FILES_SERVICE'
;
--List Column
CALL sp_remote_columns('MY_SOF_SERVER', 'nation'); --Error
--List DataSource
CALL sp_remote_datasources('MY_SOF_SERVER');


--6. Execute queries on the virtual table.
REFRESH TABLE Factory.nation IN FILES_SERVICE;
REFRESH TABLE nation;
SELECT n_nationkey, n_name FROM nation;
SELECT * FROM nation;
```
