---
gate: hostile-counsel
target: website release, corrected public explanations
commit: 9f02181
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-07T12:18:21+00:00 · tokens in=214517 out=20798
> Prompt: hostile-counsel.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `6cd2fe1e54d470d22b5b71ea116583bea65a110e5aaeadbbdf4a525b6345ea6c`
> Prompt SHA-256: `8fc4569f47058a50d8446362ca595c1b888259593a2a431f6074ae625814d195`

**AI diagnostic. Not an opinion from any EU institution, and not advice from an instructed lawyer. Written to the release scope: changed website copy, locale dictionaries, about pages, global notice, sizing caveats, download cover notice, link pinning, and the two corrected Forum‑status sentences. Enacting terms are context, not the object of clearance.**

---

## A. Round‑2 items, checked against the supplied text

| Item | Verified state | Finding |
|---|---|---|
| EN memorandum §3.2 Forum sentence: "The ECI Forum provided independent, non‑binding registration advice on 27 August 2026. The reply was acknowledged that day and the exchange is closed; it does not constitute approval of the proposed law." | Present. Consistent with GATES.md ("ANSWERED 27 August"), substantive‑closure REVIEW‑STATUS ("The exchange is closed"), about.md ("The ECI Forum exchange is complete"). | **Faithful and natural.** One traceability gap: EXTERNAL‑REVIEWS.md review 4 records "thanks, no follow‑up question" but no date for the acknowledgement. The memorandum now asserts a date the review file does not carry. Add one dated line to review 4. Non‑blocking. |
| FR memorandum §3.2: "Un accusé de réception a été envoyé le même jour et l'échange est clos ; cet avis ne constitue pas une approbation du texte proposé." | Present. | **Faithful** ("le même jour" = "that day"); idiomatic French. |
| Global notice in Base.astro | `.review-notice` rule is in the component `<style>` block; `<aside>` rendered under `!law.registered`; link to /about. | Present and honest. Two design notes below (§C3). |
| Sizing note on Objections / Explanatory / Simulator | `<p class="sizing-note">{t.reviewNotice.sizing}</p>` present in all three screens with scoped CSS; Simulator places it between intro and controls, the other two after DraftNotice, above the body. | Present on all three added screens. Objections is the right screen: the EUR 20 trillion / EUR 8 400 figures live in objection 21. |
| Five `reviewNotice` dictionaries | EN/DE/FR/ES/NL all carry text + link + sizing. ES "1,4 billones" (10¹²) and FR "1 400 milliards" are the correct magnitudes for EN "1 400 billion". | Faithful. NL "memorie" for the memorandum is legally correct but differs from the NL chrome ("Toelichting"/"Memorandum"); cosmetic. DE `home.basis` "stützt sich auf" (relies on) is slightly stronger than EN "cites"; acceptable. |
| EN simulator strings | All labels, notes, sentences and the four assumptions read grammatically; `%YEAR%` substitution yields 2046 for the 20‑year lines and 2076 for the generation line, matching `low[19]/high[19]` and index 49 in simulator.ts. Model disclosures (constant positive return, no losses/costs, zero growth still adds cohorts, band ≠ confidence interval) match the code. | No overclaim of calibration. |
| PDF/EPUB cover notice | `reviewNotice` string rendered on PDF cover and EPUB cover chapter; content matches the site notice and explicitly says the Article 352 alternative is not the text reproduced. | Present. The PDF omits the explanatory memorandum, so the only sizing figures in the artefact are in objection 21, which the cover notice covers. |
| Source‑link pinning | `REPO = …/blob/${lawCommit}`; `replaceAll` of `blob/main/` and `commits/main` across law.json. | Works, with one semantic side‑effect (§C3). |

---

## B. The four tiers, split into pre‑existing (disclosed, outside this release) and changed‑copy

### 1. Registration kills

**Pre‑existing, disclosed, not this release.**
- *Fiscal characterisation by effect (Art. 114(2)).* Verbatim exposure: Art. 5(5) "the Reserve shall pay up the shares in full in cash at their nominal value"; Art. 8(3) "financed exclusively by the instruments referred to in Article 5". Attack: a compulsory transfer of 3 % of enterprise value for nominal consideration is a levy in kind; "similar effects by imposing financial contributions on undertakings" (Forum reply, verbatim). Defence: registration test is "manifestly outside" (Reg 2019/788 Art 6(3)(c)); Forum reply states registration turns on the goals "regardless of the mechanism"; Layer 0 objectives are an assessment‑and‑proposal ask. *Uncertain litigation/registration argument, not a text defect; the site says so in the FAQ, brief, press and objection 2.*
- *Treaty change in disguise.* Answered in REGISTRATION‑TEXT §3 ("No amendment of the Treaties is sought") and home.basis in all five languages. Copy is accurate.
- *Non‑severable drafting.* Severability memorandum exists; REGISTRATION‑TEXT §4 asks for partial registration under Art 6(4). Structural note: the annexed draft's preamble cites Art 114 alone while Chapters IV–VI are argued on 352 — REGISTRATION‑TEXT concedes "it is not a completed two‑act architecture". Disclosed.

**Changed copy.** None of the reviewed strings claims registrability, Commission approval or a settled basis. Forum sentence expressly disclaims approval. **No registration kill introduced.**

### 2. Litigation kills

**Pre‑existing, disclosed.** Charter 17 uncompensated dilution of healthy going concerns (objection 1 concedes "no decided case … on the right side of Article 17"); Art. 345 (answered via Essent); necessity limb resting on a chosen target (objection 21 concedes circularity); recital 18's "less intrusive than measures already upheld in the field of bank resolution" is the sentence hostile counsel will read beside objection 1's concession that BRRD's justification is unavailable. Equal treatment between covered and uncovered undertakings turns on the 80× ratio, which recital 7 defends. All outside this release.

**Changed copy.** No string asserts proportionality, compensation, or legal validity. FAQ "Whether EU law would nevertheless classify it as a fiscal measure is contested"; press "Its possible fiscal classification and proposed Treaty bases remain contested". Memorandum §2.1 EN citing "the legal‑form and legal‑basis gates of 6 September 2026 … confirmed" leans on AI gate output as confirmation of a drafting‑form point; prefer "the 6 September form review recorded that". Pre‑existing sentence; cosmetic authority overclaim, not a validity overclaim.

### 3. Structural kills

**Pre‑existing, tracked in the two REVIEW‑STATUS files (not this release).** Stated as the prompt asks, briefly:
- *Nominal‑value squeeze.* Before crystallisation, capitalise reserves and consolidate shares so nominal value per share approaches market value. Art. 5(5) obliges the Reserve to pay nominal value in cash; Art. 8(3) gives it no income yet; Art. 9(1)(e) permits borrowing only "repaid from the first realised income". Art. 3(8) disregards artificial reductions of fair market value, not increases of nominal value. Already listed at substantive‑closure REVIEW‑STATUS 3.5 ("nominal‑value manipulation"). Verified gap in the current articles.
- *Ratio dilution by genuine payroll.* Art. 3(8) third sentence protects "an increase in remuneration for genuine work"; Annex I point 3 averages two years. Route: acquire or merge a labour‑heavy, low‑value services group and pay it well; the acquisition limb ("one of the main effects") is the counter, but "one of the main effects" of any labour‑intensive acquisition is ratio dilution, so the Commission must litigate purpose. Tracked (REVIEW‑STATUS "Fable's employee‑equity example").
- *Pre‑designation preference stack.* Art. 5(4)(b) ranks the Reserve only with classes "created after the designation". Route: issue the participating preferred before notification (Art. 3(3) gives two months; Art. 17(1) gives two months from entry into force). DC‑36 protects this window by design; REVIEW‑STATUS 3.5 records that closing it is a policy decision.
- *Enforcement without an enforcer / missing powers.* Reserve governance (appointment, liability, custody) is absent from Arts 8–9; REVIEW‑STATUS concern 2. Arts 290/291 architecture itself is present (Arts 15–16, recitals 31–32).

**Changed infrastructure (this release), all minor, none an overclaim:**
- `Base.astro`: the working‑draft notice renders only while `!law.registered`. Registration and "substantive review open" are different facts; on registration the site would drop the "legal basis … remain under review" banner although nothing in the substance changes. Consider decoupling the condition (e.g. a separate `reviewOpen` flag). Future‑state, non‑blocking.
- `.review-notice` carries `no-print`, while `.sizing-note` does not. A browser‑printed article page loses the global working‑draft notice. Remove `no-print` from the notice.
- Link pinning: `versions.md` says "If that file ever says something different from this page, the file is right and this page is a bug", but the REGISTERED.json link is now pinned to the build commit, so the linked file can never differ from the page. Either exempt that one link from pinning or reword the promise.
- `siteDoc()` loads about/brief/faq/press/sign/join via `loadLocalized(name)` without a `source:` option, so `stale` is always `false` for those translations. The about page is the target of the global notice; if the EN status section moves, the four translations will never show the stale banner. Pre‑existing mechanism; note that the four about translations already order the status section before "What this is", unlike EN, though all four declare the same source hash.
- `lawCommit` falls back to `'unknown'` outside a git checkout, which would pin every source link to `/blob/unknown/`. Build‑time hazard only.

### 4. Ridicule kills

**Changed copy, quotable but disclosed:**
- Objection 21 (rendered on the same page as the red sizing note): "the necessity limb of Article 52(1) has, for the first time, a quantity to test against, published, reproducible" sits under a box saying the figures "remain unvalidated against the current designation criteria". An op‑ed can quote the two together. This is the cost the release scope accepts ("Historical memorandum figures remain in the source text with a prominent unvalidated‑sizing notice"). Not a copy defect; a reason to close DC‑45/46 soon.
- Simulator title "The dividend, honestly" over a model that assumes constant positive returns and no losses. The page's own intro, notes and disclaimer say exactly that; the headline still writes itself. Pre‑existing title.
- JSON‑LD `@type: Legislation`, `legislationJurisdiction: 'European Union'`, on a site whose about page says "Not an EU document". `creativeWorkStatus: 'Draft'` and a Person author mitigate. Consider adding `legislationLegalForce: NotInForce` (schema.org LegalForceStatus — external proposition, verify). Metadata; non‑blocking.
- brief.md: "Within three months of designation, a company issues a non‑voting warrant" reads as if the warrant arises on issuance, whereas Art. 5(1) as repaired makes it arise "on the date on which designation … takes effect" with the recording instrument due within three months; FAQ and press already state it correctly. The Regulation's own Art. 13(1)(a) uses "issue the … warrant", so this is loose rather than wrong. Tighten: "The warrant arises at designation; the company records it within three months." Non‑blocking.

**Pre‑existing, outside scope:** recital 28 "The history of pooled public assets is a history of raids"; recital 22 "in no position to legislate its own treaty shopping"; Art. 10(6) "every third calendar year in which the distributable amount is greater than zero" (ambiguous between "every third such year" and "every third calendar year, if positive"; the plain‑language layer and FAQ adopt the first reading). Enacting text; not this release.

---

## C. Verified defect vs uncertain argument, in one line each

- **Verified text defects (all pre‑existing, tracked):** nominal‑value squeeze; Art. 10(6) counting ambiguity; Reserve governance absent; preamble/352 two‑act mismatch (conceded in REGISTRATION‑TEXT).
- **Verified changed‑copy defects:** none that overclaim validity or calibration. Precision items: brief.md warrant timing; `no-print` on the notice; versions‑page promise vs pinned link; about‑translation staleness never fires.
- **Uncertain litigation/registration arguments:** 114(2) by effect; Charter 17 fair balance; necessity/circularity; Art. 63/golden‑share reading. All disclosed in public copy.

## D. External propositions the supplied sources do not verify

Annex II character limits (100 / 1 100 / 5 000 without spaces) and the stated counts; Implementing Decision (EU) 2023/1487 and its reasoning; Council Recommendation 92/443/EEC; C‑899/19 P on partial registration; Directive (EU) 2024/2810; the "720 MEPs / Belgium 15 840 / registered on or after 16 July 2024" threshold statement in sign.md (arithmetically consistent with 22 seats, source not supplied); COCS mandatory for initiatives registered since 2023; the "roughly EUR 1 400 billion" covered‑revenue anchor in the simulator (only the EUR 20,5 trillion value figure appears in supplied text; 1 400 × 14 ≈ 19,6 trillion is consistent, not verified); the acknowledgement date of 27 August for the Forum reply (asserted by the release note, not by EXTERNAL‑REVIEWS.md).

## E. Recommended non‑blocking edits

1. Add "Acknowledged 27 August 2026; exchange closed." to EXTERNAL‑REVIEWS.md review 4.
2. Remove `no-print` from `.review-notice`; decouple the notice from `law.registered`.
3. Exempt the REGISTERED.json link from commit pinning, or reword the versions‑page promise.
4. Pass `source:` for about (and the other siteDoc pages) so translation staleness can fire.
5. brief.md: "The warrant arises at designation; the company records it within three months."
6. Optional: JSON‑LD `legislationLegalForce: NotInForce`.

No reviewed string overclaims legal validity, registrability, institutional approval or model calibration; pre‑existing substantive REVISE findings are disclosed on the notice, the about page, the memorandum §4/§5.4, the download cover and the sizing notes on the three screens where the figures appear.

VERDICT: PUBLISH

## Assistant disposition for editorial review

Raw output above is preserved verbatim. See [website release record](../../campaign/SITE-RELEASE-2026-09-07.md) for accepted fixes, qualified findings and validation. The verdict concerns publication of corrected explanations of a working draft; substantive legal findings remain open. The bundle identifies the exact site snapshot and the commit identifies its source-law baseline. Final editorial disposition remains separate.
