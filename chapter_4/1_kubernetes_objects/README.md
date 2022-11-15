##Creating, Updating and Destroying Kubernetes Objects

Create object

```
kubectl apply -f pod.yaml
```

Interactive edit

```
kubectl edit pods example-pod
```

Manipulate history of previous configuirations

```
kubectl apply -f pod.yaml view-last-applied
kubectl apply -f pod.yaml set-last-applied
kubectl apply -f pod.yaml edit-last-applied
```

Delete an object

```
kubectl delete -f pod.yaml
```

Delete with resource type and name

```
kubectl delete pods example-pod
```
