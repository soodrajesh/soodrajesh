# Raj Sood

<div align="center">

**Cloud Engineer | DevOps | AI/ML Infrastructure**

Building infrastructure that doesn't wake you up at 3 AM

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/irajeshsood)
[![Email](https://img.shields.io/badge/Email-Let's_Talk-D14836?style=flat-square&logo=gmail)](mailto:soodrajesh87@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-Read-12100E?style=flat-square&logo=medium)](https://medium.com/@soodrajesh)

</div>

---

## What I Do

I build cloud infrastructure that scales, where you're dealing with millions of users, unpredictable traffic.

Over the past 10+ years, I've worked with companies trying to figure out Kubernetes, migrate to the cloud, or get their ML models to actually work in production. I spend my time in AWS, Azure, and GCP, writing Terraform configs, Python/Bash scripts, fixing broken pipelines, and occasionally explaining to developers why they can't just SSH into production servers.

### Here's What I'm Good At

**Cloud Infrastructure** - I've designed and built systems across AWS, Azure, and GCP. Multi-cloud isn't a buzzword for me; it's what happens when your company acquires another company that uses a different cloud provider.

**Kubernetes & Containers** - EKS, AKS, GKE—pick your flavor. I've set up clusters, debugged networking issues at 2 AM.

**AI/ML Operations** - Getting a model to 95% accuracy in a Jupyter notebook is cool. Getting it to serve predictions reliably in production? That's where the real work starts. I build the infrastructure that makes ML teams productive.

**Cost Optimization** - I once cut infrastructure costs by 45% (finance team, they loved it). Turns out, you don't need a m5.24xlarge instance to run a cron job.

**Security** - I implement security from day one, not as an afterthought when the CISO sends an angry email. IAM policies, network segmentation, secrets management—the boring stuff that keeps you from becoming a headline.

```yaml
daily_tools:
  clouds: [AWS, Azure, GCP]
  iac: [Terraform, Terragrunt, CloudFormation]
  kubernetes: [EKS, Helm, ArgoCD, Kustomize]
  ai_ml: [SageMaker, Bedrock, OpenAI API]
  cicd: [GitHub Actions, Jenkins, Artifactory]
  monitoring: [Prometheus, Grafana, CloudWatch, Datadog]
  languages: [Python, Bash, YAML (yes, YAML counts)]
```

---

## Projects Worth Checking Out

### [AI Document Processing with MCP Server](https://github.com/soodrajesh/mcp-ecs-s3-api-poc)

Built an MCP server that lets Claude and other AI models read and summarize documents from S3. Uses ECS Fargate, Lambda, API Gateway, and Bedrock. Everything's in Terraform because clicking buttons in the console doesn't scale.

**Why it matters:** Shows how to integrate AI into real workflows without reinventing the wheel.

**Tech:** AWS ECS, Bedrock, S3, Lambda, API Gateway, Terraform, Docker, Python

---

### [ML Infrastructure Platform](https://github.com/soodrajesh/my-cloud-ai-demo)

Complete ML platform with EKS, SageMaker, and API Gateway. Has CI/CD via GitHub Actions and deployment scripts that actually work. Made it so data scientists can deploy models without needing to understand Kubernetes networking.

**Why it matters:** Bridges the gap between ML development and production.

**Tech:** AWS EKS, SageMaker, S3, API Gateway, Terraform, GitHub Actions, Docker, Python

---

### [OpenAI on Kubernetes](https://github.com/soodrajesh/openai-eks-project1)

Flask API using GPT-4o mini, containerized and running on EKS. Nothing fancy—just a straightforward example of how to deploy an AI-powered API without overcomplicating things.

**Why it matters:** Sometimes you just need a working example, not a framework.

**Tech:** AWS EKS, Kubernetes, OpenAI API, Flask, Docker, GitHub Actions

---

### [Kubernetes Monitoring Stack](https://github.com/soodrajesh/k8s-grafana-prometheus)

Prometheus, Grafana, and AlertManager for Kubernetes. Configured with the metrics that actually matter, not just the defaults that come out of the box.

**Why it matters:** You can't fix what you can't measure.

**Tech:** Kubernetes, Prometheus, Grafana, AlertManager, Helm, Node Exporter

---

### [ArgoCD for GitOps](https://github.com/soodrajesh/argocd-setup)

Production-ready ArgoCD setup with RBAC, monitoring, and security policies. One-command deployment that doesn't skip the important stuff.

**Why it matters:** GitOps done right makes everyone's life easier.

**Tech:** ArgoCD, Kubernetes, RBAC, Prometheus, OIDC, TLS

---

## What I've Shipped

- **Saved 45% on cloud costs** at a previous company by rightsizing instances, fixing inefficient queries, and getting rid of resources nobody remembered creating.

- **Built a multi-region ML platform** that serves predictions globally with <100ms latency. Because users don't care about your architecture—they care about speed.

- **Achieved 99.9% uptime** for production services through proper monitoring, failover strategies, and learning from every incident.

- **Deployed zero-trust security** across multiple environments. Security isn't a feature; it's a requirement.

- **Automated deployments** that cut release time from hours to minutes. Developers actually thank me for this one.

---

## Certifications (Because Sometimes They Matter)

**AWS:** Solutions Architect Professional, Developer Associate, SysOps Administrator Associate

**Google Cloud:** Professional Cloud Architect

**Azure:** Implementing Infrastructure Solutions

**Others:** Aviatrix Multi-Cloud Network Associate, Oracle Cloud Developer & Foundations, Alibaba Cloud Associate

[See all my certs on Credly](https://www.credly.com/users/rajeshsood/badge)

---

## What I'm Working On Now

Right now, I'm focused on MLOps and zero-trust security architectures. MLOps because getting models into production is still way harder than it should be. Zero-trust because the "trust the internal network" approach stopped working around 2015.

I also write about cloud engineering and DevOps on [Medium](https://medium.com/@soodrajesh). Sharing what I've learned (and the mistakes I've made) so others don't have to repeat them.

---

## Let's Work Together

If you're dealing with:
- Cloud infrastructure that's become a mess
- ML models stuck in development
- CI/CD pipelines that break more than they help
- AWS bills that make your CFO cry
- Security audits that keep finding issues

I've probably dealt with something similar. Let's talk.

**Email:** [soodrajesh87@gmail.com](mailto:soodrajesh87@gmail.com)

**LinkedIn:** [linkedin.com/in/irajeshsood](https://linkedin.com/in/irajeshsood)

**Medium:** [medium.com/@soodrajesh](https://medium.com/@soodrajesh)

---

<div align="center">

**If you find any of my repos useful, star them. If you find bugs, open an issue. If you want to chat, send me an email.**

</div>
