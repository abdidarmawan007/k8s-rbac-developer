## RBAC for developer access to spesific namespace (for example staging) in cluster gke
![alt text](https://i.imgur.com/4hPG81Z.png)


### create rbac for developer only cna access to namespace staging
```
kubectl apply -f rbac.yml
```
### in gcp iam give user permission view only kubernetes
![alt text](https://i.imgur.com/LmYKRKE.png)


