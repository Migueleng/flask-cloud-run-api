

# 🚀 Flask App on Google Kubernetes Engine (GKE)

This is a simple Flask web app containerized with Docker and deployed to Google Kubernetes Engine using Kubernetes.

---

## 🌐 What It Does

Returns:

```text
Hello from Kubernetes


🛠 Tech Stack
Flask

## Tech Stack
Flask

Docker 
 
Gunicorn

Kubernetes + GKE

Google Cloud Platform (GCP)


##Setup & Deployment Instructions
##🐳 Build and Push Docker Image

docker build -t flask-k8s-app .
docker tag flask-k8s-app gcr.io/YOUR_PROJECT_ID/flask-k8s-app
docker push gcr.io/YOUR_PROJECT_ID/flask-k8s-app



## Apply Kubernetes Manifests

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

##Get External IP and access App
kubectl get service flask-k8s-service


##Project structure
.
├── app.py              # Flask app
├── Dockerfile          # Container definition
├── requirements.txt    # Dependencies
├── deployment.yaml     # Kubernetes deployment
├── service.yaml        # Kubernetes service
└── README.md           # Project documentation


## 👤 About Me

I'm Sitou Miguel Efraim Agbodjinou, a passionate Cloud and DevOps enthusiast currently building hands-on experience with containerized applications and infrastructure automation.

I'm actively learning and working with:

Google Cloud Platform (GCP)

Kubernetes and GKE

Docker, CI/CD pipelines, and cloud architecture


I enjoy deploying real-world solutions, breaking down complex systems, and continuously growing toward a career in cloud engineering and platform reliability.

🚀 My goal is to become a Certified Cloud Engineer and work on scalable, production-grade systems.

CI/CD test
