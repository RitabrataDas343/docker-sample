# Docker

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
Docker status 
```
docker ps
docker ps -a
docker stop [CONTAINER ID]
docker image rm -f [Container Image]
```
Docker starring OS

```
docker pull ubuntu
docker run -it ubuntu
echo $0 -> home directory
apt list && history
```

```
docker build -t ctf1 .
docker run -dp 1337:22 ctf1
ssh user@localhost -p 1337
```
