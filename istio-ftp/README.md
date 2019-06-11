apply
```
  kubectl apply  -f ftp-deployment.yaml 
  kubectl apply  -f ftp-service.yaml 
  kubectl apply  -f ftp-virtualservice.yaml 
  kubectl apply  -f ftp-destionrule.yaml 
  kubectl apply  -f ftp-gateway.yaml 
```
testing

`sftp -P 31400 user@192.168.0.160`
