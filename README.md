# Serverless-Web-Application-Development-AWS-
This project is a fully serverless web application built on AWS, designed for taking and managing personal notes. It demonstrates the use of key AWS services such as **Amplify**, **API Gateway**, **Lambda**, **DynamoDB**, and **IAM** to create a secure, scalable, and cost-effective cloud-native application.

The frontend is hosted using **AWS Amplify** with integrated CI/CD pipelines for seamless deployment. The backend logic is powered by **AWS Lambda** functions that are exposed through **Amazon API Gateway**. Data is stored in **Amazon DynamoDB**, a fast and scalable NoSQL database, ensuring high performance at scale. **IAM policies** are applied to enforce secure, fine-grained access control.

---

## 🧰 Features

- 🛠️ Serverless architecture (no servers to manage)
- 🧾 RESTful APIs for notes CRUD operations
- 🚀 Scalable NoSQL data storage using DynamoDB
- 🔐 IAM-based secure access control
- 🔄 Continuous deployment with AWS Amplify
- 💸 Built-in cost optimization using pay-per-use resources

---

## 🧪 Tech Stack

- **Frontend:** AWS Amplify + JavaScript (React, Vue, or vanilla)
- **Backend:** AWS Lambda + API Gateway (Node.js)
- **Database:** Amazon DynamoDB
- **Security:** AWS IAM (with optional Cognito for auth)
- **CI/CD:** Amplify Git-based deployment

---

## 🏗️ Architecture Overview

1. **Amplify** hosts the frontend and handles CI/CD from GitHub.
2. **API Gateway** exposes RESTful routes like `/notes`, `/notes/{id}`.
3. **Lambda functions** execute backend logic (CRUD).
4. **DynamoDB** stores user notes with high availability and performance.
5. **IAM** governs secure access to services.

---

## 📦 Skills Demonstrated

- AWS Amplify setup and CI/CD configuration
- Writing and deploying Lambda functions with Node.js
- Configuring API Gateway endpoints and integrations
- DynamoDB schema design and data operations
- IAM policy configuration for role-based access

---


