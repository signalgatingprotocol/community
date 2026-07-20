# Governance

SGP is governed in the open. The rules are short on purpose.

## Roles

- **Maintainers** are listed in [`.github/CODEOWNERS`](./.github/CODEOWNERS).
  Maintainers merge code, accept RFCs, cut releases, and uphold this document.
- **Contributors** are anyone who opens a discussion, issue, RFC, or pull
  request.

## What requires an RFC

Anything that changes the protocol surface for users or implementers:

- Signal, Gate, Agent, or Mesh semantics.
- Wire formats, identifiers, or version semantics.
- Trajectory receipt semantics that other implementations must honor.
- Conformance requirements.
- Adoption of a design-stage concept as a current protocol requirement.
- Removal or breaking changes to any of the above.

Bug fixes, editorial changes, and SDK-internal improvements do not need an RFC.
When in doubt, open a discussion first.

See [`rfcs/README.md`](./rfcs/README.md) for the RFC process.

## Decision making

The default is rough consensus. Maintainers seek agreement; concrete technical
objections are addressed before a decision lands. When consensus is not
reachable, two-thirds of maintainers may close the question.

Decisions are recorded in the merged RFC, issue, or release notes. Decisions
that are not written down do not exist.

## Versioning

The protocol is versioned with [Semantic Versioning](https://semver.org).
Before 1.0, breaking changes are permitted but must be documented. At and after
1.0, breaking changes require a major version and an RFC-defined deprecation
window.

## Trademarks

"Signal Gating Protocol" and "SGP" identify this protocol and its conformant
implementations. Use them honestly. Do not use them to imply endorsement of
non-conformant work.

## Amending this document

This document is amended by RFC.
