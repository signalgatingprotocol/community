# Security Policy

## Reporting a vulnerability

**Do not open a public issue.**

Report privately through GitHub's [private vulnerability reporting][gh-pvr]
on this repository. If that is not available to you, email the maintainers
listed in [`.github/CODEOWNERS`](./.github/CODEOWNERS) directly.

Include:

- What you found.
- How to reproduce it — exact steps, minimal repro if possible.
- Affected versions or commits.
- Your assessment of impact.

You will get an acknowledgement within **72 hours**.

## What we treat as a vulnerability

- Schema or wire-format flaws that allow processors to be activated outside
  their declared conditions.
- GatePlan production paths that bypass declared gates.
- Context minimization failures that leak features the processor was not
  authorized to receive.
- Receipt forgery, tampering, or replay.
- Protocol-level denial of service against conformant implementations.
- Vulnerabilities in code published under this organization.

## Coordinated disclosure

We follow a 90-day standard disclosure window. We will work with you on a
shorter window if a fix lands sooner, or a longer window if active
exploitation makes a quiet fix safer for users. Either way, the window is
agreed in writing.

You will be credited in the advisory unless you ask not to be.

## Scope

This policy covers repositories under the
[`signalgatingprotocol`](https://github.com/signalgatingprotocol)
organization. Vulnerabilities in third-party implementations of SGP should
be reported to the implementation's own maintainers; we are happy to help
coordinate.

[gh-pvr]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability
