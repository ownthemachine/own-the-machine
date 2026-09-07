---
gate: acquis-coherence
target: generational repair candidate and separate proposals
commit: 7b33a2d
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T07:14:32+00:00 · tokens in=113941 out=8745
> Prompt: acquis-coherence.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `57269e398b7ce596e1b5384856e2c635f73dde4d7aa24d718f8a9698264b93b4`
> Prompt SHA-256: `9f93cb03aae8bc83283e9a1c8b9f828bce213de51ef6e2b261dc326fb92889ee`

# Acquis Coherence & Compatibility Review

This review examines the compatibility of the draft Citizens' Capital Regulation (`regulation/`) and its repair candidate (`proposals/2026-09-07-generational-repairs/`) against the existing EU acquis.

---

## 1. Company Law: Directive (EU) 2017/1132 & Shareholder Rights Directive (2007/36/EC)

### Substantive Analysis
1. **Pre-emption Rights:**
   * **Directive (EU) 2017/1132, Article 70(1)** establishes that whenever capital is increased by consideration in cash, shares must be offered on a pre-emptive basis to shareholders.
   * **Directive (EU) 2017/1132, Article 70(2)** limits pre-emption where classes of shares do not carry voting rights.
   * **Directive (EU) 2017/1132, Article 73** applies pre-emption to convertible securities and instruments with subscription rights.
   * *Draft Status:* Article 5(7) currently derogates from *"the first subparagraph of Article 70(2), Article 72 and Article 73"*. Derogating from Article 70(2) without expressly citing **Article 70(1)** leaves the primary cash pre-emption right un-derogated at Union level, relying solely on the catch-all member-state clause.
2. **General Meeting Competence & Capital Authorisations:**
   * **Directive (EU) 2017/1132, Article 68(1)–(3)** governs the general meeting's exclusive power to increase capital and the 5-year limit on authorised capital.
   * *Draft Status:* Fully derogated in Article 5(7).
3. **Non-Cash Consideration & Expert Reports:**
   * **Directive (EU) 2017/1132, Article 49** (incorporation consideration) is derogated. However, for capital increases post-incorporation, **Article 74** requires an independent expert report where shares are issued for non-cash consideration (relevant if the warrant grant itself or nominal settlement with pre-existing claim value is characterised as non-cash consideration under national law).
4. **Shareholder Rights Directive (Directive 2007/36/EC, as amended by Directive (EU) 2017/828 - SRD II):**
   * *Draft Status:* DRAFTING-RULES.md mandates express derogation from SRD 2007/36 (following BRRD Recitals 120–124). Operative Article 5(7) omits SRD 2007/36 entirely. Although the Reserve is non-voting, statutory share issuance without GM approval intersects national rules implementing SRD II Articles 9a–9c (shareholder approvals on related-party transactions and director remuneration/share schemes).

### Collisions & Interface Points

#### Collision 1.1: Cash Pre-emption Primacy
```
Existing Acquis (Directive (EU) 2017/1132, Art. 70(1))   | Draft Regulation (Article 5(7))
"Whenever the capital is increased by consideration in   | "Article 49, Article 68(1), (2) and (3), the first
cash, the shares shall be offered on a pre-emptive       | subparagraph of Article 70(2), Article 72 and
basis to shareholders in proportion to the capital       | Article 73 of Directive (EU) 2017/1132... shall
represented by their shares."                            | not apply..."
```
* **Severity:** Must-derogate
* **Minimal Cure:** In Article 5(7), replace *"the first subparagraph of Article 70(2)"* with *"Article 70"*.

#### Collision 1.2: Consideration Expert Report on Capital Increase
```
Existing Acquis (Directive (EU) 2017/1132, Art. 74)       | Draft Regulation (Article 5(7))
"Where capital is increased by consideration other than   | Article 49 is cited, but Article 74 of Directive
in cash... one or more experts... shall draw up a         | (EU) 2017/1132 is omitted from the enumerated list
report on the consideration..."                           | of derogations.
```
* **Severity:** Must-derogate
* **Minimal Cure:** Add *"Article 74"* of Directive (EU) 2017/1132 to the enumerated derogations in Article 5(7).

#### Collision 1.3: Shareholder Rights Directive Approval Competences
```
Existing Acquis (Directive 2007/36/EC, Arts. 9a–9c)       | Draft Regulation (Article 5(7))
Shareholder approval rights and general meeting powers    | Omission of any express reference to Directive
over share issuance and related-party transactions.       | 2007/36/EC.
```
* **Severity:** Drafting-only
* **Minimal Cure:** Insert an express statement in Article 5(7): *"Directive 2007/36/EC and national provisions transposing it shall not apply to the extent that they would require general meeting approval or otherwise restrict the issuance, subscription or holding of shares pursuant to this Article."*

---

## 2. Prospectus Regulation (EU) 2017/1129 & MiFID II (Directive 2014/65/EU)

### Substantive Analysis
1. **Transferable Security Status of the Warrant:**
   * Under **MiFID II Article 4(1)(44)**, transferable securities are classes of securities negotiable on the capital market.
   * Under **Article 5(4)(d)**, the warrant is strictly non-transferable (except to a statutory Union successor). It is therefore not negotiable and does not constitute a transferable security triggering Prospectus Regulation obligations.
2. **Public Offer Exemption:**
   * Article 5(8) explicitly provides that the issuance of the warrant and the issuance, offer, and subscription of shares pursuant to Article 5 do not constitute an "offer of securities to the public" for the purposes of Regulation (EU) 2017/1129. This prevents the primary trigger under Article 3(1) of Regulation (EU) 2017/1129.
3. **Admission to Trading Exemption:**
   * Article 5(8) provides an exemption from the obligation to publish a prospectus upon admission to trading *"where shares of the same class are already admitted to trading on the same regulated market"*.
   * *Gap:* Under Article 2(6)(a), an initial public offering (IPO) is a liquidity event. In an IPO, the underlying shares are being admitted for the first time, not *already* admitted. The draft must ensure the issuer's IPO prospectus covers the Reserve's subscribed shares without imposing a separate prospectus duty on the Reserve.
4. **MiFID II & Fund Regulation Status:**
   * Article 8(7) cleanly and expressly excludes the Reserve from the definitions of an investment firm (Directive 2014/65/EU), AIF/AIFM (Directive 2011/61/EU), and IORP (Directive (EU) 2016/2341).

### Collisions & Interface Points

#### Collision 2.1: Admission to Trading Exemption at Initial Listing (IPO)
```
Existing Acquis (Regulation (EU) 2017/1129, Art. 3(3))   | Draft Regulation (Article 5(8))
"Securities shall not be admitted to trading on a        | "...admission to trading of those shares shall be
regulated market... without prior publication of a       | exempt... where shares of the same class are
prospectus."                                             | already admitted to trading on the same regulated
                                                         | market."
```
* **Severity:** Drafting-only
* **Minimal Cure:** In Article 5(8), adjust the second limb: *"...and the admission to trading of those shares shall be exempt from the obligation to publish a separate prospectus under that Regulation where shares of the same class are admitted to trading on a regulated market."*

---

## 3. IORP II (Directive (EU) 2016/2341) & PEPP (Regulation (EU) 2019/1238)

### Substantive Analysis
1. **IORP II Exclusivity of Purpose (Article 7):**
   * Article 7 of Directive (EU) 2016/2341 requires Member States to ensure that IORPs operate exclusively for retirement-provision-related activities.
   * *Draft Status:* Article 11(1) contains an express derogation from Article 7 of Directive (EU) 2016/2341, allowing designated IORPs to administer citizens' capital accounts and distribute cash.
2. **Prudential, Biometric, and Investment Rules:**
   * National vehicles under Article 11 act solely as account keepers and payout rails for cash distributions made by the Reserve. They do not hold the underlying company equity (which is held directly by the Reserve under Article 8).
   * Because national vehicles do not underwrite biometric risks or invest scheme assets under the Citizens' Capital Regulation, the "prudent person" investment rules of IORP II (Article 19) are not engaged.
3. **PEPP Ring-Fencing:**
   * Article 11(1) requires PEPP providers acting as national vehicles to maintain holders' accounts separately from any PEPP product and exempts those accounts from Regulation (EU) 2019/1238 requirements. This avoids conflicts with PEPP rules on mandatory investment options, switching, and portability caps.

### Collisions & Interface Points

#### Collision 3.1: Custodial Legal Capacity of Statutory Pension Rails
```
Existing Acquis (Directive (EU) 2016/2341, Arts. 7 & 19) | Draft Regulation (Article 1(5) & Article 11(1))
IORP activities restricted to occupational pensions;     | Derogation is limited to Article 7 (exclusivity
prudential rules govern asset allocation.                | of purpose).
```
* **Severity:** Drafting-only
* **Minimal Cure:** The current Article 11(1) derogation is sufficient for cash payout administration. To prevent national supervisory friction regarding ring-fenced funds, Article 11(1) should clarify: *"Entitlements and distributions credited to accounts under this Regulation shall not constitute scheme assets or liabilities of an institution under Directive (EU) 2016/2341 or Regulation (EU) 2019/1238."*

---

## 4. Digital Markets Act (Regulation (EU) 2022/1925 - DMA) Architecture

### Comparison of Design Machines

| DMA Element | DMA (Reg 2022/1925) | Draft Regulation | Nature of Divergence |
|---|---|---|---|
| **Qualitative Scope** | Art. 3(1): Core platform services, substantial impact, gateway, durable. | Art. 3(1): Automated cognitive services, decoupling from labour, durable. | **Deliberate:** Target is automated productivity, not platform contestability. |
| **Quantitative Presumption** | Art. 3(2): EUR 7.5bn EU turnover or EUR 75bn market cap; 45m end users & 10k business users; 3 financial years. | Art. 3(2): EUR 7.5bn EU turnover or EUR 75bn FMV; FMV $\ge 80\times$ labour compensation; 2 financial years. | **Deliberate:** 80x labour ratio replaces user counts; 2-year durability reflects faster tech cycles. |
| **Notification Duty** | Art. 3(3): Within 2 months of crossing thresholds. | Art. 3(3): Within 2 months of crossing thresholds. | **Identical** (deliberate reuse). |
| **Designation Decision** | Art. 3(4): 45 working days. | Art. 3(4): 45 working days. | **Identical** (deliberate reuse). |
| **Rebuttal Mechanism** | Art. 3(5): Exceptionally; "manifestly call into question"; relevant market arguments excluded. | Art. 3(5): Exceptionally; "manifestly call into question"; relevant market arguments excluded. | **Identical** (deliberate reuse). |
| **Market Investigation** | Art. 17(1): Concluded within 12 months. | Art. 4(1): Concluded within 12 months. | **Identical** (deliberate reuse). |
| **Review Cycle** | Art. 4(1): Review at least every 3 years. | Art. 4(2): Review at least every 3 years. | **Identical** (deliberate reuse). |
| **Repeal & Warrant Lapse** | Art. 4(2)–(3): Repeal on change of facts. | Art. 4(3): Repeal after 2 consecutive years of non-satisfaction; uncrystallised warrant lapses in 5 years. | **Deliberate:** Balances avoidance structuring against perpetual contingent claims. |

### Assessment
The draft borrows the DMA architecture faithfully. Divergences (the labour-ratio threshold, 2-year durability period, and the 5-year warrant lapse rule) are deliberate, policy-tailored adaptations to an equity-warrant regime rather than structural drafting omissions.

---

## 5. State Aid (Articles 107–108 TFEU) & Free Movement of Capital (Article 63 TFEU)

### Substantive Analysis
1. **State Aid (Articles 107–108 TFEU):**
   * *The Reserve:* Under Article 8(2)–(3), the Reserve holds assets exclusively for holders, is financed exclusively by warrants/returns, and receives zero public budget resources. No State resources are transferred.
   * *National Vehicles:* Article 11(3) allows Member States to compensate national vehicles for verifiable net costs above the 0.3% fee cap. Recital 27 categorises account administration as a Service of General Economic Interest (SGEI) under Article 106(2) TFEU.
   * *Covered Undertakings:* The warrant is a uniform regulatory condition across all qualifying internal market operators (EU and non-EU alike); it confers no selective advantage.
2. **Free Movement of Capital (Article 63 TFEU):**
   * *Golden Share Jurisprudence:* In *Commission v Germany* (C-112/05) and progeny, the CJEU struck down special state rights (disproportionate voting caps, golden shares, vetoes, board appointments) that deter cross-border direct investment.
   * *Draft Compliance:* The Reserve is structured as the exact inverse of a golden share:
     * Non-voting shares by statute (Articles 5(4)(a) and 9(1)(a)).
     * Prohibition on management seats, instructions, or vetoes (Article 9(1)(b)–(c)).
     * Non-discriminatory scope (Article 1(4) applies to all undertakings in the internal market).
     * Rescue capital carve-out: Article 5(10), second subparagraph, permits bona fide arm's-length rescue and prudential capital to take priority over the Reserve, avoiding constraints on distressed financing.

### Collisions & Interface Points

#### Collision 5.1: State Aid Clearance for National Vehicle SGEI Compensation
```
Existing Acquis (Article 106(2) & 107(1) TFEU / Altmark)   | Draft Regulation (Article 11(3))
State compensation for SGEI must satisfy the four         | "A Member State may compensate a national vehicle
Altmark criteria or comply with the SGEI Framework        | for verifiable net costs exceeding that ceiling..."
(2012/C 8/03).                                            |
```
* **Severity:** Drafting-only
* **Minimal Cure:** Add to Article 11(3): *"Such compensation shall be calculated in accordance with the applicable Union framework for State aid in the form of public service compensation."*

---

## Overall Summary of Required Cures

1. **Directive (EU) 2017/1132 (Article 5(7)):** Derogate broadly from Article 70 (not just Article 70(2)) and add Article 74.
2. **Directive 2007/36/EC (Article 5(7)):** Add an explicit general derogation from general meeting and related-party approval requirements.
3. **Regulation (EU) 2017/1129 (Article 5(8)):** Clarify the admission-to-trading prospectus exemption to cleanly capture initial admissions (IPOs).
4. **Directive (EU) 2016/2341 & Regulation (EU) 2019/1238 (Article 11(1)):** Add clarifying language that administered accounts do not constitute IORP/PEPP scheme assets.
5. **State Aid / SGEI (Article 11(3)):** Cross-reference Union SGEI public service compensation criteria.

Because the required adjustments in Article 5(7) (Directive 2017/1132 Articles 70 and 74) are substantive derogations necessary to prevent legal collision with mandatory EU company law rules on pre-emption and non-cash valuation, the text must be revised prior to publication.

VERDICT: REVISE

## Assistant disposition prepared for the final editor

Verbatim model output ends above. The exact reviewed working-tree snapshot
is identified by the bundle hash, not the later bookkeeping commit.
See [review status and dispositions](../../proposals/2026-09-07-generational-repairs/REVIEW-STATUS.md).
No institutional opinion or final editorial approval is implied.
