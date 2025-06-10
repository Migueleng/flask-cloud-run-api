
# 🚀 Flask App on Google Kubernetes Engine (GKE)

This is a simple Flask web app containerized with Docker and deployed to GKE using Kubernetes.

## 🌐 What It Does

Returns:


Hello from Kubernetes 


## 📦 Tech Stack

- Flask
- Docker
- Gunicorn
- Google Cloud (GKE + GCR)
- Kubernetes

## 🚀 How to Deploy

1. Build and push Docker image:
```bash
docker build -t flask-k8s-app .
docker tag flask-k8s-app gcr.io/YOUR_PROJECT_ID/flask-k8s-app
docker push gcr.io/YOUR_PROJECT_ID/flask-k8s-app

## Apply kubernetes manifests
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

## get external IP address and access app
kubectl get service flask-k8s-service


I'm Miguel — passionate about cloud engineering, DevOps, and deploying real-world apps on GCP!


