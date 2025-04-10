# Cloud Notes App 📝

A fully serverless, cloud-native note-taking application built with **AWS Lambda**, **API Gateway**, **DynamoDB**, **Node.js**, and **Next.js**, with infrastructure managed via **Terraform** and CI/CD automated using **GitHub Actions**.

## 🌟 Features

- Serverless architecture with AWS Lambda & API Gateway
- Infrastructure as Code (IaC) using Terraform
- Secure user authentication (JWT or AWS Cognito)
- Persistent note storage with DynamoDB
- Responsive frontend built with Next.js
- Automated deployments with GitHub Actions & Jenkins
- Fully containerized & scalable

## 🛠️ Tech Stack

- **Frontend:** Next.js, Axios
- **Backend:** Node.js, Express.js, AWS Lambda
- **Database:** DynamoDB
- **Infra:** Terraform, AWS API Gateway
- **CI/CD:** GitHub Actions, Jenkins
- **Deployment:** AWS, Vercel

## 🚀 Getting Started

### Prerequisites

- Node.js
- AWS Account
- Terraform installed
- Vercel account (for frontend deployment)

### Backend Setup

```bash
cd backend
npm install
terraform init
terraform apply
