# Nodes

## Get nodes with labels

```
kubectl get nodes --show-labels
```

## Add a label 

```
kubectl label node <nodename> <labelname>-=<labelname>-
```

## Remove a label

```
kubectl label node <nodename> <labelname>-
```

