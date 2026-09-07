# Validation and scope

7 September 2026. The complete Article 352 alternative is a review candidate,
not a change to the website's selected draft.

- `python3 -I -m unittest discover -s reference -v`: 24 tests passed, including
  eight new holder-day/payment tests and three new stress-scenario tests.
- `python3 -I -m unittest discover -s tests -v`: 14 reviewer-tool tests passed.
- Candidate-root legislative lint: zero errors, nine terminology warnings.
  These concern capitalised institutional references; they are not a legal
  validity assessment. Lint runs with candidate/ as its working directory
  so cross-references use the actual alternative's articles.
- `python3 -I reference/stress.py`: 28 hypothetical scenario/percentage rows,
  each reporting real stake and real payment together at year 30. Assumptions
  are embedded in stress-scenarios.json; no current-company census or measured
  median-income target is supplied, so no minimum-percentage finding follows.
- New archives identify every submitted source file by hash and preserve the
  full target plus baseline and original Forum context. Review bodies and
  exact prompt versions are mapped in the closure prompt manifest.
- The ordinary Article 114 draft, website copy, public simulator and downloads
  have not been replaced by this alternative. Website build/release checks
  from the earlier repair package do not certify this different legal design.
- No new private data, external contact, filing, push, merge or deployment.

The holder-day ledger assumes verified identities and eligibility intervals.
It does not claim production security, bank integration, nationality matching
or post-payment reconciliation. It rejects silent edits to a posted year.
The reference reserve model assumes year-end contributions; the candidate
Annex additionally provides monthly inflation weighting for intra-year
contributions, which is not implemented in that prototype.

Candidate drafting: law 3c922a7; form closure: law 0338506. Tools and scenario
code: a54f8e2. Source-honesty addition to the form prompt: tools 34774a4.
Evidence-required addition to the constraint prompt: tools 93e0f11.
Original prompts and all adverse rounds remain preserved. See REVIEW-STATUS.md
for actual gate results, which are separate from these engineering checks.
