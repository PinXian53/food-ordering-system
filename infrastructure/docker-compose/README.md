## Infrastructure

### Kafka (v7.8.0)

#### Docker-compose

##### start 
```shell
docker compose -f common.yml -f kafka_cluster.yml -f postgres.yml -p food-ordering-system up -d
```

##### show
```shell
docker compose -f common.yml -f kafka_cluster.yml -f postgres.yml -p food-ordering-system ps
```

##### stop
```shell
docker compose -f common.yml -f kafka_cluster.yml -f postgres.yml -p food-ordering-system down
```

##### stop and delete volume
```shell
docker compose -f common.yml -f kafka_cluster.yml -f postgres.yml -p food-ordering-system down -v
```
