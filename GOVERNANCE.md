# Governance

SGP decisions are made in public and recorded in durable project artifacts.

## Roles

- **Maintainers** are listed in [`MAINTAINERS.md`](./MAINTAINERS.md). They review
  changes, steward RFCs, manage releases, and uphold this document.
- **Contributors** are everyone who participates through discussions, issues,
  RFCs, code, documentation, or review.

`CODEOWNERS` routes review requests. It is not the governance roster.

## What requires an RFC

An RFC is required for changes to:

- Signal, Gate, Agent, or Mesh semantics;
- public wire formats, identifiers, or version negotiation;
- trajectory receipt semantics that other implementations must honor;
- conformance requirements or test vectors;
- compatibility or deprecation policy;
- security or privacy guarantees;
- adoption of a design-stage concept such as GatePlan or a default-deny control
  plane.

Editorial fixes, implementation bugs, examples, tests, and SDK-internal
refactors do not require an RFC unless they change a public contract.

## Decision process

The default is rough consensus. Technical objections must state a concrete
failure mode, incompatibility, or unmet requirement and must receive a written
response.

Protocol decisions enter a final comment period of at least seven calendar days.
With the current two-maintainer roster, acceptance requires both non-conflicted
maintainers. If recusal or absence prevents quorum, the proposal is postponed.
Rejected and postponed proposals receive a written rationale.

## Conflicts and appeals

A maintainer must recuse from a decision when personal, financial, employment,
or authorship interests materially impair independent judgment. The recusal is
recorded on the pull request.

A contributor may appeal a decision by opening a governance issue with new
evidence or a specific process failure. The non-conflicted maintainers publish a
written disposition after a new final comment period.

## Normative hierarchy

Released specification text and conformance material define a released protocol
version. An accepted RFC is a decision record that authorizes a change. It does
not become part of a released protocol until specification, conformance, and
versioned release material are updated.

Before the first protocol release, the draft specification is informative and
the Python SDK documents the behavior of that implementation.

## Maintainer lifecycle

Maintainers are added or removed by a governance RFC. The proposal must state
the person's sustained contributions, responsibilities, and conflicts. A
maintainer may resign in writing. Six months without review, governance, or
release activity triggers an inactivity review, not automatic removal.

## Security exceptions

Maintainers may temporarily withhold exploit details and bypass the normal final
comment period when necessary to mitigate a current vulnerability. The project
publishes a retrospective decision record after coordinated disclosure.

## Versioning

SGP uses [Semantic Versioning](https://semver.org). Before 1.0, breaking changes
must still be documented with migration guidance. At and after 1.0, breaking
changes require a major version and an RFC-defined deprecation plan.

## Trademarks

"Signal Gating Protocol" and "SGP" identify this project and conformant
implementations. They must not be used to imply project endorsement.

## Amendments

This document is amended through the RFC process.
