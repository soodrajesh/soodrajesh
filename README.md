# Rajesh Sood

Senior DevOps Engineer, Dublin — 15+ years in IT, deep AWS focus. Own platform
architecture, security remediation at scale, and CI/CD for a production estate
at Workday. Recent focus: AI-assisted infra tooling and FinOps — a RAG CLI for
on-call runbooks, a cost auditor that prices its own findings. Open to
Staff/Senior DevOps, SRE, Cloud Engineering, Platform Engineering, and
Solutions Architect roles.

---

## Observability, Cost & On-Call

- **[infra-runbook-rag](https://github.com/soodrajesh/infra-runbook-rag)** — CLI + Streamlit UI that answers on-call questions over an infra repo's own docs, with local embeddings and answers cited back to the exact section.
- **[aws-cost-optimization](https://github.com/soodrajesh/aws-cost-optimization)** — Python CLI (not a Terraform demo) that scans an account for waste and prices findings against the live AWS pricing API — PDF report, ROI per fix, 54 tests, all run in CI.
- **[Kubernetes-Prometheus-Grafana-Monitoring](https://github.com/soodrajesh/Kubernetes-Prometheus-Grafana-Monitoring)** — Helm-based Prometheus/Grafana/Alertmanager stack; CI renders the chart on every push.

## GitOps & Kubernetes

- **[minikube-gitops-platform](https://github.com/soodrajesh/minikube-gitops-platform)** — ArgoCD app-of-apps + kube-prometheus-stack + Gatekeeper, non-root/NetworkPolicy/Trivy baseline enforced on every sync.
- **[Flask-ArgoCD-Kubernetes-Deployment](https://github.com/soodrajesh/Flask-ArgoCD-Kubernetes-Deployment)** — GitHub Actions → ArgoCD → Kubernetes, Kustomize overlays split by dev/prod.
- **[GitOps-EKS-ArgoCD-Flask-Deployment](https://github.com/soodrajesh/GitOps-EKS-ArgoCD-Flask-Deployment)** — Terraform-provisioned EKS + ECR feeding the same ArgoCD loop; CI runs real tests and `terraform validate` on every push.

## Security & CI/CD

- **[DevSecOps-Platform-Jenkins-SonarQube](https://github.com/soodrajesh/DevSecOps-Platform-Jenkins-SonarQube)** — self-hosted Jenkins, SonarQube, and shift-left scanners (Checkov, Semgrep, OWASP Dependency-Check) on a single EC2 host.

---

**Certifications:** AWS Solutions Architect – Professional (current) · Previously: Microsoft Azure, Google Cloud Professional Architect, Oracle OCI Architect. Verified badges: [Credly](https://www.credly.com/users/rajeshsood/badges/credly)

**Contact:** [LinkedIn](https://linkedin.com/in/irajeshsood) · [Medium](https://medium.com/@soodrajesh)
