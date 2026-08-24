# Aoun Md. — Cloud & DevOps Engineer

**Malegaon, Maharashtra, India**  
Open to **Cloud Engineer · DevOps Engineer · Infrastructure Engineer · Cloud Support Engineer** opportunities

<p>
  <a href="https://www.linkedin.com/in/aoun26">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:aounmd74@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/Aoun62336/AssembleMonitor-DevOps">
    <img src="https://img.shields.io/badge/AssembleMonitor-181717?style=flat-square&logo=github&logoColor=white" alt="AssembleMonitor">
  </a>
</p>

I work primarily with **AWS, Terraform, Kubernetes, CI/CD, GitOps, Linux, and observability**.

Most recently, I built and hardened AssembleMonitor — a full-stack construction-site management system I developed during my Software Developer internship and later extended independently with AWS/EKS infrastructure, CI/CD and GitOps, Kubernetes controls, automated validation, observability, and reliability testing.

---

## Technical Focus

- **Cloud & Infrastructure:** AWS, Amazon EKS, EC2, VPC, RDS, S3, IAM, AWS WAF, AWS Secrets Manager, Linux
- **Infrastructure as Code & Automation:** Terraform, reusable modules, `terraform test`, Ansible, Bash, YAML
- **Containers & Kubernetes:** Docker, Kubernetes, Helm, HPA, Metrics Server, NetworkPolicy, PodDisruptionBudget
- **CI/CD & GitOps:** Jenkins, GitHub Actions, Argo CD, Git, GitHub
- **Security & DevSecOps:** IAM/IRSA, External Secrets Operator, SonarQube, Trivy, Gitleaks
- **Observability & Reliability:** OpenTelemetry, AMP/Prometheus, Grafana, Loki, Tempo, CloudWatch, k6, troubleshooting, RCA/postmortems
- **Application Foundations:** Python, FastAPI, REST APIs, PostgreSQL, MySQL, React

---

## Featured Project

### [AssembleMonitor — AWS EKS · Terraform · Jenkins · Argo CD](https://github.com/Aoun62336/AssembleMonitor-DevOps)

AssembleMonitor is a construction-site management system I developed during my **Software Developer internship at Noorisys Technologies Pvt. Ltd.**

After the internship, I continued the system independently and built its AWS/Kubernetes infrastructure, CI/CD and GitOps delivery, security controls, observability, automated validation, and reliability-testing layer.

[![AssembleMonitor architecture](https://raw.githubusercontent.com/Aoun62336/AssembleMonitor-DevOps/main/docs/architecture/00-master-overview.png)](https://github.com/Aoun62336/AssembleMonitor-DevOps)

### What I implemented

- **AWS & Terraform:** Provisioned the AWS/EKS environment with Terraform, including private application subnets and routing, Amazon EKS, Application Load Balancer, AWS WAF, Amazon RDS PostgreSQL, S3, IAM, AWS Secrets Manager, CloudWatch, and Amazon Managed Service for Prometheus. Later refactored the private-networking layer within the existing VPC into a reusable Terraform module and added **5 native `terraform test` cases using a mocked AWS provider**.

- **Jenkins CI/CD:** Built a **17-stage Jenkins pipeline** with SonarQube Quality Gate, Trivy filesystem scanning, blocking HIGH/CRITICAL container-image vulnerability gates, application build validation, Docker image publishing, manual deployment approval, and Git-based Helm image-tag updates.

- **GitHub Actions:** Added a **5-job pre-merge validation workflow** covering a **23-test backend suite**, frontend production build, Terraform formatting/validation/tests, Helm validation, and Gitleaks secret scanning.

- **GitOps:** Configured Helm and Argo CD so the Git-defined Kubernetes desired state is continuously reconciled to Amazon EKS.

- **Kubernetes:** Configured frontend and backend workloads with resource requests/limits, separate process-liveness and PostgreSQL-aware readiness probes, Metrics Server, and Horizontal Pod Autoscaling from **2 to 5 replicas at a 70% CPU target**. Added and runtime-tested **NetworkPolicy** and **PodDisruptionBudget** controls in disposable k3d/K3s environments.

- **Identity & Secrets:** Configured EKS OIDC/IRSA for workload AWS access and used AWS Secrets Manager with External Secrets Operator for Kubernetes secret delivery.

- **Observability:** Implemented metrics, logs, and traces using OpenTelemetry, AMP/Prometheus, Grafana Loki, Grafana Tempo, Grafana, and CloudWatch. Added version-controlled Grafana dashboard definitions and validated local FastAPI OTLP trace delivery through the OpenTelemetry Collector.

- **Reliability & Troubleshooting:** Executed **3 controlled failure exercises** covering PostgreSQL outage, API outage, and database DNS/configuration failure. Documented investigation steps, recovery validation, root-cause analysis, troubleshooting procedures, and postmortems.

- **Supporting Operations:** Used Ansible for selected supporting EC2 configuration and k6 for performance validation.

### Explore the implementation

[Architecture](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/docs/architecture/ARCHITECTURE.md) ·
[Jenkins Pipeline](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/Jenkinsfile-gitops) ·
[GitHub Actions](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/.github/workflows/pr-validation.yml) ·
[Terraform](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/terraform) ·
[Helm / Kubernetes](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/k8s/helm-chart) ·
[Security](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/docs/architecture/SECURITY.md) ·
[Hardening & Reliability](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/docs/hardening) ·
[Operational Runbooks](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/docs/ops) ·
[Implementation Evidence](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/docs/assets/screenshots)

---

## Experience

### Software Developer Intern — Noorisys Technologies Pvt. Ltd.
`Feb 2026 – May 2026`

- Developed AssembleMonitor using **React, Python FastAPI, and PostgreSQL**, covering project, phase, task, material, attendance, expense, site-photo, and scheduling workflows.
- Built JWT-authenticated REST APIs and role-based access control for Admin, Project Manager, Site Engineer, and Client workflows.
- Used Git/GitHub for version control and exposed Swagger/OpenAPI documentation through the FastAPI application.
- After the internship, continued AssembleMonitor independently and built the AWS/Kubernetes, CI/CD, security, observability, and reliability work described above.

### Cloud Support Intern — CanveX
`Jan 2025 – Mar 2025`

- Supported web-hosting environments for client websites across hosting platforms.
- Performed website/file transfers, MySQL database migrations, and backups during hosting changes.
- Troubleshot website issues during migrations and scheduled updates, coordinating fixes with the remote support team.

---

## Education

**Master of Computer Applications (MCA)**  
Dr. B. V. Hiray College of Management and Research Center  
Savitribai Phule Pune University · `2024 – 2026`

**Bachelor of Science (B.Sc.) — Computer Science**  
M.S.G. Arts, Science and Commerce College  
Savitribai Phule Pune University · `2021 – 2024`

---

## Certifications

- **Oracle Cloud Infrastructure Foundations Associate** — Oracle
- **Oracle Cloud Infrastructure AI Foundations Associate** — Oracle
- **Web Technology** — SWAYAM
- **Ethical Hacking** — NPTEL

---

<p align="center">
  <a href="https://www.linkedin.com/in/aoun26">LinkedIn</a>
  ·
  <a href="mailto:aounmd74@gmail.com">Email</a>
  ·
  <a href="https://github.com/Aoun62336/AssembleMonitor-DevOps">AssembleMonitor</a>
</p>
