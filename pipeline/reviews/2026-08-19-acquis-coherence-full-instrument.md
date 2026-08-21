---
gate: acquis-coherence
target: complete instrument (recitals, articles, annexes)
commit: a3ef091
verdict: REVISE
disposition: merged-with-fixes
date: 2026-08-19
---

> Citation corrected on 21 August 2026. This record originally cited
> commit e22a7c3, which does not exist in this repository: it was a commit
> on the branch this work merged from, and the merge squashed it. The id
> above is the commit on main that carries the text the gate was given.
> The error predates the history rewrite of the same date and was found
> by it.

# Review

> Reviewer: OpenRouter `google/gemini-3.7-flash` · 2026-08-18T23:05:49+00:00 · tokens in=10729 out=6225
> Prompt: prompts/acquis-coherence.md · Verbatim model output below — do not edit.

### 1. Company Law: Directive (EU) 2017/1132 & SRD II

#### Collision 1.1: Missing Derogations for Consideration and Capital Formation
* **Draft Text (Article 5(2), (4), (6)):**
  > "The citizens' capital warrant shall entitle the Reserve... to subscribe at nominal value for newly issued shares..." / "Articles 68(1), (2) and (3) and 72 of Directive (EU) 2017/1132... shall not apply..."
* **Acquis Text (Directive (EU) 2017/1132, Articles 46, 49, and 50):**
  > **Art. 46:** "Shares may not be issued at a price lower than their nominal value..."  
  > **Arts. 49–50:** Require an independent expert report on any consideration other than in cash prior to the capital increase, and strict timelines for consideration settlement.
* **Analysis:** The draft purports to allow subscription "at nominal value" by operation of law, but does not identify who pays the nominal value (the Reserve pays no consideration, making it effectively unbacked, or below par if par value exceeds nominal). Recital 12 contemplates derogating from consideration rules, but Article 5(6) only derogated from Article 68 (general meeting / authorised capital) and Article 72 (pre-emption).
* **Severity:** **Must-derogate**
* **Minimal Cure:** Amend Article 5(6) to include Articles 46, 47, 49, 50, and 53 of Directive (EU) 2017/1132 in the explicit list of disapplied provisions.

---

#### Collision 1.2: Shareholder Approval and Maximum Authorised Capital Limits
* **Draft Text (Article 5(4), (6)):**
  > "The subscription... shall take effect by operation of law... Articles 68(1), (2) and (3) and 72 of Directive (EU) 2017/1132 and any corresponding provisions of the law of a Member State conferring pre-emption rights or requiring a decision of the general meeting shall not apply..."
* **Acquis Text (Directive (EU) 2017/1132, Article 68(1)–(3)):**
  > Mandates that increases in subscribed capital must be decided by the general meeting or authorised by statutes/general meeting subject to fixed statutory caps and maximum 5-year authorization periods.
* **Analysis:** The derogation in Article 5(6) successfully isolates Articles 68(1)–(3) and 72. However, national company laws governing non-voting shares often contain caps on the proportion of non-voting shares relative to total share capital (e.g., maximum 50%). When 3% non-voting equity is added, it may breach domestic class ratios without an overarching supremacy/pre-emption clause.
* **Severity:** **Drafting-only**
* **Minimal Cure:** Add to Article 5(6): *"National provisions restricting the proportion, issuance conditions or characteristics of non-voting shares shall not apply to the extent they prevent the creation, issuance or holding of shares under this Regulation."*

---

### 2. Prospectus Regulation (EU) 2017/1129 & MiFID II / AIFMD

#### Collision 2.1: Scope of Prospectus Exemption and Admission to Trading
* **Draft Text (Article 5(7)):**
  > "The offer and subscription of shares pursuant to this Article shall not constitute an offer of securities to the public for the purposes of Regulation (EU) 2017/1129."
* **Acquis Text (Regulation (EU) 2017/1129, Article 3(1) and 3(3)):**
  > **Art. 3(1):** Regulates offers of securities to the public.  
  > **Art. 3(3):** Separately prohibits the *admission of securities to trading on a regulated market* without prior publication of a prospectus.
* **Analysis:** While Article 5(7) cleanly exempts the *offer/subscription*, it ignores *admission to trading* under Article 3(3) of Regulation (EU) 2017/1129. If the covered undertaking is already listed or listing during an IPO liquidity event, the newly created 3% shares must be fungible and admitted to trading, which requires a specific exemption under Article 1(5) of Regulation (EU) 2017/1129 to prevent prospectus liabilities.
* **Severity:** **Must-derogate**
* **Minimal Cure:** Amend Article 5(7) to read: *"The issuance, offer, subscription and subsequent admission to trading on a regulated market of shares pursuant to this Article shall be exempt from the obligation to publish a prospectus under Regulation (EU) 2017/1129."*

---

#### Collision 2.2: MiFID II / AIFMD Entity-Level Licensing Exemption
* **Draft Text (Articles 8(1), (3) and 9(1)(d)):**
  > The Reserve is a standalone legal personality that manages crystallised holdings and reinvests income.
* **Acquis Text (Directive 2014/65/EU (MiFID II), Article 2(1); Directive 2011/61/EU (AIFMD), Article 2(3)):**
  > Persons managing investments or holding collective capital must be licensed as investment firms or AIFMs unless explicitly exempted (such as central banks, sovereign funds, or social security institutions).
* **Analysis:** The Reserve is not explicitly added to the statutory exclusion lists of MiFID II, AIFMD, or the Solvency II framework, creating ambiguity as to its regulatory status under Union financial services law.
* **Severity:** **Drafting-only**
* **Minimal Cure:** Insert a paragraph into Article 8: *"The Reserve shall not be considered an investment firm within the meaning of Directive 2014/65/EU or an alternative investment fund manager within the meaning of Directive 2011/61/EU."*

---

### 3. Pension Rails: IORP II & PEPP

#### Collision 3.1: Ultra Vires Mandate of IORP II "Sole Purpose" Principle
* **Draft Text (Articles 1(4), 11(1), 11(2)):**
  > **Art. 11(1):** "Existing institutions within the meaning of Directive (EU) 2016/2341 [IORP II]... may be designated."  
  > **Art. 11(2):** Compels national vehicles to administer individual accounts and distribute funds to any citizen aged 18+.
* **Acquis Text (Directive (EU) 2016/2341 (IORP II), Article 7 ('Activities of an IORP')):**
  > "Member States shall require IORPs operating within their territories to limit their activities to retirement-benefit related operations and activities arising therefrom."
* **Analysis:** IORP II establishes a strict "sole purpose" ring-fence. An IORP cannot legally act as a universal cash-distribution custodian for all Union citizens (most of whom have no employment/pension relationship with the IORP). The general savings clause in draft Article 1(4) (*"without prejudice... save as expressly provided in Article 11"*) fails to affirmatively grant Member States the power to override Article 7 IORP II without infringing national transposition acts.
* **Severity:** **Blocking**
* **Minimal Cure:** Replace Article 1(4) and insert an explicit derogation in Article 11(1): *"By way of derogation from Article 7 of Directive (EU) 2016/2341, an IORP designated as a national vehicle may carry out the account administration and distribution activities provided for in this Regulation."*

---

#### Collision 3.2: PEPP Cost Caps and Statutory Asset Segregation
* **Draft Text (Article 11(1), (3)):**
  > Allows PEPP providers under Regulation (EU) 2019/1238 to be designated, and caps national vehicle fees at 0.3% annually.
* **Acquis Text (Regulation (EU) 2019/1238 (PEPP), Articles 19, 45, and 54):**
  > Imposes strict structural contract rules, biometric underwriting allowances, investment options, and a comprehensive 1% all-in fee cap covering the entire basic PEPP architecture.
* **Analysis:** Co-mingling PEPP accounts with compulsory, non-contractual citizen distributions creates an irreconcilable conflict with PEPP statutory product rules and capital protection guarantees under Article 46 of PEPP.
* **Severity:** **Must-derogate**
* **Minimal Cure:** Clarify in Article 11 that designated PEPP providers must maintain citizen accounts as functionally and legally segregated sub-accounts distinct from PEPP contracts, exempt from the requirements of Chapters IV, V, and VI of Regulation (EU) 2019/1238.

---

### 4. DMA (Regulation (EU) 2022/1925) Architecture Divergence Analysis

| Feature | DMA Architecture (Reg. 2022/1925) | Draft Regulation Architecture | Assessment & Status |
| :--- | :--- | :--- | :--- |
| **Notification & Timeline** | Art. 3(3): Notification within 2 months of meeting thresholds. | Art. 3(3): Identical 2-month notification requirement. | **Aligned.** |
| **Rebuttal Mechanism** | Art. 3(5): Arguments must "manifestly call into question" the presumption. Commission has 45 working days to reject or open an Art. 17(3) market investigation. | Art. 3(5): Same manifest standard; excludes relevant market arguments. | **Aligned.** |
| **Intermediate Investigation on Rebuttal** | Art. 17(3): If presumption is substantiated as rebutted, Commission opens a 5-month market investigation before designation. | Art. 3(4)–(5): Commission designates within 45 working days without an intermediate investigation step. | **Sloppy Divergence:** Eliminates procedural due process step for undertakings presenting credible rebuttals. |
| **Scope of Designation** | Specific Core Platform Service (CPS) level designation (Art. 3(9)). | Entire undertaking is designated, though threshold in Art. 3(2)(b) measures only the automated segment. | **Deliberate:** The warrant is issued at the parent corporate level (3% of diluted capital), so entity-wide designation is legally required. |
| **Review & De-designation** | Art. 4(1)–(2): Review every 3 years or upon request; de-designation when conditions cease to exist. | Art. 4(2)–(3): Review every 3 years; de-designation requires *two consecutive financial years* of non-satisfaction. | **Deliberate:** Stabilises warrant property rights and prevents opportunistic short-term restructuring. |

* **Severity:** **Drafting-only**
* **Minimal Cure:** In Article 3(4), specify that where the Commission finds rebuttal arguments require detailed assessment, it may open a market investigation under Article 4(1) rather than issuing a summary designation decision within 45 working days.

---

### 5. State Aid & Free Movement of Capital

#### Collision 5.1: Art. 63 TFEU Friction on Sovereign Debt Ban
* **Draft Text (Article 12(2)):**
  > "The Reserve shall not acquire or hold, directly or indirectly, debt instruments issued or guaranteed by the Union, by a Member State, by a regional or local authority of a Member State, by a central bank or by any body the obligations of which are guaranteed by any of them."
* **Acquis Text (Article 63 TFEU):**
  > Prohibits all restrictions on the movement of capital and payments between Member States and between Member States and third countries.
* **Analysis:** Restricting a public-law reserve with legal personality from acquiring EU/Member State sovereign debt does not infringe Article 63 TFEU as an external market restriction, because it functions as an internal, statutory investment mandate/prudence constraint of an asset-holding vehicle (akin to investment limits under Article 133 of the Financial Regulation or specific fund mandates).
* **Severity:** **Drafting-only**
* **Minimal Cure:** Clarify in Recital 22 that Article 12(2) constitutes an objective portfolio governance rule to ensure non-monetisation and institutional independence.

---

#### Collision 5.2: State Aid (Article 107(1) TFEU) and State Resources Assessment
* **Draft Text (Articles 8(2), 8(3), 11(3)):**
  > Assets do not constitute revenue of the Union or Member States; Reserve receives no public funds. National vehicles capped at 0.3% fee.
* **Acquis Text (Article 107(1) TFEU):**
  > Prohibits aid granted by a Member State or through State resources which distorts competition by favouring certain undertakings.
* **Analysis:** Under CJEU jurisprudence (*Stichting Pensioenfonds Metaal en Techniek*, *PreussenElektra*), funds originating from mandatory statutory transfers held exclusively for private beneficiaries without state control or budgetary disposition do not constitute "State resources". However, forcing designated national private pension vehicles to cap administrative fees at 0.3% without state compensation could impose an uncompensated public service obligation, risking unnotified State aid/compensation frictions.
* **Severity:** **Drafting-only**
* **Minimal Cure:** Insert a provision in Article 11(3) confirming that where designated vehicles incur verifiable net costs exceeding 0.3%, Member States may compensate them strictly in line with the SGEI Framework (Commission Decision 2012/21/EU).

---

VERDICT: REVISE


---

## Editor disposition (19 August 2026)

First run of the acquis-coherence gate, on the complete instrument. Eight
collisions; all accepted, one with a verification caveat.

1.1 Consideration and expert-report derogations: accepted. Article 5(6)
    now disapplies Article 49 of Directive (EU) 2017/1132 and, in
    functional terms, the consideration and minimum-price provisions in
    so far as they would prevent subscription at nominal value. Open
    point: verify the exact article numbers of the codified Directive
    before Gate 1; the reviewer's list (46, 47, 50, 53) is not taken on
    faith.
1.2 National non-voting-share caps: accepted, sentence added to 5(6).
2.1 Prospectus admission-to-trading gap: accepted, Article 5(7) now
    covers admission where the class is already traded.
2.2 MiFID II / AIFMD / IORP status of the Reserve: accepted, new
    Article 8(6); the delegation conferral moved to 8(7).
3.1 IORP II sole-purpose ring-fence (Blocking): accepted, express
    derogation from Article 7 of Directive (EU) 2016/2341 in
    Article 11(1).
3.2 PEPP product-rule collision: accepted, segregation sentence in
    Article 11(1).
4.  DMA rebuttal procedure divergence: accepted, Article 3(5) now allows
    the Commission to open an Article 4(1) market investigation instead
    of summary designation.
5.1 Sovereign-debt ban vs Article 63 TFEU: accepted as drafting-only,
    portfolio-governance sentence added to recital 22.
5.2 Fee-cap State-aid friction: accepted, Member State compensation
    permitted in Article 11(3) and recital 21, never charged to holders
    or the Reserve.
