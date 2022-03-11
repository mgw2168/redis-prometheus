# redis-prometheus
redis operator test.

# install redis operator

```yaml
helm install redis-operator ./redis-operator --namespace dmp-system
```

# install redis

```yaml
kubectl apply -f redis/redis-standalone.yaml
```

# install grafana

```yaml
kubectl apply -f grafana/grafana-on-k8s.yaml
```