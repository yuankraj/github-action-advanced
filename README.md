# 🚀 DevSecOps CI/CD Pipeline with GitHub Actions

This project demonstrates a **complete End-to-End DevSecOps CI/CD pipeline** using **GitHub Actions, Docker, and AWS EC2**.

The pipeline automates the entire workflow from **code commit → security scanning → Docker build → deployment to production**.

---

# 🌐 Live Demo

Application URL

http://15.134.206.63/

---

# 📂 GitHub Repository

https://github.com/yuankraj/github-action-advanced

---

# ⚙️ DevSecOps CI/CD Pipeline

The pipeline automatically performs the following steps:

Developer Push Code  
↓  
GitHub Repository  
↓  
GitHub Actions CI Pipeline  
↓  
Code Quality Check  
↓  
Secrets Scan  
↓  
Dependency Vulnerability Scan  
↓  
Dockerfile Lint  
↓  
Run Tests  
↓  
Build Docker Image  
↓  
Push Docker Image  
↓  
Image Security Scan (Trivy)  
↓  
Deploy to AWS EC2  
↓  
Application Live

---

# 🔐 DevSecOps Security Checks

Security is integrated directly into the CI/CD pipeline.

Implemented security stages:

- Secrets Scanning
- Dependency Vulnerability Scanning
- Dockerfile Linting
- Container Image Vulnerability Scanning using **Trivy**

This ensures vulnerabilities are detected **before production deployment**.

---

# 🛠 Tech Stack

- GitHub Actions (CI/CD)
- Self Hosted GitHub Runner
- Docker
- AWS EC2
- Python Flask
- Trivy Security Scanner
- Linux

---

# 📁 Project Structure
