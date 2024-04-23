# teastore-cco
This a ecommerce teastore that is used to demonstrate Cisco Cloud Observability 
1. Deploy with kubectl
```
kubectl create -f teastore-cco.yaml -n teastore
```
2. Check to see that there are 5 pods deployed
```
kubectl get pods -n teastore
```
3. Gather your URL so you can access the teastore to generate some load on the application.
```
kubectl get svc -n teastore
```
