# 🧰 DevOps Portfolio Project — AWS | Terraform | EKS | Docker | Prometheus | Grafana

This is my self-hosted DevOps portfolio project designed to showcase my skills in modern DevOps tooling, cloud infrastructure, and automation. The project is deployed on AWS using Terraform and runs on a Kubernetes cluster (EKS) with full observability via Prometheus and Grafana.

---

## 🚀 Tech Stack

| Tool        | Purpose                            |
|-------------|------------------------------------|
| **AWS**     | Cloud provider                     |
| **Terraform** | Infrastructure as Code            |
| **EKS**     | Managed Kubernetes Cluster         |
| **Docker**  | Containerization                   |
| **Kubernetes** | Orchestration of the app         |
| **Prometheus** | Monitoring and metrics scraping  |
| **Grafana** | Dashboards and visualization       |
| **GitHub Actions** | CI/CD automation             |

---

## 🏗️ Architecture

![Architecture Diagram](architecture-diagram.png)

---

## 📂 Project Structure

```bash
.
├── terraform/         # Terraform code for AWS infra
├── app/               # Dockerized Flask app
├── k8s/               # Kubernetes manifests
├── monitoring/        # Prometheus + Grafana setup
├── .github/           # GitHub Actions for CI/CD
└── README.md

