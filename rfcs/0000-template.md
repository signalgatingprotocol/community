---
title: <one-line title>
authors: [<github-handle>, ...]
status: draft # draft | proposed | accepted | rejected | postponed | superseded
created: YYYY-MM-DD
target-version: <version or unassigned>
supersedes: <RFC number or none>
superseded-by: <RFC number or none>
---

# Summary

One paragraph describing what changes and what becomes possible.

# Motivation

Describe the concrete user or implementer problem and why it belongs at the
protocol layer.

# Proposal

Define schemas, wire formats, types, and semantics precisely enough for an
independent implementation.

## Schema and wire changes

List fields, types, defaults, identifiers, encoding, and unknown-field behavior.
Write `None` if the wire format does not change.

## Behavior changes

Use MUST, SHOULD, and MAY in the
[BCP 14](https://www.rfc-editor.org/info/bcp14) sense where normative strength
matters.

## Compatibility

State what breaks, who must act, and what migration or deprecation is required.

# Security and privacy

Describe trust boundaries, authorization, data exposure, replay, denial of
service, and abuse cases.

# Conformance

Provide required tests or test vectors, including invalid and boundary cases.

# Examples

Show at least one end-to-end flow using Signal, Gate, Agent, and Mesh, or
explicitly introduce and justify new vocabulary.

# Drawbacks

State what becomes more complex, slower, or harder to operate.

# Alternatives

Include the status quo and explain why rejected approaches are insufficient.

# Open questions

List unresolved decisions. Write `None` when ready for a decision.

# Adoption plan

List specification, conformance, implementation, documentation, migration,
release, and rollback work.
