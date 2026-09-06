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
> 2026-09-06T19:13:27+00:00 · tokens in=96993 out=2412
> Prompt: otm-legal-form-final.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `6ab8200f577cdd0f5c8f686c5b967e44cc171fe01099d15a96e53d40cbdeea4e`
> Prompt SHA-256: `ad366f89bfc751dcf3c5bf141092afcce6550c9756b51ed40d17b3a635555f6e`

### Review of Changed Explanatory Prose, Registration Text, Campaign Guidance, and Tooling

#### 1. Structure and Register
- **Scope & Register Alignment**: The amended public explanatory pages (`brief.md`, `faq.md`, `join.md`, `sign.md`, `press.md`, `about.md`, `contribute.md`), dictionary strings (`en.mjs`), registration fields (`REGISTRATION-TEXT.md`), campaign operating plan, and tooling configurations operate in their proper explanatory/administrative register without purporting to enact normative rules.
- **Registration Form Conformance**: `campaign/REGISTRATION-TEXT.md` satisfies the character limits without spaces required by Annex II to Regulation (EU) 2019/788:
  - Title: 79 characters (limit 100).
  - Objectives: 926 characters without spaces (limit 1,100).
  - Annex: 3,484 characters without spaces (limit 5,000).
- **Two-Act / Severability Transparency**: Objectives and Treaty provisions accurately distinguish between internal-market harmonisation (Article 114 TFEU) and residual Union-body creation/entitlement matters (Article 352 TFEU), noting the requirement of Council unanimity and Parliament consent for the latter.

#### 2. Substantive Alignment with Enacting Terms
- **Presumption vs Investigation**: Explanatory summaries across `brief.md`, `faq.md`, `press.md`, and `en.mjs` reflect Article 3's DMA-aligned architecture (rebuttable quantitative presumption based on turnover/FMV and labour compensation ratio, alongside the below-threshold market-investigation route).
- **Crystallisation Triggers**: Public copy across all files consistently reflects the three Article 5 triggers: first liquidity event, shareholder extraction exceeding 25 % of covered turnover over three consecutive financial years, and the seven-year backstop from warrant issuance.
- **Settlement & Budgets**: Correctly states that the warrant settles strictly in equity (non-voting shares subscribed at nominal value paid in cash by the Reserve), that Reserve assets/distributions remain strictly outside public budgets, and that penalties under Article 13 accrue to the general budget of the Union.
- **Distribution Frequency**: Correctly describes Article 10(6)'s condition (payment declared when per-holder amount equals at least ten times the average execution charge, backstopped by a mandatory distribution at least once in every three calendar years with positive distributable income).
- **ECI Administrative Facts**: Thresholds, signing age nuances (distinguishing national signing age from the proposed 18-year fund eligibility), collection timelines (12 months starting within 6 months of registration), and current country quotas (Belgium at 15,840 under the 720-MEP allocation) match official Commission guidance.

#### 3. House Style and Conventions
- **Punctuation & Spelling**: British English spelling is used consistently across English prose (`harmonised`, `characterisation`, `programme`). No em-dashes (`—`) appear in the changed prose; parenthetical clauses, colons, or spaced hyphens are used.
- **Tooling & Provenance**: `review.sh`, `tools/README.md`, and `test_review.py` maintain strict verification of EU routing and no-training commitments, properly isolating the explicit public-material 30-day retention exception for Fable 5.1 without claiming unverified models.

---

### Separate Pre-Existing Normative Issues (Reference Context Only)
*(Unchanged legal text; not introduced by this package)*
1. **Article 5(4)(e) vs Article 5(3)**: Article 5(4)(e) states that the warrant shall *"impose no obligation on the covered undertaking prior to a liquidity event other than the notification obligation in paragraph 6"*, which stands in tension with Article 5(3) crystallisation upon shareholder extraction or the seven-year long-stop occurring prior to a liquidity event.
2. **Article 3(8) Anti-Avoidance Boundary**: The anti-avoidance provision disregards transactions increasing labour compensation; as identified in the review plan, future legal revision should provide guidance distinguishing genuine operational hiring from avoidance schemes.

---

VERDICT: PUBLISH

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
