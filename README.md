# Docker_Matomo_MySQL_Server

Docker: 18.09.3, build 774a1f4

MySQL: 8.0

Matomo: 3.8.1

## Docker

https://github.com/Huioqy/Docker_Start_Up

* Common Ops

      docker ps -a

      docker stop $(docker ps -q) & docker rm $(docker ps -aq)

      docker rmi [OPTIONS] IMAGE [IMAGE...]

      docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

      [OPTIONS]: -d     Run container in background and print container ID

                 -e     Set environment variables

                 --name Assign a name to the container

                 --link Add link to another container

                 -p     Publish a container’s port(s) to the host

## Docker-Compose-MySQL&Matomo

edit the docker-compose.yml

    docker-compose up

    docker-compose down
