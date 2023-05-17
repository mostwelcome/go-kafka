# Kafka Go Application

This project exemplifies a straightforward application showcasing the process of producing and consuming messages through Kafka in Go.

## Prerequisites

Prior to initiation, it is imperative to verify that your system meets the prescribed prerequisites by ensuring the installation of the following requirements:

* Latest version of [Go](https://golang.org/dl/) (1.17 or higher).
* Recent version of [Apache Kafka](https://kafka.apache.org/downloads) (2.8.0 or higher).
* Recent version of [kafka-go](https://github.com/segmentio/kafka-go) (0.4.40 or higher)

## Installation

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
## Usage

1. Start your Kafka and Zookeeper servers.

2. Run the producer to send messages to Kafka:
go run kafka_producer.go

3. In a separate terminal, run the consumer to read messages from Kafka:
go run kafka_consumer.go

## Contribution

1. Fork this repository.
2. Create a branch:
```bash
git checkout -b <branch_name>.
```
3. Make your changes and commit them:
```bash
git commit -m '<commit_message>'
```
4. Push to the original branch:
```bash
git push origin <project>/<location>
```
5. Create the pull request using **relevant title, description and on-point commit messages**.

## Contact:

*To initiate contact with me regarding this application, feel free to reach out via [email](mailto:duttaswagata4082018@gmail.com?subject=Communication%20regarding%20Kafka%20Go%20Application).*
