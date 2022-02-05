# Kafka_Zookeeper

```
./zkServer.sh start
./kafka-server-start.bat ../../config/server.properties

./kafka-topics.bat --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic test-creation

./kafka-console-producer.bat --bootstrap-server localhost:9092 --topic test-creation
```
