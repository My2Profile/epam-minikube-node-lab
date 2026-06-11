# EPAM Minikube Node.js Lab

This project demonstrates a simple Node.js Express application deployed to Minikube using GitHub Actions.

## Stack

- Node.js
- Express
- Docker
- Kubernetes
- Minikube
- GitHub Actions

## Workflow

On every push, GitHub Actions:

1. Starts Minikube
2. Builds the Docker image
3. Deploys the app using Kubernetes YAML
4. Waits for the deployment
5. Tests the service URL
