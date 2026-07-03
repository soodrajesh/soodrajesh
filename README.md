# Rajesh Sood

Senior DevOps / Cloud Engineer, Dublin — 15+ years on AWS, GCP, Azure, and OCI.
Kubernetes, Terraform, and the CI/security tooling around them, plus recent work on
GenAI platform engineering (Bedrock, SageMaker). Looking at Staff / Solutions
Architect roles next.

## Repos

**Kubernetes & GitOps**
- [GitOps-EKS-ArgoCD-Flask-Deployment](https://github.com/soodrajesh/GitOps-EKS-ArgoCD-Flask-Deployment) — Terraform-provisioned EKS + ECR, ArgoCD reconciling plain manifests. CI runs real tests and `terraform validate` on every push.
- [Flask-ArgoCD-Kubernetes-Deployment](https://github.com/soodrajesh/Flask-ArgoCD-Kubernetes-Deployment) — same GitOps loop, built around Kustomize and a working GitHub Actions pipeline instead.

**DevSecOps & CI/CD**
- [DevSecOps-Platform-Jenkins-SonarQube](https://github.com/soodrajesh/DevSecOps-Platform-Jenkins-SonarQube) — self-hosted Jenkins, SonarQube, and shift-left scanners on a single EC2 host.

**ML / GenAI platform**
- [Bedrock-Terraform-Infrastructure](https://github.com/soodrajesh/Bedrock-Terraform-Infrastructure) — IAM-scoped Terraform for Bedrock access, with a CLI smoke test against Claude.
- [AWS-Sagemaker-MLOps-Pipeline](https://github.com/soodrajesh/AWS-Sagemaker-MLOps-Pipeline) — SageMaker training pipeline (XGBoost + a custom PyTorch container).
- [SageMaker-ML-Pipeline-Terraform-Lambda](https://github.com/soodrajesh/SageMaker-ML-Pipeline-Terraform-Lambda) — the Lambda-orchestrated alternative to the repo above, built to compare the two approaches.

**Observability & cost**
- [Kubernetes-Prometheus-Grafana-Monitoring](https://github.com/soodrajesh/Kubernetes-Prometheus-Grafana-Monitoring) — Helm-based Prometheus/Grafana/Alertmanager stack; CI renders the chart on every push.
- [aws-cost-optimization](https://github.com/soodrajesh/aws-cost-optimization) — Python CLI, not a Terraform demo: scans an account for waste, prices findings against the live AWS pricing API. 54 tests, all run in CI.

**Infrastructure as Code**
- [Terraform-Terragrunt-AWS-MultiEnv-S3](https://github.com/soodrajesh/Terraform-Terragrunt-AWS-MultiEnv-S3) — multi-environment Terragrunt layout.
- [crossplane-demo](https://github.com/soodrajesh/crossplane-demo) — the same AWS provisioning problem via Crossplane instead of Terraform, for comparison.

## Certifications

- AWS Solutions Architect – Professional (current)
- Previously certified: Microsoft Azure, Google Cloud Professional Architect, Oracle OCI Architect

Verified badges: [Credly](https://www.credly.com/users/rajeshsood/badges/credly)

## Contact

[LinkedIn](https://linkedin.com/in/irajeshsood) · [Medium](https://medium.com/@soodrajesh) · [rajeshsood1987@gmail.com](mailto:rajeshsood1987@gmail.com)
