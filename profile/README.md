<div align="center">

# Lattice

### Crash-proof governed runtime for AI agents.

**Your agents crash silently. You can't prove what happened. Lattice fixes both.**

---

</div>

AI agents crash and nobody knows. When something goes wrong, there's no audit trail. The status quo is systemd plus prayer. Every tool in this space helps you *write* agents. None of them help you *run* agents safely.

**Lattice Runtime** is a single Go binary that gives your agents crash-proof execution (embedded Temporal), cryptographic audit (SHA-256 hash-chained), budget enforcement, and zero-trust mesh networking. Install it, deploy your agents on top. No code changes required.

```bash
brew install latticehq/lattice/lattice
lattice server
```

## The Ecosystem

| Component | What it does | License |
|-----------|-------------|---------|
| [**Runtime**](https://github.com/latticeHQ/latticeRuntime) | Crash-proof runtime — identity, auth, audit, budget, mesh | Apache 2.0 |
| [**Workbench**](https://github.com/latticeHQ/latticeWorkbench) | 316K-line multi-model agent workspace | MIT |
| [**SDK**](https://github.com/latticeHQ/latticeSDK) | Go SDK for building on Lattice | Apache 2.0 |
| [**Inference**](https://github.com/latticeHQ/latticeInference) | Local AI serving — MLX on Apple Silicon | Apache 2.0 |
| [**Operator**](https://github.com/latticeHQ/latticeOperator) | Self-hosted deployment via SSH | Apache 2.0 |
| [**Registry**](https://github.com/latticeHQ/latticeRegistry) | Community modules, templates, stacks | Apache 2.0 |
| [**Terraform Provider**](https://github.com/latticeHQ/terraform-provider-lattice) | Infrastructure as code | MPL 2.0 |
| [**Toolbox**](https://github.com/latticeHQ/LatticeToolbox) | macOS app manager | MIT |
| [**Homebrew**](https://github.com/latticeHQ/latticeHomebrew) | One-line install | MIT |

## Why Lattice?

- **Crash-proof** — Embedded Temporal. Agents survive failures. State is never lost.
- **Auditable** — SHA-256 hash-chained audit trail. Tamper with one record, every subsequent hash breaks. SOC2/HIPAA/FedRAMP as a side effect.
- **Governed** — RBAC + ABAC via Rego. Budget enforcement. Tool whitelisting. PII blocking. All at runtime.
- **Open source** — Apache 2.0. If software decides "allow" or "deny," the decision logic must be auditable.
- **Self-hosted** — Your data stays on your infrastructure. Cloud, on-prem, edge, air-gapped.

## Links

- **Website**: [latticeruntime.com](https://latticeruntime.com)
- **Vision**: [VISION.md](https://github.com/latticeHQ/latticeRuntime/blob/develop/VISION.md)
- **Security**: security@latticeruntime.com

---

<div align="center">

**I killed the agent. It came back. I can prove it.**

</div>
