<h1 align="center">Grewanderer</h1>

<p align="center">
  <strong>Senior Backend / Platform Engineer</strong><br/>
  Go · Rust · Python · Distributed Systems · Kubernetes · Linux · Reliability · Secure Infrastructure · ML Infrastructure
</p>

<p align="center">
  <a href="mailto:rewanderer@proton.me">Email</a>
  ·
  <a href="https://kapakka.org">Website</a>
  ·
  <a href="https://github.com/grewanderer/animus-amity">Amity</a>
  ·
  <a href="https://github.com/grewanderer/animus-link">Animus Link</a>
  ·
  <a href="https://github.com/AnimusHQ/mllaboratory">ML Infrastructure Laboratory</a>
  ·
  <a href="https://github.com/grewanderer/animus-datalab-sdk">DataLab SDK</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go-backend-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go backend" />
  <img src="https://img.shields.io/badge/Rust-systems-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust systems" />
  <img src="https://img.shields.io/badge/Python-automation%20%7C%20ML%20infra-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python automation and ML infrastructure" />
  <img src="https://img.shields.io/badge/Kubernetes-platform-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes platform" />
  <img src="https://img.shields.io/badge/OpenTelemetry-observability-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry observability" />
</p>

---

## Focus

I build backend and platform systems where correctness, reliability, observability, and operational control are part of the architecture rather than afterthoughts.

My strongest axis is **Go backend engineering** for distributed, integration-heavy, and infrastructure-adjacent systems. I use **Rust** for systems and protocol-oriented components, and **Python** for automation, ML infrastructure, evaluation workflows, and operational tooling.

I work best on systems with real runtime constraints: control planes, execution platforms, Linux-based infrastructure, secure service exposure, reproducible delivery, hardware-adjacent services, and production failure modes.

---

## Selected Work

### [Amity](https://github.com/grewanderer/animus-amity)

Document-governed AI software delivery pipeline for controlled, evidence-gated implementation.

- Architect / Verifier / Executor role separation
- deterministic quorum and dual-approval protocols
- hash-locked task packs and bounded execution scopes
- vector retrieval with provenance rather than retrieval-as-truth
- durable recovery from rate limits, overload, worker crashes, and partial failures
- typed artifacts for designs, reviews, execution evidence, and completion certificates

### [Animus Link](https://github.com/grewanderer/animus-link)

Secure connectivity and delivery substrate separating cryptographic identity, transport, and delivery semantics.

- relay-assisted secure connectivity across NATs, firewalls, and untrusted networks
- end-to-end encrypted sessions where relays do not decrypt payloads
- self-certifying identity and transport-independent session semantics
- explicit delivery contracts instead of implicit online/offline behavior
- invite-first private discovery and controlled service exposure
- protocol, identity, session, relay, observability, and conformance boundaries

### [ML Infrastructure Laboratory](https://github.com/AnimusHQ/mllaboratory)

Kubernetes-backed ML infrastructure for reproducible and auditable machine-learning workflows.

- Go service architecture with explicit Control Plane / Data Plane separation
- PostgreSQL-backed metadata, policy, audit, execution evidence, and integrity fields
- Kubernetes execution for isolated workloads
- S3-compatible artifact and object-storage mediation
- Helm-based deployment model
- OIDC, RBAC, deny-by-default authorization, and internal service boundaries
- CI, security, supply-chain, deployment, and operations documentation

### [Animus DataLab SDK](https://github.com/grewanderer/animus-datalab-sdk)

Python SDK for CI systems and ML pipelines that publish metadata and execution evidence to Animus DataPilot.

- CI-driven experiment registration
- immutable experiment runs and dataset-version binding
- signed CI image attestation through git commit and image digest metadata
- live telemetry from training containers
- artifact registration from training and evaluation jobs
- deterministic identifiers and append-only telemetry
- on-prem, air-gapped, and non-interactive usage models

---

## Engineering Surface

| Area | What I build | Technical focus |
|---|---|---|
| Backend systems | API platforms, service boundaries, distributed workflows | Go, Rust, REST, gRPC, WebSockets, state machines, failure semantics |
| Platform engineering | runtime platforms, CI/CD, deployment systems, release gates | Linux, Docker, Kubernetes, Helm, GitHub Actions, GitLab CI, Jenkins, Zuul |
| Embedded Linux | custom Linux images, device services, firmware delivery | Buildroot, QEMU, rootfs composition, package integration, hardware validation |
| Reliability | observable and diagnosable production systems | Prometheus, Grafana, OpenTelemetry, ELK, structured logs, metrics, traces |
| Security & networking | controlled service exposure and secure integration paths | TLS, DTLS, OIDC, JWT, RBAC, ACLs, policy enforcement |
| ML infrastructure | reproducible execution and auditable experiment platforms | Kubernetes, PostgreSQL, S3-compatible storage, PyTorch, ONNX, ONNX Runtime |

---

## Technical Stack

```text
Languages:        Go, Rust, Python
Backend:          REST, gRPC, WebSockets, event-driven systems, message-driven systems
Data:             PostgreSQL, MySQL, SQLite, Redis, Kafka, RabbitMQ, S3-compatible storage
Platform:         Linux, Docker, Docker Compose, Kubernetes, Helm, Kustomize, Buildroot, QEMU
Delivery:         GitHub Actions, GitLab CI, Jenkins, Zuul, reproducible builds, release gates
Observability:    Prometheus, Grafana, OpenTelemetry, ELK, structured logs, metrics, traces
Security:         TLS, DTLS, OIDC, JWT, RBAC, ACLs, policy enforcement
ML Infrastructure: PyTorch, ONNX, ONNX Runtime, data pipelines, experiment automation
```

---

## Engineering Standards

- Runtime behavior matters more than repository aesthetics.
- Parser support is not feature support; runtime effect and readback matter.
- Control planes should own truth; execution environments should report evidence.
- Production systems need rollback, observability, state ownership, and defined failure semantics.
- Logs, metrics, traces, and audit records are design surfaces.
- Reproducibility is a debugging and accountability mechanism, not a tooling preference.
- Security boundaries should be explicit enough to test and boring enough to operate.

---

## Fit

Strong match for teams building backend, platform, infrastructure, embedded Linux, reliability, secure networking, AI delivery systems, or ML infrastructure products where implementation depth and architectural ownership are both required.

Relevant roles: **Senior Backend Engineer**, **Go Backend Engineer**, **Platform Engineer**, **Infrastructure Engineer**, **Systems Engineer**, **Rust Systems Engineer**, **Embedded Linux Engineer**, **Reliability Engineer**, **ML Infrastructure Engineer**, **Secure Infrastructure Engineer**.

---

<p align="center">
  <sub>I build systems that stay correct, observable, reproducible, and operable after the first implementation has shipped.</sub>
</p>
