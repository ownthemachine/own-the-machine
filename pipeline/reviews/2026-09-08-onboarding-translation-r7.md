---
gate: translation
target: campaign/organisers and site/content/*/{join,about}.md
commit: 59dec2e48ccc295880a5b9351874359bebe7cbd2
verdict: PUBLISH
disposition: pending
date: 2026-09-08
---

# Review

> Reviewer: `vertex/gemini-3.7-flash@eu` · router router.eu.requesty.ai · geolocation eu · retention 0d · trained-on false · lab google
> 2026-09-08T12:13:31+00:00 · tokens in=97793 out=3036
> Prompt: translation.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `f5b80c42e6db206a682a83ff9823a489432adc86d14b7a0ade0853d86e3a59c0`
> Prompt SHA-256: `cf90b3c229deafbbd3b93a95ec4900d6392d478dcb85d71ac3efe2beeb3fcf29`

# Review Summary

## Scope & Target
- **Campaign/Organisers Documents:** `START-HERE.md`, `HOST-CHECKLIST.md`, `LINKEDIN-PACK.md`
- **Site Pages (all 10):** `site/content/{en,fr,nl,de,es}/{join,about}.md`

---

## 1. Fidelity, Omissions & Alignment (EN Reference vs FR/NL/DE/ES)

### Organiser Onboarding & Process
- **Unpaid Volunteer Status:** Consistently and explicitly stated across `START-HERE.md`, `LINKEDIN-PACK.md`, and all five language versions of `join.md`.
- **Statutory Organiser Requirements:** Accurately specifies the requirement for at least seven eligible EU citizens of voting age residing in at least seven Member States, explicitly noting that seven different nationalities are not required and MEPs do not count toward the minimum.
- **Task & Time Allocations:** Accurately presented as suggested volunteer tasks without appointment or employment commitments.

### Privacy, Mail Routing & Data Handling
- **Mail Routing Disclosure:** Identical, accurate disclosures across all ten site pages and onboarding documents (messages to `hello@ownthemachine.eu` forwarded via Forward Email to two contacts' personal Gmail inboxes; `organisers@ownthemachine.eu` forwarded to the initiator's personal Gmail inbox).
- **Intake Notes & Retention:** Local intake note scope, 90-day review period for inactive notes, and explicit notice that Gmail inbox copies are separate and not automatically deleted upon local note deletion are faithfully preserved across all locales.
- **Provider Disclosures:** Funding sections across all About pages accurately reflect standard platform services, including Scaleway, Cloudflare, GitHub, Forward Email, and Google, as well as the initiator's personally paid Enhanced Protection account.

### Prior Review Findings Verification
- **Neutrality of MEP Correspondence:** FR, DE, and ES About pages have correctly removed gendered descriptions, harmonising with the neutral EN/NL references ("un membre belge du Parlement européen", "eines belgischen Mitglieds des Europäischen Parlaments", "un miembro belga del Parlamento Europeo").
- **LinkedIn Pack Readiness Premise:** `LINKEDIN-PACK.md` no longer pre-empts deployment, explicitly conditioning use on verifying the live join page and status update.

---

## 2. Links and Navigation
- Locale-specific links (`/fr/`, `/nl/`, `/de/`, `/es/`) correctly map to respective `/brief`, `/about`, `/law/versions`, `/law/ledger`, and `/join` routes.
- External links to GitHub, the Commission ECI portal, and mailto anchors with URI-encoded subjects are functional and consistent.

---

## 3. Optional Polish (Non-Blocking)
- Minor stylistic variance in ES About funding enumeration (`GitHub y Cloudflare, Forward Email y Google`) does not affect legal or material meaning.
- Canonical fallback link `/law/ledger` within the "Who/Qui/Wie/Wer" section across non-EN pages remains valid alongside the localized `/xx/law/ledger` in the Status section.

---

VERDICT: PUBLISH
