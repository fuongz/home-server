# Fuongz Home Server

## 1. Setup

### Traefik

1. Create `portainer` volume

```bash
docker volume create portainer_data
```

1. Run `docker-compose.yml` file

```bash
docker-compose -f docker-compose/traefik-portainer/docker-compose.yml up -d
```
