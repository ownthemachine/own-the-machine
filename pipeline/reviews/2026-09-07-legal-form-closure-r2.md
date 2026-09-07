---
gate: legal-form
target: proposals/2026-09-07-substantive-closure/candidate
commit: 0338506
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T08:41:59+00:00 · tokens in=122464 out=8459
> Prompt: legal-form.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `8b36117626703366cb9ecd59625e6e55c0e4c5ccf90bacf721073a582ee91855`
> Prompt SHA-256: `9b8a265e21d0d5cfd192ec3dfb46da8b75ff7aea6f30d03236ec18749a0a2f7a`

### Review Findings: Legal Drafting Form

#### Finding 1: Canonical Structure — Missing Formal Act Title
* **Verbatim quote:**
  ```markdown
  # Recitals

  THE COUNCIL OF THE EUROPEAN UNION,

  Having regard to the Treaty on the Functioning of the European Union, and in particular Article 352 thereof,
  ```
* **Rule breached:** Joint Practical Guide (2nd ed. 2015), Guidelines 1, 2, and 3; Commission Legislative Drafting Conventions. Every Union legislative act must commence with its formal title setting out the type of act, the adopting institution, and the subject matter in concise terms before the citations and recitals.
* **Compliant redraft:**
  ```markdown
  # COUNCIL REGULATION (EU) 2026/...

  of [date]

  on a common mechanism ensuring citizen participation in the capital value of hyper-automated undertakings in the internal market

  THE COUNCIL OF THE EUROPEAN UNION,

  Having regard to the Treaty on the Functioning of the European Union, and in particular Article 352 thereof,
  ```

---

#### Finding 2: Recitals — Floating Unnumbered Paragraph in Recital (31)
* **Verbatim quote:**
  ```markdown
  (31) In order to keep the methodologies for counting turnover, employment
  and value, and for calculating the retention necessary to preserve the
  real capital of the Reserve, aligned with technological and market
  developments, the power to adopt acts in accordance with Article 290 of
  the Treaty on the Functioning of the European Union should be delegated to
  the Commission in respect of amendments to Annexes I and II. The essential
  elements of this Regulation, including the designation criteria, the
  percentage and terms of the warrant, the entitlement and its protections,
  are laid down in the enacting terms and are not subject to delegation. It
  is of particular importance that the Commission carry out appropriate
  consultations during its preparatory work, including at expert level, and
  that those consultations be conducted in accordance with the principles
  laid down in the Interinstitutional Agreement of 13 April 2016 on Better
  Law-Making. In particular, to ensure equal participation in the
  preparation of delegated acts, the European Parliament and the Council
  receive all documents at the same time as Member States' experts, and
  their experts systematically have access to meetings of Commission expert
  groups dealing with the preparation of delegated acts.

  Essential allocation priorities, immediate loss recognition, the numerical
  collar, entitlement periods and payment backstops should remain outside
  that delegation.
  ```
* **Rule breached:** Joint Practical Guide, Guideline 10.1; `pipeline/DRAFTING-RULES.md` ("Recitals"). Every recital must consist of a single continuous paragraph identified by a unique sequential number in parentheses. An unnumbered standalone paragraph breaks the structural hierarchy.
* **Compliant redraft:**
  ```markdown
  (31) In order to keep the methodologies for counting turnover, employment
  and value, and for calculating the retention necessary to preserve the
  real capital of the Reserve, aligned with technological and market
  developments, the power to adopt acts in accordance with Article 290 of
  the Treaty on the Functioning of the European Union should be delegated to
  the Commission in respect of amendments to Annexes I and II. The essential
  elements of this Regulation, including the designation criteria, the
  percentage and terms of the warrant, the essential allocation priorities,
  immediate loss recognition, the numerical collar, entitlement periods,
  payment backstops, and the entitlement and its protections, are laid down
  in the enacting terms and are not subject to delegation. It is of
  particular importance that the Commission carry out appropriate
  consultations during its preparatory work, including at expert level, and
  that those consultations be conducted in accordance with the principles
  laid down in the Interinstitutional Agreement of 13 April 2016 on Better
  Law-Making. In particular, to ensure equal participation in the
  preparation of delegated acts, the European Parliament and the Council
  receive all documents at the same time as Member States' experts, and
  their experts systematically have access to meetings of Commission expert
  groups dealing with the preparation of delegated acts.
  ```

---

#### Finding 3: Enacting Terms — Argumentative/Non-Normative Prose in Article 5(6)
* **Verbatim quote:**
  ```markdown
  Ordinary exchange transactions shall count; this Regulation does not promise listed issuers a dormant period until the seven-year trigger.
  ```
* **Rule breached:** Joint Practical Guide, Guidelines 1.1 and 10; `pipeline/DRAFTING-RULES.md` ("Enacting Terms"). The enacting terms must be strictly normative, clear, and impersonal. Polemical statements, argumentative explanations, and colloquial disclaimers ("this Regulation does not promise...") are non-normative content prohibited within operative articles.
* **Compliant redraft:**
  ```markdown
  Ordinary exchange transactions shall count towards that threshold.
  ```

---

#### Finding 4: Definitions — Punctuation in List of Definitions (Article 2)
* **Verbatim quote:**
  ```markdown
  (14) 'automated assets' means the software systems referred to in point (3),
  the model parameters, training and inference infrastructure, data sets and
  intellectual property rights on which the provision of the goods or services
  referred to in Article 3(1)(a) principally depends.

  (15) 'legal issuer' means a legal person identified in a designation or
  transfer decision as responsible for the warrant and subscription;
  ```
* **Rule breached:** Joint Practical Guide, Guideline 15; Commission House Conventions. In a multipart definition article structured as a numbered list, all points prior to the final point must terminate with a semicolon. Point (14) incorrectly terminates with a period.
* **Compliant redraft:**
  ```markdown
  (14) 'automated assets' means the software systems referred to in point (3),
  the model parameters, training and inference infrastructure, data sets and
  intellectual property rights on which the provision of the goods or services
  referred to in Article 3(1)(a) principally depends;
  ```

---

#### Finding 5: Recitals Order — Placement of Rationale for Information Gathering Powers
* **Verbatim quote:**
  ```markdown
  (29) Information requirements and penalties should be necessary and proportionate, with specified addressees, reasons, confidentiality and effective review. Reasonable access to transfer records should be distinguished from knowledge of every anonymous trade. Ordinary trading should count towards the transfer trigger, with a defined daily valuation time, rather than be portrayed as a guaranteed dormant period for listed undertakings.
  ```
* **Rule breached:** Joint Practical Guide, Guideline 10.2 ("Recitals should be arranged in a logical order corresponding to the enacting terms"). The motivating recitals for the Article 4(5)–(6) investigatory/information powers are conflated into Recital (29) alongside Article 13 penalties, out of sequence with the Chapter II enacting terms.
* **Compliant redraft:**
  Split Recital (29) and insert the supervisory information-gathering recital directly following Recital (8) (motivating Chapter II):
  ```markdown
  (8a) In order to ensure effective supervision and verification of designation criteria and crystallisation conditions, the Commission should be empowered to request necessary records by reasoned decision, while ensuring full protection of legal professional privilege and confidential information. Legal issuers should maintain accessible records without being held liable for market transactions not reasonably discoverable.
  ```

---

VERDICT: REVISE

## Assistant disposition for editorial review

The model output above is preserved verbatim. The bundle hash identifies
the exact source snapshot; the commit records the later integrated candidate.
See [closure review status](../../proposals/2026-09-07-substantive-closure/REVIEW-STATUS.md)
for accepted repairs, qualified findings and remaining decisions. No
institutional opinion, adoption or final editorial approval is implied.
