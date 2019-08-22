# [Flux Chart](https://github.com/fluxcd/flux/tree/master/chart/flux)

## To Install
Add the Weaveworks repo:
```
helm repo add fluxcd https://charts.fluxcd.io
```

Install the chart with our customized values
```
helm install -n flux -f values.yaml fluxcd/flux
```