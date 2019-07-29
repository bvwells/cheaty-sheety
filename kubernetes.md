# Random kubernetes commands I forgety

##  Interacting with clusters

Get cluster information:
```
kubectl cluster-info
```

## Interacting with running pods

Attempt to exec command against running pod:
```
kubectl exec -v=10  -n namespace pod_name -- "ls /"
```

Print logs for running pod:
```
kubectl logs pod_name    
```

## Getting resources

Get all services in a namespace:
```
kubectl get -n namespace services
```

Get all deployments in a namespace:
```
kubectl get -n namespace deployments
```

Get all pods in a namespace:
```
kubectl get -n namespace pods
```

Get yaml for pod in a namespace:
```
kubectl get -n namespace pod pod_name -o yaml
```

## Creating resouces

Create resource defined in yaml:
```
kubectl apply -f kube.yaml
```