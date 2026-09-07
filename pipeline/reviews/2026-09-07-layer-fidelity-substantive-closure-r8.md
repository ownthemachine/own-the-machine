---
gate: layer-fidelity
target: proposals/2026-09-07-substantive-closure/candidate
commit: 146ff17
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T15:00:31+00:00 · tokens in=133658 out=9012
> Prompt: layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `a2c84f196ecea16bcc5ac53bd45a2118c21a7c3b7728e2ad51be166bd855790d`
> Prompt SHA-256: `b7977305d075dbb668b4b30e5dcbcad48837ddf5534df598194a22a33c660f40`

### 1. OVERCLAIM: Day-One Application of Conduct and Protection Rules

* **Enacting Terms (Article 18(2)):**
  > "It shall apply from [OP: please insert the date 18 months after the date of entry into force of this Regulation], with the exception of Articles 3, 4, 6(1), 8(1) and (9) to (17), 11(1), (9) and (11), 15 and 16 and Article 17(1), which shall apply from the date of entry into force for preparatory administration."
* **Plain Layer (`candidate/PLAIN.md`):**
  > "Five independent board members and an accountable executive would oversee custody, audit and an automated operation, without directing investee companies... Protection rules would bind the bodies administering this Regulation."
* **Reader Harm:** The plain text promises that the Reserve's statutory passivity (no direction/voting) and asset protection rules bind the administering bodies from creation. In the enacting terms, however, Article 18(2) establishes the Reserve and its board on day one (Article 8(1), (9)–(17)) but omits Article 9 (prohibited conduct) and Article 12 (protection against diversion) from the early-application list, leaving an 18-month preparatory window where these protections are not legally in force.
* **Minimal Fix:** Fix the **enacting terms** (`candidate/regulation/articles/18-final.md`, Article 18(2)) to include Articles 9 and 12 in the list of provisions taking effect from the date of entry into force.

---

### 2. UNDERDISCLOSURE: Priority of Arm's-Length Rescue Financing

* **Enacting Terms (Article 5(10), Subparagraph 2):**
  > "The first subparagraph shall not apply to an issuance of shares or other instruments for new consideration in money or money's worth, at arm's length, to persons who are not members of the same group as the covered undertaking, do not control it, are not connected with it and are not acting in concert with any person who controls it, where at the time of the issuance the covered undertaking is in a likelihood of insolvency within the meaning of Directive (EU) 2019/1023 or the issuance is necessary to comply with a prudential requirement under Union law, and only to the extent of the new consideration provided."
* **Plain Layer (`candidate/PLAIN.md`):**
  > "At the first statutory trigger, the Reserve would subscribe at nominal value for new non-voting shares calculated from 3% of pre-subscription capital. That base includes existing value, not just appreciation after designation."
* **Reader Harm:** Citizens and signers are not informed that the statutory anti-subordination protection (ranking equally with the most favourable post-designation share class under Article 5(4)(b)) contains an express statutory carve-out: genuine arm's-length rescue financing raised during insolvency distress or prudential requirement compliance can legally subordinate or dilute the Reserve's rank.
* **Minimal Fix:** Fix the **plain layer** (`candidate/PLAIN.md`) by adding a concise sentence disclosing that new third-party rescue financing raised in a likelihood of insolvency or for prudential compliance can take priority over the Reserve's position to the extent of new funds provided.

---

### 3. UNDERDISCLOSURE / TERM DRIFT: Cash Requirement for "Nominal Value" Subscription

* **Enacting Terms (Article 5(5) and Article 9(1)(e)):**
  > "The covered undertaking shall execute the subscription within 20 working days of the delivery of the valuation referred to in Article 6, and the Reserve shall pay up the shares in full in cash at their nominal value upon execution."
  > "The Reserve shall not: ... (e) borrow, save for temporary liquidity purposes not exceeding 2 % of the value of its assets and save for the payment of subscription amounts under Article 5(5), which borrowing shall be repaid from the first realised income of the Reserve;"
* **Plain Layer (`candidate/PLAIN.md`):**
  > "At the first statutory trigger, the Reserve would subscribe at nominal value for new non-voting shares calculated from 3% of pre-subscription capital... Initial services still need actual financing."
* **Reader Harm:** Describing the mechanism simply as "subscribing at nominal value" without explaining that the Reserve must pay up the shares in full in cash on execution obscures that the Reserve must take on subscription debt liabilities before any dividend income exists. If no lender is found to advance nominal capital cash, statutory execution fails.
* **Minimal Fix:** Fix the **plain layer** (`candidate/PLAIN.md`) to state explicitly that nominal subscription requires immediate cash payment by the Reserve, financed through statutory borrowing repaid from subsequent income.

---

VERDICT: REVISE
