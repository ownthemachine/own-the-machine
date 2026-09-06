---
gate: legal-form
target: campaign and website claim corrections
commit: ed351bc
verdict: PUBLISH
disposition: superseded-with-fixes
date: 2026-09-06
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T19:30:21+00:00 · tokens in=104132 out=2413
> Prompt: otm-legal-form-final.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `32f9b8ae499c954f6238c26cceb328374eeff0e6746f3bd78fe03878f1b3357a`
> Prompt SHA-256: `ad366f89bfc751dcf3c5bf141092afcce6550c9756b51ed40d17b3a635555f6e`

### Review of Target Bundle (Prose Corrections, Registration Text, Campaign Guidance, Tooling)

#### 1. Scope & Register Assessment
The changed target materials comprise explanatory site content (`brief.md`, `faq.md`, `join.md`, `sign.md`, `press.md`, `about.md`, `contribute.md`), the UI strings (`en.mjs`), the registration text (`campaign/REGISTRATION-TEXT.md`), campaign operating documents (`campaign/DISTRIBUTION.md`, `campaign/GATES.md`, `campaign/REVIEW-AND-LAUNCH-PLAN-2026-09-06.md`), the simulator script (`simulator.ts`), and review tooling (`review.sh`, `README.md`, `.env.example`, `tests/test_review.py`).
- Public and explanatory materials are drafted in their proper communicative register without enacting commands or impermissible normative drafting.
- ECI statutory parameters match Regulation (EU) 2019/788 and official Commission guidance (1 million valid statements; minimum thresholds in $\ge 7$ Member States; Belgium threshold set at 15,840; organizing group of 7 EU citizens resident in 7 distinct Member States; 12-month collection window starting within 6 months of registration; COCS and paper forms; institutional response without legislative compulsion).
- Technical and tooling configurations align with verified metadata (Requesty EU routing, `vertex/claude-fable-5.1@eu` 30-day retention exception for public non-sensitive inputs, no training, Astra non-substitution).

#### 2. Consistency & Drafting Form in Changed Prose
- **Substantive alignment:** Descriptions of the 3 % citizens' capital warrant accurately reflect the three alternative crystallisation routes of Article 5 (first liquidity event, shareholder extraction $>25\,\%$, and the 7-year long-stop), nominal cash payment upon subscription by the Reserve, the non-voting equity structure, and independent valuation.
- **Budgetary & fiscal caveats:** Explicitly clarifies that while the warrant is settled in equity and Reserve assets remain segregated from public budgets, regulatory/fines treatment accrues to the Union budget and the fiscal characterisation under Article 114(2) TFEU remains legally contested.
- **House style:** British English spelling is used consistently across English prose; no em-dashes (`—`) are present in the target files; numbers adhere to standard decimal and thousand conventions.

---

### Pre-existing Normative Issues (Unchanged Reference Context)
*Reported separately as pre-existing in non-target reference texts; not introduced by this bundle:*
1. **Recital 33 EDPS Consultation Date Placeholder:**
   - *Quote:* `"The European Data Protection Supervisor was consulted in accordance with Article 42(1) of Regulation (EU) 2018/1725 of the European Parliament and of the Council and delivered an opinion on [date]."` (`regulation/recitals.md`).
   - *Rule:* Recitals in adopted acts require fixed dates; placeholder is standard prior to formal EDPS referral.
2. **Article 18(2) Publication Date Placeholder:**
   - *Quote:* `"It shall apply from [OP: please insert the date 18 months after the date of entry into force of this Regulation]..."` (`regulation/articles/18-final.md`).
   - *Rule:* Standard Publications Office instruction marker in draft instruments.

---

VERDICT: PUBLISH

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
