# ENSF 400 - Assignment 3 - Kubernetes

This assignment involves deploying an Nginx service alongside two backend applications using Minikube in Codespaces, implementing a load balancing scheme with a canary deployment for the backend services.

## Getting Started

Begin by starting Minikube and enabling necessary addons:

```bash
minikube start
minikube addons enable ingress
