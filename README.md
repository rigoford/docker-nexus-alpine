# docker-nexus-alpine

Gerrit docker image with additional plugins

## Usage

Available on [Docker Hub](https://hub.docker.com/r/rigoford/docker-nexus-alpine/):

```
docker pull rigoford/docker-nexus-alpine:alpha
```

To create a basic Nexus instance use:

```
docker run \
    --detach \
    --name nexus \
    --publish 8080:8081 \
    --restart always \
    rigoford/docker-nexus-alpine:alpha
```

