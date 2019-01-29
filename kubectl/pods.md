# Pods

## Get pods per label

```
kubectl get pods -l app=nginx --all-namespaces
```

## Execute command in a container

```
kubectl exec -it busybox -c busybox-1 -- touch directory/file.txt
```