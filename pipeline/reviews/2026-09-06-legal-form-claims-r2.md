---
gate: legal-form
target: campaign and website claim corrections
commit: ed351bc
verdict: REVISE
disposition: superseded-with-fixes
date: 2026-09-06
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-06T18:06:54+00:00 · tokens in=95002 out=3940
> Prompt: otm-legal-form-claims.md · Verbatim model output below — do not edit.

> Bundle SHA-256: `d1e161a1137c9258590ca4e0f185db72bc1322b681c6df091f58c18f412a1177`
> Prompt SHA-256: `632d8fae783776e43c4b4854c668d9227ed5acb062b613503e5a535c413348f4`

### Review of Changed Package (Explanatory Copy, Registration Text, Campaign Guidance, Tooling)

#### 1. Scope & Register Assessment
The changed bundle comprises public explanatory content (`brief.md`, `faq.md`, `join.md`, `sign.md`, `press.md`, `about.md`, `contribute.md`), localization dictionary strings (`en.mjs`), simulator logic/labels (`simulator.ts`), campaign documentation (`REGISTRATION-TEXT.md`, `DISTRIBUTION.md`, `REVIEW-AND-LAUNCH-PLAN-2026-09-06.md`), and review tooling (`review.sh`, `README.md`, `.env.example`, `test_review.py`). Evaluated in their appropriate registers, the explanatory changes accurately reflect the underlying legal text (Article 3 designation presumption & investigation path; Article 5 crystallisation triggers including shareholder extraction and the 7-year backstop; Article 8 non-fiscal segregation; Article 10 universal entitlement; and Article 12 raid-resistance friction).

---

### Findings (In-Scope Package)

#### Finding 1: House Style — Disallowed Em-Dash in Review Tooling Output Template
* **Verbatim Quote:**
  ```python
  hdr = (f"# Review\n\n> Reviewer: `{sys.argv[3]}` · {sys.argv[5]}\n"
         f"> {datetime.datetime.now(datetime.timezone.utc).isoformat(timespec='seconds')} · "
         f"tokens in={u.get('prompt_tokens','?')} out={u.get('completion_tokens','?')}\n"
         f"> Prompt: {os.path.basename(sys.argv[4])} · Verbatim model output below — do not edit.\n\n")
  ```
  *(from `own-the-machine-tools/review.sh`)*
* **Rule Breached:**
  DRAFTING-RULES.md, Rule 9 (House Style: "No em-dashes; British English in prose").
* **Compliant Redraft:**
  ```python
  hdr = (f"# Review\n\n> Reviewer: `{sys.argv[3]}` · {sys.argv[5]}\n"
         f"> {datetime.datetime.now(datetime.timezone.utc).isoformat(timespec='seconds')} · "
         f"tokens in={u.get('prompt_tokens','?')} out={u.get('completion_tokens','?')}\n"
         f"> Prompt: {os.path.basename(sys.argv[4])} · Verbatim model output below; do not edit.\n\n")
  ```

---

### Pre-Existing Normative Issues (Reference Context Only)
The following pre-existing items in the unchanged legal text and recitals are recorded for completeness and do not constitute newly introduced defects in this package:

1. **Recital (33) Date Placeholder:**
   * *Quote:* `...delivered an opinion on [date].`
   * *Status:* Pre-existing drafting placeholder awaiting formal EDPS consultation date prior to adoption.
2. **Article 18(2) Publication Placeholder:**
   * *Quote:* `[OP: please insert the date 18 months after the date of entry into force of this Regulation]`
   * *Status:* Standard pre-enactment placeholder for the Publications Office.

---

VERDICT: REVISE

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
