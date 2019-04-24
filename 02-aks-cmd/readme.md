# Console Commands

```
kubectl run nginx --image=nginx
kubectl get pods
kubectl expose deployment nginx --port=80
kubectl get deployments,services
kubectl edit services/nginx
# Magic happens here: Change to LoadBalancer
kubectl get service -w
```