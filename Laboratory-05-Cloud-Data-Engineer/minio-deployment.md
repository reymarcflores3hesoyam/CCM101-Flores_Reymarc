# MinIO Object Storage Deployment

## Overview

This document describes the deployment of MinIO using Docker in KillerCoda.

## Deployment

### 1. Docker Command

docker run -d -p 9000:9000 -p 9001:9001 --name minio-server -e "MINIO_ROOT_USER=cloudadmin" -e "MINIO_ROOT_PASSWORD=CloudNova2026!" minio/minio server /data --console-address ":9001"

### 2. Ports

Port **9000** – MinIO API
Port **9001** – Web Console

### 3. Environment Variables

`MINIO_ROOT_USER` and `MINIO_ROOT_PASSWORD` set the administrator credentials.

### 4. Bucket

A bucket named **client-photos** was created, and a sample file was uploaded.
