<h1 align="center">Grewanderer</h1>

<p align="center">
  <strong>Senior Backend / Platform Engineer</strong><br/>
  Go · Rust · Python · Distributed Systems · Embedded Linux · Kubernetes · Reliability · Secure Infrastructure · ML Infrastructure
</p>

<p align="center">
  <a href="mailto:rewanderer@proton.me">rewanderer@proton.me</a> · Remote · Backend · Platform · Systems · Infrastructure
</p>

<p align="center">
  <a href="https://github.com/AnimusHQ/mllaboratory">ML Infrastructure Laboratory</a> ·
  <a href="https://github.com/grewanderer/animus_coder">Agentic Engineering Core</a> ·
  <a href="https://github.com/grewanderer?tab=repositories">Repositories</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go-backend%20systems-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go backend systems" />
  <img src="https://img.shields.io/badge/Rust-systems%20engineering-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust systems engineering" />
  <img src="https://img.shields.io/badge/Python-automation%20%7C%20ML%20infra-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python automation and ML infrastructure" />
  <img src="https://img.shields.io/badge/Linux-platform%20engineering-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux platform engineering" />
  <img src="https://img.shields.io/badge/Kubernetes-execution%20platforms-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes execution platforms" />
  <img src="https://img.shields.io/badge/Buildroot-embedded%20Linux-2A9D8F?style=flat-square&logo=linux&logoColor=white" alt="Buildroot embedded Linux" />
  <img src="https://img.shields.io/badge/PostgreSQL-state%20%7C%20audit-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL state and audit" />
  <img src="https://img.shields.io/badge/OpenTelemetry-observability-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry observability" />
</p>

---

## Profile

I build backend and platform systems where correctness, reproducibility, observability, and operational control are design requirements.

My strongest axis is **Go backend engineering** for distributed, integration-heavy, and hardware-adjacent systems. I use **Rust** for systems and protocol-oriented components, and **Python** for automation, ML infrastructure, evaluation workflows, and operational tooling.

I am most useful where product requirements meet runtime constraints: control planes, execution systems, Linux platforms, deployment pipelines, hardware-adjacent services, secure infrastructure, and production failure modes.

---

## Engineering Surface

| Surface | What I build and reason about |
|---|---|
| **Backend systems** | API platforms, service boundaries, explicit state machines, idempotent workflows, compatibility, failure semantics |
| **Platform engineering** | Linux runtime environments, reproducible builds, deployment automation, CI/CD gates, release evidence, operational ownership |
| **Embedded Linux** | Buildroot-based systems, root filesystem composition, firmware artifacts, QEMU validation, constrained-device services |
| **Reliability** | observability-first design, structured diagnostics, deterministic failure reporting, regression safety, incident feedback loops |
| **Security & networking** | secure transport, authentication, authorization, policy enforcement, deny-by-default exposure, protocol-heavy integrations |
| **ML infrastructure** | reproducible runs, dataset/artifact versioning, metadata truth, execution evidence, evaluation automation, controlled workloads |

---

## Public Work

### [ML Infrastructure Laboratory](https://github.com/AnimusHQ/mllaboratory)

Kubernetes-backed ML infrastructure for reproducible and auditable machine-learning workflows.

Engineering signal:

- Go service architecture with explicit **Control Plane / Data Plane** separation
- PostgreSQL-backed metadata, policy, audit, execution evidence, and integrity fields
- Kubernetes execution model for isolated workloads
- S3-compatible artifact and object-storage mediation
- Helm-based deployment model
- OIDC, RBAC, deny-by-default authorization, and internal service boundaries
- CI, security, supply-chain, deployment, and operations documentation discipline

### [Agentic Engineering Core](https://github.com/grewanderer/animus_coder)

Policy-first agentic coding infrastructure built around local execution, guarded automation, proof bundles, replay, and memory-as-code.

Engineering signal:

- k3s-based isolated execution profile
- default-deny egress model for runner jobs
- Git access through scoped internal proxying instead of uncontrolled direct transport
- append-style EventLog, Proof Bundle, Replay, and hash-checked execution evidence
- memory-as-code with guarded writes and provenance
- Helm-oriented deployment and runtime schema validation

---

## Technical Stack

**Languages:** Go, Rust, Python  
**Backend:** REST, gRPC, WebSockets, event-driven systems, message-driven systems, Clean Architecture, pragmatic DDD  
**Data:** PostgreSQL, MySQL, SQLite, Redis, Kafka, RabbitMQ, S3-compatible object storage  
**Platform:** Linux, Docker, Docker Compose, Kubernetes, Helm, Kustomize, Buildroot, QEMU  
**Delivery:** GitHub Actions, GitLab CI, Jenkins, Zuul, reproducible builds, deployment validation, release gates  
**Observability:** Prometheus, Grafana, OpenTelemetry, ELK, structured logs, metrics, traces  
**Security:** TLS, DTLS, OIDC, JWT, RBAC, ACLs, policy enforcement, controlled service exposure  
**ML Infrastructure:** PyTorch, ONNX, ONNX Runtime, data pipelines, experiment automation, evaluation workflows  

---

## Systems and Domains

- backend platforms for distributed and integration-heavy systems
- Linux-based embedded platforms and firmware delivery pipelines
- network operating system and command-conformance tooling
- secure overlay networking and controlled service access
- Kubernetes-backed ML infrastructure and experiment orchestration
- NAS, access-control, video/security, power-control, and device-management systems
- audio classification and signal-processing pipelines
- computer-vision inference infrastructure

---

## Engineering Principles

- Runtime behavior matters more than repository aesthetics.
- Parser support is not feature support; runtime effect and readback matter.
- A control plane should own truth; execution environments should report evidence.
- A production deployment needs rollback, observability, state ownership, and failure semantics.
- Logs, metrics, traces, and audit records are design surfaces.
- Reproducibility is a debugging and accountability mechanism, not a tooling preference.
- Security boundaries should be explicit enough to test and boring enough to operate.

---

## Fit

Strong match for teams building backend, platform, infrastructure, embedded Linux, reliability, secure networking, or ML infrastructure systems where implementation depth and architectural ownership are both required.

Relevant roles: **Senior Backend Engineer**, **Go Backend Engineer**, **Platform Engineer**, **Infrastructure Engineer**, **Systems Engineer**, **Rust Systems Engineer**, **Embedded Linux Engineer**, **Reliability Engineer**, **ML Infrastructure Engineer**, **Secure Infrastructure Engineer**.

---

<p align="center">
  <sub>
    I build systems that stay correct, observable, reproducible, and operable after the first implementation has shipped.
  </sub>
</p>
