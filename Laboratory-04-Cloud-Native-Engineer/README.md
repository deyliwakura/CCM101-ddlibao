# Laboratory 04 - The Cloud-Native Engineer

## Mission Overview

This laboratory introduces containerization and Docker. The activity compares Virtual Machines and containers and demonstrates how to deploy and manage an Nginx container.

## Objectives

- Differentiate Virtual Machines and Containers.
- Use Docker in a cloud-based Linux environment.
- Pull and run a Docker image.
- Deploy an Nginx web server.
- Manage the container lifecycle.
- Document Docker operations using Markdown.

## Docker Commands Executed

```bash
docker --version
docker info
docker pull nginx
docker run -d --name nginx-server -p 8080:80 nginx
docker ps
curl http://localhost:8080
docker stop nginx-server
docker ps -a
docker rm nginx-server
