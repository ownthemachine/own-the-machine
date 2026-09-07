# Review outcome and editor handoff

Prepared 7 September 2026. **Reviewable candidate, not cleared for release.**
The published book's generational ownership thesis is preserved. No yearly
increase in payments is guaranteed. No compulsory campaign staffing budget
or EUR 300,000 requirement is introduced by this package.

## Actual gate results

All six gates were run through Requesty. Gemini used the configured EU route
with zero retention and no training. Hostile counsel used Fable 5.1 on the
EU route with the explicitly selected 30-day retention exception and no
training. Astra was not run: its earlier availability check did not yield a
usable route; this package does not claim a new availability check.

| Gate | Rounds and actual verdicts | Disposition |
|---|---|---|
| 1 Legal form | r1 REVISE; r2 REVISE; r3 PUBLISH; r4 REVISE; r5 PUBLISH | Final prose snapshot passes this gate. |
| 2 DC compliance | r1 PUBLISH, only 28 constraints; r2 PUBLISH, all 46 | r1 is incomplete and superseded. Explicit coverage checker passes r2. |
| 3 Legal basis and rights | r1 REVISE | Material questions remain open for qualified legal assessment. |
| 4 Hostile counsel, Fable 5.1 | r1 REVISE | Accepted concerns and source qualifications below; not release clearance. |
| 5 Acquis coherence | r1 REVISE | Incorrect article references rejected; remaining interfaces open. |
| 6 Layer fidelity | r1 REVISE; r2 PUBLISH | Corrected the unconditional three-year payout summary in all five languages. |

Gate 2 and gates 3–5 assessed the r3 substantive snapshot. Subsequent changes
were explanatory and drafting-form corrections, closed through gates 1 and
6. Reserved institutional/accounting proposals have not become operative
articles. Continuing later gates despite adverse earlier gates was an
explicit diagnostic exercise, not satisfaction of the normal release order.
The README's local issue record documents the separate public-issue deviation.

All outputs, including adverse rounds, are preserved under
[pipeline/reviews](../../pipeline/reviews/). Exact source snapshots, prompt
versions and hashes are in [pipeline/bundles](../../pipeline/bundles/), with
review-to-input mapping in
[the prompt manifest](../../pipeline/bundles/2026-09-07-generational-prompts/manifest.json).
The languages-r1 archive was preparatory and was not submitted. Model role
headings are simulated, not opinions from an EU institution. A model's
self-written date or round number is not provenance. Router headers govern.
Gate 6's phrase 'adopted candidate text' is also inaccurate: no adoption occurred.

## Repairs accepted and implemented

- Warrant attachment at effective designation, independent of document delay;
  preserved transfer clocks, aggregate cap and enforceable reporting/execution.
- Genuine remuneration and evidenced valuation changes recognised, while
  artificial inflation/deflation remain subject to the anti-avoidance rule.
- Early preparatory administration separated from general application and
  completed earlier events excluded from retrospective capture.
- EN/FR memorandum and related website copy describe all three triggers,
  whole-capital valuation and contingent distributions, without claiming
  owner realisation is always required or that there are no other duties.
- Recital Charter mapping corrected; no completed EDPS consultation invented.
  Duplicate recital wording removed; operative interpretation wording clarified.
- Small distributions do not by themselves disprove concentrated ownership:
  capital accumulation and available cash income are distinct.
- The Article 10 summary now counts years with positive distributable income,
  rather than promising a payment every three calendar years regardless of income.
  It distinguishes the protected entitlement from freely usable money received.
- The reference model separates appreciation, cash income, debt, costs,
  loss recovery and deferred distributions. The public simulator remains a
  simplified illustration; its specification now states its omissions and
  that the displayed band is not a calibrated probability interval.

Legal-form r4's punctuation instruction was not automatically followed:
it conflicted with the earlier reviewer instruction. Its request to remove
'for preparatory administration' from Article 18 was also retained for the
editor because deleting a scope qualification is not merely punctuation.
The final form reviewer passed the retained wording. This is a recorded
disposition, not proof that an AI has settled legislative house style.

## Concerns that remain substantive

1. **Legal basis and property rights.** The internal-market connection,
   fiscal classification, proportionality of compulsory equity participation,
   and institutional powers need a reasoned specialist opinion. Calling the
   mechanism ownership does not itself settle its legal classification.
2. **An operable Reserve.** Appointment, accountability, staff/contracting
   powers, liability, budget rules, custody, start-up nominal-value finance
   and data responsibilities must be integrated after the editor's choices.
   Automation remains the operating preference; accountability still needs
   named legal decision-makers.
3. **Issuer and beneficiary rules.** Economic-group designation needs a
   legally identifiable issuer, treatment of entities without shares,
   minority interests and apportionment. Payment registration, citizens
   abroad, portability and the common eligibility period need integrated rules.
4. **Accounting.** Current Annex II is not the reference model. Loss treatment,
   protected capital, costs, allocation versus payment and sizing must be
   reconciled through a substantive amendment before using new projections.
5. **Enforcement and market interfaces.** Verify ordinary-exchange transfer
   observability, pre-designation preference arrangements, investigation
   powers, foreign enforcement/jurisdiction, prospectus treatment of new
   share classes, vehicle supervision and public-service compensation.
   Withholding and administration support also need explicit treatment;
   blanket claims of no public budget involvement are inappropriate.

These are scoped follow-up questions, not a finding that the project is
impossible. Neither AI verdicts nor this drafting work replace legal advice.

## Findings not adopted as established facts

See [SOURCE-CHECKS.md](SOURCE-CHECKS.md) for primary-source verification.
The acquis reviewer misidentified Directive 2017/1132 Articles 70, 72 and 74;
its proposed broader derogations were therefore not inserted. The legal-basis
review's M-S/C-201/18 identification and British Airways citation do not
support the propositions for which it used them. Predicted court odds,
parliamentary objection counts and unverified tax/market figures are not evidence.

Fable's low-price crystallisation argument overlooks later growth of a fixed
equity fraction. Its employee-equity example needs the two-year averaging rule
and the qualitative designation route. Its payment-cost algebra omits charges
and initial quotes explicitly contemplated in Annex II. These qualifications
do not dismiss separate issuer, valuation, avoidance or cost-design questions.
Future legal prompts now require source qualification and prohibit fabricated
institutional authority and numerical court probabilities. Archived reviews
retain the original prompts and output, without retrospective alteration.

## Decisions for the final editor

| Decision | Concrete candidate | What happens after selection |
|---|---|---|
| Reserve administration | Five independent trustees, board-appointed executive and accountable automation; existing institution is an alternative requiring mandate verification | Complete institutional powers, financing and governance articles. |
| Issuer and payment eligibility | Parent-level issuance with safeguards; one payment registration and eligible-holder-days | Resolve no-share entities and integrate Articles 3 and 10–11. |
| Accounting | Cash-conserving model with immediate loss recognition and separate allocation/payment | Replace conflicting accounting rules and rerun DC-45/46 sizing. |

No constitutional DC wording was changed. DC-1's older 'future value' wording
remains an explicit editorial question, and the 3% percentage is unchanged.
The reference scenarios use arbitrary units and are not a dividend forecast.
The next legal review should examine the chosen integrated design, rather
than repeatedly asking models for more favourable verdicts on unchanged risks.

## Validation

The tools suite passed 14 tests; the reference model passed 13 tests, including
multi-year cash and asset conservation. Legislative lint passed with zero
errors and seven existing terminology warnings. Final site build, release
checks and source-provenance verification are recorded in VALIDATION.md.

Changes are on local branch `feat/generational-repair-package` in all three
repositories. Nothing has been pushed, merged or deployed by this work.
