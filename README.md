# MinIO Study

This project is for learning MinIO - an S3 compatible object storage server.

## Description

A simple learning project to explore MinIO using Docker, Node.js and JavaScript.

## Requirements

- Docker
- Node.js
- JavaScript

## Installation

```bash
# Clone repository
git clone https://github.com/[username]/minio-study.git
cd minio-study

# Run MinIO with Docker
docker run -p 9000:9000 -p 9001:9001 minio/minio server /data --console-address ":9001"
```

## References

- [MinIO Documentation](https://docs.min.io/)
- [MinIO JavaScript SDK](https://docs.min.io/docs/javascript-client-quickstart-guide.html)