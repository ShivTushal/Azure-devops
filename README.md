Project Title
Multi-Cloud CI/CD Pipeline using Azure DevOps, Docker, AWS EC2 & Azure VM

Built a complete CI/CD pipeline using Azure DevOps to automate Docker-based application deployment across AWS and Azure virtual machines.

Features
Automated pipeline trigger on every Git commit
Docker image build using Dockerfile
Docker image stored as Azure Pipeline Artifact
Multi-stage YAML pipeline (Test → Build → Deploy)
Automated deployment to:
Amazon EC2
Microsoft Azure Virtual Machine
Secure SSH-based remote deployment using Azure Secure Files
Containerized Flask application deployment on port 5000
Artifact download and deployment automation using SCP and SSH
Technologies Used
Python Flask
Docker
Azure DevOps Pipelines
AWS EC2
Azure VM
Linux
YAML
SSH
Git & GitHub
CI/CD Workflow
Git Push
   ↓
Azure DevOps Pipeline Trigger
   ↓
Docker Image Build
   ↓
Docker Image Saved as TAR Artifact
   ↓
Artifact Published in Azure DevOps
   ↓
Artifact Downloaded in Deploy Stage
   ↓
Deployment to AWS EC2
   ↓
Deployment to Azure VM
Key Learnings
CI/CD pipeline automation
Docker image lifecycle
Azure Pipeline Artifacts
SSH-based deployment automation
Multi-cloud deployment workflow
YAML pipeline creation
Secure key handling using Azure Secure Files
Short Resume Version
Multi-Cloud CI/CD Pipeline Project

Designed and implemented a multi-stage CI/CD pipeline using Azure DevOps to automate Dockerized Flask application deployment across AWS EC2 and Azure Virtual Machines using SSH, Docker artifacts, and YAML-based automation.
