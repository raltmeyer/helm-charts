# helm-charts


## Update helm packages and github pages

### Create the package
```
helm package charts/test-chart
```

### Update the index
```
helm repo index . --url https://raltmeyer.github.io/helm-charts/
```

commit to repo

## how to access the pages

https://raltmeyer.github.io/helm-charts/

https://raltmeyer.github.io/helm-charts/index.yaml


## Use the helm charts

```
helm repo add raltmeyer https://raltmeyer.github.io/helm-charts/

helm repo update

helm install <release-name> raltmeyer/test-chart

```
