# Kafka structure

Kafka has producers, topics, partitions and consumers.

### Kafka Architecture

<img width="1093" alt="Screenshot 2024-12-16 at 7 47 43 PM" src="https://github.com/user-attachments/assets/f74dbe22-acdd-41d8-9f64-d80c6aedc6ea" />

-> Kafka has topics, Each topic has partitions.

-> we can have consumer groups, these consumer groups can have many consumers.

-> One consumer can consume many partitions BUT two consumers can not try to consume one partition in a single Consumer group.

-> we can use kafka as Queue ans pubsub both,
-> in Queue we have one producer and one consumer, In PubSub we have one producer and many consumer.

--> Using as Queue:- If no. of partition = no. of consumers then it each partition will have its consumer i.e. it will work like a queue
