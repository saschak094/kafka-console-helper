#Kafka

## Change directory into: 
```cd /usr/hdp/current/kafka-broker/bin```

## Create a Kafka Topic: 
``` ./kafka-topics.sh --zookeeper 127.0.0.1 --create --topic <name>  --partitions <partitions> --replication-factor <replication_factor>```

## Produce messages using the command line tools: 
```./kafka-console-producer.sh --broker-list data1.hdp.com:6667 --topic abc ```

###Consume messages using the commandline tools: 
```./kafka-console-consumer.sh --bootstrap-server data2.hdp.com:6667 --topic abc ```