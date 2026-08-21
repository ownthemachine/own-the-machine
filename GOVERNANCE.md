# Governance: how an open-source law changes

This repository is public. Every rule here is written for that fact:
strangers proposing amendments to a draft statute, in public, with the
history permanent.

## Roles

- **Editor:** David Vanheeswijck, until a campaign organisation exists and
  formally assumes the role. The editor merges; nobody else does, including
  automated tooling.
- **Reviewers:** anyone. Review rounds run by the team are committed to
  pipeline/reviews/ so outside reviewers can see the standard applied.
- **Contributors:** anyone, via issues and pull requests. No CLA; the
  licences (LICENSING.md) are the contract.

## The merge criteria

Two layers, both mandatory. Prose quality is judged last, not first.

**Substantive: the four tests.** A change fails review by definition if it
makes the instrument
1. less about assets and more about flows,
2. less universal (any means test, any discretionary gate),
3. less raid-proof (weakening entrenchment, adding emergency clauses,
   permitting sovereign self-dealing), or
4. later (moving obligations past the formation of the gains).

**Mechanical: the constraints table.** Every PR touching regulation/ must
state which DCs from regulation/memorandum/counter-arguments.md it touches.
A draft that violates a DC is rejected regardless of drafting quality. A PR
arguing a DC itself is wrong must amend the counter-arguments file first, in
the same PR, and survives only if the underlying objection is answered at
least as well as before.

## Change classes

| Class | Examples | Required before merge |
|---|---|---|
| Editorial | typo, punctuation, layout | editor's read |
| Prose | recital wording, memorandum text | legal-form gate + editor |
| Substantive | any enacting term, any threshold, any definition | full pipeline (all six gates) + editor |
| Constitutional | the four tests, the DC table, this file | full pipeline + public issue open ≥14 days + editor |

## Process

1. Open an issue describing the change and which objections (1-18) it
   relates to. Drafting starts in the issue, not the PR.
2. PR from a branch; template requires: DCs touched, change class, gates run,
   review files added under pipeline/reviews/.
3. Gates run per class (pipeline/README.md). Verdicts are committed, PUBLISH
   and REVISE alike. A REVISE with a written editor disposition can merge;
   silent overrides cannot.
4. Editor merges with a message stating what the change does to the
   instrument, not what it does to the text.

## Transparency rules

- No force-pushes to main, ever, once public. History is the product.
- Every review round, including failed ones, is committed.
- Editor dispositions that decline a finding are written into the review
  file, as in the wider project's practice.
- The site's public ledger is rendered from the review files and release
  notes: outcomes and dispositions are the public story; prompts and tooling
  remain inspectable in the tools repository.
- Funding, if any ever exists, is disclosed in campaign/ to the cent.
