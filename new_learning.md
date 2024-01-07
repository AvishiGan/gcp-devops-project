# Docker Tasks

## Build a Docker image from a Dockerfile

`docker build -t gcp-devops-project .`

- The . (dot) represents the current directory

## Push the built image to the Docker Hub repository

### Tag the image first

`docker tag gcp-devops-project:latest docker_user/gcp-devops-project:latest`

### Push the image

`docker push docker_user/gcp-devops-project:latest`

# GCP Registry and Deployment

## Push the local Docker image to both GCR and Artifact Registry

### To Google Cloud Registry (GCR)

1. Authenticate Docker with GCR
