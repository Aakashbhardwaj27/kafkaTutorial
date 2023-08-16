# Kafka Tutorial: Producer and Consumer Setup with Docker

This tutorial provides a step-by-step guide to setting up a Kafka producer and consumer using Docker containers. Apache Kafka is a powerful distributed event streaming platform commonly used for building real-time data pipelines and streaming applications.

## Prerequisites

Before you begin, ensure you have the following:

- Docker installed: [Get Docker](https://www.docker.com/get-started)

## Setting up the Kafka Environment







```
export HOST_IP=$(ifconfig | grep -E "([0-9]{1,3}\.){3}[0-9]{1,3}" | grep -v 127.0.0.1 | awk '{ print $2 }' | cut -f2 -d: | head -n1)
docker-compose up
```
