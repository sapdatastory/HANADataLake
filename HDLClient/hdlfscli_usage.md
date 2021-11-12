# hdlfscli 사용법

hdlfscli는 Data Lake IQ Client에 포함된 Data Lake Files을 위한 command-line 유틸리티입니다.
hdlfscli를 사용하면 File Container에 대한 작업을 실행할 수 있습니다.

Parameter
```shell
-s : file container endpoint
host
host:port
https://host:port
hdlfs://host

-cert : client certificate

-key : client key


-cacert : server certificate validation

-k : skip server certificate validation

-filecontainer : file container

-output : write the output into a file

-format : output format - JSON or TEXT

-pretty : Pretty print JSON results

-config : JSON configuration file
```

Configuration File 생성
```shell
# -config-file 파라미터 설정하지 않으면 default configuration file 생성
hdlfscli \
   -cert /home/hdl/hdl_files/client.crt \
   -key /home/hdl/hdl_files/client.key \
   -s https://${HDLFS_SERVER} \
   -config hdlfs1 \
   -dump-config \
   ls

# default configuration file : $HOME/.hdlfscli.config.json
cat .hdlfscli.config.json
{
  "configs": {
    "hdlfs1": {
      "timeout": 3000000000,
      "format": "text",
      "cert": "/home/hdl/hdl_files/client.crt",
      "key": "/home/hdl/hdl_files/client.key",
      "user": "",
      "role": "",
      "endpoint": "https://${HDLFS_SERVER}"
    }
  }
}

hdlfscli -config hdlfs1 ls
hdlfscli -config hdlfs1 cat file_hldfs.csv | hdlfscli -config hdlfs1 download file_hldfs.csv
hdlfscli -config hdlfs1 upload README_local.md README_hdlfs.md
hdlfscli -config hdlfs1 upload README_local.md tmp/README_hdlfs.md --tmp 디렉토리 생성 후 파일 적재
hdlfscli -config hdlfs1 -output file_local.txt download file_hdlfs.txt
```

add File into File Container
```shell
hdlfscli \
	-cert client.crt \
	-key client.key \
	-cacert rootca.crt \
	-s https://${HDLFS_SERVER} \ 
	-filecontainer ${HDLFS_FILE_CONTAINER} \ 
	upload README.md tmp/README.md

hdl@blizzard2:~/hdl_files> hdlfscli \
> -cert client.crt \
> -key client.key \
> -s https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com \
> -filecontainer c1c62fe6-39d5-40e2-a5d9-de2074363752 \
> upload README.md README.md
{"Location":"https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com/webhdfs/v1/README.md"}
```

download File from File Container
```shell
hdlfscli 
	-cert client.crt 
	-key client.key 
	-cacert rootca.crt 
	-format text 
	-output /tmp/README_COPY.md 
	-s https://${HDLFS_SERVER} 
	-filecontainer ${HDLFS_FILE_CONTAINER} 
	download tmp/README.md
```

delete File from File Container
```shell
hdlfscli 
	-cert client.crt 
	-key client.key 
	-cacert rootca.crt 
	-format json 
	-pretty 
	-s ${HDLFS_SERVER} 
	-filecontainer ${HDLFS_FILE_CONTAINER} 
	rm tmp/README.md tmp/README2.md
```

list File in File Container
```shell
hdlfscli 
	-cert client.crt 
	-key client.key 
	-cacert rootca.crt 
	-s ${HDLFS_SERVER} 
	-filecontainer ${HDLFS_FILE_CONTAINER} 
	ls tmp
   
hdlfscli 
	-cert client.crt 
	-key client.key 
	-cacert rootca.crt 
	-format json 
	-pretty 
	-s https://${HDLFS_SERVER} 
	-filecontainer ${HDLFS_FILE_CONTAINER} 
	list tmp   
```

move File in File Container
```shell
hdlfscli 
	-cert client.crt 
	-key client.key 
	-cacert rootca.crt 
	-format json 
	-pretty 
	-s https://${HDLFS_SERVER} 
	-filecontainer ${HDLFS_FILE_CONTAINER} 
	mv tmp/README.md /tmp/README2.md
```

# OpenAPI(curl) 사용법

```shell
curl --insecure -H "x-sap-filecontainer: c1c62fe6-39d5-40e2-a5d9-de2074363752" --cert ./client.crt \
--key ./client.key "https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com/webhdfs/v1/?op=LISTSTATUS" -X GET

curl --insecure -H "x-sap-filecontainer: c1c62fe6-39d5-40e2-a5d9-de2074363752" --cert ./client.crt \
--key ./client.key "https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com/webhdfs/v1/?op=WHOAMI" -X GET

curl --insecure -H "x-sap-filecontainer: c1c62fe6-39d5-40e2-a5d9-de2074363752" --cert ./client.crt \
--key ./client.key "https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com/webhdfs/v1/?op=LISTSTATUS_RECURSIVE" -X GET

```
