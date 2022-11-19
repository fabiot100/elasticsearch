# Elasticsearch

This repository contains some essential files that can be used for deploy the Elasticsearch container, using Swarm.

## Preparations

Rename the **env/elasticsearch.env_example** file to **env/elasticsearch.env** and change the parameters correctly.

## Deploy

To deploy the stack using Swarm, just follow the command below:

```shell
docker stack deploy --compose-file docker-compose.yml elasticsearch
```
