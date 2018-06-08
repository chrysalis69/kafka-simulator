# Kafka-simulator
This is a simple docker compose config that spins up a kafka cluster.
It starts 1 zookeeper and 3 kafka brokers

Before running, edit `docker-compose.yml` and replace `KAFKA_ADVERTISED_HOST_NAME` value with your machine ip.

Before excuting commands inside container export `HOST_IP` in the container with your machine IP.
