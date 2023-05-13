# Kafka Go Application

This project is a simple application demonstrating how to produce and consume messages using Kafka in Go.

## Prerequisites

Before you begin, ensure you have met the following requirements:

* You have installed the latest version of [Go](https://golang.org/dl/) (1.17 or higher).
* You have a recent version of [Apache Kafka](https://kafka.apache.org/downloads) (2.8.0 or higher).
* You have installed the Go package [github.com/segmentio/kafka-go](https://github.com/segmentio/kafka-go).

## Installing Kafka Go Application

To install Kafka Go Application, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/mostwelcome/go-kafka.git
```

2. Navigate to the cloned repository:
```bash
cd your_repository
```
3. Install dependencies:
```bash
go mod tidy
```
Using Kafka Go Application:

1. Start your Kafka and Zookeeper servers.

2. Run the producer to send messages to Kafka:
go run kafka_producer.go

3. In a separate terminal, run the consumer to read messages from Kafka:
go run kafka_consumer.go

Contributing to Kafka Go Application:

To contribute to Kafka Go Application, follow these steps:

1. Fork this repository.
2. Create a branch: git checkout -b <branch_name>.
3. Make your changes and commit them: git commit -m '<commit_message>'
4. Push to the original branch: git push origin <project>/<location>
5. Create the pull request.

Contact:

If you want to contact me you can reach me at <duttaswagata4082018@gmail.com>.

