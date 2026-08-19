---
gate: legal-form
target: regulation/recitals.md + annexes (with enacting terms as context)
commit: e9b770a
verdict: REVISE
disposition: merged-with-fixes
date: 2026-08-19
---

# Review

> Reviewer: OpenRouter `google/gemini-3.7-flash` · 2026-08-18T23:02:37+00:00 · tokens in=11477 out=3643
> Prompt: prompts/legal-form.md · Verbatim model output below — do not edit.

### 1. Recitals — Missing EDPS Consultation Recital

* **Verbatim quote:**
  > "(27) The administration of entitlements involves the processing of personal data, limited to what the identification of holders and the execution of distributions require. Regulation (EU) 2016/679 applies to such processing."
* **Rule breached:**
  Check 2; Joint Practical Guide (JPG) Guideline 10; Regulation (EU) 2018/1725, Article 42(1). Where a legislative proposal provides for the processing of personal data, the mandatory standard recital recording consultation of the European Data Protection Supervisor (EDPS) must be included.
* **Compliant redraft:**
  > "(27) The administration of entitlements involves the processing of personal data, limited to what the identification of holders and the execution of distributions require. Regulation (EU) 2016/679 applies to such processing. The European Data Protection Supervisor was consulted in accordance with Article 42(1) of Regulation (EU) 2018/1725 of the European Parliament and of the Council and delivered an opinion on [date],"

---

### 2. Recitals — Fundamental Rights Recital Specification

* **Verbatim quote:**
  > "(29) This Regulation respects the fundamental rights and observes the principles recognised by the Charter of Fundamental Rights of the European Union, in particular the freedom to conduct a business, the right to property, equality before the law and the right to an effective remedy."
* **Rule breached:**
  Check 2; pipeline drafting rules. The Charter recital must explicitly identify the relevant Articles of the Charter of Fundamental Rights of the European Union, specifically Articles 16 (freedom to conduct a business), 17 (right to property), 34 (social security and social assistance) and 47 (right to an effective remedy and to a fair trial).
* **Compliant redraft:**
  > "(29) This Regulation respects the fundamental rights and observes the principles recognised by the Charter of Fundamental Rights of the European Union, in particular the freedom to conduct a business (Article 16), the right to property (Article 17), social security and social assistance (Article 34) and the right to an effective remedy and to a fair trial (Article 47)."

---

### 3. Enacting Terms / Final Provisions — Deferred Application Scope

* **Verbatim quote:**
  > "2. It shall apply from [OP: please insert the date 18 months after the date of entry into force of this Regulation], with the exception of Article 11(1), which shall apply from the date of entry into force."
* **Rule breached:**
  Check 8; JPG Guideline 20.3; pipeline drafting rules. Recital (30) and Article 17(1) require undertakings meeting the thresholds at entry into force to notify the Commission within two months of entry into force. Under Article 18(2), however, Article 3(3) and Article 17(1) are deferred for 18 months along with the rest of the Regulation, creating an internal legal contradiction.
* **Compliant redraft:**
  > "2. It shall apply from [OP: please insert the date 18 months after the date of entry into force of this Regulation], with the exception of Article 3(3), Article 11(1) and Article 17(1), which shall apply from the date of entry into force of this Regulation."

---

### 4. Annexes — Substantive Prohibitions and Normative Rules in Annexes

* **Verbatim quote (Annex I, Point 2):**
  > "Attribution the main purpose or one of the main effects of which is to reduce the turnover of the automated segment shall be disregarded."
* **Verbatim quote (Annex II, Point 4):**
  > "No amount shall be distributed which is financed by borrowing, by the disposal of holdings effected for the purpose of the distribution or by the retention shortfall of a future year."
* **Rule breached:**
  Check 7; JPG Guideline 22.1 and 22.2. Annexes must not contain autonomous normative commands, general anti-avoidance rules, or substantive prohibitions; such provisions belong in the enacting terms, while annexes are reserved for technical calculations, descriptions and methodologies.
* **Compliant redraft:**
  *Relocate substantive rules to the enacting terms (e.g. incorporate the anti-avoidance rule into Article 3(8) and the distribution leverage prohibition into Article 8 or Article 10), and redraft the annex points to state technical calculation rules purely in descriptive terms:*
  > **Annex I, Point 2 (second sentence):** "Where such goods or services are sold together with other goods or services for a single consideration, the consideration is attributed between them on a consistent and documented basis reflecting their relative stand-alone value."
  > *(Delete third sentence of Annex I, Point 2; rely on Article 3(8) for anti-avoidance).*
  > 
  > **Annex II, Point 4:** "For the purposes of the calculation under point 2, distributable amounts exclude financing through borrowing, disposal of holdings effected to fund distributions, or anticipation of future income." *(Insert the direct prohibition into Article 8(4) or Article 10(6)).*

---

VERDICT: REVISE


---

## Editor disposition (19 August 2026)

Four findings, all accepted, two with adjustments.

1. EDPS consultation recital: added to recital 27 with the [date]
   placeholder, Article 42(1) of Regulation (EU) 2018/1725.
2. Charter recital: article numbers added (Articles 16, 17, 20 and 47).
   The reviewer's proposed Article 34 (social security) is deliberately
   not cited: the entitlement is capital ownership, not social security,
   and citing Article 34 would concede the mischaracterisation the
   instrument is designed to resist. Recorded in the recital drafting
   notes.
3. Deferred-application contradiction: accepted in full. Article 18(2)
   now excepts Article 3(3), Article 11(1) and Article 17(1), which apply
   from entry into force.
4. Autonomous commands in annexes (JPG 22): accepted in full. The
   attribution anti-avoidance rule moved into Article 3(8); the
   leverage-funded-distribution prohibition moved into Article 8(4);
   both Annexes swept into descriptive voice so that all normative force
   flows from the referencing articles.
