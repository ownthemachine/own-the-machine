---
gate: hostile-counsel
target: campaign/organisers and site/content/*/{join,about}.md
commit: cdc6a2263c305c0b93407b9e9794137737f132b5
verdict: REVISE
disposition: pending
date: 2026-09-08
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-08T12:09:05+00:00 · tokens in=145659 out=9735
> Prompt: hostile-counsel.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `f765ab23afff70f8019a9c8bd4a4d9a840372df8e58728e96b08d968c1c92e53`
> Prompt SHA-256: `9171d2136ad54f80aa8a8932ee2610de3084a9a2a72e07940bc01a4bd17c9c26`

# AI diagnostic — organiser onboarding and LinkedIn preparation

Scope reviewed: `campaign/organisers/START-HERE.md`, `HOST-CHECKLIST.md`, `LINKEDIN-PACK.md`; `site/content/{en,fr,nl,de,es}/{join,about}.md`. `REVIEW-STATUS.md` read as disposition context only. This is a prose and consent review; it does not clear the legal mechanism and does not treat model or source summaries as institutional endorsement.

## Axis-by-axis assessment

**Promises.** No response-time, membership, appointment, payment or future-income promise found. START-HERE: "Payments are not promised and would depend on income actually realised by a proposed Reserve." LinkedIn About: "Neither payments nor annual increases are guaranteed." Task times are labelled "Suggested time, not a commitment"; the working meeting is "if scheduled". Pass.

**Recruitment transparency.** Unpaid status is stated in every entry point (START-HERE, LinkedIn About, post, all five join pages). Contributor vs statutory organiser is separated everywhere; "interest does not mean the statutory group is already constituted." Pass.

**Eligibility.** All texts say seven eligible citizens residing in seven Member States, nationalities not required, MEPs do not count; join pages add EP voting age; both point to the Commission's rules. Matches the checked Commission source. Pass.

**Invented status.** No Page-created claim; "Not published; no Page created." Page fields conditional on truthful selection, with a fallback to profile-only. Site: "not published by, endorsed by, affiliated with or reviewed by" any Union institution. Forum/veteran replies labelled non-binding feedback. Pass.

**Misleading income.** Nothing in the reviewed pages quantifies a payout. Pass.

**Privacy and consent.** Routing disclosure (Forward Email, US provider → two contacts' Gmail; organisers@ → initiator's Gmail) matches the 7–8 September mail facts across all twelve texts. Intake note, 90-day review, and the explicit statement that Gmail copies are not auto-deleted are consistent between START-HERE, HOST-CHECKLIST and all join/about pages. Controller named; no private addresses in the bundle. Two defects below.

**Premature LinkedIn publicity.** The pack gates publication on live join page, functioning mailbox, opened consultation issue and explicit initiator instruction; no prospect list, targeting or outbound messaging. Pass, subject to the wording fix below.

## Material defects (exact text, minimal fix)

**1. Recipient gender leaked in three translations of the About status.** EN deliberately says "a Belgian MEP office"; NL "een Belgisch Europarlementslid" is neutral. The other three are grammatically feminine and narrow the candidate set for a recipient the project promised to keep out of the public record:

- FR: "au bureau d'une eurodéputée belge" → "au bureau d'un membre belge du Parlement européen"
- DE: "an das Büro einer belgischen Europaabgeordneten" → "an das Büro eines belgischen Mitglieds des Europäischen Parlaments"
- ES: "a la oficina de una eurodiputada belga" → "a la oficina de un miembro belga del Parlamento Europeo"

**2. LinkedIn pack asserts a deployment state it cannot vouch for.** LINKEDIN-PACK "Timing and purpose": "The website is already public and the updated draft status is live." The brief records the site copy as not deployed and the join page it links to as still being edited. Minimal fix: "The website is already public. The onboarding join page and status update must be verified live before this pack is used" (the "Before publishing" check already requires this; the premise sentence should not pre-empt it).

## Conditional check (fix only if the fact holds)

About pages, Funding: "Standard platform services on ordinary terms, including GitHub and Cloudflare, are disclosed below." Forward Email and Google now sit in the processing path but are not in this list, and "Where this site lives" still says "Two parts are not [European]". Add "Forward Email and Google" to the list; if the Forward Email plan is paid, add it to the personally-paid costs sentence per GOVERNANCE's "'None' is not an acceptable answer" rule.

## Operational preconditions (not prose defects; must precede deployment/posting)

- Independent receipt of the 8 September test messages on both routes remains unconfirmed. "Message sent" is sender-side only. Do not deploy join pages inviting email, or post the LinkedIn introduction, until a recipient-side receipt is recorded.
- The 14-day consultation issue must actually be opened and linked before the introduction; the pack says so and no completion is claimed.

## Optional polish (no revision required)

- Join pages date status "As of 6 September 2026" while About is dated 7 September; harmonise.
- FR/NL/DE/ES "Who/Qui/Wie/Wer" sections link `/law/ledger` without locale prefix, unlike the status section.
- FR About places the status section before "De quoi s'agit-il", unlike EN.
- "two project contacts" could read "the initiator and one other project contact" if accurate, so readers know who reads their mail.

VERDICT: REVISE
