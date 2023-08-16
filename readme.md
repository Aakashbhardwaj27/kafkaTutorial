[![npm version](https://img.shields.io/npm/v/kafkajs?color=%2344cc11&label=stable)](https://www.npmjs.com/package/kafkajs) [![npm pre-release version](https://img.shields.io/npm/v/kafkajs/beta?label=pre-release)](https://www.npmjs.com/package/kafkajs) [![Build Status](https://dev.azure.com/tulios/kafkajs/_apis/build/status/tulios.kafkajs?branchName=master)](https://dev.azure.com/tulios/kafkajs/_build/latest?definitionId=2&branchName=master) [![Slack Channel](https://join.slack.com/t/kafkajs/shared_invite/zt-1ezd5395v-SOpTqYoYfRCyPKOkUggK0Abadge.svg)](https://join.slack.com/t/kafkajs/shared_invite/zt-1ezd5395v-SOpTqYoYfRCyPKOkUggK0A)

<br />
<p align="center">
  <a href="https://kafka.js.org">
      <img src="https://raw.githubusercontent.com/tulios/kafkajs/master/logo/v2/kafkajs_circle.svg" alt="Logo" width="125" height="125">
  </a>

  <h3 align="center">KafkaJS</h3>

  <p align="center">
    A modern Apache Kafka® client for Node.js based Example
    <br />
    <a href="https://kafka.js.org/"><strong>Get Started »</strong></a>
    <br />
    <br />
    <a href="https://kafka.js.org/docs/getting-started" target="_blank">Read the Docs</a>
  </p>
</p>
# This is a node.js and Kafaka.js based implementation
- Kafka.js [Kafka](https://www.npmjs.com/package/kafkajs)

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

## Project Structure
   Consumer: Used to consume the messages
   Producer: Used to produce the messages

### Navigate to Producer
- Read About Producer : [Producer](https://kafka.js.org/docs/producer-example)
```
cd producer
npm install
npm start

```

### Navigate to Consumer
- Read About Consumer : [Consumer](https://kafka.js.org/docs/consumer-example)
```
cd consumer
npm install
npm start

```
