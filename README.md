# (WIP) dind

DinD (Docker in Docker) is a way to run Docker inside **privileged** Docker container. 

But it requires a [hack](https://github.com/moby/moby/blob/master/hack/dind).

There is DinD in the official [docker](https://hub.docker.com/_/docker) image on Docker Hub, but it uses Alpine.
This repository will contains DinD implementations but with other Linux distribution that I would use personally.
