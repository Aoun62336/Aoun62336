<h1 align="center">Aoun Md.</h1>

<p align="center">
  <b>DevOps &amp; Cloud Engineer</b> &nbsp;·&nbsp; AWS &nbsp;·&nbsp; Kubernetes &nbsp;·&nbsp; Terraform &nbsp;·&nbsp; GitOps
  <br/>
  <sub>Malegaon, Maharashtra, India &nbsp;|&nbsp; Open to DevOps / Cloud Engineer roles</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aoun26">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:aounmd74@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## About

MCA student with hands-on experience designing and operating cloud-native infrastructure on AWS.
I have built a production-grade platform end-to-end — from Terraform-provisioned EKS clusters
and ArgoCD GitOps delivery pipelines to full OpenTelemetry observability and zero-secret-in-Git
secrets management using IRSA and the External Secrets Operator.

---

## Core Stack

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Containers & Orchestration**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**CI/CD & GitOps**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1D4B8F?style=flat-square&logoColor=white)

**Observability**

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F79520?style=flat-square&logo=grafana&logoColor=white)

**Languages & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## Featured Project

### [AssembleMonitor — Cloud-Native Construction Management Platform](https://github.com/Aoun62336/AssembleMonitor-DevOps)

A full-stack construction site management platform deployed on AWS EKS using a
17-stage Jenkins DevSecOps CI pipeline and ArgoCD GitOps continuous delivery.

![System Context — AssembleMonitor on AWS](https://raw.githubusercontent.com/Aoun62336/AssembleMonitor-DevOps/main/docs/architecture/01-system-context.jpeg)

**Infrastructure highlights:**

- **Terraform-provisioned EKS** (v1.36) with HPA scaling 2→5 pods, ALB, WAFv2, RDS PostgreSQL, S3 — entire cluster rebuilt from scratch in ~8 min via `terraform apply`
- **GitOps pipeline** — Jenkins CI (Trivy CVE scan → SonarQube quality gate → Docker build → Docker Hub) feeds ArgoCD, which performs zero-downtime rolling updates on Helm chart tag commits in Git
- **Zero secrets in Git** — External Secrets Operator syncs credentials from AWS Secrets Manager into Kubernetes at runtime via IRSA; no base64 secrets committed anywhere
- **Full observability** — OTel Collector DaemonSet → logs to Grafana Loki, traces to Grafana Tempo, metrics to Amazon Managed Prometheus, all in Grafana
- **Security** — WAFv2 managed rules, IMDSv2 hop-limit=1, IRSA for every pod, SonarQube SAST, Trivy image scanning, all workloads in private subnets

**→ [View architecture, documentation, and deployment guides](https://github.com/Aoun62336/AssembleMonitor-DevOps)**

---

## Experience

**Software Developer Intern — Noorisys Technologies Pvt. Ltd.**
`Feb 2026 – May 2026 · Malegaon, India`

Developed and shipped full-stack features using React, Python FastAPI, and PostgreSQL.
Implemented CRUD operations, JWT authentication flows, and role-based access logic.
Built AssembleMonitor as the primary project during this internship and continued extending
its cloud infrastructure afterward, applying Terraform, EKS, ArgoCD, and full OTel
observability independently.

**Web Hosting & Cloud Support Intern — CanveX**
`Jan 2025 – Mar 2025 · Remote`

Managed web hosting environments for client operations. Executed file and asset migrations
across platforms, resolved technical issues on client sites, and maintained uptime during
updates.

---

## Education

**Master of Computer Applications (MCA)**
Dr. B. V. Hiray College of Management and Research Center · 2024 – Present · Malegaon, Maharashtra

**B.Sc. Computer Science**
M.S.G Arts, Science, and Commerce College · 2021 – 2024 · Malegaon, Maharashtra · CGPA: 7.69

---

## Certifications

| Certification | Issuer |
|:---|:---|
| AWS Solutions Architecture — Virtual Experience | Forage |
| OCI Cloud Foundations Associate | Oracle |
| OCI AI Foundations Associate | Oracle |
| Python With AI | SkillEcted |
| Web Technology | Swayam |
| Ethical Hacking | NPTEL |

---

## Languages

English &nbsp;·&nbsp; Urdu &nbsp;·&nbsp; Hindi &nbsp;·&nbsp; Arabic (Basic)
