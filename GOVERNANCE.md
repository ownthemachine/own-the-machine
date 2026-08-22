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

### The 14-day window assumes a public, and there is not one yet

The constitutional window was written for a repository people read. This one
is public but unannounced, and nobody has been asked to look at it. Running
a 14-day comment period against that audience produces no comments and then
treats the silence as ratification, which is a worse outcome than not
running it: it manufactures a legitimacy this project has not earned and
would have to defend later.

So the window runs from the first outreach, not from the merge. Until this
draft has been put in front of people who were invited to argue with it:

- constitutional changes may be merged by the editor on the full pipeline
  alone, and are **provisional**;
- each one is listed below as it is made;
- at first outreach every provisional change re-opens together, for the full
  14 days, and anything unable to survive that is reverted.

Provisional constitutional changes, pending the window:

- 21 August 2026: "Versions: the freeze at registration", added below.
- 22 August 2026: objections 20 and 21 and constraints DC-43 to DC-46 in
  regulation/memorandum/counter-arguments.md. DC-46 records that Article 1's
  objective needs quantifying before filing, which is the largest open
  drafting item this file has; the reasoning is in
  pipeline/reviews/2026-08-22-objections-20-21.md.

This clause is itself provisional under its own terms.

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

## Versions: the freeze at registration

Everything above describes a living draft. Registration under Regulation
(EU) 2019/788 changes that, and this repository has to change with it.
From the moment an initiative is registered, the annex as registered is
what citizens are asked to sign, and it cannot be amended. A draft that
keeps moving while signatures are collected against a fixed text is not
transparency; it is a gap between what was signed and what is published,
and it would rightly be read that way.

The rule is adopted here before there is anything to freeze, so that it
cannot later be written to suit a convenience.

1. **On the day of registration the filed text is frozen.** It is copied
   verbatim into versions/, with the commit it was taken from, the date of
   filing and the Commission's decision. Nothing in that directory is ever
   edited afterwards. A correction to a frozen version is a new frozen
   version, never an edit of the old one.
2. **versions/REGISTERED.json is the machine-readable state.** It names the
   registered version or records that there is none. The site reads that
   file and reports what it finds; no page states the answer from memory.
3. **The living draft continues, and says so on every page.** Work does not
   stop at registration, because the Commission's response is argued
   against the best version of the case, not the filed one. Every page
   rendering the living draft carries the distinction plainly, and the
   registered text is reachable in one click from any of them.
4. **Divergence is published, not characterised.** Where the living draft
   and the registered text differ, the difference is a diff a reader can
   read for themselves, never a claim about how minor it is.
5. **The frozen text is authoritative for what was signed. The living draft
   is authoritative for nothing until it is itself filed.**

Before registration, which is where this project stands, the state is
simply that no version is registered and the whole repository is a draft.

## Transparency rules

- No force-pushes to main, ever, once public. History is the product.
- Every review round, including failed ones, is committed.
- Editor dispositions that decline a finding are written into the review
  file, as in the wider project's practice.
- The site's public ledger is rendered from the review files and release
  notes: outcomes and dispositions are the public story; prompts and tooling
  remain inspectable in the tools repository.
- Funding and support are declared in campaign/FUNDING.md, and the
  declaration is kept current from now rather than from the moment
  Regulation (EU) 2019/788 makes it compulsory. "None" is not an
  acceptable answer while anyone is paying for anything.
