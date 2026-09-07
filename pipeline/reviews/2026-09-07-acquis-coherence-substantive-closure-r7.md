---
gate: acquis-coherence
target: proposals/2026-09-07-substantive-closure/candidate
commit: 97a0f2a
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T14:53:23+00:00 · tokens in=132336 out=9428
> Prompt: acquis-coherence.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `afd98714a0b0aab6fec36914169bf4e44acbb443cf974187f2fad4c27bdbf0ea`
> Prompt SHA-256: `5a3999c44c5c8cb03ce5344e63182bc97c04cedb366788c26a9285c3a4a409d3`

# Diagnostic: Acquis Coherence and Legislative Compatibility

**Target:** Integrated Review Candidate (`proposals/2026-09-07-substantive-closure/candidate/regulation/`)  
**Scope:** Directive (EU) 2017/1132, SRD II (Directive 2007/36/EC), Prospectus Regulation (EU) 2017/1129, MiFID II (Directive 2014/65/EU), IORP II (Directive (EU) 2016/2341), PEPP Regulation (EU) 2019/1238, DMA (Regulation (EU) 2022/1925), State Aid (Arts 107–108 TFEU), and Free Movement of Capital (Art 63 TFEU).

---

## 1. Company Law: Directive (EU) 2017/1132 & Shareholder Rights Directive

### Analysis
Compulsory warrant issuance and subsequent share subscription intersect core corporate law protections in Directive (EU) 2017/1132:
1. **General Meeting Competence for Capital Increases:** Directive (EU) 2017/1132 Article 68 *(unverified against full primary text)* vests the power to decide on capital increases in the general meeting (or within statutory authorised capital limits).
2. **Pre-emption Rights:** Directive (EU) 2017/1132 Article 72 *(unverified against full primary text)* guarantees statutory pre-emption rights to existing shareholders for cash issuances, and Article 73 *(unverified against full primary text)* applies those protections to convertible securities and warrants.
3. **Non-Cash Consideration & Expert Reports:** Directive (EU) 2017/1132 Article 70(2) *(unverified against full primary text)* requires an independent expert report on consideration other than in cash.
4. **Minimum Capital & Non-Voting Class Restrictions:** National corporate laws (implementing Directive (EU) 2017/1132 Art 49 and national company codes) frequently limit the proportion or characteristics of non-voting shares (e.g., maximum percentage of share capital, mandatory preferred dividend coupons).

### Intersections & Derogations

| Existing Acquis Provision | Candidate Draft Provision | Severity | Minimal Cure / Assessment |
|---|---|---|---|
| **Directive (EU) 2017/1132, Arts 68(1)–(3), 72, 73** *(unverified)*:<br>Mandatory general meeting approval for capital increase; statutory shareholder pre-emption rights on new shares and warrants. | **Candidate Article 5(7)**:<br>« Article 49, Article 68(1), (2) and (3), the first subparagraph of Article 70(2), Article 72 and Article 73 of Directive (EU) 2017/1132, and any corresponding provisions of the law of a Member State conferring pre-emption rights, requiring a decision of the general meeting or requiring an expert report on consideration, shall not apply... » | **must-derogate** | **Cleanly derogated.** Candidate Art 5(7) contains an express, narrow disapplication modeled on the resolution acquis (BRRD Art 123). |
| **National Non-Voting Share Caps** (under national transpositions of corporate acquis):<br>Statutory caps on non-voting stock proportions (often max 50 % of share capital) or mandatory preferential return attributes. | **Candidate Article 5(7), second sentence**:<br>« Provisions of the law of a Member State restricting the proportion, issuance conditions or characteristics of non-voting shares shall not apply to the extent that they would prevent the issuance or holding of shares pursuant to this Article. » | **must-derogate** | **Cleanly derogated.** Prevents national non-voting share caps from invalidating the statutory issuance. |
| **Directive (EU) 2017/1132, Art 74** *(unverified)*:<br>Creditor protection rules on capital reduction where shares are cancelled. | **Candidate Article 6(4)**:<br>« Where a court finds... that the valuation overstated the fully diluted capital, the Reserve shall transfer back to the covered undertaking, or cancel, the shares subscribed in excess... » | **drafting-only** | Art 74 is deliberately *not* derogated. To avoid triggering formal capital reduction creditor notice periods, specify in Art 6(4) that oversubscribed shares are transferred back into treasury/holding before any formal redemption under national law. |

---

## 2. Prospectus Regulation (EU) 2017/1129 & MiFID II (Directive 2014/65/EU)

### Analysis
- **Transferable Security Analysis:** Under Prospectus Regulation Article 2(a) and MiFID II Article 4(1)(44) *(both unverified against full primary text)*, "transferable securities" are classes of securities negotiable on the capital market. Candidate Article 5(4)(d) makes the citizens' capital warrant strictly non-transferable (except to a legislative successor of the Reserve). Consequently, the warrant itself is not a transferable security.
- **Statutory Subscription vs. Public Offer:** The compulsory subscription of shares by the Reserve could technically be construed as an issuance/offer. Candidate Article 5(8) expressly establishes that issuance and subscription do not constitute an offer of securities to the public under Regulation (EU) 2017/1129.
- **Admission to Trading:** The candidate removes previous flawed exemptions and explicitly subjects subsequent public offers or trading admissions to ordinary Prospectus Regulation rules (Art 5(8), second sentence).
- **Reserve Supervisory Status:** Candidate Article 8(7) explicitly carves out the Reserve from investment firm (MiFID II), AIF/AIFM (Directive 2011/61/EU), and IORP status.

| Existing Acquis Provision | Candidate Draft Provision | Severity | Minimal Cure / Assessment |
|---|---|---|---|
| **Regulation (EU) 2017/1129, Art 3** *(unverified)*:<br>Obligation to publish a prospectus before making an offer of securities to the public. | **Candidate Article 5(8)**:<br>« The issuance of the citizens' capital warrant and the issuance, offer and subscription of shares pursuant to this Article shall not constitute an offer of securities to the public for the purposes of Regulation (EU) 2017/1129. The admission to trading or subsequent offer of those shares shall remain subject to Regulation (EU) 2017/1129... » | **must-derogate** | **Cleanly exempted.** Separates statutory directed allocation from secondary market transactions. |
| **Directive 2014/65/EU (MiFID II), Arts 4 & 5** *(unverified)*:<br>Authorisation and operational requirements for investment firms. | **Candidate Article 8(7)**:<br>« The Reserve shall not be considered an investment firm within the meaning of Directive 2014/65/EU, an alternative investment fund or an alternative investment fund manager within the meaning of Directive 2011/61/EU... » | **must-derogate** | **Cleanly exempted.** The Reserve is a statutory passive custodian, not an intermediary providing investment services to third parties. |

---

## 3. Pension Rails: IORP II (Directive (EU) 2016/2341) & PEPP (Regulation (EU) 2019/1238)

### Analysis
Member States use established pension rails (e.g., LD in Denmark, PPK in Poland, statutory pension funds) to administer citizen accounts without creating a new 27-state administrative apparatus.
- **IORP II "Sole Purpose" Rule:** Directive (EU) 2016/2341 Article 7 *(unverified against full primary text)* requires institutions for occupational retirement provision to restrict their business exclusively to retirement-benefit operations. Designating an IORP as a national vehicle would violate this ring-fence without an EU-level derogation.
- **Candidate Derogation:** Candidate Article 11(1) expressly derogates from Article 7 of Directive (EU) 2016/2341, permitting designated IORPs to carry out account administration and distribution.
- **Segregation Safeguards:** Candidate Article 11(9) mandates strict operational, liability, and asset segregation between statutory citizen accounts and existing occupational/PEPP schemes, supervised by national competent authorities. Candidate Article 1(5) establishes that general pension law is otherwise undisturbed.

| Existing Acquis Provision | Candidate Draft Provision | Severity | Minimal Cure / Assessment |
|---|---|---|---|
| **Directive (EU) 2016/2341 (IORP II), Art 7** *(unverified)*:<br>Legal capacity limitation: IORPs must operate exclusively for retirement-benefit activities. | **Candidate Article 11(1)**:<br>« By way of derogation from Article 7 of Directive (EU) 2016/2341, an institution designated as a national vehicle may carry out the account administration and distribution activities provided for in this Regulation. » | **must-derogate** | **Cleanly derogated.** Confines the competence carve-out to administrative servicing without modifying occupational pension schemes. |
| **Regulation (EU) 2019/1238 (PEPP), Arts 6–7 & Ch. IV** *(unverified)*:<br>PEPP product rules, investment caps, and portability mandates. | **Candidate Article 11(1) & 11(9)**:<br>« A provider... designated as a national vehicle shall maintain holders' accounts separately from any product governed by that Regulation, and the requirements of that Regulation shall not apply to those accounts. » | **must-derogate** | **Cleanly ring-fenced.** Ensures national PEPP providers do not contaminate PEPP capital rules with statutory citizen distribution accounts. |

---

## 4. DMA Architecture Comparison: Regulation (EU) 2022/1925

### Systematic Comparison of Designation Machine

| Element | DMA Architecture (Reg 2022/1925) | Candidate Draft Architecture (Arts 3–4) | Nature of Divergence | Assessment |
|---|---|---|---|---|
| **Qualitative Limb** | Art 3(1): (a) significant impact on internal market; (b) important gateway; (c) entrenched and durable position. | Art 3(1): (a) automated cognitive services/goods; (b) output substantially decoupled from labour; (c) durable position. | **Deliberate** | Substantive scope adapted from platform gatekeepers to hyper-automated production. |
| **Quantitative Presumption** | Art 3(2): €7.5bn EU turnover / €75bn market cap in 3 Member States; 45m EU end users & 10k business users; sustained for **3 financial years**. | Art 3(2): €7.5bn EU turnover / €75bn FMV in 3 Member States; FMV $\ge$ 80x annual worldwide labour compensation; sustained for **2 financial years**. | **Deliberate** | Two-year period adopted to capture faster-scaling technology developments. |
| **Notification Duty** | Art 3(3): Undertaking notifies Commission within 2 months of meeting thresholds. | Art 3(3): Identical 2-month notification rule and Annex I disclosure pack. | **None** | Exact structural replication. |
| **Designation Decision** | Art 3(4): 45 working days to adopt formal designation decision. | Art 3(4): 45 working days deadline for designation decision. | **None** | Exact structural replication. |
| **Rebuttal Mechanism** | Art 3(5): "Sufficiently substantiated arguments" that "manifestly call into question" the presumption; market definition economics excluded; optional market investigation. | Art 3(5): Verbatim standard ("manifestly call into question"; relevant-market arguments barred; market investigation fallback under Art 4(1)). | **None** | Exact structural replication. |
| **Below-Threshold Designation** | Arts 3(8) & 17: Market investigation to designate qualifying undertakings below quantitative thresholds (12-month limit). | Arts 3(6) & 4(1): Market investigation within 12 months for below-threshold qualifying undertakings. | **None** | Exact structural replication. |
| **Review Cycle & Repeal** | Art 4: Regular review every 3 years; repeal upon cessation of conditions; behavioural duties immediately terminate upon repeal. | Art 4(2)–(3): Review every 3 years. Repeal after 2 consecutive non-qualifying years. **Uncrystallised warrants lapse 5 years post-repeal.** | **Deliberate / Drafting Collision** | A warrant is a contingent property right arising by operation of law, not a continuous behavioural duty. However, a chronological collision exists: under Art 4(3), repeal requires 2 non-qualifying years + 5-year lapse = 7 years, which exactly coincides with the 7-year longstop in Art 5(3)(b). |
| **Addressee & Issuer Rules** | Recital 13 / Art 2(28): Addressee is the economic "undertaking". | Arts 3(10)–(12): Explicit designation of *legal issuer*, non-overlapping perimeters, and transferee addressees. | **Deliberate** | Necessary adaptation: behavioral antitrust rules bind groups, but corporate share issuance requires a specific legal person. |

---

## 5. State Aid (Arts 107–108 TFEU) & Free Movement of Capital (Art 63 TFEU)

### Analysis
1. **State Aid / Public Compensation:**
   - The Reserve holds assets solely for citizens and is insulated from general Union/Member State budgets (Art 8(2)–(3)). Fines go to the EU budget, but no state resources flow into the Reserve.
   - Member State compensation to national vehicles (Art 11(3)–(4)) entails transfer of state resources. Candidate Article 11(10) expressly conditions such payments on Altmark criteria (defined public-service remit, pre-established cost parameters, overcompensation clawback) and preserves Treaty notification/standstill obligations under Article 108(3) TFEU.
2. **Free Movement of Capital (Art 63 TFEU) & Golden Shares:**
   - In *Commission v Germany* (C-112/05 - Volkswagen) and subsequent jurisprudence, state measures conferring disproportionate voting rights, vetoes, or management influence were held to deter foreign investment contrary to Article 63 TFEU.
   - The Reserve eliminates every element of state control:
     - No voting rights (Art 5(4)(a), Art 9(1)(a));
     - No board representation (Art 9(1)(b));
     - No management instructions (Art 9(1)(c));
     - Strictly passive portfolio management (Art 9(2)).
   - Statutory ranking protections (Art 5(4)(b) and Art 5(10)) and the arm's-length rescue-financing exception protect economic value without conferring governance privileges.

---

## Summary of Collisions and Status

1. **Directive (EU) 2017/1132 (Capital & Pre-emption):** `must-derogate` $\rightarrow$ **Cleanly derogated** in Candidate Article 5(7).
2. **Directive (EU) 2016/2341 (IORP II Ring-Fence):** `must-derogate` $\rightarrow$ **Cleanly derogated** in Candidate Article 11(1) with segregation under Article 11(9).
3. **Regulation (EU) 2017/1129 (Prospectus):** `must-derogate` $\rightarrow$ **Cleanly exempted** for statutory subscription in Candidate Article 5(8); ordinary rules preserved for admissions/secondary trading.
4. **DMA (Review & Chronology):** `drafting-only` $\rightarrow$ Five-year post-repeal warrant lapse (Art 4(3)) collides chronologically with the seven-year longstop (Art 5(3)(b)); requires timeline harmonization.
5. **State Aid & Art 63 TFEU:** `drafting-only` $\rightarrow$ Cleanly ring-fenced in Arts 9(1), 11(10), and 12.

The candidate contains no blocking acquis collisions and correctly articulates all necessary statutory derogations.

VERDICT: PUBLISH
