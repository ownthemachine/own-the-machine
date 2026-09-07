---
gate: acquis-coherence
target: proposals/2026-09-07-substantive-closure/candidate
commit: 0338506
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T09:08:42+00:00 · tokens in=122187 out=7787
> Prompt: acquis-coherence.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `bfeb26dc2cacd4667b3a17719b41b08e40250236d97aedc83397b4ebc63c46dd`
> Prompt SHA-256: `5a3999c44c5c8cb03ce5344e63182bc97c04cedb366788c26a9285c3a4a409d3`

### 1. Company Law: Directive (EU) 2017/1132 and Shareholder Rights Directive (2007/36/EC)

#### A. Statutory Capital Increases, General Meeting Approval, and Pre-emption Rights
* **Directive (EU) 2017/1132 provisions engaged:**
  * Article 68(1)–(3) [General meeting competence on capital increases and 5-year maximum authorisation period].
  * Article 70(2), first subparagraph [Independent expert report on non-cash consideration].
  * Article 72 [Pre-emption rights of existing shareholders in capital increases for cash consideration].
  * Article 73 [General meeting decision required to restrict or withdraw pre-emption rights].
  * Article 49 [Minimum capital requirements / capital maintenance – *unverified in prompt text*].
* **Candidate draft analysis:**
  Article 5(7) expressly provides that Article 49, Article 68(1)–(3), the first subparagraph of Article 70(2), Article 72, and Article 73 of Directive (EU) 2017/1132, as well as corresponding national provisions conferring pre-emption rights or requiring general meeting resolutions, do not apply to the warrant issuance or share subscription.
* **Collision Assessment & Derogation:**
  The draft correctly and specifically derogates from the necessary capital-increase and pre-emption provisions of Directive (EU) 2017/1132. It avoids overbroad disapplications (e.g., it preserves creditor-protection rules under capital reductions pursuant to Article 74 of Directive 2017/1132).

```
Candidate Article 5(7)                     Directive (EU) 2017/1132, Articles 68 & 72
"Article 49, Article 68(1), (2) and (3),   "1. Any increase in capital shall be decided
the first subparagraph of Article 70(2),   upon by the general meeting..." (Art. 68(1))
Article 72 and Article 73 of Directive     "1. Whenever the capital is increased by
(EU) 2017/1132... shall not apply to the   consideration in cash, the shares shall be
issuance of the citizens' capital warrant  offered on a pre-emptive basis to
or to the subscription of shares..."       shareholders..." (Art. 72(1))
```
* **Severity:** `must-derogate` (Properly cured by express derogation in Art. 5(7)).
* **Minimal cure:** None required; derogation is operative and narrow.

---

#### B. Shareholder Rights Directive (Directive 2007/36/EC, as amended by Directive (EU) 2017/828)
* **Provisions engaged:** Article 9c of Directive 2007/36/EC [*unverified in prompt text*] (related party transactions and shareholder approval thresholds for material dilutive corporate transactions).
* **Candidate draft analysis:** 
  The draft contains no express derogation from Directive 2007/36/EC. However, because the warrant and subscription arise by operation of Union regulation rather than by contract or management decision, and the Reserve is an independent statutory entity, it is not a "related party". To eliminate litigation risk where national implementing laws require shareholder approval for material share issuances, an express clarification is needed.

```
Candidate Article 5(7)                     Directive 2007/36/EC (SRD II), Chapter Ib [*unverified*]
[Silent on Directive 2007/36/EC]           Material transactions and shareholder
                                           approvals in listed companies.
```
* **Severity:** `drafting-only`.
* **Minimal cure:** Add a reference to Directive 2007/36/EC in Article 5(7) or recital 15 clarifying that statutory execution under Article 5 does not constitute a transaction subject to shareholder approval under Directive 2007/36/EC.

---

### 2. Prospectus Regulation (EU) 2017/1129 and MiFID II (Directive 2014/65/EU)

#### A. Transferability and Public Offer Classification
* **Prospectus Regulation (EU) 2017/1129 (Articles 1(4), 2(d), 3):**
  * The citizens' capital warrant is non-transferable (Article 5(4)(d)). Under Article 2(a) of Regulation (EU) 2017/1129 [*unverified*] / Article 4(1)(44) MiFID II [*unverified*], non-transferable instruments are not transferable securities.
  * The shares issued upon crystallisation are transferable securities. Article 5(8) expressly states that the issuance, offer, and subscription of shares pursuant to Article 5 "shall not constitute an offer of securities to the public for the purposes of Regulation (EU) 2017/1129."
  * Unlike earlier baseline drafts that attempted a problematic blanket listing-prospectus waiver for non-voting shares, Candidate Article 5(8) cleanly states: "The admission to trading or subsequent offer of those shares shall remain subject to Regulation (EU) 2017/1129, including any exemption available under that Regulation. This Article shall not require admission of the Reserve's class or make its subscription conditional on such admission."

```
Candidate Article 5(8)                     Prospectus Regulation (EU) 2017/1129, Art. 3(1)
"The issuance of the citizens' capital     "Without prejudice to Article 1(4),
warrant and the issuance, offer and        securities shall only be offered to the
subscription of shares pursuant to this    public in the Union after prior publication
Article shall not constitute an offer of   of a prospectus..."
securities to the public for the purposes
of Regulation (EU) 2017/1129..."
```
* **Severity:** `must-derogate` (Properly cured).
* **Minimal cure:** None; the statutory carve-out for subscription combined with preservation of ordinary admission rules is clean.

---

#### B. MiFID II / AIFMD Status of the Reserve
* **Directives engaged:** Directive 2014/65/EU (MiFID II), Directive 2011/61/EU (AIFMD), Directive (EU) 2016/2341 (IORP II).
* **Candidate draft analysis:**
  Article 8(7) explicitly carves out the Reserve from investment firm, AIF/AIFM, and IORP status:
  *"The Reserve shall not be considered an investment firm within the meaning of Directive 2014/65/EU, an alternative investment fund or an alternative investment fund manager within the meaning of Directive 2011/61/EU, or an institution for occupational retirement provision within the meaning of Directive (EU) 2016/2341."*
* **Severity:** `drafting-only` (Precautionary sectoral carve-out; verified as sound).

---

### 3. IORP II (Directive (EU) 2016/2341) and PEPP (Regulation (EU) 2019/1238)

#### A. Exclusivity-of-Purpose Carve-out for IORPs
* **IORP II (Directive (EU) 2016/2341), Article 7:**
  Article 7 mandates that Member States require IORPs to limit their activities to retirement-benefit related operations and activities arising therefrom.
* **Candidate draft analysis:**
  Article 11(1) contains an explicit, specific derogation:
  *"By way of derogation from Article 7 of Directive (EU) 2016/2341, an institution designated as a national vehicle may carry out the account administration and distribution activities provided for in this Regulation."*
  Article 11(9) reinforces structural integrity by mandating that designated institutions segregate assets, liabilities, accounts, and administrative costs from occupational pension schemes.

```
Candidate Article 11(1)                    Directive (EU) 2016/2341 (IORP II), Article 7
"By way of derogation from Article 7 of    "Member States shall require institutions
Directive (EU) 2016/2341, an institution   operating within their territories to
designated as a national vehicle may       limit their activities to retirement-benefit
carry out the account administration and   related operations and activities arising
distribution activities..."                therefrom."
```
* **Severity:** `must-derogate` (Properly cured).
* **Minimal cure:** None required; exact article derogation and strict ring-fencing in Art. 11(9) protect pension solvency without reopening national pension acts.

---

#### B. PEPP Ring-Fencing (Regulation (EU) 2019/1238)
* **Candidate draft analysis:**
  Article 11(1) states: *"A provider within the meaning of Regulation (EU) 2019/1238 designated as a national vehicle shall maintain holders' accounts separately from any product governed by that Regulation, and the requirements of that Regulation shall not apply to those accounts."*
  Article 11(9) mandates competent authority supervision over asset and cost segregation.
* **Severity:** `drafting-only` (Clear boundary line drawn).

---

### 4. DMA (Regulation (EU) 2022/1925) Architecture Comparison

The candidate draft borrows the quantitative presumption and designation framework of the Digital Markets Act (DMA). Below is the divergence analysis:

| DMA Architecture Element | Candidate Draft Counterpart | Divergence | Assessment |
|---|---|---|---|
| **Qualitative test (Art. 3(1))** | Article 3(1)(a)–(c) | Focuses on automated cognitive services and labour decoupling rather than core platform gateways. | **Deliberate:** Tailored to automation economics. |
| **Quantitative presumption (Art. 3(2))** | Article 3(2)(a)–(c) | Uses EUR 7.5B Union turnover or EUR 75B FMV + 3 MS; adds FMV $\ge 80\times$ labour compensation. Requires 2 financial years instead of DMA's 3 financial years (DMA Art. 3(2)(c)). | **Deliberate:** Adapted for fast-moving AI labs and audited payroll data. |
| **Notification duty (Art. 3(3))** | Article 3(3) | 2 months from meeting thresholds. Identical timeline. | **Aligned.** |
| **Designation decision (Art. 3(4))** | Article 3(4) | 45 working days. Identical timeline. | **Aligned.** |
| **Rebuttal mechanism (Art. 3(5))** | Article 3(5) | "Sufficiently substantiated arguments", "manifestly call the presumption into question", market-definition arguments excluded. | **Aligned.** |
| **Market investigation (Art. 17 / Art. 3(8))** | Article 4(1) / Article 3(6) | 12-month limit for below-threshold designation. | **Aligned.** |
| **Review cycle (Art. 4(2))** | Article 4(2) | At least every 3 years or on request. | **Aligned.** |
| **Durability & Repeal (Art. 4(3))** | Article 4(3) | Repeal requires 2 consecutive years of not meeting Art. 3(1); warrant lapses 5 years post-repeal if uncrystallised. DMA has no warrant lapse. | **Deliberate:** Protects proportionality by avoiding indefinite dormant encumbrances. |
| **Scope of addressee** | Article 3(10) | Identifies "legal issuer" and consolidated ownership perimeter rather than designating a Core Platform Service (CPS). | **Deliberate:** Necessary for corporate equity issuance vs behavioral conduct remedies. |

* **Severity:** No blocking collisions; all structural divergences from DMA are deliberate adaptations to corporate ownership rather than sloppy transcription.

---

### 5. State Aid (Articles 106–107 TFEU) and Free Movement of Capital (Article 63 TFEU)

#### A. State Aid and National Vehicle Compensation (Articles 106(2) and 107(1) TFEU)
* **Provisions engaged:** Article 11(3), (4), and (10).
* **Candidate draft analysis:**
  * The Reserve itself receives no state budget funding (Article 8(2)–(3)) and confers no selective advantage on covered undertakings (which bear dilution) or uncovered undertakings (which are subject to general legal rules).
  * Member State compensation to national vehicles for administration costs exceeding the 0.3% cap (Article 11(3)–(4)) is explicitly conditioned in Article 11(10) on the *Altmark* criteria: defined public-service tasks, objective cost parameters, overcompensation recovery, and compliance with Union State aid notification/standstill rules.

```
Candidate Article 11(10)                   TFEU Article 106(2) / Altmark Case Law [*press release*]
"Before awarding compensation under        Compensation for public service obligations
paragraph 3 or 4, a Member State shall     must satisfy defined parameters, actual cost
specify the public-service tasks,          benchmarks, and avoid overcompensation to
duration, calculation parameters,          exclude State aid under Article 107(1).
permitted costs and recovery of
overcompensation. It shall comply with
applicable Union State aid rules..."
```
* **Severity:** `drafting-only` (State aid compliance is explicitly codified).

---

#### B. Free Movement of Capital (Article 63 TFEU) and Special Public Shareholdings
* **Jurisprudence engaged:** *Commission v Germany* (C-112/05, Volkswagen golden shares) and related Article 63 case law.
* **Candidate draft analysis:**
  * Golden-share rulings prohibit disproportionate public control, vetoes, voting caps, and golden shares deterring investment.
  * The candidate draft creates a strictly non-voting, passive economic holding:
    * Article 5(4)(a) & Article 9(1)(a): strictly non-voting shares.
    * Article 9(1)(b): no board representation.
    * Article 9(1)(c): prohibition against giving management instructions.
    * Article 9(1)(e)–(g): prohibitions against leveraging or non-hedging derivatives.
  * Recital 23 expressly addresses Article 63 TFEU, establishing that mandatory passive minority equity participation without control rights avoids the deterrent governance distortions struck down in the golden-share line.

```
Candidate Article 9(1)(a)-(c)              CJEU Article 63 Case Law (C-112/05)
"The Reserve shall not:                    State measures conferring special voting
(a) exercise... any voting right...;       or veto powers disproportionate to capital
(b) seek or accept representation in       held restrict the free movement of capital.
the... management or supervisory bodies...;
(c) give instructions... to any
undertaking in which it holds an interest;"
```
* **Severity:** `drafting-only` (Compatible with Article 63 TFEU).

---

### Conclusion & Diagnostic Summary

The candidate draft under `proposals/2026-09-07-substantive-closure/candidate/` successfully resolves the primary acquis collisions identified in prior iterations:
1. Directive (EU) 2017/1132 capital maintenance, pre-emption, and non-cash valuation rules are expressly derogated from in Article 5(7).
2. Regulation (EU) 2017/1129 public-offer duties are cleanly exempted in Article 5(8) without creating a legally defective admission-to-trading exemption.
3. Directive (EU) 2016/2341 (IORP II) Article 7 is specifically derogated from in Article 11(1), accompanied by strict ring-fencing under Article 11(9).
4. DMA architectural adaptations are coherent and deliberate.
5. State aid (*Altmark*) and Article 63 TFEU (golden shares) friction points are addressed through statutory passivity and explicit SGEI parameters.

Minor drafting enhancements (such as explicit reference to SRD II in Article 5(7)) are non-blocking. On acquis coherence, the candidate package is sound.

VERDICT: PUBLISH

## Assistant disposition for editorial review

The model output above is preserved verbatim. The bundle hash identifies
the exact source snapshot; the commit records the later integrated candidate.
See [closure review status](../../proposals/2026-09-07-substantive-closure/REVIEW-STATUS.md)
for accepted repairs, qualified findings and remaining decisions. No
institutional opinion, adoption or final editorial approval is implied.
