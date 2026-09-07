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
> 2026-09-07T08:46:36+00:00 · tokens in=122452 out=11850
> Prompt: legal-form.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `477affbdae6fb6ebdacb50eefee20275f57628959bf8810991f4c923433859cb`
> Prompt SHA-256: `1457cdeb315e358e4820d682806ec61ad3d3b4702ea43ffe8118fe2b1f8ddef1`

### 1. Structure
The structural architecture follows the canonical sequence: title, citations, recitals, enacting terms (Chapters I–VIII, Articles 1 to 18 numbered continuously), and technical annexes (Annexes I and II).

---

### 2. Recitals

#### Finding 2.1: Premise of completed procedural steps in citations
- **Verbatim quote:**
  > "After transmission of the draft legislative act to the national parliaments,\n\nHaving regard to the consent of the European Parliament,"
- **Rule breached:** Joint Practical Guide (JPG) Guideline 9; Review Gate convention on distinguishing a review candidate from an adopted act (never invent completed Parliament consent or institutional transmission to make a formula look promulgated).
- **Compliant redraft:**
  ```text
  [After transmission of the draft legislative act to the national parliaments,]

  [Having regard to the consent of the European Parliament,]
  ```

#### Finding 2.2: Insufficient Article 17 Charter interference and Article 52(1) proportionality recitals
- **Verbatim quote:**
  > "(18) The warrant should serve broad citizen ownership through a limited economic participation. The interference with shareholders' property and business freedom should be accompanied by prospective attachment, retained voting control, a stated cap and independent judicially reviewable execution. Those safeguards should support the fair balance required by the Charter."
- **Rule breached:** `pipeline/DRAFTING-RULES.md` (Property rights section, BRRD recital 13 and 49 model); Prompt Rule 2 (mandatory honest Article 17 interference recital expressly naming Article 17 of the Charter plus a complete Article 52(1) Charter proportionality recital).
- **Compliant redraft:**
  ```text
  (18) This Regulation interferes with the right to property guaranteed by Article 17 of the Charter of Fundamental Rights of the European Union, as well as the freedom to conduct a business recognised by Article 16 thereof, by requiring the mandatory issuance of citizens' capital warrants and the resulting dilution of equity upon crystallisation. In accordance with Article 52(1) of the Charter, any limitation on the exercise of the rights and freedoms recognised by the Charter must be provided for by law and respect the essence of those rights and freedoms. Subject to the principle of proportionality, limitations may be made only if they are necessary and genuinely meet objectives of general interest recognised by the Union or the need to protect the rights and freedoms of others. The interference effected by this Regulation is provided for by law, respects the essence of the right to property by leaving operational control, operating cash flows and management intact, and is strictly confined to a quantified, non-controlling equity participation. It is justified by the objective of general interest in ensuring broad citizen participation in the capital value created by hyper-automated production across the internal market, and does not exceed what is necessary to achieve that objective.
  ```

#### Finding 2.3: EDPS consultation formula
- **Verbatim quote:**
  > "The European Data Protection Supervisor should be consulted under Article 42 of Regulation (EU) 2018/1725 during preparation of a Commission proposal."
- **Rule breached:** JPG Guideline 9; Regulation (EU) 2018/1725 Article 42(1) drafting convention for proposals with pending consultation.
- **Compliant redraft:**
  ```text
  The European Data Protection Supervisor was consulted in accordance with Article 42(1) of Regulation (EU) 2018/1725 of the European Parliament and of the Council and delivered an opinion on [OP: please insert date of opinion].
  ```

---

### 3. Enacting Terms

#### Finding 3.1: Passive commands without agents in Article 3(10)
- **Verbatim quote:**
  > "Outside minority interests shall be valued separately. Subsidiary equity already represented in a parent's equity shall not be counted again."
- **Rule breached:** JPG Guidelines 3.1 and 14; Prompt Rule 3 (every obligation must be placed on a defined addressee; avoid agentless passives).
- **Compliant redraft:**
  ```text
  The valuer shall value outside minority interests separately and shall not count subsidiary equity already represented in a parent's equity again.
  ```

#### Finding 3.2: List item syntax and multiple sentences in Article 5(4)(e)
- **Verbatim quote:**
  > "(e) confer no right to require subscription before the first liquidity event following designation or crystallisation under paragraph 3, whichever occurs first. This point shall not limit any issuance, notification, information, valuation or anti-avoidance obligation laid down in this Regulation."
- **Rule breached:** JPG Guideline 15 (structure of lists) and Guideline 4 (one idea per sentence; list items must grammatically complete the introductory stem).
- **Compliant redraft:**
  ```text
  (e) confer no right to require subscription before the first liquidity event following designation or crystallisation under paragraph 3, whichever occurs first, without prejudice to any issuance, notification, information, valuation or anti-avoidance obligation laid down in this Regulation.
  ```

#### Finding 3.3: Agentless declarative passives in Article 6(6)
- **Verbatim quote:**
  > "A sum of share numbers from different issuers shall not be a combined capital value. No interest shall enter the base twice."
- **Rule breached:** JPG Guidelines 3.1, 4, and 14 (imperative commands in enacting terms must have a defined operative addressee).
- **Compliant redraft:**
  ```text
  The valuer shall not treat a sum of share numbers from different issuers as a combined capital value and shall ensure that no interest enters the base twice.
  ```

---

### 4. Definitions
All definitions are situated in Article 2 (points 1 to 17). Operative definitions do not embed substantive duties, and terms are used consistently across chapters.

---

### 5. Powers and Delegations
- Essential elements (3 % warrant entitlement, trigger events, non-voting governance, asset protections) remain anchored in the primary articles.
- Delegated powers (Articles 3(9) and 8(8)) are governed by the six-paragraph standard delegation article (Article 15).
- Implementing powers (Articles 6(1) and 11(11)) correctly reference the examination procedure under Article 16 and Regulation (EU) No 182/2011.

---

### 6. Thresholds
The designation machinery in Articles 3 and 4 respects the DMA Article 3 pattern: qualitative limbs in paragraph 1, mapped quantitative presumptions in paragraph 2, self-notification within two months, 45-working-day designation deadline, cabined rebuttal excluding relevant-market definitions, below-threshold investigation route, and triennial periodic review.

---

### 7. Cross-References and Annexes
Annexes I and II provide technical calculation rules without creating autonomous obligations or rights.

---

### 8. Final Provisions and House Style
- Article 14 provides the triennial monitoring and evaluation formula with the falsification condition.
- Article 18 provides standard entry-into-force and staggered application periods.
- Text contains no em-dashes and adheres to standard British English conventions.

---

VERDICT: REVISE

## Assistant disposition for editorial review

The model output above is preserved verbatim. The bundle hash identifies
the exact source snapshot; the commit records the later integrated candidate.
See [closure review status](../../proposals/2026-09-07-substantive-closure/REVIEW-STATUS.md)
for accepted repairs, qualified findings and remaining decisions. No
institutional opinion, adoption or final editorial approval is implied.
