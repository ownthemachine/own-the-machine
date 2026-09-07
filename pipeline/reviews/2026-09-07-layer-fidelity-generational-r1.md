---
gate: layer-fidelity
target: generational repair candidate and separate proposals
commit: 7b33a2d
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T07:24:46+00:00 · tokens in=262994 out=4210
> Prompt: layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `72b15a0859641dbe5923c033a22fbb8651045c05d42fe90d7cd96a0b915efff4`
> Prompt SHA-256: `b7977305d075dbb668b4b30e5dcbcad48837ddf5534df598194a22a33c660f40`

### Finding 1: OVERCLAIM — Unconditional three-year payout promise in plain summary

- **Operative text (Article 10(6)):**
  > "The Reserve shall declare a distribution in each calendar year in which the distributable amount would provide each holder with not less than ten times the average cost of executing one payment to a holder, calculated in accordance with Annex II, and in any event not less often than once in every third calendar year in which the distributable amount is greater than zero."

- **Plain language layer (`own-the-machine-site/content/en/plain/article-10.md`, L0 line):**
  > "L0: Gives every adult EU citizen an equal automatic share of the Reserve's payouts, which cannot be sold, seized or signed away; but the law does not promise a payout every year, only at least once every three years."

- **Reader harm:** A reader relying on the L0 summary is led to believe there is a guaranteed minimum payout cadence of at least once every three years under all circumstances. In reality, Article 10(6) conditions the three-year backstop strictly on the presence of positive distributable income (`in which the distributable amount is greater than zero`). If the Reserve has zero or negative distributable income across multiple years, no distribution occurs.

- **Minimal fix (Plain layer):** Amend the L0 summary in `own-the-machine-site/content/en/plain/article-10.md` to qualify the three-year backstop:
  `L0: Gives every adult EU citizen an equal automatic share of the Reserve's payouts, which cannot be sold, seized or signed away; but the law does not promise a payout every year, only at least once in every three years with positive distributable income.`

---

VERDICT: REVISE

## Assistant disposition prepared for the final editor

Verbatim model output ends above. The exact reviewed working-tree snapshot
is identified by the bundle hash, not the later bookkeeping commit.
See [review status and dispositions](../../proposals/2026-09-07-generational-repairs/REVIEW-STATUS.md).
No institutional opinion or final editorial approval is implied.
