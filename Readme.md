# 📦 Docker Quick Reference Guide

## 🔧 Setup & Info

```markdown
docker version
docker info
docker --help
docker <command> --help
```
✅ Check installed versions and access built-in help

## 🖼 Images

```markdown
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

```markdown
docker ps
docker ps --all
docker start|stop <container>
docker rm <container>
docker exec -it <container> sh
docker logs -f <container>
docker container stats
docker inspect <container>
docker system prune
docker network prune
```
✅ Manage, inspect, clean up containers 

## 🧽 Cleanup & Maintenance

```markdown
docker image prune
docker system prune
docker network prune
```
✅ Remove unused images, networks, and containers