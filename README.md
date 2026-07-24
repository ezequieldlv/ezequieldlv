# Hi there, I'm Ezequiel! 👋

**Systems Engineering Student @ UTN FRC | SRE & DevSecOps Engineer**

I design, automate, and secure hybrid cloud-native infrastructure. My engineering focus is centered around eliminating toil, enforcing zero-trust networking boundaries, and implementing fully autonomous GitOps pipelines.

---

### 🛡️ Core Infrastructure & Projects (The Prime Triad)

*   **[mysstic-cloud](https://github.com/ezequieldlv/mysstic-cloud-iac)**
    *Tier-3 Enterprise AWS Architecture via Terraform & Ansible.*
    Provisions a modular and isolated environment (Public DMZ + Isolated Private Subnets) using secure AWS OIDC federation. Integrates shift-left security (Trufflehog & Checkov) and state-locking via DynamoDB. Implements a serverless event-driven alerting architecture (CloudWatch Alarms ➡️ SNS ➡️ Python Lambda) pushing real-time infrastructure alerts directly to Telegram.

*   **[portfolio-sre](https://github.com/ezequieldlv/portfolio-sre)**
    *High-Performance Cloud-Native Portfolio & Live Telemetry API.*
    A production-ready monorepo combining a static frontend (Hugo running on version-pinned Alpine Nginx with strict security headers) and a backend application layer (Golang REST microservice exposing server metrics). Audited via DevSecOps pipelines with QEMU multi-architecture builds, Hadolint, and Trivy vulnerability scanning. Fully automated via GitOps pull-agents (Watchtower).

*   **[mysstic-edge](https://github.com/ezequieldlv/ez-lab)**
    *Cloud-Native Edge Infrastructure & Home Lab.*
    A bare-metal microservices environment running headless on a Raspberry Pi 5. Configured via modular Docker Compose (IaC basics) and protected under Zero-Trust principles bypassing ISP CGNAT via Cloudflare Tunnels and Tailscale Mesh VPN. Features deep observability and automated self-healing mechanisms driven by custom Python scripts, Prometheus, and Grafana.

---

### 🏛️ Enterprise, Academic & Documentation Ecosystems

*   **[logistics-microservices-platform](https://github.com/ezequieldlv/logistics-microservices-platform)**
    *Distributed Enterprise Architecture | Major Academic Project.*
    An advanced distributed system built with Java Spring Boot, focused on scalability, enterprise pattern design, and containerization. Integrates Docker environments and secure identity/access management utilizing Keycloak.

*   **[knowledge-base-system](https://github.com/ezequieldlv/knowledge-base-system)**
    *Internal Documentation Platform using Docs-as-Code.*
    An automated system powered by MkDocs Material to migrate legacy knowledge structures into a markdown-based, git-versioned pipeline, dramatically optimizing technical troubleshooting search paths.

---

### 🛠️ Technical Arsenal

| Category | Technologies & Tools |
| :--- | :--- |
| **Cloud & OS** | ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white) ![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat&logo=debian&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white) |
| **Infrastructure as Code** | ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=flat&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=flat&logo=ansible&logoColor=white) |
| **Containers & GitOps** | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232088FF.svg?style=flat&logo=githubactions&logoColor=white) |
| **Languages & Scripting** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![Golang](https://img.shields.io/badge/go-%2300ADD8.svg?style=flat&logo=go&logoColor=white)  ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=java&logoColor=white) ![Bash](https://img.shields.io/badge/bash-%234EAA25.svg?style=flat&logo=gnu-bash&logoColor=white) |
| **Databases & Security** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=flat&logo=mysql&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale-5433FF?style=flat&logo=tailscale&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white) |

---

### 🔍 Current Focus & Philosophy

*   🛠️ **Active Workflow:** Building `mysstic-sentinel` (automated edge vulnerability scanning layer) and migrating local Docker workloads towards lightweight Kubernetes clusters (K3s).
*   🧠 **Philosophy:** *"Lo que no estás cambiando, lo estás eligiendo."*
*   💬 **Fun fact:** I treat my hardware nodes as immutable infrastructure; if a config drifts, I rewrite the playbook, I don't patch it via SSH.

*Let's build scalable, resilient, and secure systems together. 🚀*
