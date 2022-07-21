## Docker Swarm

<a href="https://www.bugsnag.com/blog/container-orchestration-with-docker-swarm-mode"></a>

A Docker Swarm is a group of either physical or virtual machines that are running the Docker application and that have been configured to join together in a cluster.

## Initialize Swarm

```bash

docker swarm init --advertise-addr IP Address

```
## Cluster

Docker swarm enable other server to join swarm cluster as a worker the initialized swarm will act as a Manager and the joint server will be act as node, token will be generated once you initialized the Swarm manager. Simply copy the command when you successfully initialized swarm.
- The command will look something like this:

```bash
docker swarm join --token SWMTKN-1-3pu6hszjas19xyp7ghgosyx9k8atbfcr8p2is99znpy26u2lkl-1awxwuwd3z9j1z3puu7rcgdbx 192.168.99.121:2377
```

