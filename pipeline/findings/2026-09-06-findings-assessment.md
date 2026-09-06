# Assessment of the outstanding legal-draft findings

Prepared on 6 September 2026 by the coding assistant for David Vanheeswijck's editorial review. Baseline: `0aeaada`. This is a diagnostic review of five findings, not an amendment, a completed six-gate release review or an opinion establishing the proposal's legal validity.

## Independent reviews and provenance

Both reviewers received the same immutable 34-file bundle, including the full regulation, governance, evidence and earlier findings, through the existing Requesty pipeline. Neither received the other's new review. They used the diagnostic prompt `own-the-machine-tools/prompts/findings-verification.md`.

| Reviewer | Result | Router-reported handling |
|---|---|---|
| [Fable 5.1](../reviews/2026-09-06-findings-verification-fable-r1.md), `vertex/claude-fable-5.1@eu` | REVISE | EU, 30-day retention, no training; explicit public/non-sensitive retention exception |
| [Gemini](../reviews/2026-09-06-findings-verification-gemini-r1.md), `vertex/gemini-3.7-flash@eu` | REVISE | EU, zero-day retention, no training |

Fable classifies Q1 as partly confirmed, Q2 as a confirmed textual defect with qualified consequences, Q3 as an omission requiring design decisions, Q4 as confirmed, and Q5 item by item with qualifications for dated estimates and imprecise descriptions. Gemini labels all five concerns confirmed. The assessment below preserves those findings while narrowing unsupported conclusions and declining problematic repair suggestions. Astra was not run; it was unavailable in the configured catalogue when checked earlier on 6 September.

The [manifest](../bundles/2026-09-06-findings-verification-manifest.json) identifies the archived input. Uncompressed bundle SHA-256: `02d22ea9ae2cd26b50ad50b3375bbe4c1d0a97501d8229cd209f9a78fb0357ac`. Prompt SHA-256: `27fb4afcbfe3fbbf1404d8b046adb0a19d8e31cb1b89b59ed571569e1fbf6633`. Both review headers record those same hashes. Reviews remain verbatim, with assistant dispositions outside their output. Final editorial responsibility remains with David Vanheeswijck.

## What survives direct verification

All five concerns warrant work. The strongest conclusions concern inconsistencies and omissions visible in the text. Predictions that an institution would certainly reject the proposal, or that a particular court interpretation is inevitable, are not established.

| Finding | Assessment | Practical repair direction |
|---|---|---|
| Article 5(4)(e), before a liquidity event | **Partially confirmed: narrower drafting conflict.** The warrant's no-obligations term is difficult to reconcile with extraction and seven-year crystallisation. It does not necessarily contradict the separate statutory duty to issue the warrant. | Reconcile the warrant terms with every crystallisation pathway and preserve all statutory duties. Check reporting and valuation timing together. |
| Article 3(8), genuine labour compensation | **Confirmed ambiguity/overbreadth.** The second sentence's literal effects test can reach genuine pay and employment changes, despite the avoidance context and recital 7. | Distinguish artificial avoidance from genuine hiring, genuine pay increases and genuine value changes. |
| Articles 8–9, Reserve governance | **Confirmed omission; resolution requires a design decision.** The draft establishes a legal person and assigns financial tasks without clearly identifying its decision-makers or representatives. | Specify who can act, how they are appointed and removed, what they may decide, and who audits and challenges their actions. |
| Article 13, subscription execution | **Confirmed gap in express administrative penalty coverage.** The reference to Article 5(5)'s third sentence does not clearly cover the separate ordinary execution duty in its final sentence. | Map each duty and add deliberate penalty coverage, including a clear answer for transferees. Preserve procedural safeguards. |
| EN and FR explanatory memoranda | **Confirmed fidelity and cross-reference defects.** Some old descriptions do not match the operative draft. | Correct both memoranda against the articles, including the missing French legal-basis explanation. |

## 1. Article 5: a conflict to clarify, not proof the subscription right disappears

[Article 5](../../regulation/articles/05-warrant.md) paragraph 4 governs the terms of the warrant. Paragraph 5 separately provides vesting by operation of law and execution following valuation. That distinction is the strongest defence against an allegation that paragraph 4(e) cancels every earlier statutory duty, including issuance under paragraph 1.

The surviving problem is more specific: paragraph 4(e) excludes warrant obligations before a liquidity event, whereas paragraph 3 expressly allows crystallisation before such an event. The seven-year route is particularly clear because no sale or owner cash-out is necessary. The present wording invites an avoidable argument over execution. This is not a conclusion that the undertaking would win that argument.

A repair must retain issuance, valuation cooperation, anti-avoidance and other statutory duties; merely replacing “liquidity event” with “crystallisation” in a blanket no-obligations clause may leave problems. Paragraph 6 expressly notifies impending liquidity events, but does not expressly address paragraph 3 events. Decide what must be reported, by whom and when. Crystallisation under paragraph 3 occurs on the last day of the financial year in which the condition is met, not necessarily on the seventh anniversary itself.

## 2. Article 3(8): protect real compensation, not just extra headcount

[Article 3](../../regulation/articles/03-designation.md) paragraph 8's second sentence directs disregard of arrangements increasing labour compensation or reducing fair market value. “Likewise” and the preceding avoidance language support a narrower interpretation. Recital 7 and [Annex I, point 3](../../regulation/annexes/annex-1-counting.md) also support genuine remuneration.

Those defences do not remove the drafting uncertainty. Clarify the operative condition rather than assert that regulators must disregard every genuine hiring programme. A repair requiring a “corresponding supply of labour” must be tested against higher pay for existing work: legitimate wage increases should not require extra headcount or extra hours. Genuine business losses also need to be distinguished from manipulated valuation.

Fable identifies a further policy choice supported by the first sentence: acquisitions are already covered by an effects-based avoidance rule. Narrowing the second sentence alone does not decide whether a commercially genuine acquisition of a labour-intensive business may still be disregarded. Settle and explain that distinction deliberately; do not promise that every genuine increase in group employment necessarily reduces the designation ratio under the current draft.

## 3. Reserve governance: legal accountability can coexist with automation

[Article 8](../../regulation/articles/08-reserve.md) gives the Reserve personality, assets, distribution and accounting duties. [Article 9](../../regulation/articles/09-prohibited-conduct.md) restricts how it uses those assets and expressly allows borrowing for subscription payments. The issue is neither absence of every financing route nor absence of restrictions on investment behaviour.

The missing piece is who is authorised to act for the Reserve: accept and register shares, approve a payment, sign a permitted credit agreement, appoint an auditor, respond to litigation and correct an error. Restrictions on voting or board seats in **covered companies** do not establish the Reserve's **own** governance.

Articles 15 and 16 do not provide an identified governance solution: the named delegated powers concern Annex I and II methodology; the implementing mechanism supports the valuation arrangements. Article 290 reserves essential elements to legislation and requires bounded delegation; Article 291 is not a general authorisation to fill any institutional gap. These are limits on an assumed later fix, not proof that one particular board design is mandatory. Sources: [TFEU Article 290](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:12012E290), [TFEU Article 291](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:12012E291).

Decisions needed: a dedicated statutory body or administration through a suitable existing institution; appointment/removal and independence; narrowly defined authority; representation, custody, audit, conflicts and remedies. Institutional eligibility and legal basis must be verified before choosing a host. Automation can execute routine calculations and workflows within this structure. This finding does **not** establish a need for paid campaign staff, a large bureaucracy or a EUR 300,000 campaign budget.

## 4. Article 13: distinguish a duty from the sanction for breaking it

[Article 13](../../regulation/articles/13-penalties.md) paragraph 1(b) names the third sentence of Article 5(5), which conditionally requires procurement of an equivalent subscription where governing law does not give effect to statutory vesting. The final sentence separately requires execution within 20 working days of valuation. The list does not expressly identify breach of that final sentence; periodic penalties in Article 13(2) refer back to paragraph 1.

This is a gap in express coverage of the Commission's administrative sanctions. It does not establish that the subscription obligation vanishes, that national remedies are unavailable, or that every refusal is beyond every listed offence. The conditional procurement duty depends on the effect of governing law, not simply whether a company is labelled EU or non-EU.

Article 5(11)'s “as if it were a covered undertaking” provides an argument for reaching transferees. Its interaction with Article 13's addressees should nonetheless be made explicit. Sanction type, addressee, breach, fault requirement and remedies need a deliberate mapping; do not assume the highest existing fine is automatically appropriate for every new offence.

## 5. Memoranda: specific corrections supported by the articles

Sources: [English memorandum](../../regulation/memorandum/explanatory-memorandum.md), [French courtesy memorandum](../../regulation/memorandum/explanatory-memorandum.fr.md).

- **Sections 2.4 and 3.3:** remove the claim that only value formed after designation is affected. Article 5(2) uses fully diluted capital immediately before the relevant event/date, not an incremental post-designation gains calculation. State all three crystallisation routes; owners need not realise value for the seven-year route. Describe actual voting/management restrictions instead of an unqualified “passive” label.
- **Section 3.3:** the dated nine-company estimate is not a permanent closed list. Article 3(6), future designation and transferee provisions prevent the claim that every other undertaking is unaffected. Use the operative age of 18, and distinguish entitlement from payment registration. No claim about a particular Member State's current age of majority is needed.
- **Section 3.4:** notification is not the only duty; valuation, issuance and execution also matter. Fair market value under Annex I is not necessarily an existing audited-accounts figure.
- **Section 4:** the national-vehicle fee provision is Article 11(3), not 10(6). Preserve both the actual-cost requirement and the 0.3% annual cap.
- **Sections 1.2 and 5.4:** a promised list of five open acquis interfaces is not actually enumerated. Recover and verify the underlying list or revise the claim; do not invent four missing entries.
- **French section 2.1:** add a faithful counterpart to the English explanation of the current Article 114 preamble and possible separate Article 352 architecture, after the English description has been checked.

The French courtesy file is a repository document, not the site's `content/fr/explanatory.md` translation. Local inspection of `own-the-machine-site/scripts/sync-law.mjs` and `src/components/screens/Explanatory.astro` shows that the site falls back to English when that translated content file is absent; no such file currently exists. The earlier suggestion that the courtesy document should automatically trigger the website's stale-translation banner is therefore unsupported. This is a local source check, not a fresh verification of deployed output.

## Review quality controls and declined suggestions

The model output is evidence to assess, not authority to copy. In particular, the Gemini review's following assertions or proposals are not adopted:

- Its categorical litigation/institutional-rejection predictions and exact mandatory governance architecture exceed the evidence verified here. Its case-law claims require independent source checking before citation in the law.
- An annex is operative text; the claim that both recitals and annexes are categorically unable to qualify an article should not be accepted as a general rule.
- Replacing the memorandum error with “value realised after designation” or describing realisation as the primary trigger still risks obscuring the seven-year route. Explain the actual capital base and each trigger directly.
- Its suggested four missing acquis interfaces have not been established as the promised historical list. They must not be inserted on that basis.
- Its suggested EIB/ESM hosting arrangements are not established as legally available or interchangeable. Verify institutional status, mandate and legal basis separately.
- Its assertion that Article 6 valuation within 20 working days is impossible without completed annual audited accounts is not proved by the text. Timing and information availability warrant testing, but simply delaying valuation until accounts are delivered could enable delay and change the policy.
- Its proposed subsets of gates for operative amendments do not match this repository's requirement: substantive amendments require **all six** gates, plus lint and the editor. Public constitutional procedure applies if the constitutional rules/constraints change; an ordinary governance addition is not automatically such a change.

Fable's conclusions are also qualified. Describing every procurement case as “third-country” is too categorical; governing-law effect is the actual condition. Transferee coverage is insufficiently explicit, but its exclusion from every possible interpretation is not proved. General audit/discharge, supervisory and institutional-status claims need their own legal checks; this audit does not adopt the categorical statement that being outside the general budget alone resolves all discharge questions. Its proposed no-obligation wording needs the same statutory-duty safeguards as Gemini's. Its proposed memorandum replacement “no present obligation” outside the estimated nine is not adopted without verifying the actual designation and notification position. The public constitutional-style discussion it recommends for appointments is a recommendation, not an automatic extra approval requirement imposed by this audit.

## Related findings to carry into the repair review

- **Timing, textually verified:** Article 5(5)'s conditional procurement sentence sets completion of the liquidity event as its deadline, while Article 6(3) permits valuation afterwards and execution follows valuation. An obligation to arrange effective procurement by completion might reconcile these provisions, but the text should say whether that is intended. Check this alongside the original Article 5 finding.
- **Explanatory alignment:** Fable points to related “future value” language in DC-1, audited-accounts-only language in recital 7 and “passive” in recital 23. Trace and reconcile those layers during repairs. Amending a DC is constitutional under repository rules; changing the memorandum alone cannot silently redefine it.
- **Further design checks, not adopted amendments:** transferee duties beyond issuance; share-based compensation valuation; Article 9 supervision; and whether an older payout example satisfies the project's scenario-label rule. Preserve these as follow-up checks, rather than treating every proposed remedy as verified or expanding this diagnostic into a new economic design.

## Repair order and validation

1. Correct memorandum statements already contradicted by unchanged articles, with EN/FR fidelity review. No policy choice is needed to stop overstating the existing text.
2. Prepare coordinated Article 3/5/13 drafting repairs. Test genuine hiring, pay increases for unchanged work, sham payroll and genuine valuation falls; liquidity, extraction and seven-year crystallisation; issuance followed by refusal to execute; governing-law fallback and transferee defaults.
3. Choose a minimal accountable Reserve administration model and draft its powers and safeguards. Test who can sign the first subscription payment, obtain permitted liquidity, declare a distribution, appoint an auditor and respond to a challenge, including absence or conflict of the normal decision-maker.
4. Run lint and all six gates against the full resulting substantive draft, then synchronize explanations and translations. Treaty legal basis and property-rights validity remain separate questions; this scoped diagnostic audit does not settle them.

No operative text or website content is changed by this assessment. Findings remain open until a repair is actually drafted and reviewed; a diagnostic REVISE is preserved rather than rerun until it becomes PUBLISH.

Validation: legislation lint returned zero errors and seven existing warnings. The archived bundle was decompressed and matched against the submitted input and both review hashes; the prompt matched both review hashes. Local assessment links and authored-document whitespace were checked. Verbatim review output retains its original whitespace, including Markdown line endings flagged by Git. No website rebuild is necessary for these diagnostic records, and none is claimed. These checks do not replace legal review of a future amendment.
