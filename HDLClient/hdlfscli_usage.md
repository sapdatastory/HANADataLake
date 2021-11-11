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
hdlfscli \
   -cert client.crt \
   -key client.key \
   -s https://${HDLFS_SERVER} \
   -config inst-1 \
   -dump-config \
   ls

# inst-1 configuration file
 {
   "configs": {
     "inst-1": {
       "timeout": 3000000000,
       "format": "text",
       "cert": "client.crt",
       "key": "client.key",
       "endpoint": "https://${HDLFS_SERVER}"
     }
   }
 }
 
hdlfscli -config inst-1 ls
hdlfscli -config inst-1 download file.txt
```

