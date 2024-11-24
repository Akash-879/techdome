![react](https://github.com/user-attachments/assets/96894c16-d10e-45e3-86e4-ba5e72e1310e)
![login](https://github.com/user-attachments/assets/77ada666-c3e8-43f6-80a5-5f394d303f1c)
![sign](https://github.com/user-attachments/assets/2f8407e8-977e-41b2-8953-eecfbab84683)
# Multi-Container Application Deployment with Docker Compose and Kubernetes

This project demonstrates the deployment of a multi-container React and Mongoose-based application. It includes a **frontend** (React), **backend** (Node.js with Express), and **MongoDB** for database services.

## Repositories

- **Backend**: [Techdome-backend](https://github.com/Anand-1432/Techdome-backend)  
- **Frontend**: [Techdome-frontend](https://github.com/Anand-1432/Techdome-frontend)  

## Table of Contents

1. [Architecture](#architecture)
2. [Requirements](#requirements)
3. [Setup with Docker Compose](#setup-with-docker-compose)
4. [Deployment on Kubernetes](#deployment-on-kubernetes)
5. [Screenshots/Demonstration](#screenshotsdemonstration)
6. [Troubleshooting](#troubleshooting)

---

## Architecture

The application consists of three services:
1. **Frontend**:
   - A React application for the user interface.
   - Runs on port `3000`.
2. **Backend**:
   - A Node.js Express application that provides APIs.
   - Connects to MongoDB for data persistence.
   - Runs on port `5000`.
3. **MongoDB**:
   - A NoSQL database for storing application data.
   - Exposed on port `27017`.

---

## Requirements

Ensure you have the following tools installed:
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)
- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [Kubectl](https://kubernetes.io/docs/tasks/tools/)

---

## Setup with Docker Compose

### Steps:
1. Clone the repositories:
   ```bash
   git clone https://github.com/Anand-1432/Techdome-backend
   git clone https://github.com/Anand-1432/Techdome-frontend
   
2. Create Dockerfile in each repository

3. Create a docker-compose.yml file in the project root

4. Run the application

5. Access the application:

Frontend: http://localhost:3000
Backend: http://localhost:5000

6. Deployment on Kubernetes

7. Start Minikube: Create Kubernetes deployment manifests: Apply the manifests:
