<h1 align="center">Maksim Sotnikov · Grewanderer</h1>

<p align="center">
  <strong>Lead Systems / Platform Engineer</strong><br/>
  Go · Rust · Distributed Systems · Secure Networking · Control Planes · Embedded Linux
</p>

<p align="center">
  <a href="https://kapakka.org">Website</a>
  ·
  <a href="https://www.linkedin.com/in/grewanderer">LinkedIn</a>
  ·
  <a href="https://kapakka.org/link/">Animus Link</a>
  ·
  <a href="https://github.com/AnimusHQ/mllaboratory">Animus Datalab</a>
  ·
  <a href="https://github.com/grewanderer/animus-datalab-sdk">DataLab SDK</a>
</p>

---

## Focus

I build distributed and security-sensitive systems where correctness has to survive production.

My strongest axis is **Go and Rust** across distributed control planes, protocol-heavy services, secure networking, Linux infrastructure, embedded systems, and reliability. I work across the full engineering path: architecture and specifications, implementation, negative and conformance testing, CI/release gates, observability, production diagnosis, and recovery.

My current professional work includes Go/Rust software for satellite-communications systems and a Rust network OS / command-conformance platform validated end to end with Buildroot and QEMU.

In parallel I build **Animus**, a systems portfolio organized around explicit authority, visible failure, bounded execution, security boundaries, and evidence-driven engineering.

---

## Selected Work

### [Animus Link](https://kapakka.org/link/)

Live Telegram-native managed network access. The product control plane owns entitlement and configuration state; execution nodes apply access and report runtime evidence.

- Go / PostgreSQL control plane with Telegram Mini App and bot surfaces
- multi-node Xray execution and deterministic VLESS + REALITY exports
- DB-first lifecycle orchestration with explicit partial-failure states
- health, usage, quota, audit, backup/restore, and release evidence
- voluntary support is separate from network access

### [Link Protocol Research](https://kapakka.org/systems/)

Separate **pre-1.0 Rust secure-connectivity protocol research**. It is not the managed Animus Link access product and is not represented as production v1.

- self-certifying cryptographic identity
- end-to-end encrypted sessions and relay-assisted transport
- deterministic wire formats and canonical encoding
- anti-replay and rekey state machines
- normative specifications, conformance vectors, security gates, and explicit readiness boundaries

### [Animus Datalab](https://github.com/AnimusHQ/mllaboratory)

Governed ML infrastructure for reproducible and auditable machine-learning workflows.

- Go services with explicit Control Plane / Data Plane separation
- PostgreSQL-backed authoritative metadata, policy, lineage, audit, and execution evidence
- Kubernetes-backed isolated workload execution
- S3-compatible artifact mediation and integrity metadata
- OIDC, RBAC, deny-by-default service boundaries, Helm deployment, and operational gates

### [Animus DataLab SDK](https://github.com/grewanderer/animus-datalab-sdk)

Typed, zero-runtime-dependency Python integration SDK for CI systems and ML workloads.

- dataset and immutable version registration
- experiment/run lifecycle and project-scoped dispatch
- signed CI provenance and deterministic request identity
- integrity-aware streaming artifact I/O
- bounded, non-blocking telemetry and predictable failure semantics
- on-prem, air-gapped, and non-interactive usage models

### Animus Amity / Coder — private R&D

Evidence-gated AI engineering work around document-governed delivery, independent model lanes, typed artifacts, bounded execution, deterministic approval gates, sandboxed tools, observable execution, and durable recovery. These repositories are private R&D surfaces; this profile does not publish dead or access-restricted repository links as public evidence.

---

## Engineering Surface

| Area | What I build | Technical focus |
|---|---|---|
| Distributed systems | control planes, stateful workflows, service boundaries | Go, Rust, PostgreSQL, gRPC, state machines, failure semantics |
| Systems & protocols | secure connectivity, protocol runtimes, conformance | Rust, TCP/IP, TLS/DTLS, Noise/X25519 concepts, Ed25519, AEAD |
| Platform engineering | runtime platforms, delivery systems, release gates | Linux, Docker, Kubernetes, Helm, GitHub Actions, GitLab CI, Jenkins |
| Embedded Linux | device services, firmware validation, hardware-adjacent software | Buildroot, QEMU, rootfs integration, runtime-effect validation |
| Reliability | observable and diagnosable production systems | Prometheus, Grafana, OpenTelemetry, structured logs, metrics, traces |
| ML infrastructure | governed execution and reproducible experiment platforms | Kubernetes, PostgreSQL, S3-compatible storage, Python, CI integration |

---

## Engineering Standards

- Runtime behavior matters more than repository aesthetics.
- Control planes own authoritative state; execution environments report evidence.
- Partial failure must remain visible and reconcilable.
- Parser support is not feature support; runtime effect and readback matter.
- Production claims require exact-revision tests, release identity, rollback, and operational evidence.
- Reproducibility is a debugging and accountability mechanism.
- Security boundaries should be explicit enough to test and boring enough to operate.

---

## Fit

Strong match for teams building distributed backends, platform infrastructure, secure networking, protocol-heavy systems, embedded Linux, reliability, or ML infrastructure where implementation depth and architectural ownership are both required.

Relevant roles: **Lead / Senior Systems Engineer**, **Platform Engineer**, **Senior Backend Engineer**, **Distributed Systems Engineer**, **Rust Systems Engineer**, **Protocol Engineer**, **Secure Infrastructure Engineer**.

---

<p align="center">
  <sub>I build systems that stay correct, observable, reproducible, and operable after the first implementation has shipped.</sub>
</p>
