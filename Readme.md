# 📦 Docker Quick Reference Guide

:contentReference[oaicite:0]{index=0}

---

## 🔧 Setup & Info
```bash
docker version
docker info
docker --help
docker <command> --help
```
✅ Check installed versions and access built-in help

## 🖼 Images
```bash
docker build -t <your-image>:<tag> .
docker build --no-cache -t <image>:<tag> .
docker images
docker rmi <image>
docker image prune
docker login
docker push <user>/<image>
docker pull <image>
docker search <image>
```
✅ Build, tag, clean, and share images

## 🚀 Containers
```bash
docker ps        # list running containers
docker ps --all  # list all containers
docker start|stop <container>
docker rm <container>
docker exec -it <container> sh  # or bash
docker logs -f <container>
docker container stats
docker inspect <container>
docker system prune
docker network prune
```
✅ Manage, inspect, clean up containers 

## 🧽 Cleanup & Maintenance
```bash
docker image prune
docker system prune
docker network prune
```
✅ Remove unused images, networks, and containers 

::contentReference[oaicite:30]{index=30}