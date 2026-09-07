---
gate: hostile-counsel
target: campaign/organisers and site/content/*/{join,about}.md
commit: 7934803
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-07T14:58:41+00:00 · tokens in=138537 out=10995
> Prompt: hostile-counsel.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `d0f111ca073a7e80706d280cffa67e54550904f8cac271bb9bb60c14b440f217`
> Prompt SHA-256: `9171d2136ad54f80aa8a8932ee2610de3084a9a2a72e07940bc01a4bd17c9c26`

**AI diagnostic** — sceptical-reader review of campaign/organisers/START-HERE.md, HOST-CHECKLIST.md, LINKEDIN-PACK.md and the ten site join/about pages (en/fr/nl/de/es). Other bundle files used as context only. REVIEW-STATUS.md read as the assistant's disposition, not as approval.

## What holds up

- **Promises.** No payment, membership, response-time or income promise appears. "Payments are not promised and would depend on income actually realised by a proposed Reserve" (START-HERE); "Neither payments nor annual increases are guaranteed" (LinkedIn About); "unpaid volunteer roles; no payment or expense reimbursement" (all three docs, all five join pages). Task times are "Suggested time, not a commitment." Consistent with DC-14 and recital 24.
- **Status.** "Not filed or registered", "no statements of support are being collected", "interest does not mean the statutory group is already constituted", "Forum advice is independent, non-binding, not approval" — present in EN and carried faithfully into FR/NL/DE/ES. No Page-created claim; the pack says "Not published; no Page created."
- **Eligibility.** All join pages state seven EU citizens of EP-voting age resident in seven different Member States, nationalities not required, MEPs excluded, names published, official rules govern. Matches the checked Commission facts. START-HERE adds "No identity-document collection system has been established" and defers documentation to the official process. Nothing misleading.
- **Recruitment transparency.** Contributor and statutory organiser are expressly separate decisions; "Do not promise a role" (HOST-CHECKLIST); "No person becomes an organiser through a status change in an internal tracker"; "At present the initiator handles intake; references to working together do not imply a staffed team."
- **Consent.** Email is "not permission to add you to a mailing list"; introductions only with permission; residence "voluntarily provided"; "inactivity is not consent"; passport copies withheld until secure handling exists. Retention (90-day review, deletion unless agreed) is stated on every join page and in both organiser docs identically.
- **Premature publicity.** The pack conditions the first LinkedIn introduction on opening the full 14-day constitutional consultation issue and linking it, and refuses to count private Gate 1 soundings as a public window. That satisfies GOVERNANCE's "window runs from the first outreach" on its own terms. The Page-type route is conditional on truthful mandatory fields, with a personal-profile fallback. No prospect list, no targeting, no ads.
- **Operational realism.** Single-owner intake with a 20-minute script, one small task, named reviewer, minimal access, failure queue and manual fallback is proportionate to a modest first post. "Avoid posting frequency promises that exceed actual capacity" is the right guard.

## Material defects

**1. Privacy: mail hosting undisclosed while the page enumerates its non-European processors (EN about and all four translations).**
Exact text (EN about, "Where this site lives"): *"Two parts are not, and a campaign about European ownership should say which: the domain's DNS is answered by Cloudflare, a United States company, though no page content passes through it, and the source repository is hosted on GitHub, also American."* And ("Your data"): *"If you email the project, your message is used to respond. Contributor follow-up notes and their retention are described on Take part. Those private notes are stored on the initiator's machine, outside the public repository."*
Problem: REVIEW-STATUS records that hello@ownthemachine.eu has Cloudflare MX routing and is read in a Gmail account. If so, every enquiry — including the residence and contact details the join pages ask for — passes through Cloudflare Email Routing and is stored by Google, both US companies. The page tells the reader "no page content passes through" Cloudflare and that notes sit on the initiator's machine, but says nothing about where the emails themselves live. For a page that claims to state processing "plainly rather than claimed away" and that names the controller and supervisory authority, this is a material omission, and the "Two parts are not" enumeration becomes inaccurate.
Minimal fix (EN, then mirror in FR/NL/DE/ES): after "Those private notes are stored on the initiator's machine, outside the public repository." add: *"The mailbox itself is not on that machine: mail to hello@ownthemachine.eu is routed by Cloudflare and stored in a Google mailbox, both United States companies, until the enquiry is closed and the message deleted."* And change "Two parts are not" to "Three parts are not" (or fold the mail sentence into that paragraph). Adjust the wording to whatever the actual route is; the defect is the silence, not a specific provider.

**2. Status accuracy: Belgian MEP letter (EN about "Status update" and all four translations).**
Exact text: *"The next planned approach is to a Belgian MEP office; no such send is recorded."*
Problem: campaign/GATES.md states "letter B (Belgian MEP office) sent 7 September 2026 in French", while SITE-RELEASE-2026-09-07.md says the letter "remains unsent". The bundle contradicts itself on a dated fact the page asserts. I cannot tell which is true; the page must match LETTER-B-2026-09-07-STATUS.md at deployment.
Minimal fix: verify the status file before deploying the about pages. If sent: *"A letter to a Belgian MEP office was sent on 7 September; no reply is recorded."* If unsent: leave as is and correct GATES.md (outside this review's scope, but the contradiction should not stand in public context).

## Preconditions (not text defects)

- Mailbox end-to-end delivery is unconfirmed ("no test email was sent"). The join pages and START-HERE route everyone to that address. Send and receive one test message before the onboarding pages go live, not only before the LinkedIn post.
- Confirm the public consultation issue actually opens with a dated link before the first post, as the pack requires. Do not treat the live join page as having started that window.

## Optional polish (no revision required)

- Join pages: the `mailto:` subject "Organiser introduction" is pre-filled for every enquirer, including people offering only evidence or language help; a neutral subject avoids implying organiser interest.
- Join/START-HERE: "responsibilities" and "remaining legal risks" could name organisers' personal liability under Regulation (EU) 2019/788 in one clause, so the weight of the statutory role is visible at invitation stage rather than only at the formal decision.
- About "Who" in FR/NL/DE/ES links `/law/ledger` rather than the localised ledger path used elsewhere on the same page.
- Join says "As of 6 September 2026"; about says 7 September. Harmonise on deployment.
- LinkedIn first post opens with the book title; the declared-interest paragraph lives only on the about page. A five-word pointer ("my interest as its author is declared on the site") would pre-empt the obvious comment.
- Tagline "lasting citizen ownership": defensible as the proposal's objective, but "lasting" is the one word in the public copy that DC-23 (friction, never impossibility) would rather see as "long-term".

## Disposition

The invitation, eligibility statements, income disclaimers, consent language and LinkedIn sequencing are sound and do not need legal clearance to invite scrutiny. The privacy section, however, presents itself as an exhaustive account of where a correspondent's data goes and, on the bundle's own record, omits the mail path. That is a material defect on the live-facing pages a volunteer reads before sending their residence and contact details; it is a one-sentence fix in five languages. The MEP-letter status must be reconciled before deployment.

VERDICT: REVISE
