# SpringBoot-_ApacheKafka
SpringBoot _ApacheKafka Implementation with Producer and Consumer example

Start Zookeper command 
C:\@Software_n_tools\kafka_2.13-3.4.0\bin\windows C:\@Software_n_tools\kafka_2.13-3.4.0\config\zookeeper.properties

Start Kafka server command:
C:\@Software_n_tools\kafka_2.13-3.4.0\bin\windows C:\@Software_n_tools\kafka_2.13-3.4.0\config\server.properties

 
Create Kafka topic command:
C:\@Software_n_tools\kafka_2.13-3.4.0\bin\windows kafka-topics.bat --create --topic test-topic --bootstrap-server localhost:9092 --replication-factor 1 --partitions 4
