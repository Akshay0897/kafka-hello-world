# kafka-hello-world
This is hello world application for apache kafka.

For windows: Install docker-desktop (https://www.docker.com/products/docker-desktop)
It will also install docker-compose.

For linux: todo

run docker-compose up in cmd.
run docker-compose ps to verify that zookeeper and broker services are running.

now run Kafka_Client project from solution.
then goto kafka-prodcuer folder run dotnet run from cmd.

now we have cosumer and producer running we will produce a message.

hit http://localhost:5002/api/kafka?message=Hello,World!"
you will see new logs written like "Message: Hello,kafka!" received from simpletalk_topic [[0]] @1" in consumer running cmd.

Congratulations you have successfully create hello, world app for kafka.

next: change soln. type from web-api to worker service for consumer.

