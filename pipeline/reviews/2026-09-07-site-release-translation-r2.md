---
gate: translation
target: website release, corrected public explanations
commit: 9f02181
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T12:14:21+00:00 · tokens in=141848 out=4248
> Prompt: translation.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `6cd2fe1e54d470d22b5b71ea116583bea65a110e5aaeadbbdf4a525b6345ea6c`
> Prompt SHA-256: `d9c1de6d8ad433d367df1627bb735eb007cb9f885e5235afb2ca1e5887a77f71`

### Locale-by-Locale Review

#### 1. English (Authoritative Source)
- **`reviewNotice` (`en.mjs`)**: 
  - `text`: *"Working draft: the legal basis, compulsory equity mechanism and sizing remain under review. Nothing is registered and no statements of support are being collected."*
  - `link`: *"Current status and open questions"*
  - `sizing`: *"Sizing figures in the memorandum remain unvalidated against the current designation criteria. They do not establish that the proposed 3% achieves the generational objective."*
  - **Assessment**: Legally precise; explicitly disclaims registration, support collection, and model validation.
- **`home.basis` (`en.mjs`)**: Clearly identifies Art. 114 TFEU and the Art. 352 review track, expressly states that no Treaty amendment is sought, and links cleanly to registration objectives.
- **About Page Status (`content/en/about.md`)**: Accurately dates the candidate status to 7 September 2026, records the ECI Forum exchange as closed on 27 August, discloses soundings progress (researcher sent 2 Sept, ECI veteran replied 5 Sept, Belgian MEP office planned), and states that substantive gates remain open.
- **Explanatory Memorandum & Simulator**: The ECI Forum consultation sentence in section 3.2 is accurate and closed. The simulator grammar and strings in `simulator.ts` and `en.mjs` cleanly pair payout with stake and state all model simplifications.

---

#### 2. German (`de`)
- **`reviewNotice` (`de.mjs`)**:
  - `text`: *"Arbeitsentwurf: Rechtsgrundlage, verpflichtende Kapitalbeteiligung und deren Umfang werden noch geprüft. Es ist nichts registriert, und es werden keine Unterstützungsbekundungen gesammelt."*
  - `link`: *"Aktueller Stand und offene Fragen"*
  - `sizing`: *"Die Berechnungen in der Begründung sind noch nicht anhand der aktuellen Benennungskriterien validiert. Sie belegen nicht, dass die vorgeschlagenen 3% das Ziel innerhalb einer Generation erreichen."*
  - **Assessment**: Semantic fidelity is exact; uses standard EU terminology (*Unterstützungsbekundungen*, *Rechtsgrundlage*).
- **`home.basis` (`de.mjs`)**: Precise (*"stützt sich auf Artikel 114 AEUV. Eine Alternative auf Grundlage von Artikel 352 wird geprüft..."*).
- **About Page Status (`content/de/about.md`)**: Full fidelity to EN; internal links properly prefixed (`/de/law/ledger`). Accurately translates the status of the soundings and the unvalidated sizing figures.

---

#### 3. Spanish (`es`)
- **`reviewNotice` (`es.mjs`)**:
  - `text`: *"Borrador de trabajo: la base jurídica, el mecanismo de participación obligatoria en el capital y su dimensión siguen en revisión. No hay ninguna iniciativa registrada ni se recogen declaraciones de apoyo."*
  - `link`: *"Situación actual y cuestiones abiertas"*
  - `sizing`: *"Las cifras de dimensionamiento de la exposición de motivos aún no se han validado con los criterios actuales de designación. No demuestran que el 3% propuesto alcance el objetivo en una generación."*
  - **Assessment**: Natural, correct Spanish legal register (*declaraciones de apoyo*, *exposición de motivos*, *criterios de designación*).
- **`home.basis` (`es.mjs`)**: Clear and faithful; matches Treaty citations (*artículo 114 TFUE* / *artículo 352*).
- **About Page Status (`content/es/about.md`)**: Fully aligned with English; preserves all caveats regarding unvalidated sizing, closed Forum advice, and pending MEP outreach.

---

#### 4. French (`fr`)
- **`reviewNotice` (`fr.mjs`)**:
  - `text`: *"Projet de travail : la base juridique, le mécanisme de participation obligatoire au capital et son dimensionnement restent à examiner. Rien n’est enregistré et aucune déclaration de soutien n’est recueillie."*
  - `link`: *"État du projet et questions ouvertes"*
  - `sizing`: *"Les chiffres de dimensionnement du mémorandum ne sont pas encore validés au regard des critères actuels de désignation. Ils ne démontrent pas que les 3% proposés permettent d’atteindre l’objectif sur une génération."*
  - **Assessment**: Idiomatic and legally accurate (*déclarations de soutien*, *dimensionnement*).
- **`home.basis` (`fr.mjs`)**: Accurate (*"Le projet actuel cite l’article 114 TFUE. Une autre version fondée sur l’article 352 est à l’étude..."*).
- **About Page Status (`content/fr/about.md`)**: Faithful to EN source; ledger links properly routed to `/fr/law/ledger`.
- **Explanatory Memorandum (`explanatory-memorandum.fr.md`, sec. 3.2)**: Correctly reflects the closed status: *"Le Forum de l'ICE a fourni un avis indépendant et non contraignant sur l'enregistrement le 27 août 2026. Un accusé de réception a été envoyé le même jour et l'échange est clos ; cet avis ne constitue pas une approbation du texte proposé."*

---

#### 5. Dutch (`nl`)
- **`reviewNotice` (`nl.mjs`)**:
  - `text`: *"Werktekst: de rechtsgrondslag, het mechanisme voor verplichte kapitaaldeelname en de omvang ervan worden nog onderzocht. Er is niets geregistreerd en er worden geen steunbetuigingen verzameld."*
  - `link`: *"Stand van zaken en open vragen"*
  - `sizing`: *"De berekeningen in de memorie zijn nog niet gevalideerd voor de huidige aanwijzingscriteria. Ze tonen niet aan dat de voorgestelde 3% het doel binnen een generatie bereikt."*
  - **Assessment**: Correct EU terminology (*steunbetuigingen*, *aanwijzingscriteria*, *VWEU*).
- **`home.basis` (`nl.mjs`)**: Clean and accurate.
- **About Page Status (`content/nl/about.md`)**: Full fidelity to EN; correctly routes to `/nl/law/ledger` and conveys the exact sounding statuses.

---

### Verification of Screens & Artifacts
1. **Global Notice Placement (`Base.astro`)**: Real style block contains `.review-notice`, correctly rendering across all pages when `law.registered` is false.
2. **Sizing Notice Placement**: Verified present and styled with `.sizing-note` on:
   - `Objections.astro`
   - `Explanatory.astro`
   - `Simulator.astro`
3. **Download Artifacts (`make-artefacts.mjs`)**: Cover notice includes the required unvalidated sizing caveat and non-registration disclaimer for both PDF and EPUB outputs.

No blocking omissions, unwarranted promises, or term drifts were identified.

VERDICT: PUBLISH

## Assistant disposition for editorial review

Raw output above is preserved verbatim. See [website release record](../../campaign/SITE-RELEASE-2026-09-07.md) for accepted fixes, qualified findings and validation. The verdict concerns publication of corrected explanations of a working draft; substantive legal findings remain open. The bundle identifies the exact site snapshot and the commit identifies its source-law baseline. Final editorial disposition remains separate.
