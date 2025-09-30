# 🚀 CI/CD Pipeline for a Node.js App using Jenkins 🧪💡

As a **fresher diving into DevOps**, I wanted to go beyond tutorials and build something real —  
so I created a **complete CI/CD pipeline** for a Node.js application using **Jenkins**.

---

## 🔧 Project Overview

This project sets up a Jenkins pipeline that:

- ✅ Pulls code from **GitHub** on every push  
- 🧪 Installs dependencies and runs **unit tests**  
- 🐳 Builds a **Docker image** and pushes it to **Docker Hub**  
- 🚀 Deploys the app to a **test server** (via SSH + Docker)  

---

## 📦 Tech Stack

- **Jenkins** (Freestyle & Declarative Pipeline)  
- **Node.js**  
- **GitHub**  
- **Docker**  
- **Shell Scripting**  
- **AWS EC2 (Ubuntu)**  

---

## 🎯 Key Learnings

- ⚡ **Automating builds & deployments** speeds up development and ensures reliability  
- 🔐 Handling **environment variables & credentials** securely with Jenkins secrets  
- 🛠️ **Troubleshooting pipeline failures** gave real-world insights into DevOps workflows  
- 📜 Learned how **logs, error codes, and shell scripts** can make or break a pipeline  

---

## 🖼️ CI/CD Flow

```mermaid
flowchart LR
    A[GitHub Push] --> B[Jenkins Pipeline Trigger]
    B --> C[Install Dependencies & Run Tests]
    C --> D[Build Docker Image]
    D --> E[Push Image to Docker Hub]
    E --> F[Deploy to AWS EC2 via SSH + Docker]
