## Creating a pod Manifest

Simplest way to create a Pod

```
kubectl run kuard \
--image=gcr.io/kuar-demo/kuard-amd64:blue
```

Deploy pods with pod manifest

```
kubectl apply -f kuard-pod.yaml
```

## Health Check

Liveness health checks run application-specific logic (e.g., loading a web page)
This is to verify that the application is not just running, but is functioning properly

```
kuard-pod-health.yaml
```

Readiness describes when a container is ready to serve user requests

## Resource Management

Resource requests - Minimum amount of a resource required

```
kuard-pod-resreq.ymal
```

Resource limits - Maximum amount of a resource required

```
kuard-pod-reslim.ymal
```
