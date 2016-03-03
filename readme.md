## Introduction
This is a Dockerfile to build a container image for mongo db

## Git repository
The source files for this project can be found here: https://github.com/taladocker/mongo

## Pulling from Docker Hub
Pull the image from docker hub rather than downloading the git repo. This prevents you having to build the image on every docker host:

```
docker pull tala/mongo
```