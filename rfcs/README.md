# RFCs

Substantive changes to the Signal Gating Protocol go through an RFC. This
exists so that protocol decisions are made in writing, in public, with the
people who will have to live with them.

## When you need an RFC

Open an RFC when a change affects:

- Signal, Processor, GatePlan, or Receipt schemas.
- Wire formats, identifiers, or version semantics.
- Conformance requirements.
- Security or privacy guarantees.
- Removal or breaking changes to any of the above.

You do **not** need an RFC for: bug fixes, editorial cleanups, internal
refactors of an SDK, additional examples, or new tests. If you're unsure,
open a discussion first.

## The process

1. **Discuss.** Open a thread in
   [Discussions](https://github.com/orgs/signalgatingprotocol/discussions)
   or an issue. Get rough alignment that the change is worth specifying.

2. **Write.** Copy [`0000-template.md`](./0000-template.md) to
   `rfcs/0000-short-slug.md`. Keep the `0000` prefix until the RFC is
   accepted.

3. **Open a pull request.** One file, one proposal. The PR is the
   discussion thread for the RFC.

4. **Iterate.** Maintainers and the community review. Address technical
   objections in the document, not the PR comments — comments age out, the
   document is the record.

5. **Decision.** A maintainer announces the decision on the PR:
   - **Accepted** — assigned the next number, merged.
   - **Rejected** — closed with a written rationale.
   - **Postponed** — closed for now; the rationale says what would change
     the answer.

6. **Land.** Accepted RFCs are followed by tracking issues in the affected
   repositories. The RFC is the source of truth until it is superseded by
   another RFC.

## The bar

An RFC is good when a competent implementer can build the change from the
document alone. If your reviewer has to ask what something means, the RFC
is not done.

Specifically, an RFC must answer:

- What problem does this solve, for whom?
- What changes on the wire?
- What changes for implementers? For users?
- What does it cost (complexity, performance, migration)?
- What did we consider and reject?
- How will we know it worked?

## Numbering

Numbers are assigned by maintainers at acceptance, sequentially. The RFC
file is renamed at that point — `0000-short-slug.md` becomes
`NNNN-short-slug.md`.
