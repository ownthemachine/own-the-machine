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
> 2026-09-06T19:24:51+00:00 · tokens in=153041 out=16829
> Prompt: otm-layer-fidelity-final.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `0e9bf98c7abe1e9101794d0f2a8e18b5ef7d8e097813e3a7d02f33653294d272`
> Prompt SHA-256: `78c4aaa523bc630321d2b87f296ba9ab59f5943ff931477e175fc6890d16c0bf`

# Layer-fidelity review: claim-correction package, 6 September 2026

Scope applied as instructed: the changed plain-language pages (brief, faq, join, sign, press, about, contribute), the English dictionary, the registration text, the campaign documents named as changed, and the tooling. Articles, recitals and memoranda read as reference only.

## Cleared on re-check

The items the preceding round listed as corrected do read correctly against the articles: the three crystallisation triggers appear consistently in home, brief, FAQ, press and registration; the Article 10(6) frequency rule in the FAQ tracks the article's "once in every third calendar year in which the distributable amount is greater than zero"; the "backstop / long-stop" mapping is made explicit in the FAQ; DC-14 is respected everywhere a payout is mentioned ("could be zero", "near zero for years", ranges with the stake beside them per DC-31); DC-23 is respected in home col2, brief, FAQ and press ("legal barriers, not a guarantee"); the tax question is now stated as contested; Article 3 is presented as a rebuttable presumption with the below-threshold route; funding and platform services are disclosed; the tooling's retention exception matches the About page's disclosure and the runner refuses Astra and refuses silent ZDR relaxation.

## Findings requiring correction

### 1. UNDERDISCLOSURE: the registration annex drops the age-18 condition

Articles, Article 10(1): "Every citizen of the Union who has attained the age of 18 years shall hold an entitlement under this Regulation."

Plain layer, campaign/REGISTRATION-TEXT.md §4: "Citizens of the Union would hold equal, personal and non-transferable entitlements to distributions as and when they are realised, carrying no right of individual cash redemption or sale, administered through national vehicles."

Reader harm: the registration annex is the one plain text that will sit on the Commission's register beside the signing form. Every other changed page (home col2, brief, FAQ, press) says "aged 18 or older"; the filed description does not. It matters for exactly the class the ECI rules single out: in the Member States that allow support from age 16, a 16- or 17-year-old signs a text describing an entitlement for "citizens of the Union" that the illustrated draft would not give them. That is a simplification that changes who would sign.

Minimal fix (plain layer, registration text; 3 484 of 5 000 characters used, so there is room): "Citizens of the Union aged 18 or older would hold equal, personal and non-transferable entitlements..."

### 2. TERM DRIFT: "median EU disposable income" for "median equivalised disposable income"

Articles, Article 1(2): "an amount of the order of six months of the median equivalised disposable income in the Union as published by the Commission (Eurostat)."

Plain layer, press.md: "The draft's capital objective is of the order of six months of median EU disposable income per citizen within a generation."

Reader harm: "equivalised" is the defined statistical base and it fixes the magnitude; the memorandum (objection 21) prices six months of it at about EUR 9 000. "Median EU disposable income" without the qualifier invites the household figure, which is materially larger, and the press page is the copy journalists lift verbatim. This is a defined term used with a different extension in the layer built for reuse; the same sentence in the FAQ avoids the number altogether and the memorandum carries the qualifier, so the press page is the outlier.

Minimal fix (plain layer, press.md): "six months of median equivalised disposable income in the EU (of the order of EUR 9 000 on the memorandum's figures) per citizen within a generation."

### 3. TERM DRIFT: contribute.md turns "not less raid-proof" into "strengthens"

Source rule, GOVERNANCE.md: "A change fails review by definition if it makes the instrument ... 3. less raid-proof (weakening entrenchment, adding emergency clauses, permitting sovereign self-dealing)".

Plain layer, contribute.md: "Every change to the legal text must survive four tests: ... it strengthens legal protection against diversion".

Reader harm: a prospective contributor reads that any change to the legal text must strengthen protection; a neutral drafting improvement to Article 3 would fail the test as stated. The page's own next sentence ("A pull request that weakens a protection does not merge") states the actual rule, so the page contradicts itself. Minor, but it is a changed page and the contradiction is in its first paragraph.

Minimal fix (plain layer, contribute.md): "it does not weaken legal protection against diversion".

### 4. TERM DRIFT within campaign guidance: paper collection

Plain layer, sign.md: "Official paper forms are also permitted; this campaign has not opened paper collection."

Campaign guidance, GATES.md (changed 6 September): "Hard constraints: all signatures live on the Commission's COCS (settled law since 2023)".

Reader harm: the two changed documents disagree on whether paper statements exist in law. Settled law since 2023 is that individual *online* systems are gone; paper remains. A volunteer reading GATES would tell a supporter without internet access that there is no route.

Minimal fix (GATES.md): "all online signatures live on the Commission's COCS (settled law since 2023); paper forms remain lawful and are a campaign choice".

## Optional, recorded not required

- Registration annex §4 still says "Undertakings above objective thresholds would be designated", without "presumptively" and without the rebuttal and below-threshold routes the FAQ and press now carry. Not a contradiction, but the FAQ correction has not been mirrored into the filed description.
- simulator.ts opens "Implements Annex II arithmetic as amended 19 August 2026: real-capital retention..." while the page strings say the model "simplifies the distribution arithmetic in Annex II" and "does not implement ... a separate real-capital retention calculation". The code is linked from the page as public; the header comment and the label disagree. Model unchanged, so a comment fix only.
- FAQ headings use "the fund" where the pages, articles and recital 21 say "Reserve" (and recital 21 distinguishes it from "a fund of the Union"); the mapping is clear from context.
- review.sh and the tools README still describe the draft as "unpublished legal text until it is filed"; it has been public since 19 August. Stale rationale, not a public-facing claim.

## Pre-existing defects in unchanged layers (for the six-gate legal revision, not this package)

- **Article 5(4)(e)** ("impose no obligation on the covered undertaking prior to a liquidity event other than the notification obligation in paragraph 6") contradicts Article 5(3) and 5(5), which impose subscription and procurement obligations on crystallisation before any liquidity event. The launch plan already lists this for counsel; the plain layer correctly describes 5(3), so the defect is in the article.
- **Memorandum §4 (EN and FR)** cites "Article 10(6) caps the fees national vehicles may levy"; the cap is Article 11(3). Article 10(6) is the distribution-frequency rule.
- **Memorandum §3.4** ("Both figures in the designation test are already in audited accounts") and **recital 7** ("an undertaking can establish its position from its own audited accounts alone") overstate: fair market value is derived under Annex I point 4 from a qualifying transaction, an independent valuation or market capitalisation, none of which is an audited-accounts line. The plain layer does not repeat this.
- **Memorandum §2.4** uses "the holding is passive", the word DC-41 advises the file to avoid; the recitals (23) use it too.
- **STRUCTURE.md** records "DC-26, the explicit scope-and-limits recital, is outstanding and not yet drafted", while recital 5 exists and its drafting note calls it the DC-26 recital; the memorandum also relies on recital 5. Stale index entry.

## Verdict

Findings 1 and 2 are contradictions between changed plain text and the enacting terms on who holds the entitlement and on the defined statistic that sizes the objective; both are one-line fixes in the plain layer, but they stand in the two documents most likely to be reproduced verbatim.

VERDICT: REVISE

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
