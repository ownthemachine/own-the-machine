---
gate: translation
target: website release, corrected public explanations
commit: 8c72b18
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T12:07:54+00:00 · tokens in=139164 out=5715
> Prompt: translation.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `c48ebe0c5894bcc809ce241a0a6bf2d59ee30ddcbaf47d2e4830248b11a26e0e`
> Prompt SHA-256: `f8ed4a4b9e674ec90c5b3b1baf50dea6db12ba452c0449a475505305f89fa6c1`

### 1. Scope and Review Standard

This review evaluates the explanatory copy, updated i18n dictionaries (`reviewNotice`, `home.basis`), and the dated 7 September 2026 status updates on the `/about` pages across English (authoritative) and all four target locales: French (`fr`), Dutch (`nl`), German (`de`), and Spanish (`es`).

The copy is evaluated as public explanatory prose for an openly contested working draft. It must maintain strict fidelity to legal caveats, avoid overclaiming legal validity or model calibration, properly reflect open substantive gate findings, and use natural, high-register European institutional and legal phrasing.

---

### 2. Detailed Locale-by-Locale Review

#### A. Authoritative English (`en`)
* **`reviewNotice`**:
  * `text`: *"Working draft: the legal basis, compulsory equity mechanism and sizing remain under review. Nothing is registered and no statements of support are being collected."*
  * `link`: *"Current status and open questions"*
  * `sizing`: *"Sizing figures in the memorandum remain unvalidated against the current designation criteria. They do not establish that the proposed 3% achieves the generational objective."*
  * *Assessment*: Accurate, clear disclaimer of status, ECI non-registration, and unvalidated sizing.
* **`home.basis`**:
  * *"The current draft cites Article 114 TFEU. An Article 352 alternative is under review; neither route is settled. No Treaty change is sought. `<a href=\"%REG%\">Read the proposed registration objectives.</a>`"*
  * *Assessment*: Accurately distinguishes the published Article 114 draft from the Article 352 exploration while explicitly disclaiming Treaty change.
* **About page status section (`content/en/about.md`)**:
  * Correctly dates the update (7 September 2026), names the Article 352 alternative without claiming adoption, itemises open substantive questions, qualifies the simulator as an illustrative model rather than an audited forecast, and states the factual timeline of soundings (Forum advice 27 August, researcher 2 September, ECI veteran 5 September, Belgian MEP office pending).

---

#### B. French (`fr`)
* **`reviewNotice`**:
  * `text`: *"Projet de travail : la base juridique, le mécanisme de participation obligatoire au capital et son dimensionnement restent à examiner. Rien n’est enregistré et aucune déclaration de soutien n’est recueillie."*
  * `link`: *"État du projet et questions ouvertes"*
  * `sizing`: *"Les chiffres de dimensionnement du mémorandum ne sont pas encore validés au regard des critères actuels de désignation. Ils ne démontrent pas que les 3% proposés permettent d’atteindre l’objectif sur une génération."*
  * *Assessment*: Uses standard EU French terminology (*déclaration de soutien* under Regulation (UE) 2019/788, *dimensionnement*, *critères de désignation*). Full semantic fidelity to the English source.
* **`home.basis`**:
  * *"Le projet actuel cite l’article 114 TFUE. Une autre version fondée sur l’article 352 est à l’étude ; aucune des deux voies n’est acquise. Aucune modification des traités n’est demandée. `<a href=\"%REG%\">Lire les objectifs proposés pour l’enregistrement.</a>`"*
  * *Assessment*: Accurate Treaty nomenclature (*TFUE*) and natural register.
* **About page status section (`content/fr/about.md`)**:
  * Accurately renders all caveats, open substantive issues, simulator limits, and sounding dates without term drift or added promises.

---

#### C. Dutch (`nl`)
* **`reviewNotice`**:
  * `text`: *"Werktekst: de rechtsgrondslag, het mechanisme voor verplichte kapitaaldeelname en de omvang ervan worden nog onderzocht. Er is niets geregistreerd en er worden geen steunbetuigingen verzameld."*
  * `link`: *"Stand van zaken en open vragen"*
  * `sizing`: *"De berekeningen in de memorie zijn nog niet gevalideerd voor de huidige aanwijzingscriteria. Ze tonen niet aan dat de voorgestelde 3% het doel binnen een generatie bereikt."*
  * *Assessment*: Uses established Dutch ECI terminology (*steunbetuigingen*, *aanwijzingscriteria*, *rechtsgrondslag*).
* **`home.basis`**:
  * *"Het huidige ontwerp verwijst naar artikel 114 VWEU. Een alternatief op basis van artikel 352 wordt onderzocht; geen van beide routes staat vast. Er wordt geen verdragswijziging gevraagd. `<a href=\"%REG%\">Lees de voorgestelde registratiedoelstellingen.</a>`"*
  * *Assessment*: Correct Treaty abbreviation (*VWEU*), precise legal caveats.
* **About page status section (`content/nl/about.md`)**:
  * Faithful to the English source; correctly covers open points (pre-income financing, citizen payment record corrections, unvalidated sizing), the EBI-forum exchange, and sounding chronology.

---

#### D. German (`de`)
* **`reviewNotice`**:
  * `text`: *"Arbeitsentwurf: Rechtsgrundlage, verpflichtende Kapitalbeteiligung und deren Umfang werden noch geprüft. Es ist nichts registriert, und es werden keine Unterstützungsbekundungen gesammelt."*
  * `link`: *"Aktueller Stand und offene Fragen"*
  * `sizing`: *"Die Berechnungen in der Begründung sind noch nicht anhand der aktuellen Benennungskriterien validiert. Sie belegen nicht, dass die vorgeschlagenen 3% das Ziel innerhalb einer Generation erreichen."*
  * *Assessment*: Correct German ECI terms (*Unterstützungsbekundungen*, *Benennungskriterien*, *Begründung*).
* **`home.basis`**:
  * *"Der aktuelle Entwurf stützt sich auf Artikel 114 AEUV. Eine Alternative auf Grundlage von Artikel 352 wird geprüft; keiner der beiden Wege steht fest. Eine Vertragsänderung wird nicht angestrebt. `<a href=\"%REG%\">Die vorgeschlagenen Registrierungsziele lesen.</a>`"*
  * *Assessment*: Correct Treaty abbreviation (*AEUV*), clear and natural phrasing.
* **About page status section (`content/de/about.md`)**:
  * Precise semantic equivalence, maintains all disclaimers regarding unvalidated projections and lack of EU endorsement.

---

#### E. Spanish (`es`)
* **`reviewNotice`**:
  * `text`: *"Borrador de trabajo: la base jurídica, el mecanismo de participación obligatoria en el capital y su dimensión siguen en revisión. No hay ninguna iniciativa registrada ni se recogen declaraciones de apoyo."*
  * `link`: *"Situación actual y cuestiones abiertas"*
  * `sizing`: *"Las cifras de dimensionamiento de la exposición de motivos aún no se han validado con los criterios actuales de designación. No demuestran que el 3% propuesto alcance el objetivo en una generación."*
  * *Assessment*: Correct Spanish ECI terms (*declaraciones de apoyo*, *exposición de motivos*, *criterios de designación*).
* **`home.basis`**:
  * *"El borrador actual cita el artículo 114 TFUE. Se estudia una alternativa basada en el artículo 352; ninguna de las dos vías está resuelta. No se solicita modificar los Tratados. `<a href=\"%REG%\">Leer los objetivos propuestos para el registro.</a>`"*
  * *Assessment*: Correct Treaty abbreviation (*TFUE*), faithful register.
* **About page status section (`content/es/about.md`)**:
  * Accurate rendering of caveats, soundings status, and model limits.

---

### 3. Defect and Drift Analysis

* **Blocking Omissions / Added Promises**: None. Across all five languages, the status notices, homepage basis text, and about pages consistently disclose open legal issues, unvalidated sizing, and the exploratory nature of the draft.
* **Term Drift**: None. Standard Union terminology (ECI statements of support, Treaty article references, DMA/resolution-style designation and valuation terms) is maintained across all four target languages.
* **Optional Polish (Non-blocking)**:
  * In FR `reviewNotice.sizing` and `content/fr/about.md`, *"mémorandum"* is used alongside *"exposé des motifs"*. Both are understood in this context; keeping them as-is is acceptable.

---

### 4. Integration Verification

1. **Global Review Notice (`reviewNotice`)**: Rendered in `Base.astro` whenever `!law.registered` is true, ensuring no visitor mistake the text for an active or approved initiative.
2. **Sizing Caveat & Artefacts**: Included on the Objections screen, Explanatory Memorandum, Simulator, and stamped on the generated PDF and EPUB cover pages via `make-artefacts.mjs`.
3. **No Certification Claim**: Transparent disclosure across all locales that translations were produced and verified through the open review process without human native-reader certification.

---

VERDICT: PUBLISH

## Assistant disposition for editorial review

Raw output above is preserved verbatim. See [website release record](../../campaign/SITE-RELEASE-2026-09-07.md) for accepted fixes, qualified findings and validation. The verdict concerns publication of corrected explanations of a working draft; substantive legal findings remain open. The bundle identifies the exact site snapshot and the commit identifies its source-law baseline. Final editorial disposition remains separate.
