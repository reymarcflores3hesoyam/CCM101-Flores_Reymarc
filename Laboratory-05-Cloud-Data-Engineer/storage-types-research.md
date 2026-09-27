# Cloud Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type       | Description                                                              | Primary Use Case                                       | Cloud Provider Example |
| ------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------ | ---------------------- |
| **Block Storage**  | Stores data in separate blocks and works like a virtual disk.            | Operating systems, databases, and applications.        | Amazon EBS             |
| **File Storage**   | Organizes data into files and folders that can be shared over a network. | Shared files and applications that need a file system. | Amazon EFS             |
| **Object Storage** | Stores data as objects with metadata and unique identifiers.             | Photos, videos, backups, and other large files.        | Amazon S3 / MinIO      |

## Why Object Storage for User-Uploaded Photos?

Object Storage is suitable for storing user-uploaded photos because it can handle large amounts of data and scale easily. It also allows photos to be stored with metadata and unique identifiers, making them easier to manage and access.

