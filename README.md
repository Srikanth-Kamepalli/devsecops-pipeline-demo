# DevSecOps Pipeline Demo

This project demonstrates a simple **DevSecOps pipeline** integrating security checks like static code analysis and Docker image scanning into the build and deployment process. The pipeline uses a **Flask** app and runs security tools such as **Bandit** (for Python static analysis) and **Trivy** (for Docker image vulnerability scanning).

## Project Overview

The goal of this project is to show how to build a secure DevSecOps pipeline using the following technologies:

- **Flask** (Python Web Framework)
- **Docker** (Containerization)
- **Bandit** (Static Analysis for Python)
- **Trivy** (Docker Image Security Scanner)

## Prerequisites

### Local Setup
Before running the project locally, ensure the following tools are installed:

1. **Docker**: To build and run the application inside containers.  
   - Install Docker from [docker.com](https://www.docker.com/products/docker-desktop).
2. **Bandit**: To analyze the Python code for security issues.  
   - Install Bandit by running `pip install bandit`.
3. **Trivy**: To scan Docker images for vulnerabilities.  
   - Install Trivy by following the guide on [Trivy GitHub](https://github.com/aquasecurity/trivy).

## Project Structure

```
devsecops-pipeline-demo/
├── app/
│ └── app.py
├── Dockerfile
└── requirements.txt
```
