# Ashwin E
# DevOps Engineer Portfolio

Welcome to my GitHub repository! This repository showcases various projects that demonstrate my hands-on experience in **DevOps**, including automation, CI/CD pipelines, cloud infrastructure, and containerization.

## Skills and Tools
- **Cloud Platforms**: AWS, Azure
- **CI/CD**: Jenkins, GitLab CI, GitHub Actions
- **Infrastructure as Code**: Terraform, Ansible
- **Containerization**: Docker, Kubernetes
- **Monitoring**: Prometheus, Grafana
- **Scripting**: Bash, Python
- **Version Control**: Git, GitHub
- **Operating Systems**: Linux (Ubuntu)

---

## Projects

### 1. Deploy a NodeJS Application

- **Description**: Dockerized the NodeJS application and automated its deployment using Jenkins CI/CD.
- **Details**:
  - Created a `Dockerfile` and `docker-compose` to containerize the application.
  - Wrote two bash scripts:
    - `build.sh`: Builds the Docker image.
    - `deploy.sh`: Deploys the image.
  - Pushed code to GitHub repositories for "dev" and "prod" environments, using `.dockerignore` and `.gitignore`.
  - Configured Jenkins to automate builds, pushes, and deployments based on Git branches.
  - Deployed the application on an AWS EC2 instance with IP-restricted access.
  - Monitored the application using **Prometheus**, **Grafana**, and **AWS CloudWatch**.
- **Tools Used**: AWS, EC2, Git, Docker, Jenkins, Bash, Prometheus, Grafana

---

### 2. Kubernetes Deployment with EKS and CI/CD

- **Description**: Deployed a microservices application on a Kubernetes cluster using Jenkins CI/CD pipelines.
- **Details**:
  - Automated the deployment process using Jenkins CI/CD.
  - Pushed Docker images to **AWS ECR** for storage and management.
  - Managed Kubernetes resources on **AWS EKS** for high availability.
- **Tools Used**: AWS, EKS, ECR, EC2, Git, Docker, Jenkins, Kubernetes

---

### 3. CI/CD Pipeline for Python Application

- **Description**: Set up a CI/CD pipeline for a Python application using Jenkins to automate build, test, and deployment.
- **Details**:
  - Configured Jenkins to pull code from GitHub, build the Docker image, and deploy it to an AWS EC2 instance.
  - Implemented automated testing as part of the pipeline.
- **Tools Used**: AWS, EC2, Git, Docker, Jenkins

---

### 4. AWS Infrastructure Automation Using Terraform

- **Description**: Developed and managed AWS infrastructure using Terraform, focusing on automated provisioning and state management.
- **Details**:
  - Built a custom **VPC** with public and private subnets across Availability Zones.
  - Configured routing tables, an Internet Gateway, and a NAT gateway for the subnets.
  - Deployed EC2 instances in the public subnet using user data to set up an Apache web server.
  - Used **S3** for Terraform statefile storage and **DynamoDB** for state locking to ensure infrastructure integrity.
  - Modularized Terraform code for reuse across different environments.
- **Tools Used**: Terraform, AWS (EC2, S3, VPC, DynamoDB)

---

### 5. AWS Resources Project Using Management Console

- **Description**: Created and managed AWS resources using the AWS Management Console, focusing on scalability and load balancing.
- **Details**:
  - Created a **VPC** with subnets, route tables, Internet Gateway, and NAT Gateway.
  - Deployed private EC2 instances with **Nginx** and **Apache** web servers.
  - Configured an **Application Load Balancer** to route traffic between instances.
- **Tools Used**: AWS (VPC, Subnets, Route Table, IGW, Elastic IP, NAT Gateway, EC2, Auto-scaling Group, Application Load Balancer)

---

## Education

**Bachelor of Engineering** in **Electronics and Communication Engineering**  
**Anna University**, Chennai, India  
**CGPA**: 7.42/10  
Aug 2017 – Apr 2021

---

### Contact Information

Feel free to reach out for collaboration or queries:

- **Email**: antonyashwin643@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/ashwin-e-bab1461b1/
- **Mobile**: 7339171064

---

### This portfolio showcases my skills and projects as an AWS DevOps Engineer. Check out my GitHub repositories to see my work in detail.
  




