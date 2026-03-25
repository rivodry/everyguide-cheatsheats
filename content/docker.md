# Docker Cheatsheet

## Basic Commands
- `docker build -t <name> .` - Build image
- `docker run -p 8080:80 <name>` - Run container
- `docker ps` - List running containers

## Images
- `docker images` - List images
- `docker rmi <image>` - Remove image
- `docker pull <image>` - Pull from registry

## Containers
- `docker stop <id>` - Stop container
- `docker rm <id>` - Remove container
- `docker logs <id>` - View logs

## Docker Compose
- `docker-compose up` - Start services
- `docker-compose down` - Stop services
