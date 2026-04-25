<h1 align="center">Grewanderer</h1>

<p align="center">
  <strong>Senior Backend / Platform Engineer</strong><br/>
  Go · Rust · Python · Distributed Systems · Embedded Linux · Reliability · Secure Infrastructure
</p>

<p align="center">
  Remote · <a href="mailto:rewanderer@proton.me">rewanderer@proton.me</a>
</p>

<p align="center">
  <a href="https://github.com/grewanderer/animus-link">Secure Overlay Platform</a> ·
  <a href="https://github.com/AnimusHQ/animus-lab">ML Infrastructure Lab</a> ·
  <a href="https://github.com/grewanderer/animus_coder">Agentic Engineering Core</a>
</p>

---

## Engineering Profile

I build backend, platform, and embedded Linux systems where correctness, observability, reproducibility, and operational control matter.

My strongest area is **Go backend engineering** for distributed, integration-heavy, and hardware-adjacent systems.  
I use **Rust** for systems and platform work, and **Python** for automation, tooling, ML infrastructure, and evaluation workflows.

I work best on systems that must stay understandable and operable under real production constraints: unreliable networks, constrained devices, strict integration boundaries, long-lived APIs, audit requirements, and failure modes that need to be explicit rather than hidden.

---

## What I Am Strong At

- Backend services in **Go**, **Rust**, and **Python**
- Distributed systems with explicit state, clear ownership, and predictable failure handling
- Embedded Linux and platform engineering with **Buildroot**, firmware images, rootfs composition, and hardware validation
- API design for REST, gRPC, WebSockets, SOAP / WS-*, ONVIF, RTSP, and protocol-heavy integrations
- Secure transport, authentication, authorization, OIDC/JWT, TLS/DTLS, and policy enforcement
- CI/CD for reproducible builds, firmware delivery, test automation, and release gates
- Observability with metrics, tracing, structured logs, Prometheus, Grafana, OpenTelemetry, and ELK
- ML infrastructure for reproducible experiments, data pipelines, evaluation workflows, and production-oriented inference systems

---

## Featured Work

### Secure Overlay Access Platform

A relay-first secure overlay platform in Rust for controlled service access across devices and networks.

Focus areas:

- Wire protocol design
- Identity, crypto, relay, daemon API, and CLI architecture
- Signed token policy and deny-by-default exposure
- Reproducible validation through conformance vectors and release artifacts
- Operational correctness for local and CI-driven runtime flows

Repository: [grewanderer/animus-link](https://github.com/grewanderer/animus-link)

---

### ML Infrastructure Lab

An enterprise-style machine learning infrastructure platform designed around reproducibility, auditability, and controlled execution.

Focus areas:

- Control Plane / Data Plane separation
- Dataset versioning, code references, environment locks, and policy-driven execution
- Append-only audit and explicit domain entities
- On-prem, private cloud, and air-gapped deployment models
- Backend architecture for experiment orchestration and evaluation workflows

Repository: [AnimusHQ/animus-lab](https://github.com/AnimusHQ/animus-lab)

---

### Agentic Engineering Core

A policy-first coding and automation infrastructure focused on reproducible execution, local control, proof bundles, replay, and memory-as-code.

Focus areas:

- Deterministic local execution
- Evidence-backed automation
- Policy-oriented workflows
- Reproducible engineering artifacts
- Agentic development infrastructure with operational constraints

Repository: [grewanderer/animus_coder](https://github.com/grewanderer/animus_coder)

---

## Systems I Build

### Backend & Platform Systems

- Backend services with explicit state machines and well-defined failure semantics
- API platforms with stable contracts, compatibility boundaries, and clear service evolution
- Distributed services that remain predictable across network, deployment, and runtime failures
- Event-driven systems with auditability, observability, and operational recovery paths
- Infrastructure where reproducibility and explainability are core design constraints

### Embedded Linux & Hardware-Adjacent Systems

- Custom Buildroot-based operating systems
- Package integration and root filesystem composition
- Firmware image assembly and reproducible delivery pipelines
- Runtime validation on QEMU and physical hardware
- Backend services running in constrained or hardware-adjacent environments
- Command/control systems where visible behavior must match real runtime state

### Reliability & Observability

- Production diagnosis under real infrastructure constraints
- Metrics, traces, structured logs, and release evidence
- CI/CD gates that validate behavior rather than only syntax or parser support
- Failure reporting that is deterministic, actionable, and tied to runtime truth

---

## Core Stack

**Languages:** Go, Rust, Python  
**Backend:** REST, gRPC, WebSockets, event-driven services, Clean Architecture, pragmatic DDD  
**Data:** PostgreSQL, MySQL, SQLite, Redis, Kafka, RabbitMQ  
**Platform:** Linux, Docker, Kubernetes, Helm, Kustomize, Buildroot, QEMU  
**CI/CD:** GitHub Actions, GitLab CI, Jenkins, Zuul  
**Observability:** Prometheus, Grafana, OpenTelemetry, ELK, structured logging  
**Security:** TLS, DTLS, OIDC, JWT, policy enforcement, secure transport design  
**ML Infrastructure:** PyTorch, ONNX, ONNX Runtime, data pipelines, experiment automation, evaluation workflows  

---

## Experience Summary

- Senior-level backend and platform engineering across industrial, embedded, research, ML, and infrastructure-heavy systems
- Production backend development in Go and Rust for systems with strict reliability and correctness requirements
- Embedded Linux platform work involving Buildroot, firmware images, device integration, and hardware validation
- Protocol-heavy integrations involving secure networking, video/security systems, device control, and external infrastructure
- ML and data-processing infrastructure from ingestion and preprocessing to training, evaluation, and production-oriented integration
- End-to-end ownership across architecture, implementation, testing, CI/CD, deployment, observability, and operational support

---

## Selected Project Domains

- Network Operating System and command conformance platform
- Secure overlay networking and controlled service access
- Enterprise ML infrastructure and reproducible experimentation
- Embedded Linux NAS platform on custom hardware
- Access control and video/security protocol integration
- Smart PDU backend and device control systems
- Audio classification and filtering pipelines
- Computer vision inference infrastructure

---

## Engineering Principles

- Correctness over cleverness
- Determinism over hidden state
- Operational clarity over theoretical elegance
- Explicit contracts over implicit behavior
- Reproducibility over one-off fixes
- Evidence-backed releases over unsupported claims
- Long-term maintainability over short-term delivery optics

---

<p align="center">
  <sub>
    I build systems that remain correct, observable, reproducible, and operable after the first implementation is long gone.
  </sub>
</p>
