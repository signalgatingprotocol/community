---
title: <one-line title>
authors: [<github-handle>, ...]
shepherd: <github-handle or unassigned>
status: draft # draft | proposed | accepted | rejected | postponed | superseded
created: YYYY-MM-DD
discussion: <URL>
spec-pr: <URL or none>
target-version: <version or unassigned>
decision-date: <YYYY-MM-DD or none>
supersedes: <RFC number or none>
superseded-by: <RFC number or none>
---

# Summary

State the change and what it makes possible.

# Motivation

Describe the concrete user or implementer problem and why it should be solved at
the protocol layer.

# Proposal

Define the complete behavior. A competent independent implementer should not
need private context to build it.

## Normative behavior

Use MUST, MUST NOT, SHOULD, SHOULD NOT, and MAY as defined by
[BCP 14](https://www.rfc-editor.org/info/bcp14) when normative strength matters.

## Schema and wire changes

List fields, types, defaults, identifiers, encoding, version negotiation, and
unknown-field behavior. Write `None` if the wire format does not change.

## State and failure semantics

Define ordering, retries, idempotency, timeouts, partial failure, recovery, and
observable outcomes.

# Security and privacy

Describe trust boundaries, authorization, data exposure, resource exhaustion,
replay, downgrade, and abuse cases.

# Compatibility and migration

State what breaks, who must act, deprecation timing, and how mixed versions
interoperate.

# Conformance

Provide required tests or test vectors, including invalid and boundary cases.

# Operational impact

Describe latency, throughput, storage, observability, rollout, and support cost.

# Examples

Show at least one end-to-end flow using the current Signal, Gate, Agent, and Mesh
vocabulary, or explicitly introduce and justify new vocabulary.

# Alternatives

Include the status quo and explain why each rejected approach is insufficient.

# Rollout and rollback

List specification, conformance, SDK, documentation, migration, release, and
rollback work.

# Unresolved questions

List decisions that remain open. Write `None` when the RFC is ready for final
comment.
