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
> 2026-09-06T19:15:51+00:00 · tokens in=102301 out=2831
> Prompt: otm-legal-form-final.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `ba1db5263d053af3924b13acbd2c128c2ed7419ca213e465bcb983743e4e48d3`
> Prompt SHA-256: `ad366f89bfc751dcf3c5bf141092afcce6550c9756b51ed40d17b3a635555f6e`

### 1. Scope & Register Assessment

The review scope covers the updated explanatory materials, dictionary strings (`own-the-machine-site/src/i18n/en.mjs`), registration texts (`campaign/REGISTRATION-TEXT.md`), campaign guidance, review plans, and tooling updates.

* **Explanatory & Campaign Register**: The public FAQ, Brief, Join, Press, and Distribution documents accurately translate the underlying legal mechanics into plain language without introducing normative obligations or contradicting enacting terms.
* **ECI Mechanics & Facts**: Requirements under Regulation (EU) 2019/788 are correctly stated across all modified pages (1 million valid statements; minimum thresholds in at least 7 Member States; 7 EU citizens resident in 7 different Member States regardless of nationality; Belgium threshold accurately set at 15,840; 12-month collection window; Central Online Collection System rules).
* **Warrant & Trigger Alignments**: All references to warrant crystallisation correctly incorporate the three alternative triggers under Article 5 (first liquidity event, shareholder extraction > 25 % of covered turnover over three consecutive financial years, or the seven-year long-stop).
* **Financial Flows & Budget Separation**: Accurately details that the Reserve pays nominal value upon share subscription in cash (Art. 5(5)), the undertaking pays independent valuation costs (Art. 6(3)), and penalties/fines accrue to the general budget of the Union rather than the Reserve (Art. 13(6)).
* **Distribution Mechanics**: Faithfully captures the dual conditions of Article 10(6) (10x average payment cost de minimis threshold, with a triennial mandatory distribution backstop whenever distributable income is positive).

---

### 2. House Style & Conventions Check

* **Punctuation & Typography**: No em-dashes are present in the modified text (en-dashes and hyphens are used strictly within conventional ranges and compound constructions).
* **Language**: British English spelling and terminology are consistently maintained across prose documents and UI strings (e.g. *programme*, *modelled*, *crystallise*).
* **Tooling & Privacy Guarantees**: Tooling scripts (`review.sh`, test fixtures, documentation) enforce explicit verification of EU geolocation, zero retention by default, no training use, and strictly cabined public-material exceptions.

---

### 3. Pre-existing Observations (Unchanged Legal Baseline)

The following items exist in the unchanged reference baseline and are recorded here as pre-existing:
1. **Article 18(2)**: Retains standard Publications Office placeholder `[OP: please insert the date 18 months after the date of entry into force of this Regulation]`.
2. **Recital (33)**: Retains EDPS opinion placeholder `[date]`.

---

VERDICT: PUBLISH

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
