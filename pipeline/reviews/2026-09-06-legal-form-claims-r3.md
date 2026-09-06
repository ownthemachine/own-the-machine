---
gate: legal-form
target: campaign and website claim corrections
commit: ed351bc
verdict: REVISE
disposition: superseded-with-fixes
date: 2026-09-06
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T18:45:05+00:00 · tokens in=95002 out=4307
> Prompt: otm-legal-form-claims.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `79abe9e0d85cde31a96cd9f37fb82be212757b7a3549c54f24045886f85e0c3a`
> Prompt SHA-256: `632d8fae783776e43c4b4854c668d9227ed5acb062b613503e5a535c413348f4`

### Target Scope Review (Changed Explanatory Pages, Dictionaries, Guidance & Tooling)

The changed public explanatory copy, campaign documentation, simulator and reviewer tooling successfully remediate the overclaims identified in the 6 September 2026 review (incorporating the 7-year backstop and extraction triggers into public summaries, accurately reporting ECI rules and thresholds, clarifying the non-binding nature of ECI Forum advice, and establishing verifiable EU-routing checks for review tooling). 

However, three dictionary string contradictions remain in the changed interface files (`own-the-machine-site/src/i18n/en.mjs`):

---

#### Finding 1: Stale Recital Count in Law Index String
* **Verbatim quote (`own-the-machine-site/src/i18n/en.mjs`, `lawIndex.intro`):**
  > `'Harmonised rules for citizen participation in automated productivity gains (the Citizens’ Capital Regulation). The complete working draft: <a href="%RECITALS%">30 recitals</a>, 18 articles and two annexes, each paragraph anchored and citable.'`
* **Rule breached:** DRAFTING-RULES.md / Layer Fidelity & JPG Guideline 1: Descriptive metadata and cross-references in accompanying explanatory layers must accurately reflect the current structure of the normative text (`regulation/recitals.md` contains 36 recitals, numbered (1) through (36)).
* **Compliant redraft:**
  ```javascript
  intro: 'Harmonised rules for citizen participation in automated productivity gains (the Citizens’ Capital Regulation). The complete working draft: <a href="%RECITALS%">36 recitals</a>, 18 articles and two annexes, each paragraph anchored and citable. The English text is the draft. Current at commit %COMMIT%; every change is on the <a href="%LEDGER%">ledger</a>.',
  ```

---

#### Finding 2: Stale Objection Count in Objections Metadata String
* **Verbatim quote (`own-the-machine-site/src/i18n/en.mjs`, `objections.description`):**
  > `'Seventeen objections to the draft, published at full strength, each with its design consequences.'`
* **Rule breached:** DRAFTING-RULES.md / Layer Fidelity: Explanatory layer summaries must remain synchronized with the underlying memorandum (`regulation/memorandum/counter-arguments.md` contains 21 objections following the addition of objections 18–21).
* **Compliant redraft:**
  ```javascript
  description: 'Twenty-one objections to the draft, published at full strength, each with its design consequences.',
  ```

---

#### Finding 3: Stale Objection Count in Brief Navigation String
* **Verbatim quote (`own-the-machine-site/src/i18n/en.mjs`, `brief.readObjections`):**
  > `'All nineteen objections'`
* **Rule breached:** DRAFTING-RULES.md / Layer Fidelity: Navigation link descriptors must accurately reflect the referenced memorandum file (21 objections).
* **Compliant redraft:**
  ```javascript
  readObjections: 'All twenty-one objections',
  ```

---

### Pre-Existing Normative Issues (Unchanged Reference Context)

Reported separately pursuant to review instructions; not introduced by this package:
1. **Autonomous normative command in Annex I (JPG Guideline 22):** In `regulation/annexes/annex-1-counting.md`, point 3, second paragraph contains the mandatory command: *"Compensation paid under arrangements whose main purpose or effect is to raise the undertaking's compensation of labour without a corresponding supply of labour to the undertaking shall be disregarded."* Although Article 3(8) enacts the operative disregard power, Point 3 of the Annex retains normative imperative phrasing (`shall be disregarded`) rather than purely technical/descriptive calculation rules.

---

VERDICT: REVISE

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
