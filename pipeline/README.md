# The legislation pipeline

The strictest gate set in the project, because the artefact is a draft
statute that professionals must be unable to dismiss on form, and because
the repo is public: the pipeline is part of the credibility, visible to
every reader.

Inherited from the book project's hard-won lessons: reviewers get FULL
document context, never fragments; every round is committed, PUBLISH and
REVISE alike; declined findings carry a written editor disposition; and the
automated gate is trusted on rule violations, never on whether a sentence
lands. The final read is always human.

## The six gates

Run in this order; later gates assume earlier ones passed. **The runner, the
six gate prompts and the linter live in the
[own-the-machine-tools](https://github.com/ownthemachine/own-the-machine-tools)
repository (MIT)**: machinery there, so this repository stays the civic
artefact: the law, its evidence, its governance and the ledger of its own
evolution. Review OUTPUTS are committed here under pipeline/reviews/,
because a verdict on a statute is part of the statute's history.

| # | Gate | Catches | Suggested model tier |
|---|---|---|---|
| 1 | Legal form | Joint Practical Guide violations, powers architecture, DMA threshold pattern, memorandum skeleton | fast |
| 2 | DC compliance | violations of the 30-row constraints table | fast |
| 3 | Legal basis and rights | Art. 114/173 reasoning, subsidiarity, proportionality, Charter Art. 17, Art. 345 | strongest available |
| 4 | Hostile counsel | how a litigator for covered undertakings, or the Legal Service, kills the text | strongest available |
| 5 | Acquis coherence | collisions with company law, Prospectus, IORP II, PEPP, DMA definitions | strong |
| 6 | Layer fidelity | drift between the articles, the memorandum and the plain-language layer | fast |

Before any gate: the linter from the tools repo (mechanical checks; free; no
excuse to skip).

## Which gates when

- Editorial changes: lint only.
- Prose changes: lint + gates 1 and 6.
- Substantive changes: lint + all six.
- Constitutional changes: all six plus the 14-day public issue
  (GOVERNANCE.md).

## Review file convention, and what the public actually sees

Review files live at pipeline/reviews/YYYY-MM-DD-<gate>-<slug>.md and open
with front matter the site can render:

    gate: hostile-counsel
    target: regulation/articles/03-designation.md
    commit: <sha>
    verdict: REVISE
    disposition: merged-with-fixes | declined (reason) | pending
    date: 2026-09-04

The campaign site renders a public ledger of the law's evolution from these
files and from release notes: what changed, what prompted it, what review
found, how the editor disposed of it, with a diff link. That ledger, not
this tooling, is the public story. The prompts and runner stay inspectable
here, because the repo is open and hiding machinery reads worse than owning
it, but the product is a law that shows its work, not a showcase of the
workshop.

## Status

All six gates are operational. DRAFTING-RULES.md was completed from the
legislative-drafting research on 18 August (source record with all URLs:
research-drafting-2026-08-18.md); the legal-form gate now enforces the Joint
Practical Guide, the DMA Article 3 threshold pattern, the BRRD property
architecture and the Commission's memorandum skeleton.
