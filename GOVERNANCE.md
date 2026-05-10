# Governance

SGP is governed in the open. The rules are short on purpose.

## Roles

- **Maintainers** — listed in [`.github/CODEOWNERS`](./.github/CODEOWNERS).
  Maintainers merge code, accept RFCs, cut releases, and uphold this document.
- **Contributors** — anyone who opens a discussion, issue, RFC, or pull request.

## What requires an RFC

Anything that changes the protocol surface for users or implementers:

- Signal, Processor, GatePlan, or Receipt schemas.
- Wire formats, identifiers, or version semantics.
- Conformance requirements.
- Removal or breaking changes to any of the above.

Bug fixes, editorial changes, and SDK-internal improvements do not need an
RFC. When in doubt, open a discussion first.

See [`rfcs/README.md`](./rfcs/README.md) for the RFC process.

## Decision making

The default is rough consensus. Maintainers seek agreement; concrete technical
objections are addressed before a decision lands. When consensus is not
reachable, two-thirds of maintainers may close the question.

Decisions are recorded — in the merged RFC, the issue, or the release notes.
Decisions that are not written down do not exist.

## Versioning

The protocol is versioned with [Semantic Versioning](https://semver.org).
Pre-1.0 is permitted to break. Post-1.0, breaking changes require a major
version bump and a deprecation window stated in the RFC that introduces them.

## Trademarks

"Signal Gating Protocol" and "SGP" identify this protocol and its conformant
implementations. Use them honestly. Do not use them to imply endorsement of
non-conformant work.

## Amending this document

This document is amended by RFC.
