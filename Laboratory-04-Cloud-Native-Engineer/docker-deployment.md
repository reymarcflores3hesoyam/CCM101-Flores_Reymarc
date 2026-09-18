# Docker Deployment

## Mission 4 – The Cloud-Native Engineer

This document records the Docker commands executed during Laboratory 04 using the KillerCoda Ubuntu environment. The activity demonstrates the basic workflow of working with Docker containers, including verifying the Docker installation, downloading a container image, deploying an Nginx web server, testing the application, and managing the container lifecycle.

The main application used in this laboratory is Nginx. Nginx was deployed as a Docker container instead of being installed directly on the Ubuntu environment. This demonstrates how containerization can provide a lightweight and portable way of running applications.

---

# Checkpoint 3 – Enter the Docker Playground

## Docker Environment

The Docker activities were performed using the KillerCoda Ubuntu Playground. The environment provided an Ubuntu Linux terminal with Docker already installed.

The purpose of this checkpoint was to verify that Docker was installed and that the Docker environment was operational before deploying a container.

---

## 1. Check Docker Version

```bash
docker --version
