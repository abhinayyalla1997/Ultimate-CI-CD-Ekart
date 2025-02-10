🛒 Shopping eKart CI/CD Deployment

🚀 Successfully deployed a Shopping eKart Website using a complete CI/CD pipeline with Jenkins, ensuring security, quality, and seamless delivery.

🔧 Tools & Technologies Used

✅ Version Control: GitHub

✅ CI/CD Tool: Jenkins

✅ Build Tool: Maven

✅ Code Quality Analysis: SonarQube

✅ Security Scanning: OWASP Dependency Check

✅ Artifact Repository: Nexus

✅ Containerization: Docker

✅ Image Scanning: Trivy

✅ Orchestration: Amazon EKS (Kubernetes)

✅ Domain Management: Namecheap

✅ SSL/TLS: Certbot (Optional)

📌 CI/CD Pipeline Steps

Clone the Code: Jenkins pulls the source code from GitHub.

Compile the Code: Maven is used to compile and package the application.

Static Code Analysis: SonarQube scans the code for bugs, vulnerabilities, and code smells.

Security Scanning: OWASP Dependency Check scans for vulnerable dependencies.

Build and Store Artifacts: The compiled application is stored in Nexus.

Create a Docker Image: The application is containerized using a Dockerfile.

Image Scanning: Trivy scans the Docker image for vulnerabilities.

Push Image to DockerHub: The built image is pushed to a container registry.

Deploy on Kubernetes (EKS): The application is deployed using Kubernetes deployment and service YAML files (NodePort).

Configure Custom Domain: A domain is configured via Namecheap.

(Optional) Secure the Website: Certbot is used for free TLS/SSL certificates.

🚀 Deployment Architecture

(Replace the above link with your actual architecture diagram)

📂 Project Structure

├── src/               # Application source code
├── Dockerfile         # Docker image instructions
├── Jenkinsfile        # CI/CD pipeline script
├── deployment.yaml    # Kubernetes deployment configuration
├── service.yaml       # Kubernetes service configuration
├── README.me          # Project documentation

📜 Prerequisites

Install Jenkins with required plugins (Pipeline, Docker, SonarQube, etc.)

Install Maven for build automation

Set up SonarQube for static code analysis

Deploy Nexus as an artifact repository

Set up an Amazon EKS cluster

Install Trivy for container security scanning

Configure a domain in Namecheap (Optional)

🛠️ Setup & Usage

1️⃣ Clone the Repository

git clone https://github.com/your-username/shopping-ekart-ci-cd.git
cd shopping-ekart-ci-cd

2️⃣ Run Jenkins Pipeline

Create a Jenkins Pipeline and link it to your GitHub repository.

Use the Jenkinsfile in this repository to define the pipeline steps.

3️⃣ Deploy on Kubernetes (EKS)

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

4️⃣ Verify Deployment

kubectl get pods
kubectl get services

📌 Future Enhancements

Implement GitHub Actions for an alternative CI/CD pipeline.

Add Terraform for infrastructure automation.

Improve security with RBAC policies in Kubernetes.

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

📞 Contact

👤 Your Name📧 Email: your.email@example.com🔗 LinkedIn: your-linkedin

