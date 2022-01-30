# DOCKER COMMANDS

used to check docker installation and version

used to create and run a container from an image

used to list all the currently runing containers and theirs ids

used to list the history of all the containers that have run and theirs ids

used to create a container from an image

used to run an already-created container. Returns the id of the container

used to run an already-created container and "attach" to the terminal, so It watches for the output from the container and shows It in the terminal

```sh
docker version
docker run hello-world

docker run busybox
docker run busybox echo hello from container

docker ps

docker run busybox ping ww.google.com

docker ps --all

docker create <image_name>

docker start <container_id>

docker start -a <container_id>

```
