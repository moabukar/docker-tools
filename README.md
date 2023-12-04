# Docker tool

![docker-tools](https://github.com/moabukar/docker-tools/workflows/docker-tools/badge.svg?branch=main)
![Docker Pulls](https://img.shields.io/docker/pulls/moabukar/tools)
![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/moabukar/tools?sort=semver)

A simple docker image with various tools built-in. Example usage:

```bash
docker run --rm -it moabukar/tools:<tag> /bin/bash
# OR docker run --rm -it ghcr.io/moabukar/tools /bin/bash
```

Supported tags and respective Dockerfile links
----
- [`ubuntu2204`](https://github.com/moabukar/docker-tools/blob/main/Dockerfile.ubuntu2204)
- [`ubuntu2004`, `ubuntu`, `latest`](https://github.com/moabukar/docker-tools/blob/main/Dockerfile.ubuntu2004)
- [`ubuntu1804`](https://github.com/moabukar/docker-tools/blob/main/Dockerfile.ubuntu1804)
- [`alpine`](https://github.com/moabukar/docker-tools/blob/main/Dockerfile.alpine)

Supported arch
----
- x86-64 (aka. `linux/amd64` platform in Docker)
- ~armv7~
- armv8 (aka. `linux/arm64` platform in Docker)
