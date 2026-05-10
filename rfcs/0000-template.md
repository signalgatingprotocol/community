---
title: <One-line title — what changes>
authors: [<github-handle>, ...]
status: draft           # draft | proposed | accepted | rejected | superseded
created: YYYY-MM-DD
target-version: <e.g. 0.4.0, or "next-major">
supersedes: <RFC number, if any>
superseded-by: <RFC number, if any>
---

# Summary

One paragraph. What changes, and what becomes possible because of it.

# Motivation

Why this is worth doing now. The problem in the user's words. Concrete
scenarios that are painful today and stop being painful after this RFC
lands.

# Proposal

The change, in detail. Schemas, wire formats, types, semantics. Pseudocode
or full examples where they sharpen meaning.

A reader who has read the existing spec must be able to implement this RFC
from this section alone.

## Schema changes

Show the diff against the current schemas. New fields, removed fields,
changed types. State which are required vs optional and what defaults
apply.

## Behavior changes

Describe runtime behavior precisely. Use MUST / SHOULD / MAY in the
[RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119) sense.

## Compatibility

What breaks. Who has to do work. What deprecation window applies.

# Examples

At least one end-to-end example showing a Signal entering, GatePlans being
produced, processors activating, and Receipts emitted.

# Drawbacks

Honest. What's worse after this lands.

# Alternatives

What else was considered. Why those were rejected. "Do nothing" is always
an alternative; say what's wrong with it.

# Open questions

What you don't know yet, framed so a reviewer can help answer it.

# Adoption plan

Tracking issues, target SDK versions, conformance test additions, docs to
update, migration notes. How we will know the change actually shipped.
