# Treasure Hunt Game 🎮

A real-time location-based treasure hunt game leveraging modern cloud architecture and DevOps practices.

## 🎯 Project Overview

An interactive treasure hunt game that demonstrates the implementation of real-time location tracking and modern cloud deployment practices. Built as part of CSYE7220 DevOps coursework under Professor Dino Konstantopoulos.

## 🏗️ Architecture

### Tech Stack
- **Frontend**: ReactJS
- **Backend**: Flask
- **Real-time Database**: Redis
- **Cloud Platform**: AWS EKS
- **CI/CD**: AWS CodeBuild
- **IaC**: Terraform

## 🚀 Prerequisites

```bash
# Required tools
Node.js & npm
Python & pip
Docker
AWS CLI
kubectl
eksctl
Terraform
```

## 💻 Getting Started

1. Clone the repository
```bash
git clone https://github.com/khushankmistry/treasure-hunt-game.git
cd treasure-hunt-game
```

2. Install dependencies
```bash
# Frontend
cd frontend
npm install

# Backend
cd backend
pip install -r requirements.txt
```

## 🔄 CI/CD Pipeline

The project uses AWS CodeBuild for continuous integration and delivery. Build steps are defined in `buildspec.yml`.

## 📦 Deployment

### Setting up EKS Cluster
```bash
# Initialize Terraform
terraform init

# Plan deployment
terraform plan

# Apply configuration
terraform apply
```

### Deploying Application Components
```bash
# Apply Kubernetes manifests
kubectl apply -f k8s/frontend/
kubectl apply -f k8s/backend/
kubectl apply -f k8s/redis/
```

## 📚 Additional Resources

For detailed implementation instructions, please refer to [Manifest.md](Manifest.md).

---
⭐ Don't forget to star this repo if you find it useful!
