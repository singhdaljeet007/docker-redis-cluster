# docker-redis-cluster


### Creating redis cluster

redis-cli --cluster create 10.160.0.28:7000 10.160.0.28:7001 10.160.0.98:7000 10.160.0.98:7001  10.160.0.16:7000 10.160.0.16:7001 --cluster-replicas 1
