<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=900&lines=Hi%20there%2C%20I%27m%20Abdul%20Rafay;AWS%20Solutions%20Architect;DevOps%20Engineer;I%20fix%20production%20at%203AM%20so%20you%20don%27t%20have%20to" alt="Typing SVG" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00D9FF&height=150" width="100%"/>

</div>

## 👨‍💻 About Me

I'm a **Cloud Architect and DevOps Engineer** based in Pakistan (APAC), working remotely with clients worldwide and available for onsite roles in the EU. I design, deploy, and rescue AWS infrastructure, from serverless pipelines to 173-bucket cross-account replication setups for SaaS platforms serving clients like **Novartis, Roche, and UBS**.

- 🔭 Currently freelancing as an **AWS Solutions Architect & DevOps Engineer** on Upwork
- ☁️ Core stack: **AWS** (Lambda, S3, ECS Fargate, RDS, IAM, EventBridge) + **Python / Go / Node.js**
- 🚨 I like production incidents. Restored a 3.8GB image library in under an hour, and traced a 15-day silent data-loss bug to a rogue cron job in just 6 hours
- 🐛 Two of my bug reports made it into upstream open source, one merged by the founder himself (details below)
- 📜 **AWS Certified Solutions Architect · Associate** · **AWS Certified DevOps Engineer · Professional** · **ISC2 CC**
- 📫 Reach me at **Rafay@abdulrafay.tech**

<br/>

## 🛠️ Tech Stack

<div align="center">

**Cloud & Infra**
<br/>
![AWS](https://custom-icon-badges.demolab.com/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Languages**
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Frontend**
<br/>
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Databases**
<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**CI/CD & Monitoring**
<br/>
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

</div>

<br/>

## 🐛 Open Source Contributions

Two production bugs I diagnosed on client engagements turned into confirmed fixes in upstream repos:

| Project | What happened | Proof |
|---|---|---|
| **[Forem](https://github.com/forem/forem)** (the engine behind DEV.to) | Found a Ruby constant-scoping bug crashing the admin panel with a 500 error. Filed the report, a contributor submitted the fix, and it was merged into `forem:main` **by Forem's founder, Ben Halpern**. | [Issue #23386](https://github.com/forem/forem/issues/23386) · [PR #23491](https://github.com/forem/forem/pull/23491) |
| **[RedAmon](https://github.com/samugit83/redamon)** (security automation platform) | Diagnosed a Docker Compose dependency-ordering race condition breaking GVM/PostgreSQL on every boot. Filed a detailed report; the maintainer's fix was **merged within 4 days**. | [Issue #115](https://github.com/samugit83/redamon/issues/115) · [Commit 6a75ce1](https://github.com/samugit83/redamon/commit/6a75ce19c0b5849b556a9a5422bf9e1e435b3076) |

<br/>

## 🚀 Highlighted Engagements

<table>
<tr>
<td width="50%" valign="top">

### 🏥 DocLift, Swiss SaaS (Novartis, Roche, UBS)
Architected cross-account S3 replication across **173 bucket pairs / 206K+ objects (~140GB)**. Built a 5-script Python/boto3 automation suite, deployed an EventBridge → Lambda pipeline for new tenants, and later traced a silent 15-day data-loss incident to a rogue cron job in **6 hours** using delete-marker forensics.

`AWS S3` `boto3` `EventBridge` `CloudTrail` `IAM`

</td>
<td width="50%" valign="top">

### ⚡ Insomniacs.party, Disaster Recovery
Emergency-recovered a **3.8GB / 200K+ file** image library on a revenue site (~$1K/day) within **one hour**, scripting bulk delete-marker removal and eliminating 80K+ duplicate objects from a sync-plugin bug.

`AWS S3` `Python (boto3)` `Lifecycle Rules` `Glacier`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💰 Confidential, $1M+/day Trading Infra
Designed least-privilege **IAM + Secrets Manager** architecture for API keys backing $1M+/day in trading exposure. My credential-fetch recommendation was adopted **over** the dev team's own implementation plan.

`Secrets Manager` `IAM` `KMS`

</td>
<td width="50%" valign="top">

### 🔋 ChargeOnSite, EV Charging SaaS
Audited a **21-service ECS Fargate** environment, cut ECR storage from 3TB down to a lifecycle-managed state (**$89 → $3/mo**), and flagged **$25.9K/year** in optimization opportunities in an out-of-scope cost report.

`ECS Fargate` `ECR` `OpenSearch` `Cost Optimization`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ RedAmon, Security Automation (Cyprus)
Diagnosed a `service_started` vs `service_healthy` Docker Compose race condition breaking GVM/PostgreSQL on boot. Filed a bug report that was merged upstream within 4 days.

`Docker Compose` `GVM/OpenVAS` `Neo4j` `PostgreSQL`

</td>
<td width="50%" valign="top">

### 📝 Forem, DEV.to's Engine (UK)
Deployed Forem on DigitalOcean via Fedora CoreOS/Podman, engineered a snapshot-transfer workaround for API-key restrictions, and got a Ruby scoping bug fix merged into `forem:main` by the founder.

`Fedora CoreOS` `Podman` `Ansible` `Traefik`

</td>
</tr>
</table>

<br/>

## 🤝 Connect With Me

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Rafay@abdulrafay.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafay-cloud/)
[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/rafaycloudawsdevops)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://abdulrafay.tech)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,100:0D1117&height=100"/>
