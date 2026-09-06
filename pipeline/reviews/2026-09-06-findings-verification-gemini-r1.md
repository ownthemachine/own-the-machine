---
gate: findings-verification
target: regulation
commit: 0aeaada
verdict: REVISE
disposition: assessed-repairs-pending
date: 2026-09-06
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T21:40:34+00:00 · tokens in=78580 out=11109
> Prompt: findings-verification.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `02d22ea9ae2cd26b50ad50b3375bbe4c1d0a97501d8229cd209f9a78fb0357ac`
> Prompt SHA-256: `27fb4afcbfe3fbbf1404d8b046adb0a19d8e31cb1b89b59ed571569e1fbf6633`

# Independent Legal Diagnostic Audit: Citizens' Capital Regulation Draft

**Baseline:** `0aeaada` (operative text unchanged)  
**Context:** Independent verification of outstanding diagnostic legal findings across the draft Regulation, recitals, annexes, explanatory memoranda (EN/FR), and architectural constraints.

---

## 1. Article 5(4)(e) and Operational Conflicts

### 1.1 Scope and Classification
- **Classification:** CONFIRMED (Narrow Drafting Conflict).

### 1.2 Paired Operative References and Quotations
- **Article 5(4)(e):**
  > "The citizens' capital warrant shall: … (e) impose no obligation on the covered undertaking prior to a liquidity event other than the notification obligation in paragraph 6."
- **Article 5(1):**
  > "Within three months of its designation, a covered undertaking shall issue to the Reserve a citizens' capital warrant."
- **Article 5(3):**
  > "The citizens' capital warrant shall also crystallise, and shall be exercisable on the same terms, where either of the following occurs before a liquidity event: (a) shareholder extraction … (b) seven years have elapsed since the issuance of the warrant."
- **Article 5(5):**
  > "The right to the subscription … shall vest by operation of law … on the date of crystallisation under paragraph 3. … The covered undertaking shall execute the subscription within 20 working days of the delivery of the valuation referred to in Article 6…"

### 1.3 Strongest Defensible Reading and Assessment
- **Defense:** Article 5(4) defines the terms and covenants inherent to the *financial instrument itself* ("The citizens' capital warrant shall: …"), distinguishing instrument-level covenants from autonomous statutory duties imposed directly on the undertaking by the Regulation (e.g., the duty to issue under 5(1) and the duty to execute under 5(5)). Under this reading, 5(4)(e) merely guarantees that holding the warrant confers no collateral corporate governance or reporting burdens before an event.
- **Why it Fails:** The text of Article 5(4)(e) explicitly carves out a statutory duty ("other than the notification obligation in paragraph 6"), thereby conflating instrument terms with statutory obligations. More critically, Article 5(3) creates crystallisation triggers occurring *prior to a liquidity event* (extraction or 7-year passage). Upon a paragraph 3 crystallisation, paragraph 5 mandates valuation and subscription execution. Article 5(4)(e) states that *prior to a liquidity event*, no obligation exists other than paragraph 6 notification. If extraction occurs without a liquidity event, a defending undertaking can plead that 5(4)(e) shields it from executing the subscription prior to an actual liquidity event.

### 1.4 Surviving Issue and Concrete Consequence
- The conflict does not invalidate the statutory scheme, but it creates a textual defense against non-liquidity crystallisation under Article 5(3). An undertaking resisting an extraction or 7-year long-stop crystallisation could plead Article 5(4)(e) to stall execution before national courts.
- Additionally, Article 5(6) mandates notification only for an "impending liquidity event," leaving crystallisation under paragraph 3 without an express reporting or notification procedure.

### 1.5 Minimal Repair Direction
- Amend Article 5(4)(e) to reference crystallisation generally:
  > "(e) impose no obligation on the covered undertaking prior to crystallisation pursuant to paragraph 2 or paragraph 3 other than the notification obligations laid down in this Regulation."
- Amend Article 5(6) to include a notification requirement within 30 working days following the close of any financial year in which extraction exceeds the threshold in Article 5(3)(a).
- *Policy/Safeguards Affected:* Preserves the dormant nature of the warrant while eliminating a legal loophole against non-liquidity crystallisation (DC-3, DC-12, DC-35).

### 1.6 Validation Scenario and Review Class
- **Validation Scenario:** An unlisted covered undertaking reaches year 7 without a liquidity event or dividend extraction. Upon crystallisation, the Reserve demands valuation and share subscription. The undertaking challenges the demand, citing Article 5(4)(e). The amended text must cleanly extinguish this defense.
- **Review Class:** Substantive drafting change (Gates 1, 4, 5, 6 + Editor).

---

## 2. Article 3(8) Anti-Avoidance vs. Genuine Remuneration and Recital 7

### 2.1 Scope and Classification
- **Classification:** CONFIRMED (Overbroad Enacting Command).

### 2.2 Paired Operative References and Quotations
- **Article 3(8), second sentence:**
  > "The Commission shall disregard any such arrangement when applying this Regulation, and shall likewise disregard any transaction, arrangement or attribution the main purpose or one of the main effects of which is to increase the compensation of labour, or to reduce the fair market value, referred to in point (b) of paragraph 2."
- **Recital 7:**
  > "Compensation of labour is the appropriate measure of the labour actually engaged, because it is recorded in audited accounts and cannot be increased without genuine payment for genuine work, so that an undertaking reduces its decoupling ratio only by remunerating labour, which is consistent with the objectives of this Regulation."
- **Annex I, Point 3, second paragraph:**
  > "Compensation paid under arrangements whose main purpose or effect is to raise the undertaking's compensation of labour without a corresponding supply of labour to the undertaking shall be disregarded. Article 3(8) applies."

### 2.3 Strongest Defensible Reading and Assessment
- **Defense:** The second sentence of Article 3(8) uses "likewise disregard," linking it contextually to the first sentence's anti-avoidance rule ("to avoid meeting the thresholds"). Recital 7 and Annex I point 3 confirm the legislative intent: only artificial compensation lacking an underlying supply of productive labour is targeted.
- **Why it Fails:** In Union law drafting (Joint Practical Guide Guideline 10; Case C-162/97 *Nilsson*), recitals and annexes cannot alter, restrict, or cure an unambiguous operative command in an article. Article 3(8) enacts a disjunctive objective effects test ("the main purpose or **one of the main effects** of which is to increase the compensation of labour"). Any substantial genuine hiring campaign, wage increase, or employee profit-sharing plan has as one of its main direct economic effects an increase in compensation of labour. Under the strict text of Article 3(8), the Commission would be legally mandated to disregard genuine wage expansion. Ambiguity penalises the regulator under restrictive interpretation rules (Case C-6/98 *ARD*).

### 2.4 Surviving Issue and Concrete Consequence
- Legal uncertainty for covered and borderline undertakings. An undertaking choosing to expand human employment or raise wages to reduce its decoupling ratio cannot be certain whether the Commission will disregard that payroll expansion as an avoidance effect.

### 2.5 Minimal Repair Direction
- Align the enacting text of Article 3(8), second sentence, with the substance requirement in Annex I, Point 3:
  > "…and shall likewise disregard any transaction, arrangement or attribution the main purpose or one of the main effects of which is to increase the compensation of labour without a corresponding genuine supply of labour to the undertaking, or artificially to reduce the fair market value, referred to in point (b) of paragraph 2."
- *Policy/Safeguards Affected:* Safeguards the core policy premise of the ratio (that direct employment and worker compensation are legitimate routes to avoid or exit designation).

### 2.6 Validation Scenario and Review Class
- **Validation Scenario:** A frontier software firm with a ratio of 95× hires 1,000 internal system engineers, raising its audited payroll and reducing its ratio to 70×. A competitor or regulator argues that because "one of the main effects" was to fall below 80×, the hiring must be disregarded under Article 3(8). The amended wording must protect genuine employment.
- **Review Class:** Substantive drafting change (Gates 1, 2, 4, 6 + Editor).

---

## 3. Articles 8–9 Governance Architecture and Attribution of Authority

### 3.1 Scope and Classification
- **Classification:** CONFIRMED (Essential Structural Omission / Incomplete Body Architecture).

### 3.2 Paired Operative References and Quotations
- **Article 8(1), (4), (6):**
  > "1. The European Citizens' Capital Reserve is established. The Reserve shall have legal personality… 4. The Reserve shall retain from its realised income… 6. The Reserve shall publish annually audited accounts, the valuation of its holdings and the calculation referred to in paragraph 4."
- **Article 5(5), fifth sentence:**
  > "…and the Reserve shall pay up the shares in full in cash at their nominal value upon execution."
- **Article 9(1)(e):**
  > "[The Reserve shall not:] borrow, save for temporary liquidity purposes not exceeding 2 % of the value of its assets and save for the payment of subscription amounts under Article 5(5)…"
- **Article 10(6):**
  > "The Reserve shall declare a distribution in each calendar year in which the distributable amount would provide each holder with not less than ten times the average cost of executing one payment…"
- **Article 15(2) & Article 16(1):**
  > Article 15 restricts delegated acts strictly to Annex I (3(9)) and Annex II (8(8)). Article 16 restricts committee procedure strictly to independent valuers under Article 6(1).

### 3.3 Strongest Defensible Reading and Assessment
- **Defense:** The Reserve is conceived as a fully automated, passive statutory asset pool whose functions are strictly ministerial and non-discretionary (calculating retention under Annex II arithmetic, accepting shares, transferring distributable amounts to national vehicles). Detailed internal management rules can be adopted by the Commission or by Member States under general administrative law principles or subsidiary regulations.
- **Why it Fails:** Under Union constitutional law (Articles 290 and 291 TFEU; *Meroni* v High Authority, Case 9/56; *ESMA*, Case C-270/12), conferring legal personality, asset ownership, market borrowing power, cash settlement obligations, distribution declarations, financial accounting, and legal standing in litigation requires an identifiable statutory organ, an executive head or management board, a system of appointment, a seat, and accountability mechanisms. 
- Delegated powers under Article 290 TFEU *cannot* establish essential governance elements post-enactment, and even if they could, Article 15 provides no delegation empowerment for governance. Implementing powers under Article 291 TFEU are similarly unempowered for Reserve administration.
- The Reserve cannot execute a cash payment at nominal value (Art. 5(5)), enter a credit agreement (Art. 9(1)(e)), engage an independent auditor (Art. 8(6)), or defend a lawsuit under Article 12(4) without an individual or board holding legal capacity and attributable signatory authority under Union law.

### 3.4 Surviving Issue and Concrete Consequence
- In its present form, the Reserve is a legal entity without organs or legal representation. The regulation would fail institutional scrutiny by the Council/Parliament Legal Services and the European Court of Auditors on grounds of missing governance and unassignable legal liability.
- *Distinction:* This is not a requirement for salaried campaign teams or political staff; it is the constitutional requirement that a legal person created by Union statute have an attributable executive organ and legal seat.

### 3.5 Minimal Repair Direction
- **Political/Governance Choices to Flag:**
  1. *Option A (Direct Decentralised Agency Model):* Insert Article 8a establishing a Management Board (e.g., representatives appointed by the Parliament, Council, and Commission, plus non-voting independent experts) and an Executive Director appointed for a non-renewable term, responsible solely for ministerial execution of Annex II, portfolio custody, auditing, and contracting.
  2. *Option B (Entrusted Institutional Rail Model):* Enact that the administrative, treasury, and accounting tasks of the Reserve be entrusted to an established Union institution (e.g., the European Investment Bank (EIB) or the European Stability Mechanism (ESM) under a segregated statutory mandate), acting as trustee without discretion.
- *Policy/Safeguards Affected:* Safeguards the passive, non-political character of the Reserve (DC-3, DC-13, DC-32) while supplying indispensable legal attribution.

### 3.6 Validation Scenario and Review Class
- **Validation Scenario:** A covered undertaking tenders share certificates and demands nominal cash payment pursuant to Article 5(5). The transaction requires banking execution, counterparty verification, and entry into national shareholder registers. The statutory text must clearly designate who signs and authorises the transaction.
- **Review Class:** Essential Governance Choice / Substantive Legislative Addition (Full Pipeline + Public Consultation).

---

## 4. Article 13 Penalty Coverage and Enforcement Gaps

### 4.1 Scope and Classification
- **Classification:** CONFIRMED (Specific Administrative Enforcement Gap).

### 4.2 Paired Operative References and Quotations
- **Article 13(1):**
  > "1. The Commission may by decision impose on a covered undertaking fines not exceeding 10 % of its total worldwide turnover … where it finds that the undertaking, intentionally or negligently:
  > (a) fails to issue the citizens' capital warrant in accordance with Article 5(1);
  > (b) fails to take the measures required by the third sentence of Article 5(5);
  > (c) fails to notify a liquidity event in accordance with Article 5(6);
  > (d) supplies incorrect, incomplete or misleading information under Article 3(3) or Article 4;
  > (e) circumvents Article 3(8), or fails to comply with a decision adopted pursuant to that paragraph."
- **Article 5(5), third vs. fifth sentence:**
  > *Third sentence:* "Where the law governing the covered undertaking does not give effect to the first sentence, the covered undertaking shall take all measures necessary to procure a subscription of equivalent effect no later than the completion of the liquidity event or, in the case of crystallisation under paragraph 3, no later than three months after the date of crystallisation."
  > *Fifth sentence:* "The covered undertaking shall execute the subscription within 20 working days of the delivery of the valuation referred to in Article 6, and the Reserve shall pay up the shares in full in cash at their nominal value upon execution."
- **Article 5(11), first paragraph:**
  > "…the transferee shall issue to the Reserve a citizens' capital warrant in accordance with paragraph 1 as if it were a covered undertaking…"

### 4.3 Strongest Defensible Reading and Assessment
- **Defense:** For Union-law undertakings, Article 5(5) sentence 1 operates *by operation of law* (ex lege vesting). Execution under sentence 5 is a mechanical corporate formality enforceable directly before national company registries or courts under civil remedies. Administrative fines under 13(1)(b) were intentionally restricted to third-country law undertakings (sentence 3) because foreign law cannot be overridden by Union operation of law. Furthermore, transferees under Article 5(11) are deemed bound "as if it were a covered undertaking," pulling them into Article 13(1).
- **Why it Fails (in part):** While civil remedies and national court actions exist, punitive administrative fines under Article 13(1) are subject to strict construction under the principle of legality (*nulla poena sine lege* / Charter Article 49). 
  1. An EU undertaking that issues the warrant under 5(1) but subsequently refuses to execute the subscription under sentence 5 of 5(5) (e.g., refusing to register the Reserve in the share register) does not violate 13(1)(a) (warrant was issued) or 13(1)(b) (which cross-references only sentence 3). The Commission cannot levy administrative fines under 13(1) or daily periodic penalty payments under 13(2) for this refusal.
  2. Transferees under Article 5(11) are not designated "covered undertakings" under Article 2(2). Even if deemed to issue under 5(1), non-compliance by transferees is not clearly covered in the administrative penal mandate of Article 13.

### 4.4 Surviving Issue and Concrete Consequence
- This does **not** mean there is an absence of substantive obligation or that civil remedies fail; ownership vests by law in EU jurisdictions. However, there is an asymmetric enforcement gap: the Commission's powerful administrative fining regime (up to 10% turnover) and periodic penalty payments cannot be deployed directly against an EU undertaking that willfully refuses to execute the subscription under Article 5(5), sentence 5, or against a restructuring transferee under Article 5(11)–(12).

### 4.5 Minimal Repair Direction
- Amend Article 13(1)(a) and (b):
  > "(a) fails to issue the citizens' capital warrant in accordance with Article 5(1), or fails to execute the subscription in accordance with Article 5(5);
  > (b) fails to take the measures required by the third sentence of Article 5(5);
  > (ba) being a transferee within the meaning of Article 5(11) or Article 5(12), fails to comply with the obligations laid down in those paragraphs;"
- *Policy/Safeguards Affected:* Extends administrative enforcement teeth to all execution pathways equally (DC-29, DC-33, DC-37).

### 4.6 Validation Scenario and Review Class
- **Validation Scenario:** An EU covered undertaking issues a warrant, but upon crystallisation under Article 5(3)(b) (7-year trigger), its management board refuses to issue shares or update its register. The Commission initiates infringement proceedings under Article 13. The amended text must explicitly empower Article 13(1) fines and 13(2) daily periodic penalties.
- **Review Class:** Substantive drafting change (Gates 1, 4, 5 + Editor).

---

## 5. Explanatory Memorandum Fidelity, Cross-References, and French Alignment

### 5.1 Itemized Diagnostic Verification

#### 5.1.1 "Post-designation-value-only" Description
- **Classification:** CONFIRMED (Memorandum Defect).
- **Reference:** Memorandum § 2.4 (EN & FR):
  > EN: "the obligation is prospective and attaches only to value formed after designation"  
  > FR: "l'obligation est prospective et ne s'attache qu'à la valeur constituée après la désignation"
- **Operative Text:** Article 5(2) provides that the warrant entitles subscription for "shares representing 3 % of the fully diluted capital of the covered undertaking determined immediately before that event".
- **Analysis:** For an undertaking with extensive value accumulated prior to designation, the warrant dilutes 3% of the total enterprise capital upon crystallisation, not merely the incremental value generated post-designation. Recital 18 correctly describes it as "a one-time dilution, capped at a stated percentage, borne at a moment of realised gain." The memorandum text is inaccurate and contradicts the article.
- **Repair:** Replace "attaches only to value formed after designation" with "attaches prospectively to value realised after designation".

#### 5.1.2 "Owners'-realisation-only" Description
- **Classification:** CONFIRMED (Memorandum Defect).
- **Reference:** Memorandum § 2.4 & § 3.3 Option 4 (EN & FR):
  > EN: "it crystallises only when the undertaking's own owners realise value"  
  > FR: "ne se cristallise que lorsque les propriétaires mêmes de l'entreprise réalisent de la valeur"
- **Operative Text:** Article 5(3)(b) crystallises the warrant when "seven years have elapsed since the issuance of the warrant", irrespective of whether owners have realised value.
- **Analysis:** While § 3.3 under "Economic impacts" mentions the seven-year long stop, § 2.4 and § 3.3 (Option 4) contain unqualified assertions that crystallisation occurs *only* when owners realise value.
- **Repair:** Align § 2.4 and § 3.3 Option 4 to state: "crystallises primarily upon value realisation by owners or upon the seven-year long-stop".

#### 5.1.3 "Notification-only" and "Outside-the-nine-unaffected" Descriptions
- **Classification:** CONFIRMED (Memorandum Defect).
- **Reference:** Memorandum § 3.4 & § 3.3 (EN & FR):
  > EN § 3.4: "The instrument imposes a notification duty on undertakings meeting the thresholds and nothing on anyone else."  
  > EN § 3.3: "The instrument has no effect on any undertaking outside that set…"
- **Operative Text:** Article 3(6) (market investigations for below-threshold undertakings), Article 5(11) (obligations on transferees regardless of thresholds), Article 3(8) (restructuring restrictions), Article 11 (obligations on Member States), and Article 17(1) (transitional notifications).
- **Analysis:** Stating that the instrument imposes duties on *no one else* and has *no effect* on undertakings outside the designated set is an overstatement that ignores transferees, restructuring entities, investigated entities, and Member State authorities.
- **Repair:** Clarify that substantive warrant obligations fall upon designated undertakings and their asset transferees, and that reporting/investigatory mechanisms apply as specified.

#### 5.1.4 "Audited-accounts-only" Description
- **Classification:** CONFIRMED (Memorandum Defect).
- **Reference:** Memorandum § 3.4:
  > EN: "Both figures in the designation test are already in audited accounts, so compliance requires no new measurement."
- **Operative Text:** Annex I, Point 4 requires determining "fair market value" on the basis of recent funding transactions (4(a)), independent valuation (4(b)), or 6-month average market capitalisation (4(c)).
- **Analysis:** While turnover and compensation of labour are audited lines, the fair market value of private, unlisted frontier undertakings is not an off-the-shelf line item in historical audited accounts; it requires transaction analysis or valuation under Point 4.
- **Repair:** Amend to: "The turnover and labour compensation figures are derived from audited accounts, while fair market value follows established corporate valuation standards."

#### 5.1.5 "Age of Majority" vs. Operative 18-Year Threshold
- **Classification:** CONFIRMED (Imprecise Explanatory Term).
- **Reference:** Memorandum § 3.3 (Social impacts):
  > EN: "…distributions being made from the age of majority under Article 10…"  
  > FR: "…les distributions étant effectuées à compter de l'âge de la majorité conformément à l'article 10…"
- **Operative Text:** Article 10(1) states: "Every citizen of the Union who has attained the age of 18 years shall hold an entitlement under this Regulation."
- **Analysis:** "Age of majority" is a national civil law status that varies or could vary by Member State, whereas Article 10(1) establishes an autonomous Union criterion of 18 years.
- **Repair:** Replace "from the age of majority" with "from the age of 18 years".

#### 5.1.6 Fee Cross-Reference Error
- **Classification:** CONFIRMED (Definite Drafting Citation Error).
- **Reference:** Memorandum § 4, second paragraph (EN & FR):
  > EN: "…and Article 10(6) caps the fees national vehicles may levy so that administration cannot erode the entitlement."  
  > FR: "…et l'article 10, paragraphe 6, plafonne les frais que les véhicules nationaux peuvent prélever…"
- **Operative Text:** Article 11(3) sets the 0,3 % fee cap on national vehicles. Article 10(6) governs the distribution declaration frequency and 10× payment cost de minimis rule.
- **Repair:** Correct citation from Article 10(6) to Article 11(3).

#### 5.1.7 Unenumerated Five Acquis Interfaces
- **Classification:** CONFIRMED (Structural Drafting Incompleteness).
- **Reference:** Memorandum § 1.2 & § 5.4:
  > § 1.2: "Five acquis interface points remain open and are listed in section 5.4."  
  > § 5.4: Lists only: "Five acquis interface points, including the interaction with Directive (EU) 2024/2810 on multiple-vote share structures."
- **Analysis:** Section 5.4 promises an enumeration of the five open acquis interfaces but only mentions one (Directive (EU) 2024/2810). The other four identified in the drafting research (CRR own-funds classification, AIFMD status, IORP II cross-border pension coordination, and EDPS data processing interface) are left unlisted.
- **Repair:** Explicitly enumerate all five open acquis interfaces in section 5.4.

#### 5.1.8 French Memorandum Structural Drift
- **Classification:** CONFIRMED (Translation / File Desynchronisation).
- **Reference:** Memorandum FR § 2.1 vs. Memorandum EN § 2.1.
- **Analysis:** In the English memorandum § 2.1, a crucial paragraph was inserted explaining why the draft preamble cites Article 114 alone, the procedural incompatibility of dual-citing Article 352 in an ordinary legislative act, and how Chapters IV–VI are structured for severability into a separate Article 352 Council Regulation. The French memorandum (`explanatory-memorandum.fr.md`) entirely lacks this paragraph.
- **Repair:** Translate and insert the missing § 2.1 paragraph into `explanatory-memorandum.fr.md`.

---

## 6. Directly Related New Discoveries (Outside Questions 1–5)

1. **Article 5(6) Extraction Notification Void:**
   - Article 5(6) imposes a strict notification duty on covered undertakings for *impending liquidity events* (30 working days before completion). However, it contains no reporting requirement for crystallisation triggered under Article 5(3)(a) (extraction exceeding 25% of turnover). Without an affirmative filing obligation upon crossing the extraction threshold, enforcement relies entirely on ex-post Commission audit.
2. **Article 6(3) Valuation Delivery Timeline on Crystallisation:**
   - Article 6(3) requires the valuer to deliver the valuation within 20 working days "of the date of crystallisation under Article 5(3)". Under Article 5(3), crystallisation takes effect on the *last day of the financial year*. Audited accounts for that financial year will not be completed or published within 20 working days of the year's end, making an accurate independent valuation impossible within that window. Delivery should run from the delivery/audit of the financial statements for that year.
3. **Preamble Citation vs. Chapter Scope:**
   - *[External Legal Assertion — Labelled for External Verification]*: The draft Regulation's enacting preamble cites Article 114 TFEU exclusively, while Chapter IV (Articles 8–9) creates a Union legal entity and Chapter V (Articles 10–11) establishes universal citizen entitlements. While Severability Layer 3 acknowledges this vulnerability, submitting an unsevered single act citing Article 114 alone creates an immediate ground for formal objection by the Council Legal Service.

---

## 7. Short Implementation Order for Necessary Repairs

1. **Phase 1: Operative Drafting Corrections (Substantive Class)**
   - Correct Article 5(4)(e) to reference crystallisation under paragraphs 2 and 3.
   - Refine Article 3(8), second sentence, to require lack of genuine economic/labour substance ("without a corresponding genuine supply of labour").
   - Expand Article 13(1) to penalise failure to execute subscriptions under Article 5(5), sentence 5, and transferee defaults under Articles 5(11)–(12).
   - Adjust Article 6(3) valuation delivery timeline for Article 5(3) crystallisations.

2. **Phase 2: Reserve Governance Architecture (Governance Class / Public Revision)**
   - Adopt either a direct Management Board / Executive Director structure or an institutional delegation model (e.g., EIB mandate) in Article 8, providing legal attribution and signatory powers.

3. **Phase 3: Explanatory Memorandum & Translation Realignment (Prose/Editorial Class)**
   - Correct fee cross-reference (Art. 11(3)) in EN and FR § 4.
   - Correct "age of majority" to "18 years" in EN and FR § 3.3.
   - Harmonise prospective value realisation descriptions in EN and FR § 2.4 and § 3.3.
   - List all five open acquis interfaces in EN and FR § 5.4.
   - Insert missing Article 114/352 severability paragraph into FR § 2.1.

---

VERDICT: REVISE

---

## Assistant disposition (outside verbatim model output)

Diagnostic findings assessed; no operative amendment made. The REVISE verdict is retained. See [the assessment](../findings/2026-09-06-findings-assessment.md) for accepted findings, qualifications, declined suggestions and repair order. Predictions about institutional rejection, categorical enforcement exclusions and unverified external legal assertions are not adopted as settled law. Proposed replacement wording is not approved merely because the underlying defect is accepted. Final editorial review remains with David Vanheeswijck.
