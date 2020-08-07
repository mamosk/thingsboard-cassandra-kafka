# ThingsBoard MQTT

[ThingsBoard](https://thingsboard.io/) IoT platform
with [Cassandra](https://cassandra.apache.org/) database
and [Kafka](https://kafka.apache.org/) queue service,
for [MQTT](https://mqtt.org/) demos and tests.

## Get started

To spin up the services:

1. make sure you are using Linux or MacOS
   > to run Linux in Windows
   > you can use [WSL](https://docs.microsoft.com/windows/wsl/)
1. make sure you have
   [Docker](https://docs.docker.com/engine/) and
   [Docker Compose](https://docs.docker.com/compose/)
1. clone the repo
   — follow [this guide](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
1. run following commands:

   ```bash
   cd /path/to/the/repo # replace with actual path
   docker-compose up -d
   ```

1. open your ThingsBoard login page at **http://localhost:9090**
1. use following default credentials:
   - _system administrator_:
     - `sysadmin@thingsboard.org`
     - `sysadmin`
   - _tenant administrator_:
     - `tenant@thingsboard.org`
     - `tenant`
   - _customer user_:
     - `customer@thingsboard.org`
     - `customer`

## MQTT

To send MQTT messages:

1. open the [websocket client](http://www.hivemq.com/demos/websocket-client/)
   by [HiveMQ](https://www.hivemq.com/)
1. connect to the public broker: `broker.mqttdashboard.com`
1. publish messages to the topic: `mk/thingsboard`

---

Made with 🧡 by [Fabio Michelini](https://bit.ly/mich-cv)
