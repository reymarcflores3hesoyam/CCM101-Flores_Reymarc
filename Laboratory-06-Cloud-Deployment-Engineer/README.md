# Mission 6: The Cloud Deployment Engineer

## Mission Overview

In this mission, I learned how to deploy a private cloud storage system using Docker Compose. The system used **Nextcloud** for the web application and **MariaDB** for storing the database. I also learned how the two containers work together.

## Objectives

The main goals of this mission were to:

- Learn how a multi-tier application works.
- Create a Docker Compose YAML file.
- Set up and run Nextcloud and MariaDB containers.
- Use Docker Compose to manage multiple containers at the same time.
- Document the steps and commands used during the deployment using Markdown.

## Commands Used

During the activity, I used the following commands:

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

These commands were used to create the project folder, enter the folder, create and edit the Docker Compose file, start the containers, check their status, and stop the containers after completing the activity.
