---
gate: legal-form
target: generational repair candidate and separate proposals
commit: 7b33a2d
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T22:30:33+00:00 · tokens in=115975 out=11069
> Prompt: legal-form.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `86d6ab5e053a45b648aff790394ad584d0c62dd199d9828181b81bd465f3e373`
> Prompt SHA-256: `9b8a265e21d0d5cfd192ec3dfb46da8b75ff7aea6f30d03236ec18749a0a2f7a`

### Legal-Form Review

**Scope of Review:** Candidate operative text under `regulation/` (the candidate statute) and concrete alternative policy proposals under `proposals/2026-09-07-generational-repairs/`.

---

### I. Status Distinction: Candidate Operative Text vs Proposals

1. **Candidate Operative Text (`regulation/`):** Represents the candidate legal instrument submitted for formal gate review.
2. **Proposals (`proposals/2026-09-07-generational-repairs/`):** Non-adopted policy alternatives and specifications (`governance-candidate.md`, `delivery-candidate.md`, `accounting-candidate.md`) reserved for editorial decisions. They are not part of the candidate legal act.

---

### II. Findings and Required Redrafts

#### 1. Structure: Missing Enacting Formula and Recital Punctuation
* **Verbatim Quote (`regulation/recitals.md`, Recital 36):**
  > `Early designation decisions should become effective only at general application, with no capture of liquidity events already completed.`
* **Rule Breached:** Joint Practical Guide (2nd ed. 2015), Guideline 10 & Commission House Conventions (Section 9.2). The preamble must close with a comma on the final recital, followed immediately by the canonical enacting formula: `HAVE ADOPTED THIS REGULATION:`.
* **Compliant Redraft:**
  ```markdown
  (36) Application of the substantive obligations of this Regulation should
  be deferred so that undertakings, Member States and the Commission can
  prepare, while the notification obligation applies from entry into force
  so that the first designations can take effect at general application.
  Preparatory notifications, hearings and appointment arrangements should precede general application. Early designation decisions should become effective only at general application, with no capture of liquidity events already completed,

  HAVE ADOPTED THIS REGULATION:
  ```

---

#### 2. Enacting Terms: Verb Form in Anti-Subordination Provision
* **Verbatim Quote (`regulation/articles/05-warrant.md`, Article 5(10), second subparagraph):**
  > `To the extent that the preference, ranking or other advantage conferred by the issuance exceeds the new consideration provided, the first subparagraph applies to the excess.`
* **Rule Breached:** Joint Practical Guide, Guideline 12 ("shall" in enacting terms to lay down normative legal rules; present indicative without "shall" must be reserved for descriptive or definitional statements).
* **Compliant Redraft:**
  > `To the extent that the preference, ranking or other advantage conferred by the issuance exceeds the new consideration provided, the first subparagraph shall apply to the excess.`

---

#### 3. Enacting Terms: Verb Form in Transferee Obligations
* **Verbatim Quote (`regulation/articles/05-warrant.md`, Article 5(11), third subparagraph):**
  > `The obligations of a transferee under this paragraph arise irrespective of whether the transferee meets the conditions laid down in Article 3, and this paragraph applies to any onward transfer of the automated assets by a transferee as it applies to a transfer by a covered undertaking.`
* **Rule Breached:** Joint Practical Guide, Guideline 12 (mandatory use of "shall" for enacting obligations and operative rules).
* **Compliant Redraft:**
  > `The obligations of a transferee under this paragraph shall arise irrespective of whether the transferee meets the conditions laid down in Article 3, and this paragraph shall apply to any onward transfer of the automated assets by a transferee as it applies to a transfer by a covered undertaking.`

---

#### 4. Enacting Terms: Verb Form in Safeguards and Aggregate Dilution
* **Verbatim Quote (`regulation/articles/07-safeguards.md`, Article 7(2)):**
  > `Where warrants have been issued by transferees pursuant to Article 5(11), that percentage applies to the dilution borne, taken together, by the shareholders of the covered undertaking and of every such transferee.`
* **Rule Breached:** Joint Practical Guide, Guideline 12 (mandatory use of "shall" to express legal commands).
* **Compliant Redraft:**
  > `Where warrants have been issued by transferees pursuant to Article 5(11), that percentage shall apply to the dilution borne, taken together, by the shareholders of the covered undertaking and of every such transferee.`

---

### III. Assessment of the Proposals Package (`proposals/2026-09-07-generational-repairs/`)

If any proposal is promoted to the operative text, the following drafting conventions must be observed prior to integration:
1. **Governance Candidate (`governance-candidate.md`):** Institutional structures creating bodies with direct legal representation and administrative powers cannot be inserted simply as additional paragraphs of Article 8 without a formal institutional seat, financial regulation interface, and specific Article 291 TFEU conferrals.
2. **Delivery Candidate (`delivery-candidate.md`):** Proposed Article 3(10) (legal issuers) combines designation procedure with corporate-structuring liability. If integrated, it belongs in Chapter II (Article 3) with an explicit cross-reference to the execution obligations of Chapter III (Article 5).
3. **Accounting Candidate (`accounting-candidate.md`):** The replacement of Article 8(4) and restructuring of Annex II must maintain strictly non-normative drafting inside Annex II (rules and commands located in Article 8, technical calculation formulae in Annex II).

---

VERDICT: REVISE

## Assistant disposition prepared for the final editor

Verbatim model output ends above. The exact reviewed working-tree snapshot
is identified by the bundle hash, not the later bookkeeping commit.
See [review status and dispositions](../../proposals/2026-09-07-generational-repairs/REVIEW-STATUS.md).
No institutional opinion or final editorial approval is implied.
