<div align="center">

# Lattice

### The open-source coordination layer for institutional AI.

**Individual AI made everyone productive. Institutional AI makes organizations work.**

---

</div>

AI agents are everywhere. But deploying them across an organization means duct-taping together identity, authorization, budgets, audit trails, networking, and observability from 7+ separate tools.

**Lattice Runtime** is a single open-source binary that provides all of it. One layer. One database. Replace fragmented tooling with `docker compose up`.

## The Ecosystem

| Component | What it does | License |
|-----------|-------------|---------|
| [**Runtime**](https://github.com/latticeHQ/latticeRuntime) | Coordination layer — identity, authorization, audit, budget, networking | Apache 2.0 |
| [**SDK**](https://github.com/latticeHQ/latticeSDK) | Go SDK for building Department Stacks | Apache 2.0 |
| [**Workbench**](https://github.com/latticeHQ/latticeWorkbench) | Reference Engineering Stack — multi-model agent workspace | MIT |
| [**Inference**](https://github.com/latticeHQ/latticeInference) | Local AI serving — MLX on Apple Silicon, zero-config clustering | Apache 2.0 |
| [**Operator**](https://github.com/latticeHQ/latticeOperator) | Self-hosted deployment management for Lattice infrastructure | Apache 2.0 |
| [**Registry**](https://github.com/latticeHQ/latticeRegistry) | Community ecosystem — Terraform modules, templates, department stacks | Apache 2.0 |
| [**Terraform Provider**](https://github.com/latticeHQ/terraform-provider-lattice) | Infrastructure as code for Lattice deployments | MPL 2.0 |
| [**Toolbox**](https://github.com/latticeHQ/LatticeToolbox) | macOS app manager for Lattice products | MIT |
| [**Homebrew**](https://github.com/latticeHQ/latticeHomebrew) | One-line install on macOS and Linux | MIT |
| [**Enterprise**](https://github.com/latticeHQ/latticeEnterprise) | Enterprise administration and governance | Coming soon |

## Why Lattice?

- **Open source** — Enforcement logic is Apache 2.0. If software decides "allow" or "deny," the decision must be auditable.
- **Self-hosted** — Your data never leaves your infrastructure. Cloud, on-prem, air-gapped.
- **Vendor-neutral** — Works with any AI model, any cloud, any agent framework.
- **One layer** — Identity, auth, budget, audit, networking, observability — unified, not duct-taped.

## Get Started

```bash
brew install latticeHQ/lattice/lattice
lattice server --postgres-url postgres://... --http-address 0.0.0.0:3000
```

## Links

- **Website**: [latticeruntime.com](https://latticeruntime.com)
- **Vision**: [VISION.md](https://github.com/latticeHQ/latticeRuntime/blob/develop/VISION.md)
- **Security**: security@latticeruntime.com
- **Code of Conduct**: [CODE_OF_CONDUCT.md](https://github.com/latticeHQ/latticeRuntime/blob/develop/CODE_OF_CONDUCT.md)

---

<div align="center">

**Your agents. Your coordination. Your rules. Your infrastructure.**

</div>
