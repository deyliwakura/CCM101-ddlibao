# Docker Compose Guide

## Services

The `services:` block defines the containers used in the application. In this activity, the services are MariaDB for the database and Nextcloud for the web application.

## Database Connection

Nextcloud finds the MariaDB database using the `MYSQL_HOST=database` environment variable. The value `database` refers to the database service name in the Docker Compose file.

## Docker Run vs Docker Compose

`docker run` is used to create and run individual containers manually. `docker-compose up -d` uses the YAML configuration to create and start multiple related containers together.
