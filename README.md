## rbac for developer access to spesific namespace in cluster gke

### create rbac for developer only cna access to namespace staging
```
kubectl apply -f rbac.yml
```
### in gcp iam give user permission view only kubernetes
![alt text](https://i.imgur.com/LmYKRKE.png)


