# Types of Cloud Storage

| Storage Type   | Description                                                                        | Primary Use Case                                         | Cloud Provider Example |
| -------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------- | ---------------------- |
| Block Storage  | Stores data in fixed-size blocks that can be accessed individually.                | Virtual machines, databases, and operating system disks. | AWS EBS                |
| File Storage   | Stores data as files in folders and directories that can be shared across systems. | Shared files and collaborative applications.             | AWS EFS                |
| Object Storage | Stores data as objects together with metadata and unique identifiers.              | Images, videos, backups, and other unstructured data.    | AWS S3                 |

## Why Object Storage?

Object Storage is a good choice for the client's photo-sharing application because it is designed to store large amounts of unstructured data such as images. It can organize and access many objects efficiently, making it suitable for applications that need to store millions of user-uploaded photos.
