# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T00:23:41+00:00 · tokens in=2101 out=2640
> Prompt: legal-form.md · Verbatim model output below — do not edit.

### 1. Structure: Missing Title and Enacting Formula

* **Verbatim quote:**
  > `THE EUROPEAN PARLIAMENT AND THE COUNCIL OF THE EUROPEAN UNION,`
  *(Preceding text lacks an act title; following text ends at Recital (3) without an enacting formula or enacting terms)*
* **Rule breached:** Joint Practical Guide (JPG) Guidelines 1, 2, and 12; pipeline/DRAFTING-RULES.md Item 1. An EU legislative act must follow the canonical sequence: Title, Preamble (Citations and Recitals), Enacting Formula (*"HAVE ADOPTED THIS REGULATION:"*), Enacting Terms (Articles), and Annexes. Explanatory memoranda must not replace or intermingle with enacting terms.
* **Compliant redraft:**
  ```text
  REGULATION (EU) 2026/... OF THE EUROPEAN PARLIAMENT AND OF THE COUNCIL
  of [date]
  on [subject matter]
  (Text with EEA relevance)

  THE EUROPEAN PARLIAMENT AND THE COUNCIL OF THE EUROPEAN UNION,
  [Citations and Recitals]
  HAVE ADOPTED THIS REGULATION:
  [Enacting Articles 1 to ...]
  ```

---

### 2. Recitals: Missing Mandatory Charter, Interference, and Proportionality Recitals

* **Verbatim quote:**
  > `(3) Where output is substantially decoupled from employment, the gains from automation accrue by default to a narrow base of shareholders... distribution of the ownership of automated production itself.`
  *(Recitals conclude at Recital (3))*
* **Rule breached:** pipeline/DRAFTING-RULES.md Item 2; JPG Guideline 10. Every draft act interfering with ownership/economic freedom must include:
  1. A case-specific Subsidiarity and Proportionality recital (Article 5 TEU and Protocol No 2);
  2. A Charter recital expressly citing Articles 16 (freedom to conduct a business), 17 (right to property), 34 (social security and social assistance), and 47 (effective remedy and fair trial);
  3. An Article 17 interference recital and Article 52(1) proportionality recital modelled on the BRRD precedent.
* **Compliant redraft:**
  ```text
  (4) In accordance with the principle of proportionality, it is necessary and appropriate for the achievement of the basic objective of ensuring the proper functioning of the internal market and preventing distortion of competition to lay down harmonised rules on the participation in automated production. This Regulation does not go beyond what is necessary in order to achieve the objectives pursued, in accordance with Article 5(4) of the Treaty on European Union.

  (5) This Regulation respects fundamental rights and observes the principles recognised in particular by the Charter of Fundamental Rights of the European Union, specifically Articles 16, 17, 34 and 47 thereof.

  (6) The obligations imposed under this Regulation affect the rights of shareholders under Article 17 of the Charter. In accordance with Article 52(1) of the Charter, any limitation on the exercise of the right to property must be provided for by law, respect the essence of that right and, subject to the principle of proportionality, be made only if it is necessary and genuinely meets objectives of general interest recognised by the Union. The warrant and participation requirements pursue the legitimate general interest of distributing productivity gains from automated production across the internal market, do not deprive owners of the substance of their investment, and are strictly proportionate to the objective pursued.
  ```

---

### 3. Citations: Missing Standard Committee Consultation and Procedure References

* **Verbatim quote:**
  > `Having regard to the opinion of the European Economic and Social Committee,`
  > `Acting in accordance with the ordinary legislative procedure,`
* **Rule breached:** JPG Guideline 7; Standard Commission Legislative Formatting. Acts based on Article 114 TFEU affecting general territorial and market conditions standardly cite the Committee of the Regions (or record its non-consultation where appropriate), and ordinary legislative procedure references require standard footnote apparatus in draft legislative acts.
* **Compliant redraft:**
  ```text
  Having regard to the opinion of the European Economic and Social Committee (1),
  Having regard to the opinion of the Committee of the Regions (2),
  Acting in accordance with the ordinary legislative procedure (3),
  ```

---

VERDICT: REVISE

## Editor disposition

1. **Finding 1, missing title and enacting formula. DECLINED as out of
   scope.** This task's round 1 and round 2 both concern the citations
   block alone (the "Having regard to" and "Acting in accordance with"
   lines); a title line before the preamble and the "HAVE ADOPTED THIS
   REGULATION:" formula after the recitals are whole-document structure,
   not the citations block, and are not touched by either round.
2. **Finding 2, missing mandatory recitals (Charter, subsidiarity, EDPS).
   DECLINED as out of scope.** Repeats round 1 finding 3, for the same
   reason: this task adds or amends the citations block only; it does not
   add, remove or renumber substantive recitals.
3. **Finding 3, missing Committee of the Regions citation and footnote
   apparatus. DECLINED.** This is the one finding that names the citations
   block itself, but applying it would assert something not established in
   the drafting record: no consultation of the Committee of the Regions is
   recorded anywhere in the memorandum or severability documents, and
   inventing the citation would misstate the file's own history rather than
   correct its form. The footnote-numbering apparatus the redraft proposes
   belongs to a text carrying Official Journal references, which nothing in
   regulation/recitals.md uses at present. Recorded as a further citations
   convention to weigh if and when the Committee of the Regions is in fact
   consulted, not applied now.

Residual: no finding from this round concerned the Article 114 or
procedure scoping question; both gates' original finding on that point is
resolved. Verdict stands at REVISE on findings unrelated to the citations
block's chapter-scoping, which this task does not address. One round only,
as instructed; no further round run.
