# MinIO Object Storage Deployment Documentation

Overview

This document records the steps used to deploy an open-source, S3-compatible MinIO Object Storage server using Docker in the KillerCoda Ubuntu environment.

Deployment Configuration

1. Docker Deployment Command

The following command was executed in the KillerCoda terminal to deploy the MinIO server:

docker run -d -p 9000:9000 -p 9001:9001 --name minio-server 
-e "MINIO_ROOT_USER=cloudadmin" 
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" 
minio/minio server /data --console-address ":9001"

2. Port Configuration

Port 9000 was used for the MinIO API, while port 9001 was used for the MinIO Web Console. The Web Console was accessed through port 9001 using a web browser.

3. Environment Variables

The -e options were used to configure the MinIO administrator credentials. MINIO_ROOT_USER sets the administrator username to cloudadmin, while MINIO_ROOT_PASSWORD sets the administrator password to CloudNova2026!.

4. Bucket Configuration

A bucket named client-photos was created through the MinIO Web Console. A sample file was uploaded to the bucket to verify that the Object Storage service was working correctly.

This covers the required documentation for the Docker command, Web Console port, bucket name, and environment variables. 
