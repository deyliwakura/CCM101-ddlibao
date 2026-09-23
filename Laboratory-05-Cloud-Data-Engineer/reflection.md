# Reflection

Object storage is better suited for storing millions of photos because it is designed for large amounts of unstructured data such as images, videos, and backups. Instead of storing everything inside a traditional hard drive, object storage organizes files as objects that can be accessed when needed.

Docker made it easier to deploy MinIO because I did not need to install and configure the storage server manually. I only needed to run a Docker command with the required image, ports, and environment variables. This made the deployment faster and more consistent.

A bucket is a storage container used to organize objects in cloud storage. In this activity, I created a bucket named `client-photos` where I uploaded a sample file. The bucket provides a specific place for storing the client's uploaded photos.

Large enterprise companies can protect their object storage data by keeping copies of data in different locations or servers. They can also use backups and replication so that data can still be recovered if a physical server fails. This helps reduce the risk of permanent data loss.

My confidence in using the Linux command line is improving. In this laboratory, I used commands such as `docker run`, `docker ps`, and `docker logs` to deploy and check the MinIO server. I also learned how Docker ports allow me to access a service through a web browser. Compared with my earlier activities, I am becoming more comfortable entering commands, checking results, and troubleshooting errors in the terminal.
