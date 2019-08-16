# docker-swarm-monitor
simple configurations to run docker swarm monitor componentes including prometheus server and pre-configured scraping

## run
```bash
$ git clone https://github.com/opvizordz/docker-swarm-monitor.git
$ cd docker-swarm-monitor
docker stack deploy -c docker-compose.stack.yml docker-swarm-monitor
```

### check status
```bash
docker stack ls # show swarm stack deployments and status
docker service ls # show services
docker service logs -f <service> # check logs for debugging purpose
docker stack rm docker-swarm-monitor # remove the project
```

The following components are part of this project

## cAdvisor

## node Exporter

## dockerd-exporter

## Prometheus

