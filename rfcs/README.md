# RFCs

Substantive changes to the Signal Gating Protocol go through an RFC so protocol
decisions are made in writing and in public.

## When you need an RFC

Open an RFC when a change affects:

- Signal, Gate, Agent, or Mesh semantics.
- Wire formats, identifiers, or version semantics.
- Trajectory receipt requirements shared by implementations.
- Conformance requirements.
- Security or privacy guarantees.
- Adoption of a design-stage concept as a current requirement.
- Removal or breaking changes to any of the above.

Bug fixes, editorial cleanups, internal SDK refactors, examples, and tests do not
need an RFC unless they change a public contract.

## The process

1. **Discuss.** Open a
   [Discussion](https://github.com/orgs/signalgatingprotocol/discussions) or an
   issue and establish that the change is worth specifying.
2. **Write.** Copy [`0000-template.md`](./0000-template.md) to
   `0000-short-slug.md`. Keep `0000` until acceptance.
3. **Open a pull request.** One file, one proposal. The pull request is the
   discussion thread for the RFC.
4. **Iterate.** Address substantive objections in the durable document, not only
   in comments.
5. **Decide.** A maintainer records one outcome:
   - **Accepted:** assign the next number and merge.
   - **Rejected:** close with a written rationale.
   - **Postponed:** close and state what would change the answer.
6. **Implement.** Track specification, conformance, SDK, documentation, and
   release work in the affected repositories.

An accepted RFC is a decision record. It becomes part of a released protocol
when the specification, conformance material, and versioned release are updated.

## The bar

A complete RFC answers:

- What problem does this solve, and for whom?
- What behavior or wire representation changes?
- What changes for implementers and users?
- What are the security and privacy consequences?
- What does compatibility and migration require?
- Which test vectors prove conformance?
- What alternatives were rejected?

## Numbering

Maintainers assign numbers sequentially at acceptance. The filename changes from
`0000-short-slug.md` to `NNNN-short-slug.md`.
