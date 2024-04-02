# Соусик
```
kubectl config get-contexts
kubectl config use-context k3s

ubectl apply -f .

kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml
kubectl get secret admin-user -n kubernetes-dashboard -o jsonpath={".data.token"} | base64 -d

kubectl proxy
```