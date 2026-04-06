# 🚀 DevOps CI/CD Pipeline with Kubernetes

This project demonstrates a complete DevOps workflow using Docker, Kubernetes, and GitHub Actions.

## 🧱 Architecture

GitHub → GitHub Actions → Docker Hub → Kubernetes

## 🛠️ Tech Stack

* Docker
* Kubernetes
* GitHub Actions
* Docker Hub

## 🔄 CI/CD Workflow

1. Code pushed to GitHub
2. GitHub Actions builds Docker image
3. Image pushed to Docker Hub
4. Kubernetes deploys application

## 🐳 Docker

Build:

```bash
docker build -t <your-dockerhub-username>/app .
```

Run:

```bash
docker run -p 3000:3000 <your-image>
```

## ☸️ Kubernetes

Deploy:

```bash
kubectl apply -f k8s/
```

Check:

```bash
kubectl get pods
```

## ⚙️ CI Pipeline

Located at:

```
.github/workflows/
```

## 🎯 Features

* Automated CI pipeline
* Dockerized application
* Kubernetes deployment
* Scalable setup

## 📌 Future Improvements

* Helm integration
* Monitoring (Prometheus & Grafana)
* GitOps (Argo CD)

## 👩‍💻 Author

Bhoomika M

