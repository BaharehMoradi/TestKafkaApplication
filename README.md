# testcontainers-kafka-java-demo

## Tutorial Scenario
For this tutorial, suppose you’re working at a planet-monitoring company that develops applications for monitoring incidents such as floods, earthquakes, forest fires, and similar disasters. The company is developing an earthquake notification system that creates notification requests and collects and logs them in a Google Maps location URL format.
Your job is to take over the earthquake-notifier and earthquake-collector applications that were developed as prototypes. Once you take them over, you realize that neither application has any written tests. Because both applications use Apache Kafka, using Testcontainers will work well.
The tests must validate that the applications can send notification data to an Apache Kafka instance and receive the same data from it. The Kafka instance must be created and managed within the tests by using Testcontainers.

## Prerequisites
To follow along with this tutorial, you need the following:

- Java 17
- A recent version of Docker (this article uses Docker Desktop 4.6.1.)
- Maven 3.6.2+
- A recent version of the Git

Complete explanation of the project:
https://www.atomicjar.com/2023/06/testing-kafka-applications-with-testcontainers/
