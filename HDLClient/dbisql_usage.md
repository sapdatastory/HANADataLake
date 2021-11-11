# dbisql 사용법

      dbisql -hdl -c "uid=HDLADMIN;pwd=Welcome01;host=1cb925ee-fc24-4b98-a022-b9fbe2933725.iq.hdl.trial-eu10.hanacloud.ondemand.com:443;ENC=TLS(tls_type=rsa;direct=yes)" select count(*) from RESERVATION

      dbisql -hdl -c "uid=HDLADMIN;pwd=Welcome01;host=1cb925ee-fc24-4b98-a022-b9fbe2933725.iq.hdl.trial-eu10.hanacloud.ondemand.com:443;ENC=TLS(tls_type=rsa;direct=yes)" sql.sql

      dbisql -hdl -c "uid=HDLADMIN;pwd=Welcome01;host=1cb925ee-fc24-4b98-a022-b9fbe2933725.iq.hdl.trial-eu10.hanacloud.ondemand.com:443;ENC=TLS(tls_type=rsa;direct=yes)" "select * from test02;"

      dbisql -hdl -c "uid=HDLADMIN;pwd=Welcome01;host=1cb925ee-fc24-4b98-a022-b9fbe2933725.iq.hdl.trial-eu10.hanacloud.ondemand.com:443;ENC=TLS(tls_type=rsa;direct=yes)" 'select * from test02'

      hdl@blizzard2:~> dbisql -hdl -c "uid=HDLADMIN;pwd=Welcome01;host=1cb925ee-fc24-4b98-a022-b9fbe2933725.iq.hdl.trial-eu10.hanacloud.ondemand.com:443;ENC=TLS(tls_type=rsa;direct=yes)" -nogui

      (HDLADMIN)> select * from test02
       id name   
      ----------
      100 France 
      200 한국   
      300 일본   
      400 중국   
      500 USA    

      (5 rows)


      (HDLADMIN)> quit

