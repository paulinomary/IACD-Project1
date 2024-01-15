# IACD-Project1

Assignment #1 - Containers Basics

1. Pre-requisite: Install Docker
2. Create and/or fetch the required images for the multi-container web app
3. Run the web app containers in standalone mode (no interworking yet)

Assignment #2 - Container Connectivity & Volumes

1. Connect the backend component with the database
2. Connect the frontend component with the backend component
3. Persist data from the Database
   1. MongoDB stores data on the following path: /data/db
4. Persist data from the NodeJS Web App
   1. Logs folder should be persisted

Assignment #3 - Docker Compose

1. Publish the created containers (backend, frontend and database) in DockerHub
2. Deploy the multi-container application using Docker Compose

Assignment #4 - Kubernetes Deployment


1. Install Kubernetes (minikube)
2. Deploy the multi-container application using Kubernetes Imperative Approach
   1. No data persistence
   2. Replicas (database –1; backend –2; frontend –3)
3. Deploy the multi-container application using Kubernetes Declarative Approach
   1. No data persistence
   2. Replicas (database –1; backend –2; frontend –3)

Assignment #5 - Kubernetes Connectivity & Volumes

1. Connect the backend component with the database
2. Connect the frontend component with the backend component
3. Persist data from the Database
   1. MongoDB stores data on the following path: /data/db
4. Persist data from the NodeJS Web App
   1. Logs folder should be persisted
