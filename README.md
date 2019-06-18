# postgres-node-example
docker swarm postgres master-slave replication with nodejs as front-end application

this example will require to setup your docker swarm cluster environment, you can use as many as nodes you want, 
but at least 2 nodes.

once you setup your swarm cluster, on the manager node run
docker stack deploy -c docker-stack.yml my-replication
