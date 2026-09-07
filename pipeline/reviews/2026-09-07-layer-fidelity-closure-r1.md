---
gate: layer-fidelity
target: proposals/2026-09-07-substantive-closure/candidate
commit: 0338506
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T09:08:32+00:00 · tokens in=122025 out=6513
> Prompt: layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `bfeb26dc2cacd4667b3a17719b41b08e40250236d97aedc83397b4ebc63c46dd`
> Prompt SHA-256: `b7977305d075dbb668b4b30e5dcbcad48837ddf5534df598194a22a33c660f40`

### Finding 1: UNDERDISCLOSURE — De Minimis Execution-Cost Payment Threshold

* **Articles layer (`candidate/regulation/articles/10-entitlement.md`, Article 10(6)):**
  > "The Reserve shall pay accumulated allocations in a year when the average amount due per payee is at least ten times the average execution cost under Annex II. It shall in any event pay no later than the third financial year with a positive new allocation since the previous payment."
* **Plain layer (`candidate/PLAIN.md`):**
  > "The backstop counts three years with positive new allocations, not three calendar years regardless of income."

* **Reader harm:** The plain layer mentions the three-positive-year backstop but completely omits the primary threshold rule: accumulated allocations will not be paid out in any given year unless the average balance per payee reaches at least ten times the average execution cost. Citizens reading the plain summary will not understand why distributions are withheld during positive-allocation years prior to the third year.
* **Minimal fix:** In `candidate/PLAIN.md`, add explicit disclosure that annual distributions are withheld and accumulated until the amount due reaches at least ten times the average execution cost per payee, or until three years with positive allocations have elapsed.
* **Layer to fix:** Plain layer (`candidate/PLAIN.md`).

---

### Finding 2: UNDERDISCLOSURE — National Vehicle Administrative Account Charges

* **Articles layer (`candidate/regulation/articles/11-national-vehicles.md`, Article 11(3)):**
  > "Charges levied by a national vehicle on holders shall not exceed the costs actually incurred in administering the accounts and in any event 0,3 % annually of the amounts administered."
* **Plain layer (`candidate/PLAIN.md`):**
  > "Payments depend on realised income after subscription debt, costs and capital preservation. ... Moving country changes payment administration, not ownership. Money accrued while eligible survives death and late registration. Money received is freely usable."

* **Reader harm:** The plain layer mentions fund-level costs ("subscription debt, costs and capital preservation") and notes that distributed money is freely usable, but conceals the individual account burden: national vehicles administering the accounts may deduct an annual administration fee of up to 0.3% of administered balances.
* **Minimal fix:** In `candidate/PLAIN.md`, explicitly disclose that national administering vehicles may levy an annual administration charge on holders capped at verifiable costs and at most 0.3% of administered amounts.
* **Layer to fix:** Plain layer (`candidate/PLAIN.md`).

---

### Finding 3: UNDERDISCLOSURE — Mandatory Registration with a National Vehicle for Payment

* **Articles layer (`candidate/regulation/articles/10-entitlement.md`, Articles 10(2) & 10(6)):**
  > "The entitlement shall arise by operation of law. It shall not be subject to any condition relating to income, wealth, employment, contribution history or any other personal circumstance, nor to any application, save registration for payment purposes with a national vehicle."
  > "The Reserve shall reserve funds for unregistered holders and disputed identities; registration or correction shall release amounts already due without a fresh cost threshold or waiting period."
* **Plain layer (`candidate/PLAIN.md`):**
  > "Every adult EU citizen would accrue the same amount for the same eligible days, with no income, wealth or employment test. Moving country changes payment administration, not ownership. ... National-record coordination is necessary; the prototype does not solve that identity system."

* **Reader harm:** A reader is told that accrual is automatic without an application or means test, but is not told that actually receiving disbursements requires active registration with a designated national vehicle (unregistered citizens have funds reserved but withheld).
* **Minimal fix:** In `candidate/PLAIN.md`, state clearly that while accrual occurs automatically by law, collecting payouts requires registration with a designated national vehicle.
* **Layer to fix:** Plain layer (`candidate/PLAIN.md`).

---

VERDICT: REVISE

## Assistant disposition for editorial review

The model output above is preserved verbatim. The bundle hash identifies
the exact source snapshot; the commit records the later integrated candidate.
See [closure review status](../../proposals/2026-09-07-substantive-closure/REVIEW-STATUS.md)
for accepted repairs, qualified findings and remaining decisions. No
institutional opinion, adoption or final editorial approval is implied.
