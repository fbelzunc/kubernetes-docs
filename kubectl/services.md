# Services

```
kubectl get svc
No resources found.
```

```
kubectl -n <NAMESPACE> expose deployment nginx-one
```

```
kubectl get svc
NAME        TYPE        CLUSTER-IP     EXTERNAL-IP   PORT(S)    AGE
nginx-one   ClusterIP   10.55.246.88   <none>        8080/TCP   5s
```

```
$ kubectl -n fbelzunc get ep nginx-one
NAME        ENDPOINTS                         AGE
nginx-one   10.52.7.24:8080,10.52.7.25:8080   2m
```
