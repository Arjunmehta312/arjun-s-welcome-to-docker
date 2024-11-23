# Welcome to Docker

This repository contains the files I created as part of learning Docker through the official Docker tutorials. The tutorial was followed on Docker for Desktop on Windows.

## What I Learned
- How to get started with Docker by creating containers and managing them.
- Basic Docker commands and concepts such as images, containers, and Docker Compose.
- Hands-on learning of Docker's core features, including running simple containers and building Dockerized applications.

## Prerequisites
To follow along with this tutorial, you'll need:
- [Docker for Desktop for Windows](https://www.docker.com/products/docker-desktop)
- A basic understanding of command-line operations

## Getting Started
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Arjunmehta312/arjun-s-welcome-to-docker.git
Navigate into the project folder:
```bash
cd arjun-s-welcome-to-docker
```
Follow the steps in this repository to replicate the Docker tutorial and learn the basics of Docker.
Welcome to Docker
This is a repo for new users getting started with Docker.

You can try it out using the following command:

```bash
  docker run -d -p 8088:80 --name welcome-to-docker docker/welcome-to-docker
```
Then open http://localhost:8088 in your browser to see the application running.

Building
Maintainers should see MAINTAINERS.md.

Build and Run
To build and run the project locally, follow these steps:

Build the Docker image:

```bash
docker build -t welcome-to-docker .
```
Run the container:

```bash
docker run -d -p 8088:3000 --name welcome-to-docker welcome-to-docker
```

Open http://localhost:8088 in your browser to see the application running.

License
This project is open-source and available under the MIT License.
