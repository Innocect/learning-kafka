# learning-kafka
Learning Kafka using golang


#### Basic kafka commands ####

# To go inside Kafka container in Docker, using interactive mode
1. `docker exec -it kafka[container name] /bin/sh`
2. cd opt/kafka/bin/
3. ls
# create a topic
4. ./kafka-topics.sh --create --zookeeper zookeeper:2181 --partitions 1 --replication-factor 1 --topic test
# listing a topic
5. ./kafka-topics.sh --list --zookeeper zookeeper:2181

#### GoLang steps ####