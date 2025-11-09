# arr-stack

docker-compose.yml for running the arr stack in Docker on Debian.

## Synopsis
This repository provides a Docker Compose configuration for deploying the *arr media automation services (such as Sonarr, Radarr, and related tools) on a Debian host.

## Refreshing the stack
Run the following command from the repository root to pull the latest images and restart the services with fresh containers:

```sh
docker compose pull --include-deps && docker compose down && docker compose up -d --force-recreate
```
