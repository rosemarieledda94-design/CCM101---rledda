# Mission 4: The Cloud-Native Engineer

## Mission Overview

This laboratory activity introduced Virtual Machines, containers, and Docker.
I deployed an Nginx web server using Docker and practiced managing its container lifecycle.

## Objectives

- Differentiate Virtual Machines and Containers.
- Access a Docker-enabled cloud environment.
- Execute fundamental Docker CLI commands.
- Pull, run, manage, and terminate an Nginx container.
- Document container operations using Markdown.

## Docker Commands Executed
docker --version
docker info
docker pull nginx
docker run -d -p 8080:80 --name nginx-server nginx
curl http://localhost:8080
docker ps
docker stop nginx-server
docker ps
docker rm nginx-server

## Skills Learned
Docker CLI commands
Container deployment
Nginx deployment
Port mapping
Container lifecycle management
Markdown documentation
GitHub portfolio management

### Challenges Encountered
One challenge was understanding the Docker commands and port mapping. I solved this by carefully following the commands and checking the terminal output after each step.




