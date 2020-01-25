# dpaas
Kubernetes deployment yaml
```
# Deploy
kubectl apply -f dpaas-mariadb.yaml
kubectl apply -f dpaas-receptor1.yaml
kubectl apply -f dpaas-receptor2.yaml
kubectl apply -f dpaas-receptor3.yaml
kubectl apply -f dpaas-receptor4.yaml
kubectl apply -f dpaas-receptor5.yaml
kubectl apply -f dpaas-receptor6.yaml
kubectl apply -f dpaas-receptor7.yaml
kubectl apply -f dpaas-uploadfile.yaml
kubectl apply -f dpaas-cpvs-ui.yaml

# Remove:
kubectl delete -f dpaas-mariadb.yaml
kubectl delete -f dpaas-receptor1.yaml
kubectl delete -f dpaas-receptor2.yaml
kubectl delete -f dpaas-receptor3.yaml
kubectl delete -f dpaas-receptor4.yaml
kubectl delete -f dpaas-receptor5.yaml
kubectl delete -f dpaas-receptor6.yaml
kubectl delete -f dpaas-receptor7.yaml
kubectl delete -f dpaas-uploadfile.yaml
kubectl delete -f dpaas-cpvs-ui.yaml

```
URL: https://ptpaas-dpass.k8s-prod.pharmb.io/
