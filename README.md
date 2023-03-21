### Kuberenetes Resources

Kubernetes resources are created with YAML files. Basic syntax is

```
apiVersion:
kind:
metadata:
    name:
spec:
```

To apply the resource you can run a command
```
kubectl apply -f [file-name].yaml
```
To delete the resource you can run a command
```
kubectl delete -f [file-name].yaml
```