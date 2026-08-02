<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Aoun%20Md.&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=DevOps%20%26%20Cloud%20Engineer&descSize=20&descAlignY=58&descColor=a8d8ea&animation=fadeIn" width="100%"/>

<!-- Typing SVG -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Terraform+%7C+EKS+%7C+ArgoCD+GitOps;Jenkins+DevSecOps+Pipelines;OpenTelemetry+Observability;Zero-Secret+Infrastructure+on+AWS;Open+to+DevOps+%2F+Cloud+Engineer+roles" alt="Typing SVG"/>
</p>

<!-- Social Links -->
<p align="center">
  <a href="https://www.linkedin.com/in/aoun26" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:aounmd74@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  &nbsp;
  <a href="https://github.com/Aoun62336/AssembleMonitor-DevOps" target="_blank">
    <img src="https://img.shields.io/badge/Featured%20Project-181717?style=for-the-badge&logo=github&logoColor=white" alt="Featured Project"/>
  </a>
</p>

---

## About

MCA student with hands-on experience designing and operating cloud-native infrastructure on AWS. I have built and shipped a production-grade platform entirely end-to-end — Terraform-provisioned EKS clusters, a 17-stage Jenkins DevSecOps CI pipeline, ArgoCD GitOps delivery, full OpenTelemetry observability across all three signals, and zero-secret-in-Git secrets management via IRSA and the External Secrets Operator.

I am actively seeking **DevOps / Cloud Engineer** roles where I can apply infrastructure automation, GitOps, and reliability engineering at scale.

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

**📊 Observability**

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F79520?style=flat-square&logo=grafana&logoColor=white)

  </td>
  <td valign="top" width="33%">

**🔐 Security**

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

Full-stack construction site management system deployed on **AWS EKS** using a complete GitOps DevSecOps pipeline. Built end-to-end — from infrastructure provisioning to application delivery and observability.

**What's under the hood:**

- 🏗️ **EKS v1.36** — Terraform-provisioned, HPA 2→5 pods, ALB + WAFv2, nightly destroy/rebuild in ~8 min
- 🔄 **17-stage Jenkins CI** — Trivy CVE scan → SonarQube quality gate → Docker build → ArgoCD GitOps sync
- 🔐 **Zero secrets in Git** — ESO + IRSA pulls live from AWS Secrets Manager at pod startup
- 📊 **Full OTel pipeline** — Logs → Loki · Traces → Tempo · Metrics → AMP · Dashboards → Grafana
- 🛡️ **Security-first** — WAFv2 managed rules, IMDSv2 hop-limit=1, IRSA on every service account

<br/>

**→ [View full architecture, documentation & deployment guides](https://github.com/Aoun62336/AssembleMonitor-DevOps)**

<br clear="right"/>

---

## GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Aoun62336&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats"/>
  &nbsp;&nbsp;
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aoun62336&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Aoun62336&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub Streak"/>
</p>

---

## Experience

**Software Developer Intern — Noorisys Technologies Pvt. Ltd.**
`Feb 2026 – May 2026 · Malegaon, India`

Built and shipped full-stack features using React, Python FastAPI, and PostgreSQL. Developed AssembleMonitor as the primary project — subsequently extended its infrastructure independently, applying Terraform, EKS, ArgoCD GitOps, Jenkins pipelines, and full OpenTelemetry observability from the ground up.

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

| Certification                                   | Issuer     |
| :---------------------------------------------- | :--------- |
| AWS Solutions Architecture — Virtual Experience | Forage     |
| OCI Cloud Foundations Associate                 | Oracle     |
| OCI AI Foundations Associate                    | Oracle     |
| Python With AI                                  | SkillEcted |
| Web Technology                                  | Swayam     |
| Ethical Hacking                                 | NPTEL      |

---

## Languages

🗣️ English &nbsp;·&nbsp; Urdu &nbsp;·&nbsp; Hindi &nbsp;·&nbsp; Arabic (Basic)

---

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>
