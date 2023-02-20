1. Apply namespace:
```
kubectl apply -f namespace.yaml
```

2. Install kube-prometheus-stack
```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm install kube-prometheus-stack prometheus-community/kube-prometheus-stack --version 37.3.0 -n monitoring -f values-prod.yaml
```
