# NoSQL Datahack Lab

Repo to build virtual machine for NoSQL Module Lab of Datahack BigData Master Class

## Sofware
### Service versions
* Zookeeper: 3.4.12
* Kafka: 2.0.0
* Cassandra: 3.11.3

### Docker images
* Kafka: https://hub.docker.com/r/bitnami/kafka/
* Zookeeper: https://hub.docker.com/r/bitnami/zookeeper/

## How to run

sudo /etc/systemd/system/nosqllab.service 
sudo systemctl daemon-reload
sudo systemctl enable nosqllab.service
sudo systemctl start nosqllab
sudo systemctl status nosqllab