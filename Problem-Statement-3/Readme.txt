📆 Problem Statement 3 – GoLang DateTime App with Docker & Kubernetes



✅ Objective
Create a GoLang web application that displays the current date and time, containerize it with Docker, push the image to DockerHub, and deploy it on Kubernetes using 2 replicas with an optional WAN exposure.


📁 Files

- main.go – GoLang web server showing current date and time
- Dockerfile – Container setup for the app
- deployment.yaml – Kubernetes deployment file (2 replicas)
- service.yaml – Kubernetes NodePort service
- screenshot-1-kubectl-get-all.png – `kubectl get all` output showing running pods and services
- screenshot-2-port-forward-success.png – Port-forward command successful
- README.docx – This file



🐳 DockerHub
Image URL: https://hub.docker.com/r/darsh487/datetime-app


🚀 Deployment Steps

1. Apply Kubernetes deployment and service:
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml

2. Forward local port to access app:
   kubectl port-forward service/datetime-service 8080:80

3. Access app at:
   http://localhost:8080


📸 Screenshots

1. screenshot-1-kubectl-get-all.png – Shows deployment, pods, service.
2. screenshot-2-port-forward-success.png – Port-forward command execution.


