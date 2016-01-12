# docker-libsodium
Dockerfile for Docker Hub Automated Builds

libsodium Dockerfile
====================

This repository contains **Dockerfile** of [libsodium](https://download.libsodium.org/doc/) for 
[Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/jreckner/libsodium/) published 
to the public [Docker Hub Registry](https://registry.hub.docker.com/).

## Base Docker Image

* [Ubuntu 14.04.3](https://registry.hub.docker.com/u/library/ubuntu/)

## Pull image
```
docker pull jreckner/libsodium
```

## Run
```
docker run -it --rm jreckner/libsodium
```

## Build
```
docker build -t jreckner/libsodium .
```
