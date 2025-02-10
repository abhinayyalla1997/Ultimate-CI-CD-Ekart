🚀 Shopping eKart Website Deployment with CI/CD

Overview

Successfully deployed a Shopping eKart website using a fully automated CI/CD pipeline with Jenkins. This project integrates various DevOps tools to ensure secure, high-quality, and seamless delivery.

🔧 Tools Used

✅ GitHub

✅ Jenkins

✅ Maven

✅ SonarQube

✅ OWASP Dependency Check

✅ Docker

✅ Amazon EKS

✅ Nexus

✅ Trivy

📌 Pipeline Steps

Clone the Code - Jenkins fetches the latest code from GitHub.

Build the Project - Maven compiles the source code.

Static Code Analysis - SonarQube performs quality checks.

Security Scanning - OWASP Dependency Check scans for vulnerabilities.

Artifact Storage - Build artifacts are stored in Nexus.

Docker Image Creation - A Docker image is built from the Dockerfile.

Image Scanning - Trivy scans the image for vulnerabilities.

Push Image to DockerHub - The built image is pushed to DockerHub.

Deploy to Kubernetes - The image is deployed to Amazon EKS using deployment and service YAML files.

Configure Domain - Namecheap is used to configure a custom domain.

(Optional) Secure with SSL - Certbot is used to secure the website with a free TLS/SSL certificate.

🚀 Getting Started

Clone the Repository

git clone https://github.com/yourusername/shopping-ekart.git

Modify Configuration Files

Ensure you update the Jenkins pipeline configuration and Kubernetes deployment YAML files as per your setup.

Running the CI/CD Pipeline

Trigger the Jenkins pipeline to start the automated deployment:

./jenkins-pipeline.sh

🛠 Prerequisites

Jenkins installed and configured.

AWS account with EKS set up.

Docker and Kubernetes installed locally.

SonarQube and Nexus configured.

🤝 Contributing

Contributions are welcome! Follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/new-feature).

Commit changes (git commit -m 'Add new feature').

Push to branch (git push origin feature/new-feature).

Create a pull request.

📜 License

This project is licensed under the MIT License. See the LICENSE file for more details.

