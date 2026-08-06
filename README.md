# Hi there, I'm Ajay Singh! 👋

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=0078D4&center=true&vcenter=true&width=750&lines=AJAY+SINGH;Senior+DevSecOps+Engineer;Azure+Cloud+%7C+Kubernetes+%7C+IaC+%7C+CI%2FCD;Shift-Left+Security+%7C+Zero-Trust+Architecture" alt="Typing SVG" />
</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0078D4&height=120&section=header&text=Senior%20DevSecOps%20Engineer&fontSize=30&fontColor=ffffff&animation=fadeIn" width="100%" />
</p>

<div align="center">

[![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)](https://argoproj.github.io/cd/)

</div>

---

## 🚀 About Me

Results-driven **Senior DevSecOps Engineer** with **9+ years** of technical infrastructure and cloud engineering experience, specializing in designing, automating, and securing enterprise cloud-native infrastructure on **Microsoft Azure**.

* 🔭 **Current Role:** Senior DevSecOps Engineer at **L&T Technology Services Ltd (LTTS)**.
* 🛡️ **Core Focus:** Zero-Trust Architecture, Hub & Spoke Azure Landing Zones, PaaS Private Endpoints, and Shift-Left Security Integration (**SAST & DAST**).
* ⚙️ **Automation & IaC:** Expert in **Terraform IaC**, **Infracost** cloud cost governance, **GitHub Actions & Azure DevOps** pipelines, and **GitOps with ArgoCD**.
* 📍 **Location:** Pune, Maharashtra, India.
* 📬 **Contact:** [ajays1268@gmail.com](mailto:ajays1268@gmail.com) | [ajay.singh3@ltts.com](mailto:ajay.singh3@ltts.com)

---

## ⚡ DevSecOps & Cloud Native Architecture Flow

```mermaid
graph LR
    classDef dev fill:#0f172a,stroke:#3b82f6,stroke-width:2px,color:#fff;
    classDef sec fill:#0f172a,stroke:#ef4444,stroke-width:2px,color:#fff;
    classDef build fill:#0f172a,stroke:#f59e0b,stroke-width:2px,color:#fff;
    classDef deploy fill:#0f172a,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef monitor fill:#0f172a,stroke:#8b5cf6,stroke-width:2px,color:#fff;

    A[👨‍💻 Code Commit<br>GitHub / Azure Repos] :::dev --> B[🔍 SAST Scan<br>SonarQube / CheckMarx] :::sec
    B --> C[💰 IaC & Cost Analysis<br>Terraform / Infracost] :::build
    C --> D[🐳 Containerization<br>Docker & Helm] :::build
    D --> E[🛡️ DAST Scan<br>Qualys / Veracode] :::sec
    E --> F[🎯 Compliance Gates<br>Zero-Trust Check] :::sec
    F -->|Approved| G[☸️ ArgoCD GitOps<br>Sync to AKS Cluster] :::deploy
    G --> H[📊 Observability Stack<br>Prometheus / Grafana / Datadog] :::monitor
