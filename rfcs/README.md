# RFCs

Substantive SGP changes are proposed and decided in public RFCs.

## When an RFC is required

Open an RFC for changes to Signal, Gate, Agent, or Mesh semantics; public wire
formats; trajectory receipt requirements; versioning; conformance; security or
privacy guarantees; or adoption of a design-stage control-plane concept.

Implementation bugs, editorial changes, SDK-internal refactors, examples, and
tests do not require an RFC unless they change a public contract.

## Statuses

- `draft`: authoring has started.
- `proposed`: ready for full review.
- `accepted`: approved as a decision record.
- `rejected`: declined with a written rationale.
- `postponed`: closed until stated conditions change.
- `superseded`: replaced by a later RFC.

## Process

1. **Discuss.** Open a
   [Discussion](https://github.com/orgs/signalgatingprotocol/discussions) or RFC
   sketch issue and establish the problem.
2. **Write.** Copy [`0000-template.md`](./0000-template.md) to
   `0000-short-slug.md`. Keep `0000` until acceptance.
3. **Propose.** Open one pull request containing the RFC. A non-author
   maintainer becomes shepherd and confirms the document is reviewable.
4. **Review.** Resolve substantive objections in the RFC text. Add test vectors
   or prototypes where semantics cannot be evaluated from prose alone.
5. **Final comment period.** The shepherd announces at least seven calendar
   days for final review and records the planned disposition.
6. **Decide.** Apply the governance threshold, record the rationale, assign a
   number to an accepted RFC, and merge the decision record.
7. **Implement.** Track specification, conformance, implementation, migration,
   and release work separately.

An accepted RFC authorizes a change. Released specification and conformance
material remain normative for released protocol versions.

## Required quality

A complete RFC states:

- the user or implementer problem;
- precise normative behavior using
  [BCP 14](https://www.rfc-editor.org/info/bcp14) terms where appropriate;
- schema and wire-format changes;
- security and privacy implications;
- compatibility, migration, rollout, and rollback;
- conformance tests or test vectors;
- operational and performance impact;
- alternatives and unresolved questions.

## Numbering and index

Maintainers assign numbers sequentially at acceptance. The filename changes from
`0000-short-slug.md` to `NNNN-short-slug.md`.

Accepted, proposed, postponed, rejected, and superseded RFCs will be indexed in
this file when the first numbered RFC is accepted.
