# hdlfscli 사용법

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

