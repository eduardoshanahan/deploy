# Docker image based in Python Fabric to automate deployments

A Docker image with scripts based in Python Fabric to simplify the deployment of my products in a remote server.

[TOC]

## Running an interactive session

```bash
docker build . --t eduardoshanahan/deploy:latest
docker run -it --rm eduardoshanahan/deploy
```

Or with Docker Compose

```bash
docker-compose run --rm shell
```

## Development

If you want to make some changes and version it, [bumpversion](https://pypi.python.org/pypi/bumpversion) is available

```bash
bumpversion patch
```
