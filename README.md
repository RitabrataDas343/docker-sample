#Docker

Creating base using docker
```
docker build -t hello-docker .
docker image ls
docker run hello-docker
```
From Docker-Hub

```
docker pull vulnerabilities/web-dvwa
docker run --rm -it -p 8000:80 vulnerabilities/web-dvwa
```
