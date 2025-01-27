# Dockerized Laravel API and Nuxt.js Client with Nginx Proxy

## Prerequisites

- Docker
- Docker Compose

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. Build and start the containers:
   ```bash
   docker-compose up --build
   ```

3. Open your browser and navigate to `https://localhost`. You should see the Nuxt.js application being served through the Nginx proxy.

## CI/CD with GitHub Actions

This project includes a GitHub Actions workflow to build and push Docker images to Docker Hub. The workflow is triggered on pushes to the `main` branch.

## Screenshots

![Nuxt.js Application](./screenshots/nuxtjs-app.png)
![Nginx Proxy](./screenshots/nginx-proxy.png)

