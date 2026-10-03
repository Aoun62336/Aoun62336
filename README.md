# Aoun Md. | Cloud & DevOps Engineer

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
  <a href="https://github.com/Aoun62336/CallMissed-Ai-Workspace">
    <img src="https://img.shields.io/badge/CallMissed_AI_Workspace-181717?style=flat-square&logo=github&logoColor=white" alt="CallMissed AI Workspace">
  </a>
</p>

I work with **AWS, Terraform, Docker, Kubernetes, CI/CD, GitOps, Linux, security, observability, and infrastructure automation**.

My work currently includes two main DevOps projects with different deployment approaches:

- **AssembleMonitor**, a full-stack construction-site management system deployed on AWS EKS with Terraform, Jenkins, Argo CD, Kubernetes reliability controls, observability, and security scanning.
- **CallMissed AI Workspace**, a containerized React and FastAPI application deployed on AWS Lambda using ECR, Terraform, GitHub Actions, OIDC authentication, Secrets Manager, health checks, and automated rollback.

---

## Technical Focus

- **Cloud & Networking:** AWS, EKS, Lambda, ECR, EC2, VPC, ALB, RDS, S3, WAF, subnets, NAT, route tables, security groups, DNS
- **Infrastructure as Code & Automation:** Terraform, Ansible, Linux, Bash, YAML
- **Containers & Kubernetes:** Docker, Kubernetes, Helm, HPA, Metrics Server, NetworkPolicy, PodDisruptionBudget
- **CI/CD & GitOps:** Jenkins, GitHub Actions, Argo CD, Git, GitHub
- **Security & Identity:** IAM, IRSA, GitHub OIDC, AWS Secrets Manager, External Secrets Operator, Trivy, SonarQube, Gitleaks
- **Observability & Reliability:** OpenTelemetry, Prometheus, AMP, Grafana, Loki, Tempo, CloudWatch, k6, troubleshooting, reliability testing
- **Development & Testing:** Python, FastAPI, React, TypeScript, PostgreSQL, SQLAlchemy, Alembic, REST APIs, pytest

---

# Featured Projects

## [AssembleMonitor | AWS EKS · Terraform · Jenkins · Argo CD](https://github.com/Aoun62336/AssembleMonitor-DevOps)

Construction-site management system developed during my **Software Developer internship at Noorisys Technologies Pvt. Ltd.**, then extended independently with AWS infrastructure and DevOps automation.

[![AssembleMonitor architecture](https://raw.githubusercontent.com/Aoun62336/AssembleMonitor-DevOps/main/docs/architecture/00-master-overview.png)](https://github.com/Aoun62336/AssembleMonitor-DevOps)

### What I implemented

- **AWS & Terraform:** Provisioned EKS, VPC networking, ALB, WAF, RDS PostgreSQL, S3, IAM, Secrets Manager, CloudWatch, and AMP using Terraform. Refactored networking into a reusable module and added 5 native `terraform test` cases with a mocked AWS provider.

- **Jenkins CI/CD:** Built a 17-stage Jenkins pipeline covering application validation, SonarQube Quality Gate, Trivy filesystem and image scanning, Docker publishing, manual deployment approval, and Git-based Helm image updates.

- **GitHub Actions:** Implemented a 5-job pre-merge workflow covering 23 backend tests, frontend builds, Terraform validation and tests, Helm validation, and Gitleaks scanning.

- **GitOps:** Configured Helm and Argo CD to reconcile the Git-defined Kubernetes state with Amazon EKS.

- **Kubernetes:** Configured resource requests and limits, liveness and readiness probes, Metrics Server, HPA from 2 to 5 replicas at a 70% CPU target, NetworkPolicy, PodDisruptionBudget, and topology-spread controls.

- **Identity & Secrets:** Used EKS OIDC and IRSA for workload AWS access, with AWS Secrets Manager and External Secrets Operator for secret delivery.

- **Observability:** Implemented metrics, logs, and traces using OpenTelemetry, AMP/Prometheus, Grafana, Loki, Tempo, and CloudWatch.

- **Reliability:** Ran controlled PostgreSQL, API, and DNS/configuration failure exercises and documented investigation, recovery, root cause, and operational procedures.

- **Performance & Automation:** Used k6 for load testing and Ansible for selected EC2 configuration tasks.

### Explore AssembleMonitor

[Architecture](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/docs/architecture/ARCHITECTURE.md) ·
[Jenkins Pipeline](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/Jenkinsfile-gitops) ·
[GitHub Actions](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/.github/workflows/pr-validation.yml) ·
[Terraform](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/terraform) ·
[Helm / Kubernetes](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/k8s/helm-chart) ·
[Security](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/docs/architecture/SECURITY.md) ·
[Reliability](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/docs/hardening) ·
[Runbooks](https://github.com/Aoun62336/AssembleMonitor-DevOps/tree/main/docs/ops)

---

## [CallMissed AI Workspace | AWS Lambda · ECR · Terraform · GitHub Actions](https://github.com/Aoun62336/CallMissed-Ai-Workspace)

React and FastAPI application supporting multi-turn chat, image generation, and browser voice interaction through the CallMissed API, with AWS deployment and DevOps automation implemented independently.

### What I implemented

- **Application Delivery:** Containerized the React and FastAPI application using a multi-stage Docker build and deployed the same application image to AWS Lambda.

- **AWS & Terraform:** Provisioned Amazon ECR, Lambda, Function URL, Secrets Manager, CloudWatch, IAM, and supporting configuration using Terraform in `us-east-1`.

- **CI:** Built GitHub Actions checks covering Ruff, 19 pytest tests, frontend production builds, repository and container scanning with Trivy, and Terraform validation.

- **CD:** Used GitHub Actions with AWS OIDC instead of long-lived AWS access keys, published immutable container images to ECR, deployed them to Lambda, and verified health before accepting a release.

- **Rollback:** Captured the previously deployed Lambda image and automatically restored it if deployment health checks failed.

- **Security:** Kept provider credentials server-side in AWS Secrets Manager, added reviewer access protection, request validation, request throttling, signed application sessions, and a switch to disable new paid API requests.

- **Health & Operations:** Implemented separate liveness and readiness endpoints, CloudWatch logging, deployment smoke checks, cost controls, operational runbooks, and teardown procedures.

- **Voice:** Created bounded voice sessions from the backend while browser audio connected directly to the provider media service, with mute, end-session, microphone cleanup, and a 180-second session limit.

### Explore CallMissed AI Workspace

[Repository](https://github.com/Aoun62336/CallMissed-Ai-Workspace) ·
[Architecture](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/docs/ARCHITECTURE.md) ·
[Decisions](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/docs/DECISIONS.md) ·
[CI Workflow](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/.github/workflows/ci.yml) ·
[Deployment Workflow](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/.github/workflows/deploy.yml) ·
[Terraform](https://github.com/Aoun62336/CallMissed-Ai-Workspace/tree/main/infrastructure/terraform) ·
[Runbook](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/docs/RUNBOOK.md) ·
[Test Evidence](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/docs/TEST_EVIDENCE.md)

---

## Professional Experience

### Software Developer Intern | Noorisys Technologies Pvt. Ltd.
`Feb 2026 - May 2026`

- Developed AssembleMonitor using **React, FastAPI, and PostgreSQL** for project, phase, task, material, attendance, expense, site-photo, and scheduling workflows.
- Built REST APIs and database operations using SQLAlchemy and Alembic.
- Implemented JWT authentication and role-based access control for Admin, Project Manager, Site Engineer, and Client roles.
- Documented application APIs using Swagger/OpenAPI and managed source control through Git and GitHub.

### Cloud Support Intern | CanveX
`Jan 2025 - Mar 2025`

- Supported web-hosting environments and website administration across hosting platforms.
- Performed website, file, and database migrations with backups before infrastructure changes.
- Troubleshot website issues during migrations and scheduled updates while coordinating with a remote support team.

---

## Education

### Master of Computer Applications (MCA)
**Dr. B. V. Hiray College of Management & Research Centre**  
Savitribai Phule Pune University  
`2024 - 2026`

### Bachelor of Science in Computer Science (B.Sc. CS)
**M.S.G. Arts, Science and Commerce College**  
Savitribai Phule Pune University  
`2021 - 2024`

---

## Certifications

- **Oracle Cloud Infrastructure Foundations Associate** | Oracle
- **Oracle Cloud Infrastructure AI Foundations Associate** | Oracle
- **Web Technology** | SWAYAM
- **Ethical Hacking** | NPTEL

---

<p align="center">
  <a href="https://www.linkedin.com/in/aoun26">LinkedIn</a>
  ·
  <a href="mailto:aounmd74@gmail.com">Email</a>
  ·
  <a href="https://github.com/Aoun62336/AssembleMonitor-DevOps">AssembleMonitor</a>
  ·
  <a href="https://github.com/Aoun62336/CallMissed-Ai-Workspace">CallMissed AI Workspace</a>
</p>
