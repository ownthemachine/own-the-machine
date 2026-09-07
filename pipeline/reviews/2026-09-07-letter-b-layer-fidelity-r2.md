---
gate: layer-fidelity
target: campaign/LETTER-B-2026-09-07.md
commit: 6f7acf4
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T11:24:57+00:00 · tokens in=90124 out=2191
> Prompt: letter-b-layer-fidelity.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `26ad22fd4fccabbfad5090b57550bf51b94b7ba28e81e52759749c89e9f7979f`
> Prompt SHA-256: `c0886c5973cc6a3fd4ca34ec8a04c743df06990d44af3f5cb7112b3dcecb6a0d`

### Analysis of `campaign/LETTER-B-2026-09-07.md`

#### 1. Overclaim Check
- **Plain-language text (Letter B & Questions):** *"Citizen payments would depend on the income the reserve actually realises; neither an amount nor an annual increase is guaranteed."* / *"The size of the stake, legal basis and compulsory equity mechanism still need justification."* / *"This was advice on registration, not approval of the proposed law."*
- **Operative / Memorandum baseline:** Aligns with Article 1(2), Article 8(4), Article 10(6), Annex II, DC-14 (compounding from small, no income guarantee), and DC-23 (no absolute guarantees). The letter explicitly disclaims legal approval or guaranteed distributions.
- **Finding:** No overclaim detected.

#### 2. Underdisclosure Check
- **Plain-language text (Letter B & Questions):** Notes the core constraints relevant to an introductory outreach email seeking advice: non-voting status (*"holding non-voting equity"* / *"participations sans droit de vote"*), contingent income dependence, and contested legal basis/mechanisms.
- **Operative / Memorandum baseline:** Detailed operational mechanics (e.g. 10x payment execution cost floor, 5-year lapse upon repealed designation, PEPP/IORP ringfencing) are properly reserved for the published draft and follow-up technical materials rather than overloaded into a short introductory letter.
- **Finding:** No underdisclosure relative to the correspondence genre and scope.

#### 3. Term Drift & Bilingual Fidelity Check
- **English source vs. French sending text:**
  - *"non-voting equity in qualifying undertakings"* $\leftrightarrow$ *"participations sans droit de vote dans les entreprises répondant aux critères retenus"*
  - *"income the reserve actually realises"* $\leftrightarrow$ *"revenus effectivement perçus par la réserve"*
  - *"compulsory equity mechanism"* $\leftrightarrow$ *"mécanisme de participation obligatoire au capital"*
- **Finding:** Terminology is consistent with the enacting terms (Articles 2, 5, 8, 10) and memorandum across both languages.

---

VERDICT: PUBLISH

## Assistant disposition for editorial review

Raw output above is preserved verbatim. The bundle hash identifies the exact
reviewed snapshot. See [letter status](../../campaign/LETTER-B-2026-09-07-STATUS.md)
for findings and conditions. This is correspondence review, not clearance of
the law or permission to send. Final editorial disposition remains pending.
