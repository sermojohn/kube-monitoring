1. Install goldilocks
```
helm repo add fairwinds-stable https://charts.fairwinds.com/stable
helm repo update
helm install goldilocks fairwinds-stable/goldilocks --version 6.1.2 -n monitoring -f values.yaml
```
