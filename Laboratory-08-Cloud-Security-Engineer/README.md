# Laboratory 08 – The Cloud Security Engineer

## Mission Overview

This mission focuses on cloud server security by learning how to audit basic security principles, deploy a web server using Docker, and configure a host-based firewall using UFW. The activity demonstrates how proper firewall rules help protect a server from unauthorized network access.

## Objectives

- Understand the Principle of Least Privilege.
- Identify and reduce the server's attack surface.
- Apply a Default Deny Policy.
- Deploy an Nginx web server using Docker.
- Configure UFW firewall rules to control network traffic.
- Verify the web server and firewall configuration.
- Document the commands, results, and lessons learned.

## Commands Executed

### Check Docker

```bash
docker --version
docker ps
```

### Deploy the Nginx Web Server

```bash
docker run -d --name secure-web-app -p 8080:80 nginx
docker ps
curl http://localhost:8080
```

### Configure the Firewall

```bash
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 8080/tcp
sudo ufw status verbose
sudo ufw status numbered
curl -I http://localhost:8080
```

## Skills Learned

Through this mission, I learned how to deploy an Nginx web server with Docker, configure firewall rules with UFW, and control incoming and outgoing network traffic. I also learned why unnecessary open ports can increase security risks and why SSH access should be allowed before enabling the firewall. This activity improved my Linux command-line skills, troubleshooting, and cloud security awareness.

