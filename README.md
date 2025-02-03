# Automated AWS Infrastructure & CI/CD Pipeline

## Overview
This project automates AWS infrastructure deployment and CI/CD pipeline setup using **Terraform, Ansible, and Jenkins**. It provisions AWS resources such as VPCs, security groups, and EC2 instances while integrating Jenkins with Nginx as a reverse proxy for a streamlined deployment process.

## Technologies Used
- **Terraform** – Infrastructure as Code (IaC) for AWS provisioning  
- **Ansible** – Configuration management and automation  
- **Jenkins** – CI/CD automation  
- **Nginx** – Reverse proxy for Jenkins  
- **AWS** – EC2, VPC, Security Groups  

## Features
- Automated AWS resource provisioning with **Terraform**
- Ansible playbook for **Jenkins installation** and **Nginx reverse proxy** setup  
- CI/CD integration for efficient deployments  
- Secure and scalable infrastructure  

## Setup Instructions

### Prerequisites
- Terraform installed (`>= 1.x`)
- Ansible installed (`>= 2.9`)
- AWS credentials configured (`~/.aws/credentials`)

### Deployment Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo/aws-infra-ci-cd.git
   cd aws-infra-ci-cd
