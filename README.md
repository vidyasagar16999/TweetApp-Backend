# TweetApp-Backend


Step-1 : Start the Zookeeper using the below command in cmd

$	C:\kafka_2.12-2.8.1.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

Step-2 : Start the Kafka Server using the below command in cmd

$	C:\kafka_2.12-2.8.1.\bin\windows\kafka-server-start.bat .\config\server.properties

Step-3 : Execute the below command in cmd for creating Kafka Message

$	C:\kafka_2.12-2.8.1.\bin\windows\kafka-topics.bat -zookeeper localhost:2181 -topic tweetappNew --create --partitions 3 --replication-factor 1
