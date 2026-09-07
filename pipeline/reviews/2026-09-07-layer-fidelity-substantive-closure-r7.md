---
gate: layer-fidelity
target: proposals/2026-09-07-substantive-closure/candidate
commit: 97a0f2a
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T14:54:32+00:00 · tokens in=132174 out=5111
> Prompt: layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `afd98714a0b0aab6fec36914169bf4e44acbb443cf974187f2fad4c27bdbf0ea`
> Prompt SHA-256: `b7977305d075dbb668b4b30e5dcbcad48837ddf5534df598194a22a33c660f40`

### Finding 1: UNDERDISCLOSURE — Five-Year Warrant Lapse Post-Repeal

* **Candidate Regulation (Article 4(3)):**
  > "Repeal shall not affect a citizens' capital warrant already arisen, save that a warrant shall lapse five years after repeal if it has not crystallised by that date."
* **Plain Layer (`candidate/PLAIN.md`):**
  > *(Silent on warrant lapse following designation repeal)*
* **Reader Harm:** 
  A citizen or covered undertaking reading the plain summary is led to believe that once a warrant arises upon designation, the Reserve's contingent entitlement to 3% equity remains permanently intact until a trigger occurs. They are not informed that if an undertaking's designation is repealed, an uncrystallised warrant is subject to complete extinction after a 5-year lapse window.
* **Minimal Fix (Plain Layer):**
  Add a brief sentence to `candidate/PLAIN.md` clarifying that if a company's designation is repealed before a trigger occurs, an uncrystallised warrant lapses after five years.

---

### Finding 2: UNDERDISCLOSURE — Termination of Accrual on Loss of EU Citizenship

* **Candidate Regulation (Article 10(4)):**
  > "Death or loss of Union citizenship shall end accrual for subsequent days and shall not cancel prior accrual."
* **Plain Layer (`candidate/PLAIN.md`):**
  > "Every adult EU citizen would accrue the same amount for the same eligible days, with no income, wealth or employment test... Money accrued while eligible survives death and late registration."
* **Reader Harm:** 
  While `PLAIN.md` mentions that accrual is tied to eligibility and survives death, it omits the explicit rule that renouncing or losing EU citizenship terminates daily accrual for all subsequent days (while locking in past accruals). A reader experiencing cross-border or nationality changes would not know the exact boundary condition for future accruals.
* **Minimal Fix (Plain Layer):**
  Update the sentence in `candidate/PLAIN.md`: "Money accrued while eligible survives death, loss of Union citizenship and late registration; subsequent daily accrual ends if citizenship is lost."

---

### Finding 3: UNDERDISCLOSURE / BURDEN — Restructuring Obligation for Entities Without Share Capital

* **Candidate Regulation (Article 3(11)):**
  > "Where a legal issuer has no share capital, it shall procure equity participation through a corporate holding entity representing the same residual economic interest... The use of a holding entity shall not restart the statutory clock or convert the obligation into a payment charge."
* **Plain Layer (`candidate/PLAIN.md`):**
  > "A covered company's warrant would arise when designation takes effect. At the first statutory trigger, the Reserve would subscribe at nominal value for new non-voting shares calculated from 3% of pre-subscription capital."
* **Reader Harm:** 
  Enterprises structured without ordinary share capital (e.g., partnerships, mutuals, or novel corporate forms) are given no notice in the plain layer that designation imposes a mandatory obligation to create or procure a corporate holding entity to deliver equivalent equity participation.
* **Minimal Fix (Plain Layer):**
  Add a note in `candidate/PLAIN.md` stating that covered entities without conventional shares must establish an equivalent corporate holding structure to issue the equity participation.

---

VERDICT: REVISE
