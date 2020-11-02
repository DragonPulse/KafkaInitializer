# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.3.5.RELEASE/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.3.5.RELEASE/maven-plugin/reference/html/#build-image)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/2.3.5.RELEASE/reference/htmlsingle/#using-boot-devtools)

### Command For Executing
Docker-compose -f docker-compose.yml up -d

docker ps 
###COpy the ocntiner id of Kafka
docker exec -it containerId /bin/sh

ls

cd opt

cd bitnami

cd kafka

cd bin

ls


kafka-topics.sh --create  --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic billsummary

 kafka-topics.sh --list --zookeeper zookeeper:2181



###KAFKA UI 
docker run -it  -p 9000:9000 -e KAFKA_BROKERCONNECT=localhost:9092 obsidiandynamics/kafdrop

