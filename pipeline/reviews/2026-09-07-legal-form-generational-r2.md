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
> 2026-09-06T22:34:18+00:00 · tokens in=114271 out=9565
> Prompt: legal-form.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `519a7601866ad0f2ad1b9b8508a19bbf53fc073107f9de861495e1fa69869b83`
> Prompt SHA-256: `9b8a265e21d0d5cfd192ec3dfb46da8b75ff7aea6f30d03236ec18749a0a2f7a`

### Gate 1 Review: Legal Form and EU Drafting Conventions

**Scope of Review:** Verification of candidate operative text under `regulation/` (`recitals.md`, `articles/01-18.md`, `annexes/annex-1-counting.md`, `annexes/annex-2-retention.md`) and evaluation of concrete choices under `proposals/2026-09-07-generational-repairs/` against the Joint Practical Guide (2nd ed. 2015), the Commission Legislative Drafting Rules, and `pipeline/DRAFTING-RULES.md`.

---

### Evaluation by Review Dimension

1. **STRUCTURE & CANONICAL ORDER**
   - **Order of components:** Title, citations, recitals, enacting terms (Chapters I through VIII, Articles 1 to 18), Annexes I and II follow canonical EU ordering strictly.
   - **Internal enacting terms sequence:** Subject matter and scope (Ch. I, Art. 1) $\rightarrow$ Definitions (Art. 2) $\rightarrow$ Designation and review (Ch. II, Arts. 3–4) $\rightarrow$ Rights and obligations (Ch. III–VI, Arts. 5–12) $\rightarrow$ Penalties, monitoring, delegation, and comitology (Ch. VII, Arts. 13–16) $\rightarrow$ Transitional and final provisions (Ch. VIII, Arts. 17–18). Articles are numbered continuously.
   - **Status of proposals:** Files under `proposals/2026-09-07-generational-repairs/` (`accounting-candidate.md`, `delivery-candidate.md`, `governance-candidate.md`) are properly sequestered as policy decision packages for the editor and are not incorporated into the operative enacting terms.

2. **RECITALS**
   - Numbered continuously (1) to (36); all recitals correctly use "should" rather than mandatory "shall".
   - Recitals contain no autonomous normative commands.
   - Core provisions map to motivating recitals in provision order.
   - Subsidiarity and proportionality recital (34) contains filled, case-specific reasoning.
   - Charter recital (35) explicitly cites Charter Articles 16, 17, 20, 34, and 47.
   - Recitals (18) and (19) provide an honest Charter Article 17 interference justification and Article 52(1) proportionality analysis on the BRRD model.
   - Recital (33) includes the formal EDPS consultation statement pursuant to Article 42(1) of Regulation (EU) 2018/1725.
   - *Defect identified:* Recital (10) contains a temporal discrepancy with Articles 17(3) and 18(2) regarding the cut-off date for pre-existing liquidity events (see Finding 1 below).

3. **ENACTING TERMS**
   - Enacting provisions consistently command in the present indicative "shall" (no "must", "will", or "should").
   - Direct applicability is preserved without generic "Member States shall ensure" formula, except for genuine Member State designations under Article 11(1) and reimbursements under Article 11(4).
   - Addressees are defined and passive constructions without legal agents are avoided.
   - Sentences observe the "one idea per sentence" discipline (JPG Guideline 1).

4. **DEFINITIONS (Article 2)**
   - All 14 definitions are centralized in Article 2 and employ standard exhaustive formula ("means").
   - Definitions do not contain autonomous substantive obligations (JPG Guideline 14).
   - Operative terms are used consistently throughout enacting terms.

5. **POWERS & DELEGATION (Articles 290/291 TFEU)**
   - Essential elements (warrant triggers, dilution cap of 3%, Reserve non-voting structure, citizen entitlement conditions, and shareholder dilution ceilings) remain strictly in the basic act.
   - Article 15 sets out the standard 6-paragraph "Exercise of the delegation" formula (CSDR Art. 67 pattern), covering empowerments in Article 3(9) and Article 8(8).
   - Article 16 establishes the standard examination procedure (comitology) under Regulation (EU) No 182/2011 for implementing acts under Article 6(1).
   - Recitals (31) and (32) incorporate standard 2016 Interinstitutional Agreement on Better Law-Making consultation language and comitology citations.

6. **DESIGNATION THRESHOLDS (DMA Article 3 Pattern)**
   - Article 3 strictly reproduces the validated DMA Article 3 architecture: cumulative qualitative criteria (paragraph 1), quantitative presumption thresholds (paragraph 2), 2-month self-notification deadline (paragraph 3), 45-working-day Commission designation decision (paragraph 4), cabined rebuttal excluding market definition (paragraph 5), below-threshold designation via market investigation (paragraph 6), anti-circumvention/anti-avoidance rule (paragraph 8), and periodic review at least every 3 years (Article 4(2)).

7. **CROSS-REFERENCES & ANNEXES**
   - All cross-references resolve within the instrument.
   - Annexes I and II are strictly technical/methodological counting and retention rules, containing no autonomous rights, duties, or penal sanctions (JPG Guideline 22).

8. **FINAL PROVISIONS**
   - Article 14 establishes standard 3-year evaluation and reporting machinery (DMA Art. 53 pattern) paired with the specific falsification reporting duty.
   - Article 17 provides transitional rules for pre-existing undertakings and listings.
   - Article 18 provides the standard 20th-day entry-into-force formula and a deferred 18-month general application date with an express carve-out for early preparatory administration.

9. **HOUSE STYLE**
   - No em-dashes (`—`) in the legislative text.
   - British English spelling maintained.

---

### Findings and Required Redrafts

#### Finding 1 (Recitals — Temporal alignment with enacting terms)
- **Verbatim quote:**
  `regulation/recitals.md`, Recital (10):
  > "For the same reason, an admission to trading which occurred before the entry into force of this Regulation should not constitute a liquidity event, and this Regulation should not apply to a liquidity event or other crystallising event completed before its entry into force."
- **Rule breached:** Joint Practical Guide (2nd ed. 2015), Guideline 10 (Recitals must accurately state the reasons for and reflect the provisions of the enacting terms). Article 17(3) and Article 18(2) specify that liquidity events completed before the *date of general application* (18 months after entry into force) do not give rise to an obligation under Article 5 or crystallise a warrant, whereas Recital (10) refers to "entry into force".
- **Compliant redraft:**
  > "For the same reason, an admission to trading which occurred before the entry into force of this Regulation should not constitute a liquidity event, and this Regulation should not apply to a liquidity event or other crystallising event completed before its date of general application."

---

VERDICT: REVISE

## Assistant disposition prepared for the final editor

Verbatim model output ends above. The exact reviewed working-tree snapshot
is identified by the bundle hash, not the later bookkeeping commit.
See [review status and dispositions](../../proposals/2026-09-07-generational-repairs/REVIEW-STATUS.md).
No institutional opinion or final editorial approval is implied.
