# Debian 9 Ansible Test Image

[![GitHub Actions](https://github.com/MonolithProjects/docker-systemd-debian9/workflows/Dockerfile%20test/badge.svg?branch=master)](https://github.com/MonolithProjects/docker-systemd-debian9/actions)
[![DockerHub-size](https://img.shields.io/microbadger/image-size/monolithprojects/systemd-docker9/master)](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9)
[![DockerHub-layers](https://img.shields.io/microbadger/layers/monolithprojects/systemd-debian9)](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9)
[![DockerHub-pulls](https://img.shields.io/docker/pulls/monolithprojects/systemd-debian9)](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9)
[![DockerHub](https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-debian9?maxAge=2592000)](https://hub.docker.com/repository/docker/monolithprojects/systemd-debian9)

Debian 9 docker image (based on actual base image version). Contains built in `ansible` user with sudo privileges.
Dandy for using it with Molecule for Ansible role testing.

## Tags

- `latest`: Latest version of the image

## How-to

  1. Run command `docker pull monolithprojects/systemd-debian9:latest`  
  2. Run a container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-debian9:latest`  

## License

MIT

## Author Information

Created in 2020 by Michal Muransky
