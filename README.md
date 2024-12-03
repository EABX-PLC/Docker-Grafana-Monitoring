# Docker Grafana Monitoring

Docker for Grafana Monitoring Setup for EABX.

## Installation.

### Windows server using CMD or PowerShell and Podman.

#### 1. Clone the repo.

```CMD

```

```CMD
# Change directory to location of grafana-docker-compose.yaml
cd <PATH>

# Setup Grafana image in Podman.
podman compose --project-name grafana-monitoring --file grafana-docker-compose.yaml up --detach
```

## Refereces.

1. [grafana.com](https://grafana.com/).
2. [Releases](https://grafana.com/grafana/download?edition=oss)
3. [Docker images](https://hub.docker.com/r/grafana/grafana/tags)
4. [Grafans Plugins](https://grafana.com/grafana/plugins/)
