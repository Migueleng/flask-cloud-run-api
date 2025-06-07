# flask-api
This is a simple Flask-based REST API designed to run on **Google Cloud Run**. It's containerized with Docker and ready for deployment.

## Features
- RESTful endpoints with Flask
- Dockerized for easy deployment
- Ready for Google Cloud Run
- Secure and scalable

  flask-cloud-run-api/
├── app.py
├── requirements.txt
├── Dockerfile
├── .gitignore
└── README.md

''bash
git clone git@github.com:Migueleng/flask-cloud-run-api.git
cd flask-cloud-run-api

pip install -r requirements.txt

python app.py


##Docker setup
# Build the Docker locally
docker build -t flask-api .
# Run the container locally 
docker run -p 8080:8080 flask-api


##Deploy the Google Cloud Run
1- Push the Docker image to Google Container REgistry  or Artifact Registry
2- Deploy using gcloud CLI 
gcloud run deploy flask-api \
  --source . \
  --region us-central1 \
  --platform managed \
  --allow-unauthenticated


Contact :
Sitou Miguel Efraim Agbodjinou 
Github: Migueleng 

