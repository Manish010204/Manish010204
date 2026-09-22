<div align="center">

# Hey, I'm Manish Kumar Thakur 👋

### Cloud & DevOps Engineer | AWS Certified Solutions Architect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manish-thakur-lpu/)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:p2004.manishthakur@gmail.com)
[![AWS SAA](https://img.shields.io/badge/AWS_SAA-Certified-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://drive.google.com/file/d/1wHWnIq8x9wYhg2vQvt35clTA81AcNnAX/view)

</div>

---

## About Me

Final year CSE student at Lovely Professional University passionate about building production-grade cloud infrastructure and automating everything. I build things that actually run on AWS — not just tutorials.

- 🔭 Currently building: **Cost & Security Governance Dashboard on AWS**
- 🏗️ Just shipped: **Production-grade 3-tier AWS infrastructure with Terraform**
- ☁️ Certified: **AWS Solutions Architect – Associate**
- 📍 Based in: **India** | Open to remote roles

---

## Tech Stack

**Cloud**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazonaws&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)

**DevOps & IaC**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**Security**

![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## Featured Projects

### 🏗️ [Production-Grade Multi-Tier AWS Infrastructure](https://github.com/Manish010204/aws-multitier-infra)

> 3-tier AWS infrastructure built entirely with modular Terraform

```
Internet → ALB (public subnets) → EC2 ASG (private subnets) → RDS MySQL (isolated)
                                        ↓
                          CloudWatch → SNS → Email Alerts
```

**What makes it real:**
- Provisioned **43 AWS resources** across 2 AZs using 4 Terraform modules
- Defense-in-depth: EC2 SG → ALB SG chaining, zero public IPs on app/db tier
- 5 CloudWatch alarms with SNS email alerting
- CI/CD via GitHub Actions — validates Terraform on every push
- Remote state in S3 with DynamoDB locking

`Terraform` `AWS` `VPC` `ALB` `ASG` `RDS` `CloudWatch` `SNS` `GitHub Actions`

---

### 🔒 [Production-Grade DevSecOps CI/CD Pipeline](https://github.com/Manish010204/Production-Grade-DevSecOps-CI-CD-Pipeline-on-AWS-)

> Security-first CI/CD pipeline blocking vulnerabilities before they reach production

**What makes it real:**
- 6-stage pipeline: Code → SAST → SCA → Image Scan → Deploy → Validate
- SonarQube (SAST) + Trivy (SCA + image scanning) with automated security gates
- Hardened Docker images to AWS ECR → EKS with IAM + RBAC least-privilege
- Blocks vulnerable container images from reaching production EKS cluster

`Jenkins` `SonarQube` `Trivy` `Docker` `AWS ECR` `EKS` `IAM` `RBAC`

---

### 🤖 [LLM-Driven AIOps for Kubernetes](https://github.com/Manish010204)

> Self-hosted LLM-based AIOps — no cloud AI APIs, full privacy

**What makes it real:**
- Self-hosted LLaMA for real-time RCA across 10+ microservices
- Closed-loop MAPE-K auto-remediation reducing MTTR by ~40%
- Chaos Mesh for controlled failure injection and testing

`Kubernetes` `LLaMA` `Python` `Chaos Mesh` `Docker`

---

## Certifications

| Certification | Issuer | Date |
|---|---|---|
| [AWS Certified Solutions Architect – Associate](https://drive.google.com/file/d/1wHWnIq8x9wYhg2vQvt35clTA81AcNnAX/view) | Amazon Web Services | May 2026 |
| [AWS Networking Zero to Hero](https://drive.google.com/file/d/1W3Ovt0CQV5CZLTssRaJkDtRg91OfCSI1/view) | Udemy | Mar 2026 |
| [AWS Solutions Architect Training](https://drive.google.com/file/d/1v63bBm64ZURpeMgKzJnRfuQ0CmcJWTjz/view) | AWS Student Program | Jan 2026 |

---

## GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=Manish010204&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Manish010204&theme=tokyonight" alt="Top Languages" />

</div>

---

## What I'm Looking For

Open to **Cloud Engineer**, **DevOps Engineer**, and **Junior SRE** roles where I can build and operate real infrastructure at scale.

<div align="center">

**Let's connect →** [LinkedIn](https://www.linkedin.com/in/manish-thakur-lpu/) | [Email](mailto:p2004.manishthakur@gmail.com)

</div>
