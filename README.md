# MeshCommander in Docker

![Lint](https://github.com/elliotmatson/meshcommander/actions/workflows/lint.yml/badge.svg)
![Docker Build](https://github.com/elliotmatson/meshcommander/actions/workflows/docker-image.yml/badge.svg)

Run [MeshCommander](http://www.meshcommander.com/meshcommander) inside Docker to provide a simple way to get access to Intel
AMT out-of-band management on Linux. MeshCommander is accessible on port 3000,
which is exposed by the container.

This repository is [vga101/meshcommander](https://hub.docker.com/r/vga101/meshcommander/), but set up to update automatically with dependabot, so it should always have an updated version of meshcommander

```
docker pull ghcr.io/elliotmatson/meshcommander:latest
```
