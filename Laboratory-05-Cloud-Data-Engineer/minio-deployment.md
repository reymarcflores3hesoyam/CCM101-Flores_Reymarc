# MinIO Object Storage Deployment Documentation

## Overview

This document records the steps used to deploy an open-source, S3-compatible MinIO Object Storage server using Docker in the KillerCoda Ubuntu environment.

## Deployment Configuration

### 1. Docker Deployment Command

The following command was executed in the KillerCoda terminal to deploy the MinIO server:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
minio/minio server /data --console-address ":9001"
