# Rajesh Sood

Senior DevOps / Cloud Engineer, Dublin. 15+ years building and running infrastructure
on AWS, with Azure, GCP, and OCI along the way — Kubernetes, Terraform, and the
security/CI tooling around them. More recently that's extended into platform
engineering for teams adopting Bedrock and SageMaker: the interesting part isn't
calling the model API, it's the IAM boundaries, the cost controls, and the CI/CD
around it that make it something a team can run, not just a notebook that works once.

I'm currently looking at Staff / Solutions Architect roles. Rather than claim that
title, here's the specific evidence for why I think I'm ready for it:

- **I evaluate architectures, not just build one.** Several repos below deliberately
  implement the same problem two different ways so the tradeoff is explicit instead
  of assumed — a managed-pipeline vs. Lambda-orchestrated approach to the same
  SageMaker training problem, Terraform vs. Crossplane for the same AWS provisioning.
  A Solutions Architect's job is comparing options and defending a choice; this is
  what that looks like in practice, not just in a slide.
- **Security and cost are design inputs, not a follow-up pass.** IAM roles are split
  by blast radius (a Lambda that can start a training job can't touch anything else
  in SageMaker), ECR repos carry lifecycle policies, and one whole repo
  ([aws-cost-optimization](https://github.com/soodrajesh/aws-cost-optimization)) exists
  because I'd rather automate the boring part of a cost review than do it in a
  spreadsheet by hand.
- **I audit at the scope of a portfolio, not one project.** This year I went through
  every repo below, actually ran the tools (`terraform validate`, real test suites,
  linters, checkov) instead of eyeballing the code, and fixed what they found — a
  production Terragrunt environment with a completely empty `variables.tf`, a
  Terraform provider config with a dependency cycle, a metrics endpoint that worked
  under the dev server but 500'd under gunicorn. That's the same kind of pass a Staff
  engineer runs across a team's systems during a reliability push, or a Solutions
  Architect runs during technical due diligence — I just ran it on my own portfolio
  first. Every repo's "Known gaps" section is the honest result of that pass, not a
  template.
- **Multi-cloud experience is certified where it counts.** Professional-level AWS
  (Solutions Architect) is current; I've also previously held certifications across
  GCP, Azure, and OCI — see below.

## Repos

**Kubernetes & GitOps**
- [GitOps-EKS-ArgoCD-Flask-Deployment](https://github.com/soodrajesh/GitOps-EKS-ArgoCD-Flask-Deployment) — Terraform-provisioned EKS + ECR, ArgoCD reconciling plain manifests. CI runs real tests and `terraform validate` on every push.
- [Flask-ArgoCD-Kubernetes-Deployment](https://github.com/soodrajesh/Flask-ArgoCD-Kubernetes-Deployment) — same GitOps loop, built around Kustomize and a working GitHub Actions pipeline instead.

**DevSecOps & CI/CD**
- [DevSecOps-Platform-Jenkins-SonarQube](https://github.com/soodrajesh/DevSecOps-Platform-Jenkins-SonarQube) — self-hosted Jenkins, SonarQube, and a stack of shift-left scanners on a single EC2 host, with the tradeoffs of that "single-host POC" choice written down, not hidden.

**ML / GenAI platform**
- [Bedrock-Terraform-Infrastructure](https://github.com/soodrajesh/Bedrock-Terraform-Infrastructure) — IAM-scoped Terraform for Bedrock access, with a CLI smoke test against Claude.
- [AWS-Sagemaker-MLOps-Pipeline](https://github.com/soodrajesh/AWS-Sagemaker-MLOps-Pipeline) — SageMaker training pipeline (XGBoost + a custom PyTorch container), Terraform + shell end to end.
- [SageMaker-ML-Pipeline-Terraform-Lambda](https://github.com/soodrajesh/SageMaker-ML-Pipeline-Terraform-Lambda) — the Lambda-orchestrated alternative to the repo above, built specifically to compare the two approaches.

**Observability & cost**
- [Kubernetes-Prometheus-Grafana-Monitoring](https://github.com/soodrajesh/Kubernetes-Prometheus-Grafana-Monitoring) — Helm-based Prometheus/Grafana/Alertmanager stack; CI actually renders the chart on every push, not just lints the YAML.
- [aws-cost-optimization](https://github.com/soodrajesh/aws-cost-optimization) — a Python CLI, not a Terraform demo: scans an account for waste, prices findings against the live AWS pricing API, turns it into a PDF. 54 tests, all run in CI.

**Infrastructure as Code**
- [Terraform-Terragrunt-AWS-MultiEnv-S3](https://github.com/soodrajesh/Terraform-Terragrunt-AWS-MultiEnv-S3) — multi-environment Terragrunt layout (the repo where the audit pass caught the empty prod `variables.tf` mentioned above).
- [crossplane-demo](https://github.com/soodrajesh/crossplane-demo) — the same AWS resource provisioning problem via Crossplane instead of Terraform, for comparison.

## Certifications

- AWS Solutions Architect – Professional (current)
- Previously certified: Microsoft Azure, Google Cloud Professional Architect, Oracle OCI Architect

Verified badges: [Credly](https://www.credly.com/users/rajeshsood/badges/credly)

## Contact

[LinkedIn](https://linkedin.com/in/irajeshsood) · [Medium](https://medium.com/@soodrajesh) · [rajeshsood1987@gmail.com](mailto:rajeshsood1987@gmail.com)
