# Signal Gating Protocol

**The executive function layer for agent graphs.**

Agents are getting better. The graphs they form are not. There is no shared
control plane. Every team reinvents routing, gating, context shaping, and
auditability — incompatibly. SGP fixes that.

SGP is an open protocol. It standardizes five things, and only five things:

1. **Processors** — what an agent is, and what activates it.
2. **Signals** — typed events with features and provenance.
3. **GatePlans** — the executive router's decision about what runs next.
4. **Context minimization** — only the inputs a processor needs.
5. **Receipts** — verifiable records of what ran and why.

That is the surface. Everything else composes on top.

---

## What SGP is not

- Not a tool protocol. That is [MCP](https://modelcontextprotocol.io).
- Not agent chat. That is A2A.
- Not commerce. That is UCP.

SGP is the missing layer between them: the executive function that decides
which processor runs, on which signal, with which context, and proves it
afterward.

---

## Start here

| Path | Where |
|------|-------|
| Read the spec | [signalgatingprotocol.github.io/specification](https://signalgatingprotocol.github.io/specification) |
| Build with the SDK | [signalgatingprotocol/python-sdk](https://github.com/signalgatingprotocol/python-sdk) |
| Discuss the protocol | [GitHub Discussions](https://github.com/orgs/signalgatingprotocol/discussions) |
| Propose a change | [RFC process](./rfcs/README.md) |
| Report a vulnerability | [SECURITY.md](./SECURITY.md) |

---

## This repository

This is the public home of the SGP community. It holds:

- **Governance** — how the protocol evolves. See [GOVERNANCE.md](./GOVERNANCE.md).
- **RFCs** — substantive protocol changes. See [rfcs/](./rfcs/).
- **Conduct** — how we work together. See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).
- **Contribution paths** — see [CONTRIBUTING.md](./CONTRIBUTING.md).

Implementation lives in the SDK repositories. Specification text lives on the
website. This repo is for the human and process layer that sits around them.

---

## License

Apache License 2.0. See [LICENSE](./LICENSE).
