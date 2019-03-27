# Docker_Matomo_MySQL_Server

Docker: 18.09.3(774a1f4) & 2.0.0.3(31259)

MySQL: 8.0

Matomo: 3.9.1

Apache: https://hub.docker.com/r/bitnami/apache/

OS: Ubuntu 16.04, MacOS 10.14.4, CentOS 7


## Docker-Compose-MySQL & Matomo & Apache

* Edit the docker-compose.yml

1. Create mysql database for Matomo

2. Inisitalize Matomo on port 4000, the name of database service should be the service name of mysql database
 (i.e., db)

3. Start an apache server for the websites

        docker-compose up

        docker-compose down
