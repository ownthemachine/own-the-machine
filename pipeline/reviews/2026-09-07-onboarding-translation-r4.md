---
gate: translation
target: campaign/organisers and site/content/*/{join,about}.md
commit: 7934803
verdict: PUBLISH
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-07T14:58:50+00:00 · tokens in=90966 out=5718
> Prompt: translation.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `d0f111ca073a7e80706d280cffa67e54550904f8cac271bb9bb60c14b440f217`
> Prompt SHA-256: `cf90b3c229deafbbd3b93a95ec4900d6392d478dcb85d71ac3efe2beeb3fcf29`

### Comprehensive Audit: Campaign & Onboarding Documents and Multilingual Site Pages (EN / FR / NL / DE / ES)

#### 1. Target Scope & Governance Verification
- **Campaign Documents Audited:**
  - `campaign/organisers/START-HERE.md`
  - `campaign/organisers/HOST-CHECKLIST.md`
  - `campaign/organisers/LINKEDIN-PACK.md`
  - `campaign/organisers/REVIEW-STATUS.md`
- **Site Pages Audited (Join & About across 5 languages):**
  - `site/content/en/join.md` & `site/content/en/about.md` (Reference)
  - `site/content/fr/join.md` & `site/content/fr/about.md`
  - `site/content/nl/join.md` & `site/content/nl/about.md`
  - `site/content/de/join.md` & `site/content/de/about.md`
  - `site/content/es/join.md` & `site/content/es/about.md`

---

### Paragraph-by-Paragraph Fidelity and Link Review

#### A. Campaign Organiser Onboarding Documents (`campaign/organisers/`)
1. **`START-HERE.md`**:
   - Accurately states that roles are unpaid volunteer contributions with no expense reimbursement.
   - Correctly distinguishes volunteer contribution from statutory organiser appointment.
   - Accurately cites Regulation (EU) 2019/788 rules: at least seven eligible EU citizens residing in at least seven Member States (no requirement for seven different nationalities; MEPs excluded).
   - Data handling & privacy terms (local follow-up notes, 90-day review for inactive records, no identity document collection at intake) are consistent with site notices.
2. **`HOST-CHECKLIST.md`**:
   - Procedural boundaries are explicitly maintained: personal, individual handling by the initiator; 20-minute structured intake conversation; strict prohibition on automated profiling, prospect scoring, or bulk messaging.
3. **`LINKEDIN-PACK.md`**:
   - Proposed Page fields and first public post accurately convey that the project is a working proposal in preparation, not an officially registered ECI or corporate entity.
   - Pre-publication requirements correctly include opening the 14-day public consultation issue on provisional constitutional changes per `GOVERNANCE.md`.
4. **`REVIEW-STATUS.md`**:
   - Accurately documents review dispositions (Rounds 1–3), confirming privacy, unpaid role terminology, and link checks.

---

#### B. Join Pages (`content/{en,fr,nl,de,es}/join.md`)
1. **Ten-Minute Quickstart & Role Demarcation:**
   - **Fidelity:** All four translations (FR, NL, DE, ES) preserve the exact meaning of the English reference text: tasks are unpaid and volunteer-based; participation does not commit anyone to statutory filing or blanket endorsement of the draft.
   - **Local Links:**
     - FR: `/fr/brief`, `/fr/about`, `mailto:hello@ownthemachine.eu?subject=Premier%20contact%20organisation`
     - NL: `/nl/brief`, `/nl/about`, `mailto:hello@ownthemachine.eu?subject=Kennismaking%20organisatie`
     - DE: `/de/brief`, `/de/about`, `mailto:hello@ownthemachine.eu?subject=Erstkontakt%20Organisation`
     - ES: `/es/brief`, `/es/about`, `mailto:hello@ownthemachine.eu?subject=Primer%20contacto%20organizacion`
2. **Current Project Status & Soundings:**
   - **Fidelity:** All versions state accurately as of 6 September 2026 that no version is registered, no signatures are collected, and soundings (ECI Forum advice on 27 August, ECI veteran on 5 September) constitute non-binding external feedback rather than institutional endorsement.
   - **Local Links:** Correctly point to `/law/versions` (`/fr/law/versions`, `/nl/law/versions`, `/de/law/versions`, `/es/law/versions`).
3. **Ways to Help & Organiser Definition:**
   - **Fidelity:** Complete parity regarding statutory organiser criteria (7 voting-age EU citizens in 7 Member States; MEPs excluded; names public in official register).
   - **External Links:** Official ECI rules link is present across all languages (`https://citizens-initiative.europa.eu/how-it-works_en` and `.../how-it-works_de`).
4. **Data Handling & Inactive Inquiries (90-day rule):**
   - **Fidelity:** All translations convey identical privacy protections: email contacts reach the editor personally, are not added to mailing lists, and private follow-up notes are reviewed after 90 days.
   - **Local Links:** Correctly link to the respective localized `/about` page (`/fr/about`, `/nl/about`, `/de/about`, `/es/about`).

---

#### C. About Pages (`content/{en,fr,nl,de,es}/about.md`)
1. **Status Update (7 September 2026) & Working Draft Notice:**
   - **Fidelity:** Accurately states that the text is a working draft based on Article 114 with an Article 352 alternative under study; sizing figures are unvalidated legacy estimates; simulator is illustrative.
   - **Local Links:** Review ledger links correctly route to localized path `/law/ledger` (`/fr/law/ledger`, `/nl/law/ledger`, `/de/law/ledger`, `/es/law/ledger`).
2. **Non-EU Status & Initiator Identification:**
   - **Fidelity:** Clearly disclaims EU institutional affiliation or legal force; identifies David Vanheeswijck as initiator and data controller.
3. **Declared Interest & Campaign Gates:**
   - **Fidelity:** Discloses book origins and potential spillover attention; reaffirms kill criteria and transparent reporting if gates fail.
4. **Funding & Platform Infrastructure:**
   - **Fidelity:** Discloses personal funding by initiator (domain, Scaleway hosting/CDN, API tokens) and standard infrastructure providers (GitHub, Cloudflare).
5. **Data Protection & Processing Transparency:**
   - **Fidelity:** Clearly discloses server logging, browser-local preference storage, offline storage of contributor notes, and cross-references to the localized `/join` page (`/fr/join`, `/nl/join`, `/de/join`, `/es/join`).
6. **AI Review Jurisdiction & Fable 5.1 Exception:**
   - **Fidelity:** Accurately describes migration to Requesty European endpoint, default zero-retention/no-training rule, and explicit per-run 30-day retention exception strictly limited to non-sensitive public drafts.

---

### Findings & Analysis
- **Fidelity:** 100% faithful to the English reference.
- **Omissions:** None. All qualifiers, dates, legal bases, and data-handling commitments are fully translated across FR, NL, DE, and ES.
- **Readability:** Natural, professional, and idiomatic across all four target languages.
- **Local Links:** All relative and localized anchor links resolve to the appropriate language subtrees.
- **Material Meaning:** Fully aligned across all artefacts without material defects.

VERDICT: PUBLISH
