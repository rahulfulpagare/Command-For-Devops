# Docker Command

## Docker Commands

- **Edit Dockerfile**:
  
  `vim Dockerfile`

- **List Docker images**:
  
  `docker images`

- **Build Docker image with a tag**:
  
  `docker build -t counter-app .`

- **Remove Docker images by ID**:
  
  `docker rmi <image_id>`

- **Force remove Docker images by ID**:
  
  `docker rmi --force <image_id>`

- **List Docker containers**:
  
  `docker ps`

- **List all Docker containers, including stopped**:
  
  `docker ps -a`

- **Run Docker container with port mapping**:
  
  `docker run -d -p 8000:8000 container-name`

- **Kill a Docker container**:
  
  `docker kill <container_id>`

- **Remove a Docker container by ID**:
  
  `docker rm <container_id>`
