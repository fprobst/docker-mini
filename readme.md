
# Docker Mini

Änderung nur für Slack.

## Docker Hub

https://hub.docker.com/r/probstl/docker-mini/

`docker pull probstl/docker-mini`

## Docker Image erstellen

Erstellt das Docker Image auf Basis von node:7

`docker build -t docker-mini .`

## Docker Images anzeigen

`docker images`

## Docker Container starten

`docker run --name docker-mini-container -p 8080:8080 -d docker-mini`

## Laufende Container anzeigen

`docker ps`

## Details über den Container

`docker inspect docker-mini-container`

## Container Shell

`docker exec -it docker-mini-container bash`

## Container anhalten und beenden

`docker stop docker-mini-container`

`docker rm docker-mini-container`
