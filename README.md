<div align="center">

<img src="./assets/banner.svg" alt="Rishikesh Sharma - Principal Cloud Architect &amp; Agentic AI Systems" width="100%" />

<a href="https://readme-typing-svg.demolab.com/">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;weight=600&amp;size=21&amp;pause=1100&amp;color=00E5FF&amp;center=true&amp;vCenter=true&amp;width=900&amp;height=60&amp;lines=Senior+DevSecOps+Engineer+%7C+Cloud+Architect;Microsoft+Azure+%7C+Terraform+IaC+%7C+Zero-Trust+CI%2FCD;Agentic+AI+Engineering+%7C+Model+Context+Protocol+(MCP)+%26+RAG;Migrating+100%2B+Workloads+with+Zero-Downtime;Building+Self-Healing+%26+FinOps-Optimized+Cloud+Platforms" alt="Animated DevSecOps headline" />
</a>

### 🔐 Senior DevSecOps Engineer &amp; Cloud Architect | Agentic AI Systems

**Enterprise Cloud Infrastructure · Zero-Trust Security · GitOps Automation · Autonomous SRE**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white)](https://github.com/RisikeshSharma?tab=repositories)
[![Control Plane](https://img.shields.io/badge/Status-Available_for_Senior_Roles-16803D?style=for-the-badge&amp;logo=opsgenie&amp;logoColor=white)](#-connect)

</div>

---

## 👋 About Me

I am a **Senior DevSecOps Engineer &amp; Cloud Solutions Architect** specializing in production-grade Microsoft Azure infrastructure, multi-cloud landing zones, shift-left pipeline security, and cutting-edge **Agentic AI systems (Model Context Protocol, RAG, and autonomous SRE operations)**.

My architectural background focuses on **governing and migrating mission-critical workloads** to the cloud with zero downtime, enforcing zero-trust infrastructure as code (Terraform), and accelerating engineering delivery cycles while maintaining 100% CIS compliance.

* ☁️ **Cloud &amp; Scale:** Designing enterprise Hub-and-Spoke topologies, Azure Cloud Adoption Framework (CAF) landing zones, and Kubernetes platforms (AKS/EKS).
* 🛡️ **DevSecOps &amp; Supply Chain:** Baking automated security gates (Checkov, Trivy, GitLeaks, OPA Gatekeeper) into Azure DevOps and GitHub Actions CI/CD pipelines.
* 🤖 **Agentic AI &amp; LLMOps:** Implementing **Model Context Protocol (MCP)** and **LangGraph Multi-Agent Swarms** for automated incident triage, root cause analysis (RCA), and self-healing GitOps PR remediation.
* 💰 **FinOps &amp; Cost Governance:** Cutting up to 32% cloud OPEX through automated resource rightsizing, orphan storage cleanup, and predictive CI/CD cost gating.

---

## 🧭 Portfolio Delivery Map

```mermaid
flowchart TD
    subgraph Core["🏛️ Architecture & Governance"]
        A[Rishikesh Sharma Portfolio] --> B[Azure CAF Landing Zones]
        A --> C[Multi-Cloud Workload Migration]
        A --> D[Agentic AI SRE & MCP Platform]
    end

    subgraph DevSecOps["🛡️ DevSecOps & Automation"]
        B --> E[Terraform Modular IaC]
        E --> F[Infracost Budget Gate]
        E --> G[Checkov & Trivy Security Gate]
        G --> H[Azure DevOps / GitHub Pipelines]
    end

    subgraph AI["🤖 Autonomous AI Operations"]
        D --> I[Model Context Protocol Host]
        I --> J[Vector Runbook RAG - Qdrant]
        J --> K[Self-Healing GitOps Hotfix PR]
    end

    subgraph Runtime["☸️ Production Runtime"]
        H --> L[Zero-Trust AKS Cluster]
        K --> L
        L --> M[Cilium eBPF & Vault Secrets]
    end

    classDef blue fill:#0B1F3A,stroke:#0078D4,stroke-width:2px,color:#fff;
    classDef green fill:#052e16,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef purple fill:#2e1065,stroke:#a855f7,stroke-width:2px,color:#fff;
    class A,B,C,E,F,H blue;
    class G,L,M green;
    class D,I,J,K purple;
```

---

## 🧰 Technology Stack

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=azure,aws,terraform,kubernetes,docker,githubactions,git,linux,bash,powershell,python,postgres,prometheus,grafana&amp;perline=7" alt="Technology Stack Icons" />
</a>

</div>

<br/>

| Domain | Skills, Frameworks &amp; Enterprise Tooling |
|---|---|
| ☁️ **Cloud &amp; Architecture** | Microsoft Azure, AWS, Hub-and-Spoke VNets, ExpressRoute, Azure Firewall Premium, Private Endpoints, Azure Landing Zones (CAF), Azure Site Recovery (ASR) |
| 🏗️ **Infrastructure as Code** | Terraform, OpenTofu, Terragrunt, modular design, remote state lease-locking in Azure Blob Storage, drift detection |
| 🔄 **CI/CD &amp; Automation** | GitHub Actions, Azure DevOps Pipelines, multi-stage YAML, reusable workflows, blue/green canary deployments |
| 🔐 **DevSecOps &amp; Supply Chain** | Shift-Left security, Checkov (CIS Benchmarks), Trivy, GitLeaks, SonarQube, OPA Gatekeeper, HashiCorp Vault, Cosign SBOM |
| 🤖 **Agentic AI &amp; LLMOps** | Model Context Protocol (MCP), Multi-Agent Swarms (LangGraph), Vector DBs (Qdrant, ChromaDB), GraphRAG, Ollama, Self-Healing SRE |
| 📦 **Containers &amp; Mesh** | Kubernetes (AKS/EKS), Docker, Helm 3, ArgoCD (GitOps), Cilium eBPF network security, Istio Service Mesh |
| 📊 **Observability &amp; SRE** | Prometheus, Grafana, OpenTelemetry, Azure Monitor, Azure Monitor Agent (AMA), Data Collection Rules (DCR), PagerDuty |
| 💰 **FinOps &amp; Governance** | Infracost pre-merge budget gates, Azure Policy Initiatives, Rightsizing, Reserved Instances (RI), Savings Plans |

---

## 🚀 Featured Enterprise Projects

### 1. 🔐 [`Terraform-Azure-modularInfrastructure-GitHubActionsCICD-multiEnvironment`](https://github.com/RisikeshSharma/Terraform-Azure-modularInfrastructure-GitHubActionsCICD-multiEnvironment)
Production-grade modular Terraform framework implementing Azure infrastructure across multiple environments (Dev, Staging, Prod) with automated GitHub Actions CI/CD workflows.
* **Architecture:** Enterprise modular structure with Azure Blob Storage remote state leasing, parameter validation, and environment isolation.
* **Automation &amp; CI/CD:** Fully automated linting, security scanning, plan generation, and zero-downtime provisioning pipelines.

[**Explore Azure Modular Infrastructure →**](https://github.com/RisikeshSharma/Terraform-Azure-modularInfrastructure-GitHubActionsCICD-multiEnvironment)

---

### 2. ☸️ [`axion-argocd-gitops`](https://github.com/RisikeshSharma/axion-argocd-gitops) &amp; [`Axion_Deployment_Helm`](https://github.com/RisikeshSharma/Axion_Deployment_Helm)
GitOps-driven continuous delivery platform managing microservice deployments with **Argo CD**, Helm 3, and Kubernetes.
* **GitOps Automation:** Declarative configuration management for UI services, telemetry, simulation engines, data ingestion, and PostgreSQL.
* **Zero-Downtime:** Automated drift detection, replica scaling, blue-green sync, and declarative rollout management.

[**Explore ArgoCD GitOps Repository →**](https://github.com/RisikeshSharma/axion-argocd-gitops) · [**Explore Axion Helm Charts →**](https://github.com/RisikeshSharma/Axion_Deployment_Helm)

---

### 3. ☁️ [`Azure_Kubernetes_Infra`](https://github.com/RisikeshSharma/Azure_Kubernetes_Infra) &amp; [`AWS_EKS_Infra`](https://github.com/RisikeshSharma/AWS_EKS_Infra)
Production-ready Kubernetes clusters across Microsoft Azure (AKS) and Amazon Web Services (EKS).
* **Multi-Cloud Container Runtime:** Hardened network security, zero-trust ingress, namespace-level isolation, and external secrets integration.
* **Scalability &amp; Reliability:** Production node pools, auto-scaling controllers, and Prometheus/Grafana observability.

[**Explore Azure AKS Infrastructure →**](https://github.com/RisikeshSharma/Azure_Kubernetes_Infra) · [**Explore AWS EKS Infrastructure →**](https://github.com/RisikeshSharma/AWS_EKS_Infra)

---

### 4. 🏗️ [`Terraform-Code-Practices`](https://github.com/RisikeshSharma/Terraform-Code-Practices)
Curated collection of enterprise Terraform best practices, reusable pattern libraries, and security benchmarks.
* **Best Practices:** Reusable module blueprints, variable validation rules, state locking patterns, and CI/CD security gating.

[**Explore Terraform Code Practices →**](https://github.com/RisikeshSharma/Terraform-Code-Practices)

---

## 🔒 How I Approach DevSecOps

- **Shift-Left Security:** Embed security checks directly into developer workflows (Git pre-commit hooks, SAST, SCA, and IaC scanning).
- **Zero-Trust Identity:** Eliminate permanent elevated privileges using Microsoft Entra ID Privileged Identity Management (PIM) with Just-In-Time access.
- **Immutable Infrastructure as Code:** Enforce version-controlled, modular Terraform modules with remote state lease locking in Azure Blob Storage.
- **Predictive FinOps Gates:** Integrate Infracost directly into pull requests to make cloud expenditure transparent and accountable before merge.
- **Autonomous &amp; Self-Healing Resiliency:** Augment human operators with Model Context Protocol (MCP) agents that safely triage incidents and draft auditable GitOps rollbacks.

---

## 🎯 Current Focus

- Expanding **Model Context Protocol (MCP)** server integrations for multi-cloud telemetry and automated SRE triage.
- Enhancing **eBPF-based observability and security** on Kubernetes using Cilium and OpenTelemetry.
- Developing multi-region disaster recovery frameworks ensuring **RTO &lt; 15 minutes** and **RPO &lt; 5 minutes**.
- Optimizing enterprise **Azure Monitor Agent (AMA)** Data Collection Rules to filter telemetry costs at the ingestion source.

---

## 📈 Engineering Telemetry

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RisikeshSharma&amp;show_icons=true&amp;theme=radical&amp;hide_border=true&amp;include_all_commits=true&amp;count_private=true" alt="Rishikesh Sharma's GitHub Stats" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=RisikeshSharma&amp;theme=radical&amp;hide_border=true" alt="GitHub Streak" width="48%" />

</div>

---

## 🤝 Connect

I welcome conversations regarding Cloud Architecture, Enterprise DevSecOps transformations, Kubernetes platforms, and Autonomous AI/LLMOps infrastructure.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-RisikeshSharma-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white)](https://github.com/RisikeshSharma)
[![Email](https://img.shields.io/badge/Email-Direct_Inquiry-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white)](mailto:srishikesh39@gmail.com)

<br/>

<img src="./assets/footer.svg" alt="Rishikesh Sharma Control Plane" width="100%" />

</div>
