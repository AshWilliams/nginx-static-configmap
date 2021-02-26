# nginx-static-configmap


```
kubectl create ns prueba
kubectl create configmap endpoint-config --from-file=config.js -n prueba

kubectl apply -f .\mi-servicio.yaml -n prueba
```
