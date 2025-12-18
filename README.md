# Usage
```sh
docker run --rm -it -p YOUR_PORT:80 ghcr.io/Nucleify/nuc_documents
```

API Documentation URL:
- http://YOUR_IP:YOUR_PORT/docs

# Local build

## Build Docker
```sh
docker build -t nuc-documents -f Dockerfile
```

## Run locally built image
```sh
docker run -p 1080:80 -it --rm nuc-documents
```
