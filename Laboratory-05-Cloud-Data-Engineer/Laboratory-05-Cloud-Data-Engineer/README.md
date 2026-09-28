# Laboratory 05: The Cloud Data Engineer

## Mission Overview
In this mission, I was reassigned to the Cloud Data Engineering Team at CloudNova Technologies. The client is building a photo-sharing application and needs a place to store millions of user-uploaded images. Because containers are ephemeral, images cannot live inside the web server container. I built a proof-of-concept Object Storage environment by deploying MinIO (an S3-compatible server) using Docker on a KillerCoda Playground, creating a bucket named `client-photos`, and uploading a test file through the web console.

## Objectives
- Differentiate between Block, File, and Object Storage.
- Deploy an S3-compatible Object Storage server (MinIO) using Docker.
- Access a cloud service through a web interface using port forwarding.
- Create a storage bucket and upload objects (files) to the cloud.
- Document cloud storage operations using Markdown.
- Continue expanding a professional GitHub Cloud Computing Portfolio.

## Tools Used
- KillerCoda Ubuntu Playground
- Docker
- MinIO (`minio/minio` image)
- MinIO Web Console (port 9001)
- GitHub and Markdown
- Web browser

## Skills Learned
- Explaining the differences between block, file, and object storage
- Running a containerized service with `docker run`, port mapping (`-p`), and environment variables (`-e`)
- Verifying running containers with `docker ps`
- Accessing a service running on a specific port through the browser
- Creating buckets and uploading objects in S3-compatible storage
- Documenting technical work in Markdown and organizing a GitHub repository

## Repository Contents
| File | Description |
|------|-------------|
| `storage-types-research.md` | Block vs File vs Object storage comparison |
| `minio-deployment.md` | Technical steps for the MinIO deployment |
| `reflection.md` | Mission reflection |
| `screenshots/` | Evidence screenshots |
