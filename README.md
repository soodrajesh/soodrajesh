# Hey there! 👋 I'm Raj

<div align="center">

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Cloud+Engineering+%26+DevOps+Expert;AI%2FML+Enthusiast;10%2B+Years+of+Experience;Kubernetes+%26+Terraform+Specialist)

**Cloud Engineering & DevOps Specialist | Building Infrastructure that scales**

_Been doing this for 10+ years, still learning every day_

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/irajeshsood)

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:soodrajesh87@gmail.com)

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/soodrajesh)

[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@soodrajesh)

</div>

---

## About Me

I'm a cloud engineer who's been building infrastructure for over a decade. I spend most of my time working with AWS, Kubernetes, Terraform, and lately a lot of AI/ML infra. I like solving real problems, not just deploying fancy tech for the sake of it.

**What I care about:**

- **Actually solving problems** - I try to focus on what the business needs, not just what's cool

- **AI/ML in production** - Been working with ML infrastructure for a while now, and it's been interesting figuring out how to make it work reliably

- **Multi-cloud reality** - Most companies use more than one cloud, so I've gotten comfortable with AWS, Azure, and GCP

- **Security from the start** - Learned the hard way that bolting security on later doesn't work well

```yaml
what_i_work_with:
  clouds: ["AWS", "Azure", "GCP"]
  infrastructure: ["Terraform", "Terragrunt", "CloudFormation"]
  containers: ["Kubernetes", "EKS", "Docker"]
  ai_ml: ["SageMaker", "Bedrock", "OpenAI"]
  gitops: ["ArgoCD", "Helm", "Kustomize"]
  monitoring: ["Prometheus", "Grafana", "CloudWatch"]
  ci_cd: ["GitHub Actions", "Jenkins", "Artifactory"]
```

### What I Actually Do

- **ML Infrastructure** - Setting up the plumbing so ML models can run in production without breaking

- **Multi-cloud setups** - Building solutions that works across different clouds because that's usually what companies need

- **Automation** - Writing scripts and pipelines so we don't have to do the same thing manually 50 times

- **Monitoring** - Making sure we know when things break before users do

- **Security** - Trying to build things securely from the beginning (easier said than done)

- **Cost Optimization** - Helped cut costs by about 45% at one place by just being smarter about how we used resources

---

## Tech Stack

<div align="center">

### ☁️ Clouds I Work With

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

### 🏗️ Infrastructure

![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

### 🔄 CI/CD & Automation

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

### 🤖 ML & AI

![SageMaker](https://img.shields.io/badge/Amazon_SageMaker-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

![Bedrock](https://img.shields.io/badge/Amazon_Bedrock-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

### 💻 Languages & Scripts

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)

### 📊 Monitoring

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)

</div>

---

## Some Projects I've Built

<div align="center">

**Solutions I've actually deployed and used | Open source repos | Real code**

</div>

---

### 1. 🤖 [AI Document Processing Platform](https://github.com/soodrajesh/mcp-ecs-s3-api-poc)

**MCP Server with S3 Integration**

Built an MCP server that lets AI models (via Bedrock) read and summarize files from S3. Used ECS Fargate, Lambda, and API Gateway because serverless is usually simpler.

**Tech:** `AWS ECS` `Bedrock` `S3` `Lambda` `API Gateway` `Terraform` `Docker` `Python`

**What it does:**

- MCP server that talks to Amazon Bedrock for document processing.

- When files get uploaded to S3, Lambda processes them automatically.

- ECS Fargate service that scales up/down as needed

- API Gateway with API keys (because security matters)

- CloudWatch monitoring and SNS alerts.

- All infrastructure in Terraform.

**Check it out if you want to see:** How to set up MCP servers, Terraform configs, and monitoring that actually works

---

### 2. 🚀 [ML Infrastructure Platform](https://github.com/soodrajesh/my-cloud-ai-demo)

**EKS + SageMaker + API Gateway**

End-to-end ML setup with EKS, SageMaker, and API Gateway. Has GitHub Actions for CI/CD and scripts to deploy everything with one command.

**Tech:** `AWS EKS` `SageMaker` `S3` `API Gateway` `Terraform` `GitHub Actions` `Docker` `Python`

**What it does:**

- Terraform scripts to spin up an EKS cluster automatically

- SageMaker for training and deploying models

- S3 for storing data and model artifacts

- API Gateway to expose models via REST API

- GitHub Actions pipeline that deploys infrastructure and models

- One command to set everything up (with validation and cleanup)

- Proper error handling (because things always break)

**Worth looking at for:** Deployment scripts, CI/CD workflows, and how to actually run ML models in production

---

### 3. 🎯 [OpenAI on Kubernetes](https://github.com/soodrajesh/openai-eks-project1)

**Flask API with GPT-4o mini on EKS**

Simple Flask API using OpenAI's GPT-4o mini, containerized and running on EKS. Nothing fancy, just works.

**Tech:** `AWS EKS` `Kubernetes` `OpenAI API` `Flask` `Docker` `GitHub Actions`

**What it does:**

- Flask API that calls OpenAI GPT-4o mini for text generation

- Dockerized for easy deployment

- Runs on EKS

- GitHub Actions for CI/CD

- Simple endpoint that takes prompts and returns generated text

- Basic K8s manifests (deployment and service)

**Good for seeing:** How to deploy a simple API on Kubernetes, GitHub Actions setup, and Flask integration

---

### 4. 📊 [K8s Monitoring Stack](https://github.com/soodrajesh/k8s-grafana-prometheus)

**Prometheus & Grafana for Kubernetes**

Monitoring setup for K8s clusters with Prometheus, Grafana, AlertManager, and the usual observability tools.

**Tech:** `Kubernetes` `Prometheus` `Grafana` `AlertManager` `Helm` `Node Exporter` `kube-state-metrics`

**What it does:**

- Prometheus collecting and storing metrics

- Grafana dashboards to visualize everything

- AlertManager for notifications (so I don't have to watch dashboards 24/7)

- Node Exporter for host metrics

- kube-state-metrics for K8s object monitoring

- Blackbox Exporter to check if endpoints are up

- Helm charts for easy deployment

- RBAC and security policies included (because default K8s security isn't great)

**Useful for:** Setting up monitoring, Helm charts, and dashboards that actually show useful info

---

### 5. 🔄 [ArgoCD Setup](https://github.com/soodrajesh/argocd-setup)

**ArgoCD for Enterprise K8s**

ArgoCD setup with security, automation, and monitoring. Made it so you can deploy with one command.

**Tech:** `ArgoCD` `Kubernetes` `RBAC` `Prometheus` `OIDC` `TLS`

**What it does:**

- ArgoCD installation that runs with one command

- RBAC policies and network security configured

- Supports multiple environments (dev/staging/prod)

- High availability for production

- Prometheus metrics integration

- Automated backups (because losing configs sucks)

- OIDC integration for authentication

**Check it out for:** Security configs, automation scripts, and how to set up ArgoCD properly

---

**Note:** All these repos have actual code, Terraform configs, and docs. Feel free to use them, fork them, or just see how I did things.

---

## Some Numbers

<div align="center">

| Thing | What I Did | Result |

|:---|:---|:---|

| Cost Optimization | Made infrastructure smarter | **Saved ~45% on ops costs** |

| Reliability | Built HA architectures | **Got to 99.9% uptime** |

| Deployment Speed | Automated CI/CD | **Deployments 80% faster** |

| Security | Security-first design | **Zero security incidents** |

| Scale | Multi-region deployments | **Global reach** |

| ML Ops | Production ML pipelines | **Automated model serving** |

</div>

---

## Why I'm Different (I Guess?)

- **I focus on solving problems** - Not just deploying tech for the sake of it

- **Security matters** - I try to build things securely from the start

- **Always learning** - The cloud world changes fast, so I keep up with new tools

- **I share what I learn** - Write on Medium sometimes, help teams when I can

- **Practical over perfect** - Sometimes good enough is actually good enough

---

## What I'm Into

I write about and work on:

- **Cloud architecture** - How to design solutions that actually scales

- **DevOps practices** - Automation and CI/CD that doesn't suck

- **Cloud security** - Building secure infrastructure

- **Cost optimization** - Making cloud bills less painful

- **MLOps** - Getting ML models to production without too much pain

**[Read my blogs on Medium](https://medium.com/@soodrajesh)**

---

## What I'm Working On Now

- **MLOps** - Making ML pipelines that don't break in production

- **Zero Trust** - Security architectures that make sense

- **Cost** - FinOps and cloud cost management

- **Green cloud** - Trying to be more efficient with resources

---

## Certifications

<div align="center">

### 🎖️ AWS

![AWS Solutions Architect Professional](https://img.shields.io/badge/AWS-Solutions%20Architect%20Professional-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

![AWS Developer Associate](https://img.shields.io/badge/AWS-Developer%20Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

![AWS SysOps Administrator Associate](https://img.shields.io/badge/AWS-SysOps%20Administrator%20Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

### 🌐 Other Clouds

![Google Cloud Professional Cloud Architect](https://img.shields.io/badge/GCP-Professional%20Cloud%20Architect-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

![Microsoft Azure Infrastructure](https://img.shields.io/badge/Azure-Implementing%20Infrastructure%20Solutions-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

![Alibaba Cloud Associate](https://img.shields.io/badge/Alibaba%20Cloud-Associate-FF6A00?style=for-the-badge&logo=amazon-aws&logoColor=white)

### 🔗 Networking & Oracle

![Aviatrix Multi-Cloud Network Associate](https://img.shields.io/badge/Aviatrix-Multi--Cloud%20Network%20Associate-00A1C9?style=for-the-badge&logo=aviatrix&logoColor=white)

![Oracle Cloud Developer 2020](https://img.shields.io/badge/Oracle%20Cloud-Developer%202020%20Associate-F80000?style=for-the-badge&logo=oracle&logoColor=white)

![Oracle Cloud Foundations 2020](https://img.shields.io/badge/Oracle%20Cloud-Foundations%202020%20Associate-F80000?style=for-the-badge&logo=oracle&logoColor=white)

**[All my certs on Credly](https://www.credly.com/users/rajeshsood/badge)**

</div>

---

## Let's Talk!

Always happy to chat about cloud, DevOps, or whatever. If you're working on:

- **Cloud architecture** - Need help designing something?

- **Infrastructure optimization** - Want to make things faster/cheaper?

- **DevOps** - Setting up CI/CD or automation?

- **AI/ML infrastructure** - Getting models into production?

**Hit me up!**

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/irajeshsood)

[![Email](https://img.shields.io/badge/Send_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:soodrajesh87@gmail.com)

[![Medium](https://img.shields.io/badge/Read_My_Blog-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@soodrajesh)

</div>

---

<div align="center">

_"The best way to predict the future is to build it."_

**⭐ Star my repos if you find them useful!**

</div>

