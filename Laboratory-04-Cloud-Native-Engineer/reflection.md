# Reflection

Docker is faster to set up compared to installing a complete operating system on a virtual machine. With Docker, I can pull an image and run a container in only a few commands. A virtual machine usually needs more setup because it includes a complete guest operating system. This makes containers useful when applications need to be deployed quickly.

The port mapping `-p 8080:80` is necessary because it connects port 8080 on the host machine to port 80 inside the Nginx container. This allows me to access the Nginx web server through the host using `http://localhost:8080`. Without port mapping, the service inside the container may not be directly accessible from the host.

When I use `docker rm` to remove a container, the container itself is deleted. Any data stored only inside that container can also be lost. This shows why important application data should be stored using appropriate persistent storage instead of relying only on the container.

Containerization can make DevOps collaboration easier because applications can be packaged with their required environment and run consistently. Team members can use the same Docker image and commands, reducing differences between development and deployment environments.

My GitHub portfolio is also evolving as I add documentation, commands, screenshots, and reflections from each laboratory activity. Lab Activity 4 adds practical experience with Docker, Nginx, containers, and container lifecycle management. This helps demonstrate what I learned throughout the cloud computing activities.
