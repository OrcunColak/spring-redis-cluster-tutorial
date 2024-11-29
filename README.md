# Crete cluster

```
redis-cli --cluster create \
redis-node-1:6379 \
redis-node-2:6379 \
redis-node-3:6379 \
--cluster-replicas 0
```

# Check cluster state

```
redis-cli -c -h redis-node-1 -p 6379 cluster info
```

# Swagger UI
http://localhost:8080/swagger-ui/index.html