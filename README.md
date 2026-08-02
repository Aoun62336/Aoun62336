# Aoun Md. &nbsp;·&nbsp; DevOps & Cloud Engineer

<p>
  <a href="https://www.linkedin.com/in/aoun26" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  &nbsp;
  <a href="mailto:aounmd74@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/></a>
  &nbsp;
  <a href="https://github.com/Aoun62336/AssembleMonitor-DevOps" target="_blank"><img src="https://img.shields.io/badge/Featured%20Project-181717?style=flat-square&logo=github&logoColor=white" alt="Featured Project"/></a>
</p>

Cloud-native infrastructure engineer building production-grade platforms on AWS — end-to-end, from IaC provisioning to GitOps delivery and full observability. I treat infrastructure as a product: automated, secure by design, and observable by default.

Open to **DevOps / Cloud Engineer** roles. → [aounmd74@gmail.com](mailto:aounmd74@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aoun26)

---

## Core Stack

<table>
  <tr>
    <td valign="top" width="33%">

**☁️ Cloud & IaC**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

  </td>
  <td valign="top" width="33%">

**☸️ Containers & Orchestration**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

  </td>
  <td valign="top" width="33%">

**🔄 CI/CD & GitOps**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1D4B8F?style=flat-square&logoColor=white)

  </td>
</tr>
<tr>
  <td valign="top" width="33%">

**📊 Observability & Reliability**

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F79520?style=flat-square&logo=grafana&logoColor=white)

  </td>
  <td valign="top" width="33%">

**🔐 DevSecOps & Security**

![IRSA](https://img.shields.io/badge/IRSA-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![WAF](https://img.shields.io/badge/AWS%20WAF-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![ESO](https://img.shields.io/badge/Ext.%20Secrets%20Op.-EF7B4D?style=flat-square&logo=argo&logoColor=white)

  </td>
  <td valign="top" width="33%">

**💻 Languages & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

  </td>
</tr>
</table>

---

## Featured Project

<a href="https://github.com/Aoun62336/AssembleMonitor-DevOps">
  <img align="right" width="420" src="https://raw.githubusercontent.com/Aoun62336/AssembleMonitor-DevOps/main/docs/architecture/01-system-context.jpeg" alt="AssembleMonitor Architecture"/>
</a>

### [AssembleMonitor — Cloud-Native Construction Platform](https://github.com/Aoun62336/AssembleMonitor-DevOps)

Full-stack construction site management system deployed on **AWS EKS** using a complete GitOps DevSecOps pipeline. Built end-to-end — from infrastructure provisioning to application delivery and observability — with a focus on security-by-design and operational reliability.

**What's under the hood:**

- 🏗️ **EKS** — Terraform-provisioned; HPA scales 2→5 pods under load; ALB + WAFv2; nightly destroy/rebuild completes in ~8 min, validating full IaC reproducibility
- 🔄 **17-stage Jenkins CI** — Shift-left security: Trivy CVE scan → SonarQube quality gate → Docker build → ArgoCD GitOps sync; Git is the single source of truth for all deployments
- 🔐 **Zero secrets in Git** — ESO + IRSA pulls live credentials from AWS Secrets Manager at pod startup; every service account scoped with least-privilege IRSA
- 📊 **Full OTel pipeline** — Logs → Loki · Distributed Traces → Tempo · Metrics → AMP · Dashboards → Grafana; SLO/SLI definitions drive alert burn-rate rules
- 🛡️ **Security-first** — WAFv2 managed rules, IMDSv2 hop-limit=1, IRSA on every service account, automated vulnerability scanning on every pipeline run

<br/>

**→ [View full architecture, documentation & deployment guides](https://github.com/Aoun62336/AssembleMonitor-DevOps)**

<br clear="right"/>

---

## Experience

**Software Developer Intern — Noorisys Technologies Pvt. Ltd.**
`Feb 2026 – May 2026 · Malegaon, India`

Built and shipped full-stack features using React, Python FastAPI, and PostgreSQL. Developed AssembleMonitor as the primary project — subsequently extended its infrastructure independently, owning the full delivery lifecycle: Terraform provisioning, EKS cluster management, ArgoCD GitOps pipelines, 17-stage Jenkins CI, and a full OpenTelemetry observability stack on AWS.

**Web Hosting & Cloud Support Intern — CanveX**
`Jan 2025 – Mar 2025 · Remote`

Managed web hosting environments for client operations. Executed cross-platform asset and file migrations, resolved production issues on client sites, and maintained uptime during live updates.

---

## Education

🎓 **Master of Computer Applications (MCA)** — Dr. B. V. Hiray College of Management and Research Center
`2024 – Present · Malegaon, Maharashtra`

🎓 **B.Sc. Computer Science** — M.S.G Arts, Science, and Commerce College
`2021 – 2024 · Malegaon, Maharashtra · CGPA: 7.69`

---

## Certifications

| Certification                                   | Issuer     | Relevance                          |
| :---------------------------------------------- | :--------- | :--------------------------------- |
| AWS Solutions Architecture — Virtual Experience | Forage     | Cloud architecture & AWS services  |
| OCI Cloud Foundations Associate                 | Oracle     | Multi-cloud fundamentals           |
| OCI AI Foundations Associate                    | Oracle     | AI/ML on cloud platforms           |
| Python With AI                                  | SkillEcted | Automation & scripting             |
| Web Technology                                  | Swayam     | Full-stack fundamentals            |
| Ethical Hacking                                 | NPTEL      | Security mindset & threat modeling |

---

## Languages

🗣️ English &nbsp;·&nbsp; Urdu &nbsp;·&nbsp; Hindi &nbsp;·&nbsp; Arabic (Basic)
