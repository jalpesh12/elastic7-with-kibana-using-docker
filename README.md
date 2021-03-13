# elastic7-with-kibana-using-docker
Elastic 7 with Kibana using docker

## Installing Elasticsearch 7 with Kibana using Docker Compose

This repo includes a docker-compose.yml file that can be used for setting up a single node Elasticsearch 7 cluster along with Kibana

### Pre-Requisites
- Install Docker engine. I would recommend the official site https://docs.docker.com/engine/install/
- Install Docker compose. For this also, I would recommend official site https://docs.docker.com/compose/install/

Once you have install both Docker and Docker Compose and ensured that Docker engine is running, clone this repo and from the project's root directory, run:

```
docker-compose up -d
```

This should bring up the Elasticsearch and Kibana containers. You can verify by running:

```
docker-compose ps
```


The output should list both the containers and their status should be `Up`.