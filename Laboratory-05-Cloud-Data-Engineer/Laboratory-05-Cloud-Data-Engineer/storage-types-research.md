# Research: Types of Cloud Storage

| Storage Type | Description (How does it store data?) | Primary Use Case | Cloud Provider Example |
|--------------|----------------------------------------|------------------|------------------------|
| **Block Storage** | Splits data into fixed-size blocks, each with its own address. It is attached to a single server like a virtual hard drive, and the operating system formats it with a file system. | Operating system disks, databases, and applications needing low-latency, high-performance storage. | AWS EBS (Elastic Block Store) |
| **File Storage** | Stores data as files in a hierarchy of folders and directories, shared over a network using protocols such as NFS or SMB. | Shared drives, home directories, content management, and applications where many servers need the same files. | AWS EFS (Elastic File System) |
| **Object Storage** | Stores data as objects in flat containers (buckets). Each object holds the data, metadata, and a unique ID, and is accessed through an HTTP/API. | Massive amounts of unstructured data such as images, videos, backups, and logs. | AWS S3 (Simple Storage Service) |

## Recommendation to the Client
Object Storage is the best choice for your user-uploaded images because it scales almost without limit, so millions of photos can be stored without managing disk sizes or folder structures. It is also cost-effective and keeps images outside your web server containers, so they are not lost when a container is restarted or replaced. Each image can be accessed directly over the web through a unique URL, which fits a photo-sharing application well.
