# OpenAPI 사용법

```shell
curl --insecure -H "x-sap-filecontainer: c1c62fe6-39d5-40e2-a5d9-de2074363752" --cert ./client.crt \
--key ./client.key "https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com/webhdfs/v1/?op=LISTSTATUS" -X GET

curl --insecure -H "x-sap-filecontainer: c1c62fe6-39d5-40e2-a5d9-de2074363752" --cert ./client.crt \
--key ./client.key "https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com/webhdfs/v1/?op=WHOAMI" -X GET

curl --insecure -H "x-sap-filecontainer: c1c62fe6-39d5-40e2-a5d9-de2074363752" --cert ./client.crt \
--key ./client.key "https://c1c62fe6-39d5-40e2-a5d9-de2074363752.files.hdl.prod-ap12.hanacloud.ondemand.com/webhdfs/v1/?op=LISTSTATUS_RECURSIVE" -X GET
```
