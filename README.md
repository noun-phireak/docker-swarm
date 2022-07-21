## Docker Swarm

<a href="https://www.bugsnag.com/blog/container-orchestration-with-docker-swarm-mode"></a>

A Docker Swarm is a group of either physical or virtual machines that are running the Docker application and that have been configured to join together in a cluster.

## Initialize Swarm

```bash

docker swarm init --advertise-addr IP Address

```
## Cluster

The Docker Swarm allows other servers to join the swarm cluster as workers, with the initialized swarm acting as a manager and the joint server acting as a node. A token is generated once the swarm manager is initialized. Simply copy the command when you successfully initialized the swarm.
- The command will look something like this:

```bash
docker swarm join --token SWMTKN-1-3pu6hszjas19xyp7ghgosyx9k8atbfcr8p2is99znpy26u2lkl-1awxwuwd3z9j1z3puu7rcgdbx 192.168.99.121:2377
```

