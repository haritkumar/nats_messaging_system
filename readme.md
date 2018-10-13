![alt text](https://nats.io/img/large-logo.png)
## NATS
NATS Server is a simple, high performance open source messaging system for cloud native applications, IoT messaging, and microservices architectures.

### NATS server
NATS provides a lightweight server that is written in the Go programming language.


### Run server
```sh
docker run haritkumar/nats-server -p 4222:4222 -p 8222:8222 -p 6222:6222
client, management, and cluster ports
```
