# Aoun Md. — Cloud & DevOps Engineer

**Malegaon, Maharashtra, India** · Open to **Cloud Engineer · DevOps Engineer · Infrastructure Engineer · Cloud Support Engineer** roles

<p>
  <a href="https://www.linkedin.com/in/aoun26"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:aounmd74@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/Aoun62336/AssembleMonitor-DevOps"><img src="https://img.shields.io/badge/Featured%20Project-181717?style=flat-square&logo=github&logoColor=white" alt="AssembleMonitor featured project"></a>
</p>

Cloud and DevOps Engineer focused on **AWS, Terraform, Kubernetes, CI/CD, GitOps, and observability**. I have hands-on experience from software engineering and cloud-support internships, and I independently extended **AssembleMonitor** into an AWS/EKS environment covering infrastructure provisioning, delivery automation, workload identity, secret management, autoscaling, and telemetry.

---

## Technical Focus

- **Cloud & Infrastructure as Code:** AWS, Terraform, Ansible, Linux
- **Containers & Kubernetes:** Docker, Kubernetes, Amazon EKS, Helm
- **CI/CD & GitOps:** Jenkins, Argo CD, Git, GitHub, SonarQube, Trivy
- **AWS Identity & Security:** IAM, IRSA, AWS Secrets Manager, External Secrets Operator, AWS WAF
- **Observability & Operations:** OpenTelemetry, Amazon Managed Service for Prometheus, Grafana, Loki, Tempo, CloudWatch, k6
- **Application Foundations:** Python, Bash, FastAPI, PostgreSQL, React

---

## Featured Project

### [AssembleMonitor — AWS EKS & DevOps Infrastructure](https://github.com/Aoun62336/AssembleMonitor-DevOps)

AssembleMonitor is a construction site management application that I continued independently after my Software Engineer internship and used as the basis for a hands-on Cloud/DevOps implementation on AWS and Kubernetes.

[![AssembleMonitor architecture](https://raw.githubusercontent.com/Aoun62336/AssembleMonitor-DevOps/main/docs/architecture/00-master-overview.png)](https://github.com/Aoun62336/AssembleMonitor-DevOps)

**What I implemented:**

- **AWS & Terraform:** Defined the core AWS/EKS environment with Terraform, including Amazon EKS, dedicated private application subnets, Application Load Balancer, AWS WAF, Amazon RDS PostgreSQL, Amazon S3, IAM, AWS Secrets Manager, and monitoring resources.
- **CI/CD & GitOps:** Built a **17-stage Jenkins pipeline** with Trivy scanning, SonarQube analysis and Quality Gate, application build validation, Docker image build/push, HIGH/CRITICAL image vulnerability gates, manual deployment approval, and Git-based Helm image-tag updates. Argo CD reconciles the Git-defined desired state to Amazon EKS.
- **Kubernetes:** Configured frontend/backend Deployments and Services, health probes, resource requests/limits, Metrics Server, and Horizontal Pod Autoscaling. The application HPAs scale from **2 to 5 replicas at a 70% CPU target**.
- **Identity & Secrets:** Used EKS OIDC/IRSA for workload AWS access and AWS Secrets Manager with External Secrets Operator for Kubernetes secret delivery.
- **Observability:** Implemented OpenTelemetry-based metrics, logs, and traces using Amazon Managed Service for Prometheus, Grafana Loki, Grafana Tempo, and Grafana, with a separate external scraper for Node Exporter metrics from supporting EC2 tooling.
- **Supporting Operations:** Used Ansible for selected supporting EC2 configuration and k6 for manual post-deployment performance testing.

**Explore the implementation:**

[Architecture](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/docs/architecture/ARCHITECTURE.md) ·
[Jenkins Pipeline](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/Jenkinsfile-gitops) ·
[Terraform](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/terraform) ·
[Helm / Kubernetes](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/k8s/helm-chart) ·
[Security](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/docs/architecture/SECURITY.md) ·
[Observability Config](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/k8s/helm-chart/values/observability.yaml) ·
[Implementation Screenshots](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/docs/assets/screenshots)

---

## Experience

### Software Developer Intern — Noorisys Technologies Pvt. Ltd.
`Feb 2026 – May 2026`

- Developed full-stack features for AssembleMonitor using **React, Python FastAPI, and PostgreSQL**.
- Implemented application functionality including JWT-based authentication, role-based access control, CRUD workflows, and project/task scheduling features.
- After the internship, I continued AssembleMonitor independently; the AWS, Kubernetes, CI/CD, security, and observability work described above was implemented during that independent phase.

### Cloud Support Intern — CanveX
`Jan 2025 – Mar 2025`

- Supported web-hosting environments for client websites across multiple hosting platforms.
- Performed website/file transfers, database migrations, backups, and technical troubleshooting during onboarding, platform transitions, and scheduled updates.
- Supported service continuity while resolving issues affecting live client websites.

---

## Education

**Master of Computer Applications (MCA)**  
Savitribai Phule Pune University · `2024 – 2026`

**Bachelor of Science (B.Sc.) — Computer Science**  
Savitribai Phule Pune University · `2021 – 2024`

---

## Certifications

- **Oracle Cloud Infrastructure Foundations Associate** — Oracle
- **Oracle Cloud Infrastructure AI Foundations Associate** — Oracle
- **Web Technology** — SWAYAM
- **Ethical Hacking** — NPTEL

<details>
<summary><strong>Selected Training & Coursework</strong></summary>

- **AWS Solutions Architecture** — Forage *(Job Simulation)*
- **Python With AI** — Training

</details>

---

<p align="center">
  <a href="https://www.linkedin.com/in/aoun26">LinkedIn</a> ·
  <a href="mailto:aounmd74@gmail.com">Email</a> ·
  <a href="https://github.com/Aoun62336/AssembleMonitor-DevOps">AssembleMonitor</a>
</p>
