# Docker-Compose with kafka cluster
Kafka cluster with 3 brokers for testing purposes with official images.

Requirements:
- Docker-Compose
- Docker

Startup with:

```
docker-compose up -d
```

Zookeeper Hosts:  
Internal Docker: zookeeper:2181  
External Docker: localhost:2181  

Broker hosts:  
Internal Docker: kafka-1:9092,kafka-2:9092,kafka-3:9092  
External Docker: localhost:29092,localhost:29093,localhost:29094  

Shutdown with:

```
docker-compose down
```


