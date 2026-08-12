# Rajesh Sood

Senior DevOps Engineer, Dublin — 15+ years on AWS. Own platform architecture,
security remediation at scale, and CI/CD for a production estate at Workday.
Recent focus: AI/ML infrastructure — production inference wired into CI/CD on
Bedrock, SageMaker training pipelines. Open to Staff/Senior DevOps, Platform
Engineering, and AI/ML Infrastructure roles.

---

## AI/ML Platform
- **[Bedrock-Terraform-Infrastructure](link)** — IAM-scoped Terraform for Bedrock access, with a CLI smoke test against Claude.
- **[AWS-Sagemaker-MLOps-Pipeline](link)** — SageMaker training pipeline (XGBoost + custom PyTorch container).
- **[SageMaker-ML-Pipeline-Terraform-Lambda](link)** — same problem, Lambda-orchestrated — built as a second approach to compare against the pipeline above.

## Kubernetes & GitOps
- **[GitOps-EKS-ArgoCD-Flask-Deployment](link)** — Terraform-provisioned EKS + ECR, ArgoCD reconciling plain manifests. CI runs real tests and `terraform validate` on every push.
- **[Flask-ArgoCD-Kubernetes-Deployment](link)** — same GitOps loop, built around Kustomize and GitHub Actions instead.

## Security & CI/CD
- **[DevSecOps-Platform-Jenkins-SonarQube](link)** — self-hosted Jenkins, SonarQube, and shift-left scanners on a single EC2 host.

## Observability & Cost
- **[Kubernetes-Prometheus-Grafana-Monitoring](link)** — Helm-based Prometheus/Grafana/Alertmanager stack; CI renders the chart on every push.
- **[aws-cost-optimization](link)** — Python CLI (not a Terraform demo) that scans an account for waste and prices findings against the live AWS pricing API. 54 tests, all run in CI.

## Infrastructure as Code
- **[Terraform-Terragrunt-AWS-MultiEnv-S3](link)** — multi-environment Terragrunt layout.
- **[crossplane-demo](link)** — the same AWS provisioning problem via Crossplane, for comparison against Terraform.

---

**Certifications:** AWS Solutions Architect – Professional (current) · Previously: Microsoft Azure, Google Cloud Professional Architect, Oracle OCI Architect. Verified badges: [Credly](link)

**Contact:** [LinkedIn](link) · [Medium](link)
