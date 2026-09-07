---
gate: layer-fidelity
target: proposals/2026-09-07-substantive-closure/candidate
commit: 0338506
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T09:15:46+00:00 · tokens in=122553 out=5018
> Prompt: layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `db037b182cdd21ffde0241690b1a956a49513b5a5faecc6e3a872056b518792d`
> Prompt SHA-256: `b7977305d075dbb668b4b30e5dcbcad48837ddf5534df598194a22a33c660f40`

### Drift Analysis: Layer Fidelity Review

#### 1. Overclaim Analysis
* **DC-14 (Compounding from small / payout realism):**
  * *Enacting Terms (Annex II, Art. 8(4), Art. 10(6)):* Allocations require realised cash income strictly exceeding debt service, administrative expenses, and capital preservation benchmarks. Zero-income or loss years yield zero allocations.
  * *Plain Layer (`candidate/PLAIN.md`):* *"Payments depend on realised income after subscription debt, costs and capital preservation. Losses are recognised immediately. Capital can grow without a payment, and both can fall short of the policy's ambition... Neither capital preservation nor larger annual payments is guaranteed."*
  * *Finding:* Fully aligned. No early-year or guaranteed income is promised.
* **DC-23 (Raid resistance as friction, never impossibility):**
  * *Enacting Terms / Recitals (Recital 28, Art. 12):* Operative asset-lock and interpretive protections without claiming to bind future sovereign legislatures.
  * *Plain Layer (`candidate/PLAIN.md` & `candidate/MEMORANDUM.md`):* Explains institutional governance and asset segregation without promising unbreachable entrenchment.
  * *Finding:* Fully aligned.

#### 2. Underdisclosure Analysis
* **Lock-up & Inalienability:** Disclosed in `candidate/PLAIN.md` (*"Citizens could not sell or cash out their personal entitlement"*).
* **Non-Voting Status:** Disclosed in `candidate/PLAIN.md` (*"new non-voting shares"*, *"without directing investee companies"*).
* **Event-Dependence & Trigger Mechanism:** Disclosed in `candidate/PLAIN.md` (*"warrant would arise when designation takes effect"*, crystallising upon liquidity events, extraction >25%, or 7-year clock).
* **Vehicle Administration Fee & Registration Condition:** Disclosed in `candidate/PLAIN.md` (*"Receiving a payment requires registration with a designated national vehicle"*, vehicle fee cap at 0.3% annually).
* **Inheritability of Accrued Monetary Claims:** Disclosed in `candidate/PLAIN.md` (*"Money accrued while eligible survives death and late registration"*).
* *Finding:* No underdisclosures identified.

#### 3. Term Drift Analysis
* **Defined Terms:** Core statutory terms (`covered undertaking`, `citizens' capital warrant`, `Reserve`, `national vehicle`, `eligible day`, `allocation`, `distribution`, `shareholder extraction`) are used consistently across `candidate/regulation/`, `candidate/MEMORANDUM.md`, and `candidate/PLAIN.md`.
* **Flow vs. Claim Nuance:** The distinction between an un-cashed daily *allocation* (monetary claim) and an executed *distribution* (payment) under Articles 2(12), 2(17), and 10 is maintained faithfully in the plain layer without colloquial conflation.
* *Finding:* No term drift identified.

VERDICT: PUBLISH

## Assistant disposition for editorial review

The model output above is preserved verbatim. The bundle hash identifies
the exact source snapshot; the commit records the later integrated candidate.
See [closure review status](../../proposals/2026-09-07-substantive-closure/REVIEW-STATUS.md)
for accepted repairs, qualified findings and remaining decisions. No
institutional opinion, adoption or final editorial approval is implied.
