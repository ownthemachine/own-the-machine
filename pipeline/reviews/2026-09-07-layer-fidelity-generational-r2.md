---
gate: layer-fidelity
target: generational repair candidate and separate proposals
commit: 7b33a2d
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T07:26:59+00:00 · tokens in=265047 out=3068
> Prompt: layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `74300e532e405b0c6d37e434ae5145fa476e4fea7310dac550437442c63be301`
> Prompt SHA-256: `b7977305d075dbb668b4b30e5dcbcad48837ddf5534df598194a22a33c660f40`

### Drift Detection Analysis

#### 1. Overclaim Assessment (DC-14, DC-23, Timing & Protections)
* **DC-14 (Compounding & Starting Flow):**
  * *Operative/Memorandum Layer:* Article 8(4), Article 10(6), and Annex II mandate that distributions derive solely from realised income in excess of real capital preservation, smoothing over trailing years and subject to de minimis cost thresholds. Objection 14/15 notes that initial distributions will be modest or zero.
  * *Plain-Language Layer:* `faq.md`, `brief.md`, `plain/article-10.md`, and `simulator/SPEC.md` consistently state that payments start small, can be zero, depend on fund income after costs/retentions, and do not represent guaranteed immediate wages or income replacement.
* **DC-23 (Raid Resistance as Friction):**
  * *Operative/Memorandum Layer:* Article 12 drafting notes and Counter-Arguments Objection 9/20 explicitly state that ordinary secondary legislation cannot formally bind a determined future sovereign legislature; the goal is creating high legal and procedural friction.
  * *Plain-Language Layer:* `brief.md`, `faq.md`, and `plain/article-12.md` state: *"Legal safeguards resist diversion but cannot prevent all future amendments."* No absolute invulnerability is promised.

#### 2. Underdisclosure Assessment (Burdens, Limits, Alienability)
* **Non-voting / Governance:** Articles 5(4)(a) and 9(1) establish the strictly non-voting status of the Reserve's holdings. This is disclosed throughout `plain/article-5.md`, `plain/article-9.md`, `faq.md`, `brief.md`, and `press.md`.
* **Inalienability & Lock-up:** Article 10(5) prohibits assignment, pledge, attachment, surrender, or cash redemption of entitlements. This restriction is faithfully reflected across all five language sets of `plain/article-10.md`, `faq.md`, and `brief.md`.
* **Crystallisation & Payout Triggers:** The three crystallisation triggers (liquidity event, shareholder extraction >25%, and 7-year backstop) under Article 5(3) are accurately explained in `brief.md`, `faq.md`, and `plain/article-5.md`.

#### 3. Term Drift Assessment
* Defined terms from Article 2 (*covered undertaking*, *citizens' capital warrant*, *Reserve*, *liquidity event*, *shareholder extraction*, *automated assets*) maintain identical extensions and conceptual boundaries across the enacting terms, explanatory memorandum, and plain summaries.
* The separation between adopted candidate text in `regulation/` and exploratory alternative models in `proposals/2026-09-07-generational-repairs/` is strictly maintained.

No drift, overclaim, or underdisclosure detected.

VERDICT: PUBLISH

## Assistant disposition prepared for the final editor

Verbatim model output ends above. The exact reviewed working-tree snapshot
is identified by the bundle hash, not the later bookkeeping commit.
See [review status and dispositions](../../proposals/2026-09-07-generational-repairs/REVIEW-STATUS.md).
No institutional opinion or final editorial approval is implied.
