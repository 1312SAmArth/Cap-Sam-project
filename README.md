# 🚀 End-to-End MLOps & Data Engineering Project

This project demonstrates a **production-oriented MLOps and Data Engineering pipeline** that covers **data ingestion, reproducible ML workflows, containerized deployment, CI/CD, and cloud-native deployment on AWS**.

It is built to reflect **real-world industry practices** and is intended as a **resume-ready internship project**.

---

## 📌 Project Overview

The system processes structured data through reproducible pipelines, tracks machine learning experiments, exposes predictions via a REST API, and deploys the application on a scalable Kubernetes cluster with automated CI/CD.

---

## 🧠 Key Contributions

1. **Built reproducible data and ML pipelines using DVC (≈30%)** with data versioning, parameter tracking, and experiment reproducibility.  
2. **Containerized and deployed a Flask-based REST API using Docker (≈25%)** to support real-time model inference and portability.  
3. **Designed a scalable, cloud-native deployment on AWS EKS (≈25%)** with automated CI/CD using GitHub Actions and AWS ECR.  
4. **Integrated a modern MLOps and Data Engineering stack (≈20%)** including Python, MLflow (Dagshub), DVC, Docker, AWS, Airflow, and Git.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **ETL & Orchestration**: Apache Airflow  
- **Experiment Tracking**: MLflow (Dagshub)  
- **Data Versioning**: DVC + S3  
- **API**: Flask  
- **Containerization**: Docker  
- **CI/CD**: GitHub Actions  
- **Cloud & Orchestration**: AWS (ECR, EKS), Kubernetes  

---
Data → ETL Pipeline → DVC + MLflow
→ Flask API → Docker → AWS ECR
→ AWS EKS → LoadBalancer

## 🏗️ Architecture (High-Level)

