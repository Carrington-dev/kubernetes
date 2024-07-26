# kubernetes
kubernetes Tutorial From Beginner To Advanced Notes 

## To Apply Or Create Items


### Config Maps
```bash
kubectl apply -f file_name.yaml
```
### Describe Config Maps

```bash
kubectl describe configmap <configmap_name>
```

### Secret Keys

1. Convert secrets to base64
```bash
echo -n 'admin' | base64
```
2. Create secrets
```bash
kubectl apply -f file_name.yaml
```

3. Get secrets
```bash
kubectl get secrets
```
Describe
```bash
kubectl describe secret <secret_name>
```

## Environment Demo Config Maps


## Environment Demo Secret Keys