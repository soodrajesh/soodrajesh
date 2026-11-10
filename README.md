# Rajesh Sood

Senior DevOps Engineer in Dublin, 15+ years in IT. Day job: AWS platform
architecture, vulnerability remediation at scale, and CI/CD for a production
estate. Open to Senior DevOps, SRE, Platform Engineering, Cloud Engineering and
Solutions Architect roles.

Write-ups are on
[irajeshsood.com/blog](https://irajeshsood.com/blog/).

---

## Platform and delivery

- **[gcp-gke-platform-engineering](https://github.com/soodrajesh/gcp-gke-platform-engineering)**: GKE Autopilot developer platform. Pod Security, policy-as-code and Binary Authorization as three separate admission gates; Argo CD; Cloud Deploy canary with a bad-release rollback drill.
- **[gcp-cloudrun-secure-delivery](https://github.com/soodrajesh/gcp-cloudrun-secure-delivery)**: vulnerability gate, two KMS-signed attestations checked by Binary Authorization, digest-pinned canary to Cloud Run.
- **[gcp-keyless-cicd-supply-chain](https://github.com/soodrajesh/gcp-keyless-cicd-supply-chain)**: GitHub Actions to Cloud Run with no stored credentials. Workload Identity Federation pinned to one workflow file, Sigstore signing, SBOM and SLSA provenance, verify-before-deploy.
- **[gcp-network-landing-zone](https://github.com/soodrajesh/gcp-network-landing-zone)**: hub-and-spoke on Network Connectivity Center. Prod and dev reach shared services but not each other.
- **[gcp-sre-reliability-lab](https://github.com/soodrajesh/gcp-sre-reliability-lab)**: SLOs as code, multi-window multi-burn-rate alerts per the SRE Workbook, a live chaos drill, and a Gemini-drafted postmortem.

## AI agents and MCP

- **[gcp-mcp-gateway-gke](https://github.com/soodrajesh/gcp-mcp-gateway-gke)**: one gateway between agents and MCP servers. Short-lived tokens, per-caller tool filtering, upstream calls under the gateway's own identity. agentgateway on GKE Autopilot.
- **[gcp-mcp-platform](https://github.com/soodrajesh/gcp-mcp-platform)**: remote MCP servers on Cloud Run with Google identity tokens verified in-app, per-caller scopes, Firestore rate limiting and a BigQuery audit trail.
- **[gcp-agent-orchestration-platform](https://github.com/soodrajesh/gcp-agent-orchestration-platform)**: multi-agent incident response (ADK, A2A, MCP) with Firestore-checkpointed runs, rollbacks gated on human approval, a spend cap and a kill switch.
- **[gcp-agent-regression-harness](https://github.com/soodrajesh/gcp-agent-regression-harness)**: compares a baseline and a candidate model or prompt over tool-call traces, with statistics deciding regression or not. Runs as a CI gate.
- **[gcp-agent-cost-observability-platform](https://github.com/soodrajesh/gcp-agent-cost-observability-platform)**: token and cost logging to BigQuery for a 3-agent Gemini pipeline, injection and exfiltration guardrails, scheduled LLM-judge evals.
- **[gcp-enterprise-rag-platform](https://github.com/soodrajesh/gcp-enterprise-rag-platform)**: RAG with access control enforced in SQL before retrieval, DLP redaction, CMEK, and no internet route for the model.

## Security and governance tools

Each one reads a project, produces findings, and keeps models away from the decision: a model can explain a result but cannot change it.

- **[gcp-iam-blast-radius](https://github.com/soodrajesh/gcp-iam-blast-radius)**: follows service-account impersonation chains and scores what each identity could become; every least-privilege fix is re-simulated before it is shown.
- **[gcp-plan-review-agents](https://github.com/soodrajesh/gcp-plan-review-agents)**: security, cost, reliability and compliance agents review a Terraform plan; a deterministic judge returns approve / needs_changes / block.
- **[gcp-security-posture-scanner](https://github.com/soodrajesh/gcp-security-posture-scanner)**: Cloud Asset Inventory plus CIS-mapped Rego rules and Checkov in one BigQuery finding schema with open / resolved / reopened lifecycle.
- **[gcp-secrets-sprawl-detector](https://github.com/soodrajesh/gcp-secrets-sprawl-detector)**: leaked credentials in env vars, buckets, logs and VM metadata, ranked by who can read them and what they unlock.
- **[gcp-data-residency-pii-auditor](https://github.com/soodrajesh/gcp-data-residency-pii-auditor)**: finds personal data in BigQuery and GCS and checks region, readers, CMEK and retention against a written policy.
- **[gcp-deploy-risk-scorer](https://github.com/soodrajesh/gcp-deploy-risk-scorer)**: risk score for a diff plus hard flags no model can lower, turned into canary %, bake time and reviewers.
- **[gcp-drift-triage](https://github.com/soodrajesh/gcp-drift-triage)**: adopt / revert / investigate / ignore for each drifted resource, with the change attributed via Cloud Audit Logs.

## Data, serverless and FinOps

- **[gcp-streaming-data-platform](https://github.com/soodrajesh/gcp-streaming-data-platform)**: Pub/Sub with an enforced Avro schema, BigQuery subscription, dead-lettering and replay, PII-masked authorized views.
- **[gcp-serverless-orders-platform](https://github.com/soodrajesh/gcp-serverless-orders-platform)**: Cloud Workflows saga that retries transient failures and compensates business ones; no overselling under a 120-order stress test.
- **[gcp-cloudrun-rightsizer](https://github.com/soodrajesh/gcp-cloudrun-rightsizer)**: replays real traffic through an autoscaling and billing simulator to find the cheapest config that still meets an SLO.
- **[gcp-finops-cost-anomaly-detector](https://github.com/soodrajesh/gcp-finops-cost-anomaly-detector)**: z-score anomaly detection on billing data in a Cloud Run Job, alerting through Pub/Sub.

## Earlier work: AWS and Kubernetes

- **[infra-runbook-rag](https://github.com/soodrajesh/infra-runbook-rag)**: answers on-call questions over an infra repo's own docs and routes Alertmanager alerts to the matching runbook section, with no LLM call on the paging path.
- **[minikube-gitops-platform](https://github.com/soodrajesh/minikube-gitops-platform)**: Argo CD app-of-apps, kube-prometheus-stack and Gatekeeper with a non-root / NetworkPolicy / Trivy baseline.
- **[GitOps-EKS-ArgoCD-Flask-Deployment](https://github.com/soodrajesh/GitOps-EKS-ArgoCD-Flask-Deployment)** · **[Flask-ArgoCD-Kubernetes-Deployment](https://github.com/soodrajesh/Flask-ArgoCD-Kubernetes-Deployment)** · **[Kubernetes-Prometheus-Grafana-Monitoring](https://github.com/soodrajesh/Kubernetes-Prometheus-Grafana-Monitoring)** · **[DevSecOps-Platform-Jenkins-SonarQube](https://github.com/soodrajesh/DevSecOps-Platform-Jenkins-SonarQube)** · **[SageMaker-ML-Pipeline-Terraform-Lambda](https://github.com/soodrajesh/SageMaker-ML-Pipeline-Terraform-Lambda)**
- **[security-findings-classifier](https://github.com/soodrajesh/security-findings-classifier)**: LoRA-tuned DistilBERT that predicts severity, trained on real Trivy findings.

---

**Certifications**

- AWS Certified Solutions Architect – Professional · Amazon Web Services
- AWS Certified Generative AI Developer – Professional · Amazon Web Services · Expires Nov 2029

Previously: Google Cloud Professional Cloud Architect, Oracle OCI Architect Professional, AWS Developer and SysOps Associate. All on [Credly](https://www.credly.com/users/rajeshsood).

**Contact:** [irajeshsood.com](https://irajeshsood.com/portfolio/) · [LinkedIn](https://www.linkedin.com/in/irajeshsood/) · [Medium](https://medium.com/@soodrajesh)
