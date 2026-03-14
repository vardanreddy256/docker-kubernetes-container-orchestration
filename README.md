# Dockerized Application Deployment with Kubernetes and Jenkins CI/CD

This project demonstrates a complete DevOps workflow including containerization, orchestration, and automated deployment.

## Project 3: Container Orchestration using Kubernetes

Steps:
1. Containerized a Flask application using Docker
2. Pushed Docker image to Docker Hub
3. Deployed application to Kubernetes cluster
4. Exposed service using NodePort

Tools:
- Docker
- Kubernetes
- Docker Hub

## Project 4: Automated CI/CD Pipeline using Jenkins

The deployment process is automated using Jenkins.

Pipeline Workflow:

Developer → GitHub → Jenkins Pipeline → Docker Build → Docker Hub → Kubernetes Deployment

Pipeline Stages:
1. Checkout code from GitHub
2. Build Docker image
3. Push Docker image to Docker Hub
4. Deploy application to Kubernetes using kubectl

Tools:
- Jenkins
- Docker
- Kubernetes
- GitHub

## Architecture

GitHub → Jenkins → Docker → Docker Hub → Kubernetes

## Technologies Used

- Python Flask
- Docker
- Kubernetes
- Jenkins
- GitHub
