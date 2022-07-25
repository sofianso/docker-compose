# Docker Compose Learning Material

https://onedigital.udemy.com/course/docker-kubernetes-the-practical-guide/learn/lecture/22167052#notes

## What is Docker Compose?

Docker Compose allows multiple docker build and docker run in one configuration file. It will not replace Dockefile, images or containers.

## Start Docker Compose

```bash
docker-compose up
```

To start Docker Compose in detach mode

```bash
docker-compose up -d
```

## Delete Containers and Networks

```bash
docker-compose down
```

## Delete Containers, Networks and Volumes

```bash
docker-compose down -v
```
