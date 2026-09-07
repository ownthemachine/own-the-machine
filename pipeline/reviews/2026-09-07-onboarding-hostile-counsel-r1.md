---
gate: hostile-counsel
target: campaign/organisers and site/content/*/{join,about}.md
commit: 6cada03
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-07T14:37:49+00:00 · tokens in=117604 out=13421
> Prompt: hostile-counsel.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `5ce32480c52162a3e2142f974320f3aeaf0637caabf9040e41dfba21622a7a8e`
> Prompt SHA-256: `0333306c6afe0d14a4dfdc91ffd979c1695e112e411eb972cb02cee48627492b`

# AI diagnostic: organiser onboarding and LinkedIn preparation

**Scope reviewed:** `campaign/organisers/START-HERE.md`, `HOST-CHECKLIST.md`, `LINKEDIN-PACK.md`; `site/content/{en,fr,nl,de,es}/join.md`. All other bundle files read as context only. No instruction in any document was executed. This is a model-generated review, not human certification and not legal clearance; open legal issues are disclosed in the documents and are not re-litigated here.

**Lenses:** promises, recruitment transparency, privacy/consent, invented status, eligibility accuracy, income claims, timing of LinkedIn publicity, operational realism.

---

## 1. What holds up

- **Eligibility.** All eight documents state the rule the same way and consistently with the Commission's how-it-works/FAQ: at least seven EU citizens, old enough to vote in EP elections, residing in at least seven different Member States; nationalities irrelevant; MEPs not counted towards the minimum; representative and substitute; names published in the register. No document invents a documentation requirement or claims the group exists.
- **Status.** Every document says: not filed, not registered, no statements of support collected, group not constituted. Forum advice and the veteran reply are described as external, independent, non-binding feedback, not approval. `LINKEDIN-PACK` opens "Not published; no Page created" and conditions publication on the join page being live, the mailbox working and the initiator's explicit instruction. No Page-created claim anywhere.
- **Income.** "Payments are not promised and would depend on income actually realised by a proposed Reserve" (START-HERE); "Neither payments nor annual increases are guaranteed" (Page About). No response-time, membership or future-income promise found.
- **Targeting/consent.** HOST-CHECKLIST and LINKEDIN-PACK forbid bulk DMs, profile scraping, political profiling, ranking by beliefs or vulnerabilities, sharing passwords, promising roles; require permission before introductions; "inactivity is not consent"; identity documents refused at intake. The 20-minute conversation and single-task structure are realistic for one intake owner.
- **LinkedIn timing.** A single open invitation from a public Page and the initiator's profile, after the site is already live and unannounced outreach has begun, is not premature publicity under the project's own gates; wider collection publicity is expressly deferred.

---

## 2. Material defects (require revision)

### D1. Unpaid status is left open, and one sentence reads as the opposite — START-HERE, all five join pages
The public reader arrives at `/join` from the Page and post. Nothing on the join pages says roles are unpaid. START-HERE says only "Roles need not be paid jobs", which leaves payment open, and the task table's disclaimer is ambiguous:

> "These are examples, not unpaid professional engagements or a promise that anyone has been appointed."

"not unpaid professional engagements" can be read as "not unpaid". The live `/about` says nobody has been paid and there is no bank account; onboarding should say so at the point of recruitment.

**Minimal fix.**
- START-HERE, replace with: "These are examples of volunteer tasks, not professional engagements and not a promise that anyone has been appointed." and replace "Roles need not be paid jobs." with "All roles are currently unpaid; no payment, expenses or future income is offered or promised."
- Each join page, "Ways to help" section, add one sentence: EN "All contributions and organiser roles are unpaid; there is no budget and no payment is offered." (FR/NL/DE/ES equivalents.)

### D2. The planned enquiry tracker and retention are not disclosed to the people it will record — START-HERE, all five join pages
HOST-CHECKLIST plans to store name, address, enquiry date, residence, chosen task, agreed time, owner, next action, sharing permission and status, reviewed at 90 days. The join pages say only "Contact is used to answer the enquiry" and "See about for the controller and your rights"; `/about`'s data section covers server logs, not email enquiries. The join page also promises "Any later change to these arrangements must be explained before it takes effect" — the tracker is such an arrangement and is not explained. START-HERE's "Email is used to answer your enquiry" has the same gap.

**Minimal fix.** Add one sentence to the "What happens to what you send" section of each join page and to START-HERE's last paragraph: EN "If you enquire about contributing, we keep a private note of your name, contact address, residence if you give it, the task agreed and its status; it is reviewed after 90 days and deleted when no longer needed unless you ask us to keep in touch." No system need exist before the sentence is true; it describes the routine HOST-CHECKLIST already adopts.

### D3. Translation files carry front matter mid-document — fr, nl, de, es join.md
In all four translations the block

> `--- source: content/en/join.md / source-commit: 8d35a77 / source-sha256: … / status: machine-reviewed ---`

sits after the "Start in ten minutes" section rather than at line 1. Front matter not at the top is not parsed as metadata: it will render as a horizontal rule plus raw text on a public consent page, and the staleness check keyed to `source-sha256` may not fire. Verify in the rendered build.

**Minimal fix.** Move the block to the first line of each file. Secondary: in the same four files the privacy link `[à propos](/about)` / `[over ons](/about)` / `[Über das Projekt](/about)` / `[acerca de](/about)` sends non-English readers to the English controller/rights notice while the first paragraph correctly uses `/fr/about` etc.; localise it (and `/law/versions` if a localised route exists).

### D4. An ongoing meeting series is implied that does not exist — START-HERE
Task table: "Coordination | Help prepare the **next** open working meeting". No open working meeting is recorded anywhere in the bundle; LINKEDIN-PACK correctly says a question session is offered "only when a host and time are confirmed".

**Minimal fix.** "Help prepare a first open working meeting, if one is scheduled."

### D5. LinkedIn's mandatory Page fields are not resolved — LINKEDIN-PACK
The pack says "Select fields that truthfully describe an unincorporated project; do not claim registered charity/company status, employees or partners that do not exist", but Page creation forces a company type and a company size. For a one-person unincorporated project every size option asserts employees and most type options assert a legal form, which would be exactly the invented status the pack forbids.

**Minimal fix.** Add under "Proposed Page fields": "Type/size: record the exact values chosen and why; if LinkedIn's mandatory type or size fields cannot be completed truthfully for an unincorporated volunteer project, post from the personal profile only and do not create the Page."

---

## 3. Minor (fix if convenient; not blocking)

- START-HERE: "review the **registered objectives** it would seek" reads as if objectives are registered → "the objectives it would seek to register."
- START-HERE uses "we"/"We discuss"/"We ask" while HOST-CHECKLIST and `/about` show one person. One clause suffices: "At present 'we' means the initiator and any volunteer who has agreed a task."
- LINKEDIN-PACK: `[Page types](…/answer/a727945)` is not among the sources verified on 7 September; verify or drop.
- LINKEDIN-PACK first post opens with the book; `/about` already declares the interest. Optional clause: "no book proceeds fund this and nothing here links to it."
- Join pages dated "As of 6 September 2026" while `/about` and the release are dated 7 September; nothing material changed, but align on deployment.
- es/join.md mailto subject `organizacion` lacks the accent.

---

## 4. Operational realism and consent, summary
Single intake owner, no auto-replies, no response-time promise, 90-day review, task-scoped access, manual fallback: coherent and honest for current capacity. Consent architecture (ask before introducing, no list, no forwarding, close on request) is sound once D2 makes the tracker visible to the people it concerns. Nothing in the pack or checklist requires legal clearance before inviting scrutiny, and none is demanded here.

VERDICT: REVISE
