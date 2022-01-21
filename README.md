# Monitoring

Deployement monitoring service with Grafana, Prometheus, Node exporter, Cadvisor and traefik

## Dependency

[Traefik v2 configuration](https://github.com/mbeurel/traefik)

## Config

**Copy environnement file**
```bash
cp .env.dist .env
```

**Edit environnement file**
```bash
vi .env
```
_Enter your parameters_


**Copy docker-compose file**
```bash
cp docker-compose.dist.yaml docker-compose.yaml
```

**Edit docker compose file**
```bash
vi docker-compose.yaml
```
_Enter your parameters_


**Copy prometheus config file**
__config/prometheus/prometheus.dist.yaml__
```bash
cp config/prometheus/prometheus.dist.yaml config/prometheus/prometheus.dist.yaml
```

**Edit docker compose file**
```bash
vi docker-compose.yaml
```
_Enter your parameters_

**Start Docker composer**
```bash
docker-compose up # -d to detach container
```