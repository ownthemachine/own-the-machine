---
gate: layer-fidelity
target: website release, corrected public explanations
commit: 9f02181
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T12:14:59+00:00 · tokens in=142015 out=1955
> Prompt: layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `6cd2fe1e54d470d22b5b71ea116583bea65a110e5aaeadbbdf4a525b6345ea6c`
> Prompt SHA-256: `3d21a9d607dd5030d825934abb594ef990c3202d96663e0ccaf0a65d6982e3b4`

### 1. Verification of Target Repairs & Checks

#### A. Explanatory Memorandum: Consultation Status (EN & FR)
* **English (`explanatory-memorandum.md`, Section 3.2):**
  > "The ECI Forum provided independent, non-binding registration advice on 27 August 2026. The reply was acknowledged that day and the exchange is closed; it does not constitute approval of the proposed law."
* **French (`explanatory-memorandum.fr.md`, Section 3.2):**
  > "Le Forum de l'ICE a fourni un avis indépendant et non contraignant sur l'enregistrement le 27 août 2026. Un accusé de réception a été envoyé le même jour et l'échange est clos ; cet avis ne constitue pas une approbation du texte proposé."
* **Assessment:** Both sentences accurately report the disposition of Sounding 1 from `EXTERNAL-REVIEWS.md`. They maintain strict fidelity to the closed exchange and avoid overclaiming institutional assent. The French translation is natural and idiomatic.

#### B. Sizing & Unvalidated Valuation Notices
* **Site Screens (`Objections.astro`, `Explanatory.astro`, `Simulator.astro`):**
  All three templates now render `<p class="sizing-note">{t.reviewNotice.sizing}</p>` backed by scoped styles (`.sizing-note { border-left: 3px solid var(--serial-red); ... }`).
* **Global Working Draft Notice (`Base.astro`):**
  The `.review-notice` class is defined in the primary component `<style>` block.
* **Download Artefacts (`make-artefacts.mjs`):**
  PDF and EPUB covers carry explicit warnings that historical memorandum sizing figures remain unvalidated against the current payroll-ratio designation criteria.

#### C. Plain Layer Fidelity (DC-14, DC-23, Underdisclosure & Term Drift)
* **DC-14 (Compounding from small, income dependence):** Site copy (`faq.md`, `brief.md`, `plain/article-10.md`, `simulator.ts`, and i18n dictionaries) consistently qualifies distributions as contingent on positive distributable income exceeding payment costs ($10\times$ execution threshold), clarifies that early payouts may be zero, and presents the generational capital target as an unguaranteed objective rather than an immediate wage replacement.
* **DC-23 (Raid resistance as friction):** Plain explanations (`plain/article-12.md`, `home.col2`, `brief.md`, `faq.md`) describe protections as statutory legal barriers and friction against diversion, explicitly disclaiming that future sovereign amendments are impossible to enact.
* **Underdisclosure & Non-voting/Lock-up:** Non-voting equity status, non-transferability, lack of cash redemption, and the requirement of registration with national vehicles are disclosed across the FAQ, Brief, and plain-article summaries.
* **Grammar & Consistency:** English simulator assumption strings and metadata dictionaries read naturally with correct subject-verb agreements and terminology.

---

VERDICT: PUBLISH

## Assistant disposition for editorial review

Raw output above is preserved verbatim. See [website release record](../../campaign/SITE-RELEASE-2026-09-07.md) for accepted fixes, qualified findings and validation. The verdict concerns publication of corrected explanations of a working draft; substantive legal findings remain open. The bundle identifies the exact site snapshot and the commit identifies its source-law baseline. Final editorial disposition remains separate.
