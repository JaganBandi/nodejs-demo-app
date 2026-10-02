# nodejs-demo-app

# Node.js CI/CD Pipeline

## Project Overview

This project demonstrates a simple CI/CD pipeline for a Node.js application using GitHub Actions and Docker.

## Tools Used

- Node.js
- Express.js
- Git
- GitHub
- GitHub Actions
- Docker
- Docker Hub

## CI/CD Pipeline

The pipeline works as follows:

1. Developer pushes code to the "main" branch.
2. GitHub Actions is automatically triggered.
3. The code is checked out.
4. Node.js is configured.
5. Dependencies are installed using "npm ci".
6. The application is tested using "npm test".
7. Docker logs in to Docker Hub.
8. A Docker image is built.
9. The Docker image is pushed to Docker Hub.

## Docker Image

Docker Hub repository:

jaganbandi/nodejs-demo-app

## Application

The Node.js application runs on port "3000".

## Result

The project successfully demonstrates automated:

**Test → Build → Push**

using GitHub Actions and Docker.
