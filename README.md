# Rajesh Sood

Cloud and DevOps Engineer based in Dublin, Ireland. I've spent most of my career building and
running infrastructure on AWS, with Azure, GCP, and OCI along the way — Kubernetes,
Terraform, CI/CD, and more recently the platform engineering work that comes with
teams adopting Bedrock and SageMaker for GenAI/ML workloads.

## What I work on

- Multi-cloud infrastructure and IaC (Terraform, Terragrunt, CloudFormation, Crossplane)
- Kubernetes and GitOps (EKS, Helm, ArgoCD)
- DevSecOps and CI/CD (Jenkins, GitHub Actions, SonarQube, Checkov/Snyk-style scanning)
- SRE and observability (Prometheus, Grafana, cost and reliability tooling)
- ML/GenAI platform engineering (SageMaker, Bedrock, IAM boundaries around model access)

## A few repos worth a look

- [GitOps-EKS-ArgoCD-Flask-Deployment](https://github.com/soodrajesh/GitOps-EKS-ArgoCD-Flask-Deployment) — Terraform-provisioned EKS cluster and ECR registry, ArgoCD watching plain Kubernetes manifests for the deploy loop.
- [Flask-ArgoCD-Kubernetes-Deployment](https://github.com/soodrajesh/Flask-ArgoCD-Kubernetes-Deployment) — a second GitOps setup, this one with a real GitHub Actions pipeline feeding ArgoCD via Kustomize.
- [DevSecOps-Platform-Jenkins-SonarQube](https://github.com/soodrajesh/DevSecOps-Platform-Jenkins-SonarQube) — self-hosted Jenkins and SonarQube on EC2 with a set of shift-left security scanners wired in.
- [Bedrock-Terraform-Infrastructure](https://github.com/soodrajesh/Bedrock-Terraform-Infrastructure) — IAM-scoped Terraform for Bedrock access, with a CLI smoke test against Claude.
- [Kubernetes-Prometheus-Grafana-Monitoring](https://github.com/soodrajesh/Kubernetes-Prometheus-Grafana-Monitoring) — a Helm-based Prometheus/Grafana/Alertmanager stack for cluster observability.
- [aws-cost-optimization](https://github.com/soodrajesh/aws-cost-optimization) — a Python CLI that audits an AWS account for waste and prices findings against the live Price List API.
- [Terraform-Terragrunt-AWS-MultiEnv-S3](https://github.com/soodrajesh/Terraform-Terragrunt-AWS-MultiEnv-S3) — a small multi-environment Terragrunt layout for S3-backed state.

Most of these are personal builds rather than production systems — each README is
upfront about what's real versus what's a placeholder, and what I'd change given more
time.

## Certifications

- AWS Solutions Architect – Professional
- AWS Developer Associate
- AWS SysOps Administrator Associate
- Google Cloud Professional Architect
- Azure Implementing Infrastructure Solutions
- Oracle Cloud Developer & Foundations
- Aviatrix Multi-Cloud Network Associate

## Contact

[LinkedIn](https://linkedin.com/in/rajeshsood) · [soodrajesh87@gmail.com](mailto:soodrajesh87@gmail.com)
