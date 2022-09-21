# `kubectl-inline`
Kubectl plugin to quickly create Kubernetes' resources in your `$EDITOR`

### Usage
```sh
kubectl inline [flags] [resource type]
```

Some usable flags are:
* `-n|--namespace`: To specify a target namespace
* `-r|--recover`: To recover the last resource created with `kubectl-inline`
* `-r|--apply`: Apply to your cluster

Some resource types are:
* `cm`/`configmap`
* `secret`
* `svc`/`service`
