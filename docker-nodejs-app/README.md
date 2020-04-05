# Docker-based application written in node.js
This application use to show a start level example of docker-based application in node.js 


## Command to use 

To build docker image 

```
docker build -t melonyq/cloudmelonstartapp .
```


Run docker application

```
docker run -p 49160:8080 -d melonyq/cloudmelonstartapp
```


Check local docker images 

```
docker images
```


Get container ID and other useful information

```
docker ps
```


