# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T00:10:34+00:00 · tokens in=1993 out=2333
> Prompt: legal-form.md · Verbatim model output below — do not edit.

### Assessment of Citations & Chapter-Scoping (Specific Question)

Scoping Article 352 TFEU to specific chapters within the same citation block and splitting the enacting procedure within a single Regulation is **not legally defensible** under EU drafting conventions and CJEU constitutional case-law:

1. **Incompatible Procedures (*Titanium Dioxide*, C-300/89; *Parliament v Council*, C-130/10):** Under Joint Practical Guide (JPG) Guidelines 4.2 and 4.3, dual legal bases are permissible only where the procedures are compatible. Article 114 TFEU (ordinary legislative procedure, qualified majority voting, full co-decision) and Article 352 TFEU (special legislative procedure, Council unanimity, European Parliament consent only) are procedurally mutually exclusive. 
2. **Unity of the Enacting Instrument:** EU drafting rules do not permit "layered" or chapter-scoped citations that apply different voting rules and parliamentary prerogatives to different chapters of a single legislative act. 
3. **Correct Drafting Form:** Where the substantive components truly require separate legal bases with incompatible procedures, EU legislative technique mandates **splitting the proposal into two distinct legal acts** (e.g., a Regulation based on Article 114 TFEU for the internal market / warrant obligations, and a separate Regulation based on Article 352 TFEU establishing the Reserve and citizen entitlements).

---

### Findings

#### Finding 1: Incompatible Dual Legal Basis Scoped by Chapter
* **Verbatim quote:**
  > "Having regard to the Treaty on the Functioning of the European Union, and in particular Article 114 thereof and, as regards Chapters IV and V, Article 352 thereof,"
* **Rule breached:** Joint Practical Guide (JPG) Guideline 4.3 (Citation of legal bases with incompatible legislative procedures; Case C-300/89 *Commission v Council* [*Titanium Dioxide*]); Commission House Conventions on Citations. A single legislative act cannot combine Article 114 and Article 352 by chapter-scoping.
* **Compliant redraft:**
  *(If maintaining the measure strictly under Article 114 TFEU as a single act):*
  > "Having regard to the Treaty on the Functioning of the European Union, and in particular Article 114 thereof,"
  *(Alternatively, split into two separate proposals where Chapters IV and V form an independent instrument cited solely under Article 352 TFEU).*

---

#### Finding 2: Split / Incompatible Legislative Procedure in Enacting Formula
* **Verbatim quote:**
  > "Acting in accordance with the ordinary legislative procedure and, as regards the provisions based on Article 352 of the Treaty on the Functioning of the European Union, in accordance with the procedure laid down in that Article,"
* **Rule breached:** JPG Guideline 4.4 and Standard Enacting Formula Conventions. The procedural citation cannot be bifurcated across different provisions within a single Regulation.
* **Compliant redraft:**
  > "Acting in accordance with the ordinary legislative procedure,"

---

#### Finding 3: Missing Mandatory Recitals
* **Verbatim quote:**
  > *(Recitals (1) to (3) end without the mandatory standard recitals)*
* **Rule breached:** `pipeline/DRAFTING-RULES.md` (Recitals: mandatory Charter recital citing Articles 16, 17, 34, and 47; dedicated Article 17 interference and Article 52(1) proportionality recital; detailed case-specific Subsidiarity and Proportionality recital citing Article 5 TEU; EDPS consultation recital where data processing occurs).
* **Compliant redraft:**
  Insert the mandatory closing recitals following the substantive recitals:
  > "(4) Since the objectives of this Regulation cannot be sufficiently achieved by the Member States because of the cross-border scale and market fragmentation caused by divergent national participation and automation regimes, but can rather, by reason of the Union-wide scope of automated undertakings, be better achieved at Union level, the Union may adopt measures, in accordance with the principle of subsidiarity as set out in Article 5 of the Treaty on European Union. In accordance with the principle of proportionality as set out in that Article, this Regulation does not go beyond what is necessary in order to achieve those objectives.  
  (5) This Regulation respects the fundamental rights and observes the principles recognised in particular by the Charter of Fundamental Rights of the European Union, notably Articles 16, 17, 34 and 47 thereof. Any limitation on the right to property (Article 17) and the freedom to conduct a business (Article 16) is provided for by law, respects the essence of those rights and freedoms, and is strictly proportionate to the internal market and social cohesion objectives of general interest pursued by the Union in accordance with Article 52(1) of the Charter."

---

VERDICT: REVISE

## Editor disposition

1. **Finding 1, incompatible dual legal basis scoped by chapter. DECLINED.**
   The reviewer's own compliant redraft is to drop Article 352 or split the
   act in two. That is the substantive legal-basis choice the severability
   memorandum and explanatory memorandum section 2.1 already make and argue
   for at length; it is the memorandum's decision, not this citations-block
   task's, and this task does not restructure the act. Recorded as the
   standing legal-basis risk, not a wording defect in the citations block.
2. **Finding 2, split procedural line in the enacting formula. DECLINED.**
   The procedural bifurcation objected to here is the direct consequence of
   Finding 1: it exists because Article 352 governs Chapters IV and V under
   a different procedure. Declined for the same reason as Finding 1 and
   recorded alongside it.
3. **Finding 3, missing mandatory recitals (Charter, subsidiarity, EDPS).
   DECLINED as out of scope.** This task adds a citations block ahead of
   the existing recitals; it does not add, remove or renumber substantive
   recitals. Whether the recital sequence needs a Charter recital, a
   dedicated Article 5 TEU subsidiarity and proportionality recital, or an
   EDPS-consultation recital is a drafting decision for the recitals and
   memorandum, outside this gate's scope.

Residual: verdict stands at REVISE. No change was applied, so no second
round was run under the two-round cap.
