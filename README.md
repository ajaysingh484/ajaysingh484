<div align="center">

  <!-- Animated Header with Animated Name -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078D4,50:00C8FF,100:1E3A8A&height=180&section=header&text=AJAY%20SINGH&fontSize=50&fontColor=ffffff&animation=fadeIn" width="100%" />

  <br/>

  <!-- Animated Name & Role Typing Banner -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=2500&pause=800&color=00C8FF&center=true&vCenter=true&width=900&lines=👋+Hi,+I'm+AJAY+SINGH;Senior+DevSecOps+Engineer;Azure+Cloud+Architect;Terraform+Infrastructure+as+Code;AKS+%7C+Docker+%7C+Kubernetes;Azure+DevOps+%7C+GitHub+Actions;GitOps+with+ArgoCD;Cloud+Security+%7C+DevSecOps" alt="Typing SVG Animation" />

</div>

---

# 💫 About Me

I'm a **Senior DevSecOps Engineer** with **9+ years of IT experience**, specializing in **Microsoft Azure, Kubernetes, Terraform, CI/CD, GitOps, Cloud Security, and Infrastructure Automation**.

I enjoy building **production-grade, secure, highly available, and scalable cloud platforms** using Infrastructure as Code and DevSecOps best practices. My focus is on automation, reliability, security, and continuous improvement.

<div align="center">

| ☁️ Core Competencies | 🛡️ Security & Observability |
| :--- | :--- |
| ☁️ Microsoft Azure | 🔐 DevSecOps & Shift-Left Security |
| ☸️ Azure Kubernetes Service (AKS) | 📊 Monitoring & Observability |
| ⚙️ Terraform (IaC Modularization) | 🌐 Hub & Spoke Azure Networking |
| 🚀 Azure DevOps & GitHub Actions | 🔐 PaaS Private Endpoints & Zero-Trust |
| 🔄 GitOps Workflows (ArgoCD) | ⚡ Infracost Cost Governance |

</div>

<br/>

> **"Automate Everything • Secure by Design • Deploy with Confidence."**

---

# 🚀 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=azure,terraform,docker,kubernetes,github,azuredevops,git,bash,linux,python,prometheus,grafana,vscode&perline=7" />

</div>

---

# ☁️ Azure & DevSecOps Badge Ecosystem

<p align="center">
  <img src="https://img.shields.io/badge/AKS-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"/>
  <img src="https://img.shields.io/badge/Application%20Gateway-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure%20Front%20Door-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure%20Key%20Vault-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure%20SQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Private%20Endpoints-00C8FF?style=for-the-badge"/>
</p>

---

# ⚡ DevSecOps & GitOps Architecture Flow

```mermaid
graph LR
    classDef dev fill:#0f172a,stroke:#00C8FF,stroke-width:2px,color:#fff;
    classDef sec fill:#0f172a,stroke:#ef4444,stroke-width:2px,color:#fff;
    classDef build fill:#0f172a,stroke:#f59e0b,stroke-width:2px,color:#fff;
    classDef deploy fill:#0f172a,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef monitor fill:#0f172a,stroke:#8b5cf6,stroke-width:2px,color:#fff;

    A[👨‍💻 Code Commit<br>GitHub / Azure Repos] :::dev --> B[🔍 SAST Scan<br>SonarQube / CheckMarx] :::sec
    B --> C[💰 IaC & Cost Check<br>Terraform / Infracost] :::build
    C --> D[🐳 Containerize<br>Docker & Helm] :::build
    D --> E[🛡️ DAST Scan<br>Qualys / Veracode] :::sec
    E --> F[🎯 Compliance Gate<br>Zero-Trust Check] :::sec
    F -->|Approved| G[☸️ ArgoCD GitOps<br>Sync to AKS] :::deploy
    G --> H[📊 Observability<br>Prometheus / Grafana] :::monitor
