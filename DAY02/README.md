#  消费者

```
bin/kafka-console-consumer.sh --bootstrap-server 192.168.0.217:9092   --topic topic-188562644 --group test_grp  --consumer-property enable.auto.commit=true --from-beginning
```



#  生产者


```
java -cp ./libs/*  dms.kafka.demo.KafkaProducerDemo 192.168.0.217:9092 topic-188562644

```

