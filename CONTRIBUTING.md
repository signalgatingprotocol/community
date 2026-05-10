# Contributing

There are three ways in. Pick the smallest one that fits.

## 1. Discuss

For questions, ideas, half-formed thoughts, and ecosystem signal:

→ [GitHub Discussions](https://github.com/orgs/signalgatingprotocol/discussions)

You do not need to know if your idea is good. You need to write it down so
others can react to it.

## 2. Open an issue

For concrete bugs and concrete proposals that don't yet need an RFC:

→ [New issue](https://github.com/signalgatingprotocol/community/issues/new/choose)

Pick a template. Fill it in. The templates exist so that the first reply
you get is useful.

## 3. Submit an RFC

For changes to the protocol surface — schemas, wire formats, conformance,
versioning. The process is in [`rfcs/README.md`](./rfcs/README.md).

Open the RFC as a pull request against [`rfcs/`](./rfcs/). One file, one
proposal. Use [`rfcs/0000-template.md`](./rfcs/0000-template.md).

## Code

Code lives in the SDK repositories — start with
[`python-sdk`](https://github.com/signalgatingprotocol/python-sdk). Follow
that repo's contribution guide for build, lint, and test conventions.

## Standards we hold ourselves to

- **Clarity over cleverness.** If a reviewer needs a paragraph to understand
  a function, the function is wrong, not the reviewer.
- **Small diffs.** One change per pull request. Refactors that aren't part of
  the change ship separately.
- **Spec first.** Behavior that affects implementers is documented before it
  is merged.
- **No dead code.** No commented-out blocks, no "future use" stubs, no
  vestigial flags.
- **Receipts everywhere.** If we change behavior, the changelog and the
  release notes say so plainly.

## Licensing of contributions

By submitting a contribution, you agree it is licensed under Apache 2.0 — the
license of this repository — and that you have the right to submit it.

## Conduct

By participating, you agree to the [Code of Conduct](./CODE_OF_CONDUCT.md).
