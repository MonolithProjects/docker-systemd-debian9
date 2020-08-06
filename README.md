# Debian 9 Ansible Test Image

[![GitHub Actions](https://github.com/MonolithProjects/docker-systemd-debian9/workflows/Dockerfile%20test/badge.svg?branch=master)](https://github.com/MonolithProjects/docker-systemd-debian9/actions)
[![DockerHub-layers](https://img.shields.io/microbadger/layers/monolithprojects/systemd-debian9)](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9)
[![DockerHub-pulls](https://img.shields.io/docker/pulls/monolithprojects/systemd-debian9)](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9)
[![DockerHub](https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-debian9?maxAge=2592000)](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9)

Docker image with debian9 and enabled systemd. Image contains also `ansible` user (UID/GID 1000) with NOPASSWD:ALL sudo rights.  
This docker image is ment to be used for development purpose. I do not recomend to use it in production.

## Tags

- `latest`  
- `<monthly build timestamp>` for the list of the tags see the [Docker Hub](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9/tags?page=1)

## How-to

  1. Run command `docker pull monolithprojects/systemd-debian9:latest`  
  2. Run a container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-debian9:latest`  

## License

MIT

## Author Information

Created in 2020 by Michal Muransky
