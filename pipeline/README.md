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

Run in this order; later gates assume earlier ones passed. All via
`pipeline/review.sh <file-or-bundle> <out> pipeline/prompts/<gate>.md`.

| # | Gate | Prompt | Catches | Suggested model tier |
|---|---|---|---|---|
| 1 | Legal form | legal-form.md | Joint Practical Guide violations: normative recitals, "should" in enacting terms, undefined terms, broken cross-references, powers architecture | fast |
| 2 | DC compliance | dc-compliance.md | violations of the 28-row constraints table | fast |
| 3 | Legal basis and rights | legal-basis.md | Art. 114/173 reasoning, subsidiarity, proportionality, Charter Art. 17, Art. 345 | strongest available |
| 4 | Hostile counsel | hostile-counsel.md | how a litigator for covered undertakings, or the Legal Service, kills the text | strongest available |
| 5 | Acquis coherence | acquis-coherence.md | collisions with company law, Prospectus, IORP II, PEPP, DMA definitions | strong |
| 6 | Layer fidelity | layer-fidelity.md | drift between the articles, the memorandum and the plain-language layer | fast |

Before any gate: `python3 scripts/lint-legislation.py` (mechanical checks;
free; no excuse to skip).

## Which gates when

- Editorial changes: lint only.
- Prose changes: lint + gates 1 and 6.
- Substantive changes: lint + all six.
- Constitutional changes: all six plus the 14-day public issue
  (GOVERNANCE.md).

## Status

DRAFTING-RULES.md and the legal-form prompt are scaffolds pending the
legislative-drafting research (in flight, 18 Aug); they carry TODO markers
and must be completed from its findings before the first article is gated.
Gates 2-6 are operational now.
