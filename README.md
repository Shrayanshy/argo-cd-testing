# GitOps Testing Repository

This repository contains Kubernetes manifests for testing GitOps functionality with DeploAI.

## Contents

- `nginx-deployment.yaml` - A simple nginx deployment with service and ingress for GitOps testing

## Usage

This repository is designed to be used with DeploAI's GitOps functionality to test:
- Git clone operations
- Kubernetes manifest application
- Auto-sync functionality
- Webhook triggers

## Test Deployment

The nginx deployment includes:
- 2 replicas of nginx
- Service exposure on port 80
- Ingress configuration for external access
- Resource limits and requests
