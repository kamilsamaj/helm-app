# helm-app
Simple Helm app

## Prerequisites
* Install
* Running Kind cluster with local registry
```bash
kind create cluster --name helm-app

```

## Steps
* Build Docker container
```bash

```

* Build Helm chart
```bash
helm create helloworld-chart
cd helloworld-chart
helm lint
```


