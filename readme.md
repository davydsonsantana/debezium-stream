## Configure kubernetes namespace
1. Create namespace to use.
```sh
kubectl create namespace confluent
```
2. Set created namespace as default for your kubernetes context
```sh
kubectl config set-context --current --namespace rancher-desktop
```
