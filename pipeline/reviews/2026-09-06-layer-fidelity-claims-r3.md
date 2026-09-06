---
gate: layer-fidelity
target: campaign and website claim corrections
commit: ed351bc
verdict: REVISE
disposition: see-claims-disposition
date: 2026-09-06
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-06T19:36:54+00:00 · tokens in=153216 out=27479
> Prompt: otm-layer-fidelity-r3.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `32f9b8ae499c954f6238c26cceb328374eeff0e6746f3bd78fe03878f1b3357a`
> Prompt SHA-256: `69e50293bef58b180b6c70fc2f047c7d5bc4be65a32ae9968fb8223b6b58090c`

# Layer-fidelity review: claim-correction package, 6 September 2026

Scope applied as instructed: the changed plain pages (brief, FAQ, join, sign, press, about, contribute), `en.mjs` strings, `REGISTRATION-TEXT.md`, DISTRIBUTION/GATES/launch plan, simulator source and strings, and the review tooling, read against the unchanged articles, annexes, recitals and memoranda as reference. Pre-existing defects in reference layers are listed separately at the end and do not bear on the verdict.

## What the corrections get right (verified, not assumed)

- DC-14: no plain page states a first-year or early-year income. Home ("Returns may be small or zero"), brief ("may be zero"), FAQ ("could be zero"), press ("could be zero") all match Annex II point 2 and recital 24. The simulator reports year 20 and year 50 only, shows the stake beside every payout (DC-31, `stakeSentence`, `generationSentence`), permits zero in `fmt`, and its assumption strings describe what `run()` actually does (positive `r`, no retention line, collar floored at `0.02 * capital`, cohorts continuing at `growth = 0`).
- DC-23: home, brief, FAQ and press all state protection as friction ("cannot prevent all future amendments", "legal barriers, not a guarantee", "cannot guarantee that future legislators never amend"). No plain page says "untouchable" any more.
- Article 10(6) is now rendered precisely in the FAQ (ten-times-cost rule, once-in-every-third-positive-year backstop, roll-forward), and the FAQ glosses "backstop" as the draft's "long-stop".
- Triggers are consistent across home, brief, FAQ, press and registration: first liquidity event, extraction above the Article 5(3)(a) threshold, seven-year long-stop; issuing the warrant is distinguished from crystallising it.
- Registration now discloses nominal cash payment (5(5)), valuation costs on the undertaking (6(3)), fines to the budget (13(6)), the Article 352 two-act incompleteness, and non-automatic repeal (14(3)); the labour-share premise is gone.
- Sign/join/about/press: 18-or-older, seven Member States of residence not nationalities, Belgium 15,840 on 720 MEPs, COCS online with paper permitted, response-not-legislation. All match the bundle's stated ECI facts.
- Tooling: `review.sh` exits 2 on REVISE/missing/ambiguous verdicts, stamps bundle and prompt hashes, refuses Astra substitution and silent ZDR relaxation; README and about.md describe that behaviour accurately, and neither claims Astra ran.

## Findings

### 1. UNDERDISCLOSURE (scope narrowing) — registration annex omits the below-threshold designation route and the rebuttal that the FAQ and press now disclose

Plain layer (REGISTRATION-TEXT.md §4, the text that would be filed):
> "Undertakings above objective thresholds would be designated on the model of Regulation (EU) 2022/1925."

Articles:
> Article 3(2): "An undertaking shall be presumed to satisfy…"; Article 3(5): "The undertaking may … present sufficiently substantiated arguments …"; Article 3(6): "The Commission may designate as a covered undertaking any undertaking that satisfies the requirements of paragraph 1 without meeting the thresholds of paragraph 2, following a market investigation…"

Same site, corrected FAQ:
> "A company may rebut the presumption. The Commission may also designate a company below those thresholds after investigation."

Reader harm: the filing text presents the thresholds as the perimeter, which is the exact narrowing the launch plan classed "Immediate" for the FAQ and brief. The FAQ was fixed; the annex, which is the fixed text a registration officer and every signer reads, still carries the narrower description, so two plain pages now give the instrument two different reaches. A signer reading only the Commission's register would learn the wider reach (and the Commission's investigation power) from a critic, not from the organisers.

Minimal fix (plain layer, registration §4; ~60 characters, within the 5 000 limit): "Undertakings would be designated on the model of Regulation (EU) 2022/1925: a rebuttable presumption above objective thresholds, and designation on the facts below them after a market investigation."

While in that paragraph, two minor precisions in the same layer: "enforcement fines accrue to public budgets" should read "to the Union budget" (Article 13(6) names the general budget of the Union and excludes the Reserve; "public budgets" implies national receipt), and "above a stated share of its turnover" should read "of its turnover from the covered activity" (Article 5(3)(a) measures against covered turnover, a smaller denominator that fires sooner). Neither alone would warrant REVISE.

### 2. TERM DRIFT — "backstop" now names two different rules depending on layer

Plain layer: home col1 "a seven-year backstop"; brief "the seven-year backstop"; press "the seven-year backstop after issuance"; simulator `lagNote` and assumptions "the seven-year backstop".
Articles/recitals: recital 12 "The seven-year long-stop"; memorandum §5.3 "the seven-year long stop".
Memorandum, objection 15 and DC-40: "a hard backstop of one distribution in every three years"; Article 10 drafting notes "The three-year backstop".

Reader harm: a reader who moves from the home page to the objections page meets "backstop" first as the warrant's seven-year rule and then as the distribution's three-year rule, with the recital calling the first one "long-stop". Only the FAQ glosses the two words together. This does not change who would sign, but it is a defined-concept split across layers on a project whose credibility is precision, and the label check in `check-labels.mjs` exists for exactly this defect class.

Minimal fix (plain layer): use "seven-year long-stop" in home, brief, press and the simulator strings, or gloss once per page as the FAQ does ("seven-year long-stop (backstop)"). No article change.

### 3. TERM DRIFT (low) — retention exception described as a class on the site, as a single run in the tooling

Plain layer (about.md): "For the public or intended-for-publication, non-sensitive material Fable 5.1 reviews introduced on 6 September 2026, the editor permits the router-reported 30-day retention…"
Tooling (README): "The editor requested Fable 5.1 for the public claim-correction review. For that public-material run only, use the documented retention exception"; `.env.example`: "public-material exceptions require REVIEW_REQUIRE_ZDR=0 explicitly"; `review.sh`: exception per invocation, positional, Fable only.

Reader harm: a reader relying on the zero-retention disclosure cannot tell from the site whether one review or a standing category of reviews runs under 30-day retention. The runner makes it per-run and explicit; the site reads as a standing policy.

Minimal fix (plain layer, about.md): "…the editor may permit, explicitly and per run, the router-reported 30-day retention for public, non-sensitive material; each such review's provenance line records it." Tooling unchanged.

## Optional preferences (not required; recorded separately)

- FAQ one-sentence answer says the fund "pays equal distributions to adult EU citizens"; every other page uses "would" and "aged 18 or older". Align tense and age wording (Article 10(1) fixes 18; "adult" is a Member State concept).
- "Fund" is used colloquially (FAQ "Who controls the fund?", "a small fund") for a body Article 8(7) and recital 21 expressly distinguish from a fund; the Forum's own sceptical framing was "the creation of a fund". "Reserve" throughout would cost nothing.
- Home "basis" and brief "Legal basis" list Articles 114 and 352 as proposed bases; the draft's preamble cites 114 alone. The registration text discloses this; a short clause on home/brief ("the draft's preamble cites Article 114; Article 352 would need a separate act") would close the gap for readers who never reach the registration page.
- Article 11(3) charges on holders (up to 0,3 % annually) are nowhere in the plain layer; FAQ "after costs" reads as Reserve costs. One clause in "Do I get money?" would disclose the only charge a citizen personally bears.
- Registration §4 alternates "a common reserve"/"The reserve" with "The Reserve"; pick the defined-term capitalisation.
- Contribute: "A pull request that weakens a protection does not merge" is stronger than GOVERNANCE.md, which says such a change "fails review by definition" while a REVISE with a written disposition can merge. "Fails review under the published governance rules" is the exact statement.

## Pre-existing defects in reference layers (for the six-gate legal revision, not this package)

1. **Article 5(4)(e) v Article 5(3)/(5).** 5(4)(e) says the warrant imposes "no obligation on the covered undertaking prior to a liquidity event other than the notification obligation in paragraph 6", yet 5(3) crystallises before any liquidity event and 5(5) then obliges execution within 20 working days. The plain layer correctly follows 5(3); the articles are internally inconsistent. Related: Article 5(6) notifies liquidity events only; there is no notification duty for 5(3) crystallisation. The launch plan already lists this for counsel.
2. **Article 13(1) coverage.** The fine list reaches failure to issue the warrant, third-country procurement measures, notification and information failures, and circumvention; failure to execute the subscription itself (last sentence of 5(5)) by a Union-law undertaking is not enumerated, and 13(2) periodic penalties are tied to the paragraph 1 list. Worth hostile counsel's attention.
3. **Memorandum §4 cross-reference (EN and FR):** "Article 10(6) caps the fees national vehicles may levy" — the cap is Article 11(3); 10(6) is the distribution-frequency rule.
4. **Memorandum, objection 15 v objection 21:** "roughly EUR 400 of owned capital behind every citizen by year thirty" is a pre-22 August figure; objection 21 and the current simulator model put the per-adult stake in the thousands (about EUR 8 400 within a generation at 3 %). Objection 15 also states a payout order without the stake beside it, which DC-31 forbids in the project's own material.
5. **Memorandum §3.3 (social impacts):** "distributions being made from the age of majority under Article 10" — Article 10(1) fixes 18, not majority.
6. **FR courtesy memorandum** lacks the 6 September paragraph in §2.1 on the preamble citing Article 114 alone; the `source-commit` staleness banner should be firing on that page. Verify it does.

VERDICT: REVISE

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.

Specific disposition: required findings 1–3 were corrected in the final r9 bundle and independently checked by the standard layer-fidelity closure run r4. Fines now name the Union budget; the extraction denominator names covered activity. Optional preferences are not represented as compulsory legal findings. The ordinary-language word fund denotes the proposed Reserve in an expressly hypothetical explanation; the page disclaims any current benefit. Constitutional non-weakening rules remain the contribution criterion, notwithstanding the general ability to record dispositions on other REVISE findings. Unchanged statutory and memorandum issues remain open.
