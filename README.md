# Signal Gating Protocol community

Public governance and RFCs for typed, gated, observable signal flow in
multi-agent systems.

## Current model

| Primitive | Responsibility |
| --- | --- |
| **Signal** | Typed, immutable event with identity, lineage, priority, and metadata. |
| **Gate** | Composable policy that admits, drops, transforms, or controls signal flow. |
| **Agent** | Asynchronous signal processor with typed handlers and lifecycle. |
| **Mesh** | Directed agent topology with gated edges and coordination patterns. |

The [Python SDK](https://github.com/signalgatingprotocol/python-sdk) is the
reference implementation.

## Maturity

| Surface | Status |
| --- | --- |
| Signal, Gate, Agent, and Mesh runtime | Implemented in the alpha Python SDK |
| JSON signal wire envelope and trajectory receipts | Implemented in the alpha Python SDK |
| Cross-runtime interoperability and conformance suite | Draft |
| GatePlan and default-deny control plane | Design stage |

Design-stage concepts are proposals, not current protocol requirements. They
become part of SGP only through the RFC, specification, conformance, and release
process described in this repository.

## Start here

| Goal | Destination |
| --- | --- |
| Read the current draft | [Specification](https://signalgatingprotocol.github.io/specification/) |
| Build with the reference implementation | [Python SDK](https://github.com/signalgatingprotocol/python-sdk) |
| Ask a question or challenge the design | [Discussions](https://github.com/orgs/signalgatingprotocol/discussions) |
| Propose a protocol change | [RFC process](./rfcs/README.md) |
| Understand project decisions | [Governance](./GOVERNANCE.md) |
| Report a vulnerability privately | [Security policy](./SECURITY.md) |

## Repository scope

This repository contains governance, RFCs, contribution guidance, conduct
rules, and protocol-level issue templates. Executable implementation work
belongs in the affected SDK repository. Published documentation and the draft
specification live on the project website.

## License

Apache License 2.0. See [LICENSE](./LICENSE).
