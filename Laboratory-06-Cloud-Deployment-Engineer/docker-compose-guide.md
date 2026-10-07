# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block is used to list the containers that Docker Compose will create and manage. Each service represents a container that is needed for the application. In this project, there are two services: **database** and **app**. The database service runs MariaDB, while the app service runs Nextcloud.

## How Does the Nextcloud App Find the Database?

The Nextcloud app finds the database by using the `MYSQL_HOST` environment variable. The value of this variable is set to **database**, which is the name of the MariaDB service. Because both containers are connected to the same Docker network, Nextcloud can communicate with MariaDB using this service name.

## `docker run` vs `docker-compose up -d`

The `docker run` command is usually used to create and start one container at a time. If there are many containers, we may need to enter several commands. Docker Compose makes this easier by using a YAML file where we can put the settings for all the services.

The `docker-compose up -d` command starts all the services defined in the YAML file. The `-d` option means that the containers will run in the background. This makes Docker Compose useful for applications that need multiple containers working together.
