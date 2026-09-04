<h1 align="center">Maksim Sotnikov · Grewanderer</h1>

<p align="center">
  <strong>Senior / Lead Systems & Platform Engineer</strong><br/>
  Go · Rust · Distributed Systems · Secure Networking · Control Planes · Embedded Linux
</p>

<p align="center">
  <strong>Current:</strong> Moscow, Russia → relocating to Batumi, Georgia in September 2026<br/>
  Registered Georgian Individual Entrepreneur · available for interviews now
</p>

<p align="center">
  <a href="https://kapakka.org">Portfolio</a>
  ·
  <a href="https://www.linkedin.com/in/grewanderer">LinkedIn</a>
  ·
  <a href="https://github.com/Animus-OSC">Animus OSC</a>
  ·
  <a href="https://github.com/Animus-OSC/animus-datalab-sdk">DataLab SDK</a>
  ·
  <a href="https://github.com/AnimusHQ/mllaboratory">DataLab public snapshot</a>
</p>

---

## Engineering focus

I build distributed and security-sensitive systems where correctness has to survive production, partial failure, upgrades, and operator error.

My strongest axis is **Go and Rust** across distributed control planes, protocol-heavy services, secure networking, Linux infrastructure, embedded systems, and reliability. I work across the full path: architecture and specifications, implementation, negative and conformance testing, CI/release gates, observability, production diagnosis, recovery, and operational documentation.

My current professional work includes Go/Rust software for distributed industrial and communications systems and a Rust network OS / command-conformance platform validated end to end with reproducible Buildroot/QEMU firmware images.

In parallel I build **Animus**, a systems portfolio organized around explicit authority, visible failure, bounded execution, security boundaries, and evidence-driven engineering.

## Evidence you can inspect

| System | Public boundary | What it demonstrates |
|---|---|---|
| [Animus DataLab SDK](https://github.com/Animus-OSC/animus-datalab-sdk) | Public, Apache-2.0 | Typed Python SDK, zero runtime dependencies, integrity-aware streaming I/O, bounded telemetry, signed CI provenance, compatibility and release discipline |
| [Animus DataLab public snapshot](https://github.com/AnimusHQ/mllaboratory) | Public open-core snapshot | Go services, Control Plane / Data Plane separation, PostgreSQL-authoritative state, Kubernetes execution, Helm, audit, RBAC and operational boundaries |
| [Animus Link](https://kapakka.org/link/) | Public product surface; implementation not published here | Go/PostgreSQL control-plane engineering, multi-node execution, lifecycle reconciliation, usage/health/audit and failure visibility |
| [Link protocol research](https://kapakka.org/systems/) | Pre-1.0 research; private implementation | Rust protocol design, cryptographic identity/session concepts, deterministic wire formats, anti-replay/rekey state machines and conformance methodology |
| Professional systems work | Employer/private code | Distributed/device-facing Go/Rust services, embedded Linux integration, Buildroot/QEMU validation, networking, observability and production diagnosis |

I deliberately distinguish **public evidence**, **live product behavior**, **private professional work**, and **pre-release R&D** instead of presenting every repository as production-ready.

## Selected systems work

### Animus DataLab

Governed ML infrastructure for reproducible and auditable machine-learning workflows.

- Go services with explicit Control Plane / Data Plane separation
- PostgreSQL-backed authoritative metadata, policy, lineage, audit, and execution evidence
- Kubernetes-backed isolated workload execution
- S3-compatible artifact mediation and integrity metadata
- OIDC, RBAC, deny-by-default service boundaries, Helm deployment, and operational gates
- public integration surface: [Animus DataLab SDK](https://github.com/Animus-OSC/animus-datalab-sdk)

### Animus Link

Managed network-access engineering plus a separate pre-1.0 secure-connectivity research track.

- production control-plane work in Go/PostgreSQL with explicit lifecycle and failure states
- multi-node execution, health, usage, quota, audit, backup/restore and release evidence
- separate Rust protocol R&D around self-certifying identity, encrypted sessions, relay-assisted transport, deterministic encoding, anti-replay/rekey state machines and conformance vectors
- research is explicitly not represented as a production protocol release

## Engineering surface

| Area | What I build | Technical focus |
|---|---|---|
| Distributed systems | control planes, stateful workflows, service boundaries | Go, Rust, PostgreSQL, gRPC, state machines, failure semantics |
| Systems & protocols | secure connectivity, protocol runtimes, conformance | Rust, TCP/IP, TLS/DTLS, Noise/X25519 concepts, Ed25519, AEAD |
| Platform engineering | runtime platforms, delivery systems, release gates | Linux, Docker, Kubernetes, Helm, GitHub Actions, GitLab CI, Jenkins |
| Embedded Linux | device services, firmware validation, hardware-adjacent software | Buildroot, QEMU, rootfs/package integration, runtime-effect validation |
| Reliability | observable and diagnosable production systems | Prometheus, Grafana, OpenTelemetry, structured logs, metrics, traces |
| ML infrastructure | governed execution and reproducible experiment platforms | Kubernetes, PostgreSQL, S3-compatible storage, Python, CI integration |

## Production standards

- **Runtime evidence over repository aesthetics.** A feature is not complete because the parser or API accepts it.
- **Authoritative state is explicit.** Control planes own intent; execution environments report evidence.
- **Partial failure stays visible.** Degraded state must remain inspectable and reconcilable.
- **Release claims are revision-specific.** Tests, release identity, rollback and operational evidence matter.
- **Reproducibility is operational infrastructure.** It shortens diagnosis and makes claims auditable.
- **Security boundaries are testable.** Permission, identity, transport and execution scope should be explicit enough to verify.

## Availability

I am currently in Moscow and relocating to **Batumi, Georgia in September 2026**. My **Georgian Individual Entrepreneur is already registered**.

- available for interviews now;
- international remote B2B contracting from Georgia after relocation;
- open to senior/lead systems, platform, backend, distributed-systems, Rust, protocol and secure-infrastructure roles;
- open to full-time opportunities where location or relocation terms are explicit.

**Contact:** [rewanderer@proton.me](mailto:rewanderer@proton.me)

---

<p align="center">
  <sub>I build systems that stay correct, observable, reproducible, and operable after the first implementation has shipped.</sub>
</p>
