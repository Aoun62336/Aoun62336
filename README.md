# Aoun Md. | Cloud & DevOps Engineer

**Malegaon, Maharashtra, India**

Open to **Cloud Engineering, DevOps, Infrastructure, and Cloud Support** opportunities.

[**Portfolio**](https://aoun62336.github.io/) · [LinkedIn](https://www.linkedin.com/in/aoun26/) · [Email](mailto:aounmd74@gmail.com) · [Resume](https://aoun62336.github.io/resume/Aoun_MD_Resume.pdf)

I work with AWS infrastructure, Terraform, Linux, Docker, Kubernetes, CI/CD, and GitOps. My background includes internships in DevOps, software development, and cloud support.

My projects focus on how applications are deployed, secured, monitored, and verified. I document the engineering decisions, implementation details, testing evidence, and limitations behind the work.

---

## Featured Engineering Projects

### 01. [AssembleMonitor](https://github.com/Aoun62336/AssembleMonitor-DevOps)

**AWS EKS · Terraform · Jenkins · Argo CD · Observability**

A construction management application I contributed to during my software development internship at Noorisys Technologies. I subsequently implemented its AWS infrastructure and DevOps workflows independently.

- **Infrastructure:** Used Terraform to configure AWS resources around an existing default VPC, including EKS, ALB, WAF, RDS PostgreSQL, S3, IAM, and supporting networking.
- **CI/CD and GitOps:** Implemented GitHub Actions validation and a 17-stage Jenkins release pipeline. Argo CD reconciles approved Helm configuration changes to EKS.
- **Security and observability:** Configured IRSA, Secrets Manager, External Secrets Operator, Trivy scanning, OpenTelemetry, Grafana, Loki, Tempo, and Amazon Managed Prometheus.
- **Verification:** Documented pipeline checks, Terraform tests, and controlled reliability exercises. Database, API, and DNS fault drills were conducted in a separate local Docker Compose environment.

<p align="center">
  <a href="https://aoun62336.github.io/work/assemblemonitor/">
    <img
      src="https://raw.githubusercontent.com/Aoun62336/Aoun62336.github.io/master/src/assets/project-media/assemblemonitor-aws.png"
      alt="AssembleMonitor AWS architecture showing EKS, VPC networking, ALB, RDS, and supporting AWS services"
      width="520"
    />
  </a>
</p>  

**[Case Study](https://aoun62336.github.io/work/assemblemonitor/)** · [Source Code](https://github.com/Aoun62336/AssembleMonitor-DevOps) · [Architecture](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/docs/architecture/ARCHITECTURE.md) · [GitOps Pipeline](https://github.com/Aoun62336/AssembleMonitor-DevOps/blob/main/Jenkinsfile-gitops)

### 02. [RenewGrid](https://github.com/Aoun62336/RenewGrid-DevOps)

**GitHub Actions · Jenkins · Docker · Terraform · AWS EC2**

An e-waste management application used to implement, troubleshoot, and verify different container delivery and infrastructure automation workflows during my DevOps internship.

- **GitHub Actions:** Automated application validation, security scanning, versioned GHCR image publication, and ephemeral Docker Compose verification.
- **Jenkins:** Built a self-managed CI/CD pipeline on AWS EC2, including testing, Trivy scanning, SBOM generation, Docker Hub publication, and Compose deployment.
- **Terraform:** Managed a separate local Docker Compose environment declaratively, including resource lifecycle and state reconciliation.
- **Verification:** The documented Jenkins Build #7 completed successfully on October 24, 2026, including 26 passing backend tests, frontend validation, security checks, and deployment verification.

These were separate delivery implementations using the same application, not consecutive stages of one production pipeline.

<p align="center">
  <a href="https://aoun62336.github.io/work/renewgrid/">
    <img
      src="https://raw.githubusercontent.com/Aoun62336/Aoun62336.github.io/master/src/assets/project-media/renewgrid-delivery.png"
      alt="RenewGrid engineering diagram showing CI/CD, container delivery, and Terraform workflows"
      width="520"
    />
  </a>
</p>

**[Case Study](https://aoun62336.github.io/work/renewgrid/)** · [GitHub Actions Repository](https://github.com/Aoun62336/RenewGrid-DevOps) · [Jenkins & Terraform Repository](https://github.com/Aoun62336/RenewGrid-Terraform-IaC) · [Verification Evidence](https://github.com/Aoun62336/RenewGrid-Terraform-IaC/blob/main/evidence/jenkins/jenkins-verification.md)

### 03. [CallMissed AI Workspace](https://github.com/Aoun62336/CallMissed-Ai-Workspace)

**AWS Lambda · ECR · Terraform · GitHub Actions · OIDC**

A React and FastAPI AI workspace supporting chat, image generation, and browser-based voice sessions through an external provider API. I implemented its serverless AWS delivery and operational controls.

- **Serverless deployment:** Packaged the application as a container image and deployed it to AWS Lambda using Terraform-managed infrastructure.
- **CI/CD:** Implemented GitHub Actions validation, Trivy scanning, immutable ECR image publication, and AWS deployment authentication through OIDC.
- **Security and operations:** Used Secrets Manager, request controls, application health checks, CloudWatch logging, and previous-image rollback logic.
- **Verification:** Recorded 19 passing backend tests, provider smoke checks, and a previous-image rollback and restoration exercise. The automatic health-failure rollback path is implemented but was not established by that particular drill.

<p align="center">
  <a href="https://aoun62336.github.io/work/callmissed/">
    <img
      src="https://raw.githubusercontent.com/Aoun62336/Aoun62336.github.io/master/src/assets/project-media/callmissed-runtime.png"
      alt="CallMissed serverless runtime architecture showing the application and AWS Lambda integration"
      width="520"
    />
  </a>
</p> 

**[Case Study](https://aoun62336.github.io/work/callmissed/)** · [Source Code](https://github.com/Aoun62336/CallMissed-Ai-Workspace) · [Architecture Decisions](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/docs/DECISIONS.md) · [Test Evidence](https://github.com/Aoun62336/CallMissed-Ai-Workspace/blob/main/docs/TEST_EVIDENCE.md)

---

## Technical Skills

| Area | Technologies |
|---|---|
| **Cloud & Infrastructure** | AWS, EC2, EKS, Lambda, VPC, ALB, RDS, S3, IAM, Terraform |
| **CI/CD & Containers** | GitHub Actions, Jenkins, Docker, Kubernetes, Helm, Argo CD, GHCR, ECR |
| **Security & Observability** | Trivy, SonarQube, Gitleaks, Secrets Manager, IRSA, OpenTelemetry, Prometheus, Grafana, Loki, Tempo, CloudWatch |
| **Development & Operations** | Linux, Bash, Python, FastAPI, React, TypeScript, PostgreSQL, pytest, Ansible |

---

## Professional Experience

**DevOps Intern | Elevate Labs**  
*October 2026*

Implemented CI/CD workflows for RenewGrid using GitHub Actions and Jenkins. Worked with Docker image publication, AWS EC2 deployment verification, Terraform-managed local infrastructure, automated testing, security scanning, and troubleshooting.

**Software Developer Intern | Noorisys Technologies Pvt. Ltd.**  
*February 2026 to May 2026*

Contributed to AssembleMonitor using React, FastAPI, and PostgreSQL, including application workflows, database operations, APIs, authentication, and role-based access control. Independently implemented its AWS and DevOps infrastructure after the internship.

**Cloud Support Intern | CanveX**  
*January 2025 to March 2025*

Supported web-hosting operations, website and database migrations, backups, content verification, and technical troubleshooting.

---

## Education

**Master of Computer Applications (MCA)**  
Dr. B. V. Hiray College of Management & Research Centre  
Savitribai Phule Pune University | 2024 to 2026

**Bachelor of Science in Computer Science**  
M.S.G. Arts, Science and Commerce College  
Savitribai Phule Pune University | 2021 to 2024

---

## Certifications

- Oracle Cloud Infrastructure 2025 Certified Foundations Associate
- Oracle Cloud Infrastructure 2025 Certified AI Foundations Associate
- Web Technology | SWAYAM
- Ethical Hacking | NPTEL

---

For detailed architecture diagrams, engineering decisions, implementation evidence, and technical articles, visit my **[Cloud & DevOps Portfolio](https://aoun62336.github.io/)**.
