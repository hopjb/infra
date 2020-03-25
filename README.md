# hopjb/infra

HOPJB infrastructure.

Currently holds https://hopjb.com + fastdl

Running on a single server with k3s

## Installing

```
curl -sfL https://get.k3s.io | sh -
k3s kubectl delete service traefik -n kube-system
k3s kubectl apply -k .
```
