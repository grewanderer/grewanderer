<h1 align="center">Grewanderer</h1>

<p align="center">
  <strong>Senior Backend / Platform Engineer</strong><br/>
  Go · Rust · Python · Distributed Systems · Embedded Linux · Kubernetes · Reliability · Secure Infrastructure · ML Infrastructure
</p>

<p align="center">
  <a href="mailto:rewanderer@proton.me">rewanderer@proton.me</a> · Remote · Backend · Platform · Systems · Infrastructure
</p>

<p align="center">
  <a href="https://github.com/grewanderer?tab=repositories">Repositories</a> ·
  <a href="https://github.com/AnimusHQ/mllaboratory">ML Infrastructure Laboratory</a> ·
  <a href="https://github.com/grewanderer/animus_coder">Agentic Engineering Core</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go-Backend%20Systems-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go Backend Systems" />
  <img src="https://img.shields.io/badge/Rust-Systems%20Engineering-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust Systems Engineering" />
  <img src="https://img.shields.io/badge/Python-Automation%20%7C%20ML%20Infra-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python Automation and ML Infrastructure" />
  <img src="https://img.shields.io/badge/Linux-Platform%20Engineering-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux Platform Engineering" />
  <img src="https://img.shields.io/badge/Buildroot-Embedded%20Linux-2A9D8F?style=flat-square&logo=linux&logoColor=white" alt="Buildroot Embedded Linux" />
  <img src="https://img.shields.io/badge/Kubernetes-Execution%20Platforms-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes Execution Platforms" />
  <img src="https://img.shields.io/badge/PostgreSQL-State%20%26%20Audit-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL State and Audit" />
  <img src="https://img.shields.io/badge/OpenTelemetry-Observability-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry Observability" />
</p>

---

## Engineering Focus

I build backend, platform, and embedded Linux systems where correctness, reproducibility, observability, and operational control are part of the design rather than added after release.

My strongest axis is **Go backend engineering** for distributed, integration-heavy, and hardware-adjacent systems. I use **Rust** for systems and protocol-oriented components, and **Python** for automation, ML infrastructure, evaluation workflows, and operational tooling.

The work I am best suited for sits at the boundary between application backends, runtime infrastructure, Linux platforms, deployment systems, and production failure modes.

---

## What I Actually Optimize For

| Area | Engineering work I care about | Typical stack / concepts |
|---|---|---|
| Backend systems | API platforms, service boundaries, explicit state machines, compatibility, failure semantics | Go, Rust, REST, gRPC, WebSockets, PostgreSQL, Redis, Kafka, RabbitMQ |
| Platform engineering | reproducible builds, deployment automation, CI/CD gates, runtime ownership, release evidence | Linux, Docker, Kubernetes, Helm, GitHub Actions, GitLab CI, Jenkins, Zuul |
| Embedded Linux | custom runtime images, package integration, rootfs composition, firmware artifacts, hardware-adjacent services | Buildroot, QEMU, Linux, device integration, constrained environments |
| Reliability | observability-first design, structured diagnostics, deterministic failure reporting, regression safety | Prometheus, Grafana, OpenTelemetry, ELK, logs, metrics, traces |
| Security & networking | secure transport, identity/session boundaries, policy enforcement, controlled service exposure | TLS, DTLS, OIDC, JWT, ACLs, protocol design, relay-assisted systems |
| ML infrastructure | reproducible execution, metadata truth, artifact mediation, evaluation automation, controlled workloads | Kubernetes, PostgreSQL, S3-compatible storage, PyTorch, ONNX, ONNX Runtime |

---

## Public Engineering Evidence

### [ML Infrastructure Laboratory](https://github.com/AnimusHQ/mllaboratory)

A Kubernetes-backed ML infrastructure platform centered on reproducible and auditable machine-learning workflows.

**What it demonstrates:**

- Go service architecture with explicit Control Plane / Data Plane separation
- PostgreSQL-backed metadata, policy, audit, execution evidence, and integrity fields
- Kubernetes execution model for isolated workloads
- S3-compatible artifact/object storage mediation
- Helm-based production deployment shape
- OIDC, RBAC, deny-by-default authorization, internal service boundaries
- CI, security, supply-chain, deployment, and operational documentation discipline

**Relevant searches:** ML Infrastructure Engineer, Platform Engineer, Go Backend Engineer, Kubernetes Platform, Control Plane, Data Plane, Auditability, Reproducibility.

---

### [Agentic Engineering Core](https://github.com/grewanderer/animus_coder)

Policy-first agentic coding infrastructure designed around local execution, guarded automation, proof bundles, replay, and memory-as-code.

**What it demonstrates:**

- k3s-based isolated execution profile
- default-deny egress model for runner jobs
- Git access through a scoped internal proxy rather than direct uncontrolled transport
- EventLog, Proof Bundle, Replay, and hash-checked execution evidence
- memory-as-code with guarded writes and provenance
- Helm-oriented deployment and runtime schema validation

**Relevant searches:** Agentic Engineering, DevTools Infrastructure, Secure Automation, Kubernetes Runners, Policy Enforcement, Reproducible Execution, Local-First Automation.

---

## Current Deep Work Areas

These are the technical domains I keep returning to because they expose real engineering trade-offs instead of only framework usage.

### Backend control planes

- authoritative metadata stores
- idempotent state transitions
- compatibility-preserving API evolution
- service boundaries that do not collapse under operational pressure
- audit-ready workflows and evidence records
- control-plane / data-plane separation

### Runtime and platform systems

- Linux production environments
- Docker and Kubernetes runtime behavior
- deployment topology, readiness, liveness, rollout, and reconciliation semantics
- reproducible build and release pipelines
- artifact integrity and release gates
- air-gapped or restricted-network deployment constraints

### Embedded and hardware-adjacent systems

- Buildroot-based Linux images
- root filesystem composition
- firmware build orchestration
- QEMU-backed validation
- runtime behavior on constrained targets
- service-to-device control paths and failure reporting

### Protocol-heavy integration

- REST, gRPC, WebSockets
- SOAP / WS-*, ONVIF, RTSP
- secure transport boundaries
- authentication and authorization flows
- replay, timeout, retry, and compatibility semantics
- observability for systems that fail at integration edges

### ML and data infrastructure

- dataset and artifact versioning
- reproducible execution plans
- experiment automation and evaluation workflows
- model integration behind service boundaries
- inference-oriented backend design
- auditability and policy around data-processing systems

---

## Technical Depth

### Languages

- **Go:** backend services, platform APIs, control planes, integrations, infrastructure services
- **Rust:** systems components, protocol modeling, secure networking, runtime-critical tooling
- **Python:** automation, ML workflows, evaluation tooling, data-processing pipelines, operational scripts

### Backend and distributed systems

- REST, gRPC, WebSockets
- event-driven and message-driven systems
- explicit state machines and failure semantics
- API compatibility and service evolution
- Clean Architecture and pragmatic DDD
- PostgreSQL, MySQL, SQLite
- Redis, Kafka, RabbitMQ

### Platform, Linux, and delivery

- Linux operations and diagnostics
- Docker, Docker Compose, Kubernetes
- Helm, Kustomize
- Buildroot, QEMU, firmware images
- GitHub Actions, GitLab CI, Jenkins, Zuul
- reproducible builds and release automation
- deployment validation and runtime evidence

### Observability and reliability

- Prometheus, Grafana, OpenTelemetry
- structured logs, metrics, traces
- ELK stack
- production debugging under real infrastructure constraints
- incident-driven feedback loops
- regression safety through tests, smoke checks, and CI gates

### Security, networking, and execution control

- TLS / DTLS
- OIDC / JWT
- authentication and authorization
- deny-by-default service exposure
- policy enforcement
- secure transport design
- Kubernetes workload isolation
- controlled execution and evidence capture

### ML infrastructure

- PyTorch, ONNX, ONNX Runtime
- data pipelines and preprocessing
- experiment orchestration
- evaluation automation
- metadata and artifact tracking
- production-oriented model integration

---

## System Domains

I have worked across systems where software quality is measured by runtime behavior, not by repository aesthetics alone:

- backend platforms for distributed and integration-heavy systems
- Linux-based embedded platforms and firmware delivery pipelines
- network operating system and command-conformance tooling
- secure overlay networking and controlled service access
- Kubernetes-backed ML infrastructure and experiment orchestration
- NAS, access-control, video/security, power-control, and device-management systems
- audio classification and signal-processing pipelines
- computer-vision inference infrastructure

---

## Engineering Standards

I prefer systems that can be inspected, replayed, tested, and operated.

- A claim is not complete until the failure mode is described.
- Parser support is not feature support; runtime effect and readback matter.
- A deployment is not production-ready until rollback, observability, and state ownership are clear.
- A control plane should own truth; execution environments should report evidence.
- Logs, metrics, traces, and audit records are design surfaces, not post-release decorations.
- Reproducibility is not a tooling preference; it is a way to make debugging and accountability possible.
- Security boundaries should be explicit enough to test and boring enough to operate.

---

## Good Fit

I am a strong fit for teams building products where backend implementation depth and platform ownership meet:

- Senior Backend Engineer
- Go Backend Engineer
- Platform Engineer
- Infrastructure Engineer
- Systems Engineer
- Rust Systems Engineer
- Embedded Linux Engineer
- Reliability Engineer
- ML Infrastructure Engineer
- Secure Infrastructure Engineer

The best match is work involving backend systems, platform engineering, Kubernetes, Linux, embedded/runtime constraints, distributed services, secure networking, reliability, reproducibility, auditability, or ML infrastructure.

---

<p align="center">
  <sub>
    I build systems that stay correct, observable, reproducible, and operable after the first implementation has shipped.
  </sub>
</p>
