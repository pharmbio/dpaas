# dpaas
This is the Kubernetes yaml for a complete deployment of the dpaas service https://ptpaas.service.pharmb.io/

## Deploy
```
# Persistent Volume/Persistent Volume Claim
kubectl apply -f dpaas-pv-pvc.yaml

# Database
kubectl apply -f dpaas-mariadb.yaml

# Deploy models (pod/service/ingress for all models)
kubectl apply -f dpaas-receptor1.yaml
kubectl apply -f dpaas-receptor2.yaml
kubectl apply -f dpaas-receptor3.yaml
kubectl apply -f dpaas-receptor4.yaml
kubectl apply -f dpaas-receptor5.yaml
kubectl apply -f dpaas-receptor6.yaml
kubectl apply -f dpaas-receptor7.yaml

# Deploy upload pod-service-ingress
kubectl apply -f dpaas-uploadfile.yaml

# Web-gui
kubectl apply -f dpaas-cpvs-ui.yaml
```
## Remove:
```
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
