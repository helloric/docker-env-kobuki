# Docker environment for kobuki
ROS 2 humble docker environment for the kobuki base.

Based on the [packages build using docker as well](https://github.com/helloric/docker-kobuki-compile/)

## Usage
Just install docker-ce on your machine and pull the docker image.
Afterwards run the docker environment on your machine, thats easiest with docker compose, just run `docker compose up -d`.
You could also setup systemd to automatically start the image, however you probably want to use this project as base and create your own docker-compose file.