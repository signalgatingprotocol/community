# Contributing

Choose the smallest path that fits the change.

## Discuss

Use [GitHub Discussions](https://github.com/orgs/signalgatingprotocol/discussions)
for questions, early ideas, prior art, and design exploration.

## Open an issue

Use the [issue templates](https://github.com/signalgatingprotocol/community/issues/new/choose)
for a reproducible protocol documentation bug, a focused question, or an RFC
sketch.

Implementation bugs belong in the affected SDK repository.

## Submit an RFC

Changes to the current protocol surface or adoption of a design-stage concept
follow [`rfcs/README.md`](./rfcs/README.md). Copy
[`rfcs/0000-template.md`](./rfcs/0000-template.md), complete every applicable
section, and open one pull request containing one proposal.

## Submit implementation code

Start with the
[`python-sdk`](https://github.com/signalgatingprotocol/python-sdk) and follow its
repository-specific setup, lint, type-check, and test commands.

## Review standard

- Keep each pull request coherent and reviewable.
- Explain the user or implementer impact.
- Support protocol claims with a specification section, test vector, or
  reproducible example.
- Update specification and conformance material with public contract changes.
- Separate unrelated refactors from behavior changes.
- Resolve substantive review comments in the durable document or code, not only
  in the conversation thread.

For documentation changes, render the affected Markdown, verify every changed
link, and check terminology against the current maturity table in
[`README.md`](./README.md).

## License and conduct

By submitting a contribution, you agree that it is licensed under Apache 2.0
and that you have the right to submit it. Participation is governed by the
[Code of Conduct](./CODE_OF_CONDUCT.md).
