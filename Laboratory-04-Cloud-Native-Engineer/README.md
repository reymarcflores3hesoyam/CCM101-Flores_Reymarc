# Laboratory 04 – The Cloud-Native Engineer

## Mission Overview

Laboratory 04 focuses on cloud-native engineering, containerization, and Docker. The main goal of this activity is to understand the difference between traditional Virtual Machines and Containers and to experience the basic Docker workflow using the KillerCoda Ubuntu environment.

In this laboratory, I used the KillerCoda Playground to verify the Docker installation, download the official Nginx image, run an Nginx web server inside a container, test the web server using an HTTP request, and manage the container lifecycle. I also documented the commands and results using Markdown and organized the evidence screenshots in my GitHub Cloud Computing portfolio.

## Objectives

The objectives completed in this laboratory were:

- Differentiate traditional Virtual Machines from Containers.
- Understand the basic architecture of Virtual Machines and Containers.
- Compare the boot time of VMs and Containers.
- Compare the resource efficiency of VMs and Containers.
- Understand the different isolation levels of VMs and Containers.
- Access a Docker-enabled cloud environment using KillerCoda.
- Verify that Docker was installed and running.
- Execute fundamental Docker CLI commands.
- Pull the official Nginx image from Docker Hub.
- Run an Nginx container in detached mode.
- Map host port 8080 to container port 80.
- Test the Nginx web server using `curl`.
- List running Docker containers.
- Stop a running container.
- Verify that a container has stopped.
- Remove a Docker container.
- Verify that the container has been removed.
- Document the Docker procedures using Markdown.
- Organize laboratory screenshots and files in GitHub.

## Docker Environment

The Docker activities were performed using the KillerCoda Ubuntu Playground.

The environment used during the activity was:

- Operating System: Ubuntu 24.04.4 LTS
- Architecture: x86_64
- Docker Version: 29.1.3

## Docker Commands Executed

### Checkpoint 3 – Docker Verification

#### Check Docker Version

```bash
docker --version
