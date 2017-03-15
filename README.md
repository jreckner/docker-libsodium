# docker-libsodium
Dockerfile for Docker Hub Automated Builds

libsodium Dockerfile
====================

This repository contains **Dockerfile** of [libsodium](https://download.libsodium.org/doc/) for 
[Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/jreckner/docker-libsodium/) published 
to the public [Docker Hub Registry](https://registry.hub.docker.com/).

## Base Docker Image

* [Ubuntu 14.04.5](https://registry.hub.docker.com/u/library/ubuntu/)

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

License
=======

The MIT License (MIT)

Copyright (c) 2016 jreckner

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
