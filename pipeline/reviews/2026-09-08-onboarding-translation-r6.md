---
gate: translation
target: campaign/organisers and site/content/*/{join,about}.md
commit: cdc6a2263c305c0b93407b9e9794137737f132b5
verdict: PUBLISH
disposition: pending
date: 2026-09-08
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-08T12:07:33+00:00 · tokens in=95512 out=5586
> Prompt: translation.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `f765ab23afff70f8019a9c8bd4a4d9a840372df8e58728e96b08d968c1c92e53`
> Prompt SHA-256: `cf90b3c229deafbbd3b93a95ec4900d6392d478dcb85d71ac3efe2beeb3fcf29`

### 1. Review of Campaign / Organisers Documents

* **`campaign/organisers/START-HERE.md`**:
  * **Fidelity & Completeness:** Accurately reflects current project status (Gate 1 soundings complete, Gate 2 pending, draft not filed/registered). Accurately incorporates the verified mail routing setup (Forward Email forwarding `hello@` to two Gmail inboxes; `organisers@` to initiator Gmail; local intake note retention and 90-day review). Correctly states statutory requirements (seven eligible EU citizens residing in seven Member States; different nationalities not required; MEPs excluded).
  * **Links & Actionability:** Correct absolute URLs (`ownthemachine.eu` and official ECI FAQ). No material defects.

* **`campaign/organisers/HOST-CHECKLIST.md`**:
  * **Fidelity & Operations:** Aligns with governance rules, privacy architecture (local intake tracking, separation from mailbox copies), and no-targeting / no-profiling constraints. No material defects.

* **`campaign/organisers/LINKEDIN-PACK.md`**:
  * **Fidelity & Platform Constraints:** Correctly identifies LinkedIn Page mechanics (free organisation page, personal account authority, creator super-admin), requires truthful category selection, mandates the 14-day public constitutional consultation before publishing, and includes necessary sizing and legal status disclaimers in the copy. No material defects.

---

### 2. Check of `join.md` Pages (EN Reference, FR, NL, DE, ES)

#### Paragraph-by-Paragraph Fidelity and Local Links

1. **Title & Introductory Disclaimer (Unpaid Roles):**
   * *EN:* "Start in ten minutes" / "These are unpaid volunteer contributions and organiser roles. This invitation offers no payment or expense reimbursement."
   * *FR / NL / DE / ES:* All four translations faithfully reproduce the unpaid status and lack of reimbursement with natural phrasing (`bénévoles et non rémunérées`, `vrijwillig en onbetaald`, `ehrenamtlich und unbezahlt`, `voluntarias y no remuneradas`).

2. **Step 1–3 Action Steps:**
   * *Fidelity:* Consistent across all languages.
   * *Local Links:*
     * EN: `/brief`, `/about`
     * FR: `/fr/brief`, `/fr/about`
     * NL: `/nl/brief`, `/nl/about`
     * DE: `/de/brief`, `/de/about`
     * ES: `/es/brief`, `/es/about`
   * *Email subjects:* Accurately localized in mailto links.

3. **Where this actually stands:**
   * *Fidelity:* All languages accurately convey the 6 September 2026 status, the 27 August Forum advice, and the 5 September veteran feedback without claiming Commission approval.
   * *Local Links:* `/law/versions` mapped correctly to `/fr/law/versions`, `/nl/law/versions`, `/de/law/versions`, `/es/law/versions`.

4. **Ways to help (Question / Organise / Connect):**
   * *Fidelity:* Fully preserved in all languages; GitHub repo links correctly maintained.

5. **What being an organiser means:**
   * *Fidelity:* Exact legal precision maintained in all translations (7 citizens of voting age residing in 7 Member States; MEP exclusion; nationalities not required).
   * *Links:* Official rules link accurately preserved (`how-it-works_en` / `how-it-works_de`).

6. **How to get in touch & What happens to what you send (Privacy / Mail routing / Intake notes):**
   * *Fidelity:* All language versions accurately state that `hello@` forwards via Forward Email (US provider) to two Gmail inboxes and `organisers@` to the initiator's Gmail; the distinction between local private intake notes and email retention in Gmail is explicitly rendered.
   * *Local Links to About:*
     * FR: `/fr/about`
     * NL: `/nl/about`
     * DE: `/de/about`
     * ES: `/es/about`

---

### 3. Check of `about.md` Pages (EN Reference, FR, NL, DE, ES)

#### Paragraph-by-Paragraph Fidelity and Local Links

1. **Status Update (7 September 2026):**
   * *Fidelity:* Accurately describes the Article 114 working draft, Article 352 exploration, unvalidated legacy sizing caveat, 2 September researcher approach, 5 September veteran response, and the sending of the French letter to the Belgian MEP office on 7 September 2026.
   * *Local Links:* `/law/ledger` mapped to `/fr/law/ledger`, `/nl/law/ledger`, `/de/law/ledger`, `/es/law/ledger`.
   * *Note on Section Order:* In FR, NL, DE, and ES, the "Status update" section is placed at the top ahead of "What this is" (in EN it is placed second). Both sections are present in full; the reordering is an acceptable editorial presentation choice that does not alter substantive meaning.

2. **What this is / Not an EU document / Who / Who publishes this:**
   * *Fidelity:* Clear disclaimers of official EU status, lack of legal force, and initiator identity (David Vanheeswijck) are fully aligned across all languages.
   * *Ledger Links:* Maintained accurately.

3. **Declared interest / The gates / Funding:**
   * *Fidelity:* Accurately renders book interest disclosure, published kill criteria, zero third-party campaign funding as of 6 September 2026, and initiator-funded hosting/API costs.

4. **Your data (Privacy, Technical Logs, Forward Email / Gmail, 90-day Intake):**
   * *Fidelity:* Full parity across all languages regarding zero cookies/analytics, server logs, US Forward Email forwarding to Gmail, and 90-day local intake review.
   * *Local Links to Join:*
     * EN: `[Take part](/join)`
     * FR: `[Participer](/fr/join)`
     * NL: `[Meedoen](/nl/join)`
     * DE: `[Mitmachen](/de/join)`
     * ES: `[Participar](/es/join)`

5. **Where this site lives & Where the review runs:**
   * *Fidelity:* Explicitly identifies Scaleway (France), Cloudflare DNS (US), GitHub (US), Requesty European endpoint, EU-hosting/zero-retention default, and the explicit 30-day retention exception for public non-sensitive Fable 5.1 runs introduced on 6 September 2026. Parity is maintained in FR, NL, DE, and ES.

6. **Accessibility:**
   * *Fidelity:* WCAG 2.1 AA / WCAG 2.2 target standards and repo issue link preserved across all languages.

---

### 4. Summary of Findings

* **Fidelity & Material Meaning:** No omissions or substantive divergences across translations.
* **Idiomatic Readability:** High quality across FR, NL, DE, and ES, adhering to professional EU administrative and legal register.
* **Local Links:** All relative links correctly include language prefixes (`/fr/`, `/nl/`, `/de/`, `/es/`) where appropriate.

VERDICT: PUBLISH
