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
> 2026-09-06T18:53:01+00:00 · tokens in=95141 out=2880
> Prompt: otm-legal-form-claims.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `f93d00082b61e798519005e6dd56c81bbbb7e401e04466b22510d1c315bfee08`
> Prompt SHA-256: `632d8fae783776e43c4b4854c668d9227ed5acb062b613503e5a535c413348f4`

### 1. Scope and Review of Changed Materials

The package under review comprises updates to public explanatory copy (`brief.md`, `faq.md`, `join.md`, `sign.md`, `press.md`, `about.md`, `contribute.md`), English i18n dictionaries (`en.mjs`), registration texts (`REGISTRATION-TEXT.md`), campaign strategy and review plans (`DISTRIBUTION.md`, `REVIEW-AND-LAUNCH-PLAN-2026-09-06.md`), interactive simulator logic (`simulator.ts`), and review runner tooling (`review.sh`, `README.md`, `.env.example`, `tests/test_review.py`).

The texts were reviewed against the *Joint Practical Guide* (2nd ed. 2015), Commission house conventions, and `pipeline/DRAFTING-RULES.md`.

---

### 2. Form & Drafting Rule Assessment (in Proper Register)

1. **Structure & Registration Constraints:**
   - `campaign/REGISTRATION-TEXT.md` satisfies the format and character limits of Annex II to Regulation (EU) 2019/788:
     - Title: 79 characters (limit: 100).
     - Objectives: 932 characters without spaces (limit: 1 100).
     - Annex: 3 295 characters without spaces (limit: 5 000).
   - Clear institutional separation is maintained between the primary request (Layer 0 objectives) and the annexed illustrative draft Regulation.

2. **Substantive Alignment & Threshold Fidelity:**
   - Explanatory pages (`faq.md`, `brief.md`, `press.md`, `home` strings) accurately reflect the normative mechanics of the underlying Regulation:
     - **Designation Presumption:** Cumulative criteria mapped to Article 3(2) (EUR 7,5 billion Union turnover / EUR 75 billion valuation in ≥3 Member States; market value ≥80× worldwide labour compensation; 2-year durability) along with the Article 3(6) below-threshold investigation route.
     - **Warrant & Crystallisation:** 3 % non-voting equity warrant subscribed at nominal value; crystallisation upon the earlier of a liquidity event, shareholder extraction >25 % of covered turnover over three consecutive financial years, or the 7-year backstop (Articles 5(2), 5(3), 5(4)).
     - **Entitlement:** Personal, non-transferable, non-redeemable right vested in Union citizens aged 18+ by operation of law; payout contingent on realised income under the Norway-style retention rule (Articles 8(4), 10, Annex II).
     - **ECI Administrative Facts:** Minimum 1 million valid statements of support, threshold in ≥7 Member States, 7 EU citizens resident across 7 Member States; 12-month collection period; correct post-2024 European Parliament seat apportionment threshold for Belgium (15 840).

3. **House Style & Register:**
   - Prose adheres to British English spelling conventions (`harmonised`, `characterisation`, `prioritise`, `licence`).
   - Punctuation conforms to house style: em-dashes are absent across all changed files; en-dashes/hyphens are used appropriately for number ranges.

4. **Tooling & Provenance Integrity:**
   - `review.sh` and `README.md` correctly enforce EU geolocation and no-training constraints while providing a strictly scoped, documented switch for the 30-day retention exception on public Fable 5.1 runs without silently dropping other guarantees.

---

### 3. Pre-existing Normative Observations (Reference Context Only)

The following items concern the unchanged normative source text and are recorded separately for completeness:

1. **Annex I, Point 3 (Autonomous Prohibition):**
   - *Quote:* `"Compensation paid under arrangements whose main purpose or effect is to raise the undertaking's compensation of labour without a corresponding supply of labour to the undertaking shall be disregarded. Article 3(8) applies."`
   - *Rule:* JPG Guideline 22 (Annexes should contain technical/methodological rules and not independent normative prohibitions).
   - *Status:* Pre-existing. The command is cross-referenced to Article 3(8), where the substantive disregard power is established in the enacting terms.

---

VERDICT: PUBLISH

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
