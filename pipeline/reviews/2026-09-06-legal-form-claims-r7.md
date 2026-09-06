---
gate: legal-form
target: campaign and website claim corrections
commit: ed351bc
verdict: PUBLISH
disposition: superseded-with-fixes
date: 2026-09-06
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T19:17:37+00:00 · tokens in=104129 out=2165
> Prompt: otm-legal-form-final.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `0e9bf98c7abe1e9101794d0f2a8e18b5ef7d8e097813e3a7d02f33653294d272`
> Prompt SHA-256: `ad366f89bfc751dcf3c5bf141092afcce6550c9756b51ed40d17b3a635555f6e`

### Review of Changed Explanatory Text, Registration Prose, Campaign Plan, and Tooling

#### 1. Scope and Registration Register Review
- **Registration Text (`campaign/REGISTRATION-TEXT.md`)**: Checked against Regulation (EU) 2019/788 Annex II character limits (without spaces). Title (79 chars / limit 100), Objectives (932 chars / limit 1 100), and Annex (3 484 chars / limit 5 000) strictly respect official character ceilings. The text correctly caveats the two-act architecture between Article 114 TFEU and Article 352 TFEU, accurately records that the illustrative draft cites Article 114 alone, clarifies that enforcement fines under Article 13(6) accrue to the general budget of the Union rather than the Reserve, notes the nominal value cash settlement for shares upon warrant exercise under Article 5(5), and avoids unhedged assertions regarding European labour-share decline.
- **Public Explanatory Copy (`brief.md`, `faq.md`, `press.md`, `about.md`, `sign.md`, `join.md`, `i18n/en.mjs`)**: The public-facing layers align with enacting terms in Chapter II (cumulative qualitative criteria and rebuttable presumption with Article 4 market investigations), Chapter III (crystallisation triggers including liquidity events, shareholder extraction above 25 %, and the 7-year backstop under Article 5(3)), and Chapter V (Article 10(6) distribution frequency ratio to execution costs with the three-year backstop for positive distributable income).
- **Campaign Guidance and Operating Plan (`campaign/GATES.md`, `campaign/DISTRIBUTION.md`, `campaign/REVIEW-AND-LAUNCH-PLAN-2026-09-06.md`)**: Threshold counts reflect the current post-2024 Parliament baseline (720 MEPs; Belgium at 15 840). Organising group requirements accurately distinguish seven EU citizens residing in seven different Member States from seven different nationalities. The plan documents volunteer and automation-first engineering without imposing unauthorised spending or altering constitutional merge tests.
- **Tooling and Retention Scope (`review.sh`, `README.md`, `.env.example`, `test_review.py`)**: Provenance verification confirms EU endpoint routing, explicitly scopes the Fable 5.1 30-day retention exception to public/intended-for-publication non-sensitive material with zero-training preserved, and correctly accounts for GPT-6 Astra profile readiness without falsely asserting execution.

---

### Pre-Existing Reference Items (Unchanged Context)
*Reported separately; not introduced by the current package:*
1. **Single Legal Basis Citation in Enacting Preamble (`regulation/recitals.md`)**: The draft preamble cites Article 114 TFEU alone. As documented in Section 2.1 of the Explanatory Memorandum and Layer 3 of the Severability Memorandum, Chapters IV to VI (Reserve creation, direct entitlement, and protection) require enactment via a separate Council Regulation under Article 352 TFEU if Article 114 is held not to encompass Union-level asset-holding bodies.
2. **Operational Interface in Article 5(4)(e)**: Article 5(4)(e) provides that the warrant imposes no pre-liquidity obligation other than notification under paragraph 6; this operates in structural tension with paragraph 3 crystallisations occurring prior to a liquidity event.

---

VERDICT: PUBLISH

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
