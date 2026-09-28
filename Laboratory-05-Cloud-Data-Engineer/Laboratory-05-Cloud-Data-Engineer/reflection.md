# Mission Reflection

This laboratory activity helped me understand why cloud applications use different types of storage depending on their requirements. Object storage is better suited for storing millions of photos because it is designed for large amounts of unstructured data. Instead of treating every photo like a traditional disk block, object storage stores files as objects with metadata and unique identifiers inside buckets. This makes it practical for applications such as photo-sharing platforms where users continuously upload and retrieve images.

Using Docker also made deploying the MinIO storage server easier. Instead of manually installing and configuring all the required components, I was able to start MinIO using a Docker image and a single command. The environment variables allowed me to configure the administrator username and password, while the port mappings allowed me to access the MinIO service through the browser. This showed me how containers can make application deployment more consistent and convenient.

A bucket is a logical container used to organize objects in object storage. In this activity, I created a bucket called `client-photos`, which served as the storage location for the sample file that I uploaded.

Large enterprise companies can protect object storage data from physical server failures by using redundancy, replication, backups, and distributed storage systems. Instead of relying on only one physical server, copies of data can be stored across multiple disks, servers, or locations. This helps prevent data loss when hardware fails.

My confidence in navigating the Linux command line is also improving. At first, commands can look unfamiliar, especially when several options are included in one command. However, practicing Docker commands, checking running containers with `docker ps`, and understanding command options helped me become more comfortable working in the terminal. This activity showed me that understanding what each command does is more important than simply memorizing it.
