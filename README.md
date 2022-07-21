## Docker Swarm

<a href="https://www.bugsnag.com/blog/container-orchestration-with-docker-swarm-mode"></a>

A Docker Swarm is a group of either physical or virtual machines that are running the Docker application and that have been configured to join together in a cluster.

## Initialize Swarm

```bash

docker swarm init --advertise-addr IP Address

```
## Cluster

Docker swarm enable other server to join swarm cluster as a node the initialized swarm will act as a Manager and the joint server will be act as node

