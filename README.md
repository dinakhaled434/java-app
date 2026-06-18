# Java Application CI/CD Pipeline

This project demonstrates a professional *DevOps lifecycle* for a Java application, integrating automation from code commit to cluster observability.

## 🚀 Key Features

* *Continuous Integration (CI):* Fully automated pipeline using *GitHub Actions* for building, testing, and containerization.
* *GitOps Deployment (CD):* Automated deployment managed by *ArgoCD*, ensuring the cluster is always in sync with the repository (Self-Healing).
* *Observability (Monitoring):*
    * *Prometheus:* Real-time metrics collection from the Kubernetes cluster.
    * *Grafana:* Visual dashboards for performance monitoring.
    * *Alertmanager:* Configured to trigger alerts for system incidents.

## 🛠️ Tech Stack
* *Application:* Java 11, Maven
* *CI/CD:* GitHub Actions
* *Containerization:* Docker, Docker Hub
* *Orchestration & GitOps:* Kubernetes (K8s), ArgoCD
* *Observability:* Prometheus, Grafana, Alertmanager

## 📊 Project Status
The application deployment is fully managed via GitOps, maintaining a *Healthy* and *Synced* status in the Kubernetes cluster.

---
Developed by Dina Khaled.
