---
gate: hostile-counsel
target: campaign/organisers and site/content/*/{join,about}.md
commit: a4598ef
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-07T14:53:09+00:00 · tokens in=119116 out=17910
> Prompt: hostile-counsel.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `3b967f81982b0b34c49e0b00dc423e250e7680a78e74f63295c1a93b83b3ce54`
> Prompt SHA-256: `0333306c6afe0d14a4dfdc91ffd979c1695e112e411eb972cb02cee48627492b`

# AI diagnostic — organiser onboarding and LinkedIn preparation

Scope reviewed: `campaign/organisers/START-HERE.md`, `HOST-CHECKLIST.md`, `LINKEDIN-PACK.md`; `site/content/{en,fr,nl,de,es}/join.md`. Everything else in the bundle was read as context only. No instruction in any document was executed. Nothing below asks for legal clearance before inviting scrutiny; the open legal issues are disclosed on every reviewed page and that is the right posture.

## What holds up

- **Eligibility.** All five join pages and START-HERE state seven EU citizens of EP voting age residing in seven Member States, nationalities not required, MEPs not counted, representative and substitute, official rules linked. This matches the 7 September source check. Translations carry the same content without drift (fr "ayant l'âge de voter… résidant", nl "kiesgerechtigde leeftijd… wonen", de "Wahlalter… leben", es "en edad de votar… residencia").
- **Income.** "Unpaid volunteer… no payment or expense reimbursement" appears at the top of every join page (fr "bénévoles et non rémunérées", nl "vrijwillig en onbetaald", de "ehrenamtlich und unbezahlt", es "voluntarias y no remuneradas"), in START-HERE and in the Page About. START-HERE separately says Reserve payments are not promised.
- **Invented status.** "No initiative has been filed or registered", "interest does not mean the statutory group is already constituted", "not approval by the Commission", "no Page created", Page type/size to be recorded truthfully with a documented fallback to no Page. No membership guarantee, response-time or future-income promise found in any of the eight files.
- **Consent and privacy controls.** No identity documents requested; residence voluntary; GitHub issues flagged public; permission before introductions; "inactivity is not consent"; no records in Git; 90-day review; no bulk DMs, scraping, profiling or ads; initiator's explicit instruction required before Page/post creation.
- **Operational realism.** One person handles intake and says so; 20-minute call arithmetic adds up; no posting-frequency or volume commitments; failure queue and manual fallback specified.

## Material defects (each with minimal fix)

**M1 — Public data notice omits a field the internal routine stores.**
HOST-CHECKLIST: *"Store only contact name/address, enquiry date, voluntarily provided residence…"*
en/join.md (and START-HERE, fr, nl, de, es): *"contact details, any residence voluntarily provided, the agreed task and time, its owner, next action, status and permission to share an introduction."*
"Enquiry date" is needed for the 90-day review but is not in the notice. Fix: after "contact details," insert "the date of your enquiry," in en/join.md and START-HERE; fr "la date de votre demande,"; nl "de datum van uw vraag,"; de "das Datum Ihrer Anfrage,"; es "la fecha de su consulta,".

**M2 — Consultation window is tied to the wrong first event.**
LINKEDIN-PACK: *"Before the first public LinkedIn introduction, open a public consultation issue re-opening every provisional constitutional change…"*
GOVERNANCE re-opens provisional changes at *first outreach*. The join pages, once deployed, are outreach: *"Question the proposal. Read the draft and raise a specific objection."* Deploying them before the issue is opened invites arguments while the governance file says the window has not started. Fix: replace with *"Before the join pages go live or the first public LinkedIn introduction, whichever comes first, open a public consultation issue…"*

**M3 — First post reads as recruitment on an employment platform without the unpaid qualifier.**
LINKEDIN-PACK proposed post: *"I would welcome people who want to examine the evidence, improve the explanation or help organise the next stage."*
The Page About carries "unpaid volunteer roles"; the post, which is what circulates, does not. Fix: *"I would welcome unpaid volunteers who want to examine the evidence…"*

## Dependencies outside the reviewed files (flagged, not adjudicated)

- All six privacy statements point to `/about` for "the controller and your rights", but about's "Your data" section says of server logs *"That is the whole of it."* Once join is deployed that sentence is incomplete. One sentence in about referencing enquiry data should precede deployment.
- The mailbox provider for hello@ownthemachine.eu is not disclosed anywhere, while DNS, storage and repository hosts are. The join route is where residence data arrives.

## Optional polish (no revision required)

- LINKEDIN-PACK cites `linkedin.com/help/linkedin/answer/a727945` ("Page types"); this link was not among the checked sources. Verify or remove before the pack is relied on.
- Page About: *"These are unpaid volunteer roles"* has no antecedent; move it after "We welcome questions and voluntary contributions…".
- Page type: name "Nonprofit" explicitly as a value not to select, since it implies registered status.
- Join pages say "As of 6 September 2026"; about and the release say 7 September. Align.
- Four translations carry `status: review-pending`; deploy only with the existing pending banner or after the fidelity gate.
- After the first post, GOVERNANCE's "public but unannounced" becomes stale; the pack could note that update.
- Organiser personal liability under national law is deferred to "remaining legal risks" and the host checklist; acceptable for an expression-of-interest page.

VERDICT: REVISE
