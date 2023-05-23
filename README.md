# Openbox VNC Lightweight Container

## Synopsis

Lightweight desktop Container designed for speed, and flexibility.

## Running Locally

### Requirements
- Docker

### Building Container Image
```
docker build -t brpedromaia_openbox_vnc:latest . -f ContainerFile
```

### Running Lighttpd Container Image
```
docker run --rm -it --name docker build -t brpedromaia_openbox_vnc:latest . -f ContainerFile
 -p 5900:5900 brpedromaia_openbox_vnc:latest
```
