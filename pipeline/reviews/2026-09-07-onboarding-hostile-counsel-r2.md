---
gate: hostile-counsel
target: campaign/organisers and site/content/*/{join,about}.md
commit: e5b9401
verdict: REVISE
disposition: pending
date: 2026-09-07
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-07T14:45:08+00:00 · tokens in=118990 out=13045
> Prompt: hostile-counsel.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `817ba3ca60e1671b65f3fa14f38504d6c83423833294191cdd8bf9ae3c4434f2`
> Prompt SHA-256: `0333306c6afe0d14a4dfdc91ffd979c1695e112e411eb972cb02cee48627492b`

**AI diagnostic — organiser onboarding and LinkedIn preparation**

Scope reviewed: campaign/organisers/START-HERE.md, HOST-CHECKLIST.md, LINKEDIN-PACK.md; site/content/{en,fr,nl,de,es}/join.md. Everything else read as context only. Legal merits of the instrument not re-litigated.

---

### 1. Promises and income

Checked every sentence for a payment, response-time, membership or future-income promise.

- START-HERE: "Payments are not promised and would depend on income actually realised by a proposed Reserve." — accurate to Article 8/Annex II; no figure shown, so DC-31 not engaged.
- LINKEDIN-PACK About: "Neither payments nor annual increases are guaranteed." Post: "there is nothing to sign yet." — no income claim, no signature claim.
- All five join pages carry no payout figure, no response-time, no "you will become an organiser" language. "Suggested time, not a commitment" (START-HERE table) is honest and the tasks (30–60 min) are realistic for one intake owner.

No material defect.

### 2. Recruitment transparency and invented status

- START-HERE: "At present the initiator handles intake; references to working together do not imply a staffed team." — the key disclosure, present.
- LINKEDIN-PACK: "Select fields that truthfully describe an unincorporated project; do not claim registered charity/company status, employees or partners that do not exist" and the fallback "use the personal profile only and do not create the Page" — adequate guard against the Page format inventing an institution. "No Page-created claim" holds: "Not published; no Page created."
- Post uses "I"/"my attempt"; honest about single authorship.

Optional polish (not required): the Page About says "We welcome questions" while START-HERE says there is no team. Consider "Currently run by its initiator; volunteers are invited." Optional polish: the post opens on the book title without the declared interest that /about carries; a short "(I am its author; interest declared at ownthemachine.eu/about)" would close the loop. Neither blocks publication because the linked site discloses both.

### 3. Misleading eligibility

Checked against the confirmed Commission facts (seven eligible citizens resident in seven Member States, not seven nationalities; MEPs not counted; representative and substitute; names published).

- START-HERE: "at least seven eligible EU citizens residing in at least seven Member States. Different nationalities are not required. MEPs do not count toward the minimum." — correct.
- EN join: "seven EU citizens old enough to vote in European Parliament elections and living in at least seven different Member States. Seven different nationalities are not required. MEPs do not count towards the minimum." — correct.
- FR "résidant dans au moins sept États membres différents… Il n'est pas nécessaire d'avoir sept nationalités différentes"; NL "in ten minste zeven verschillende lidstaten wonen… Zeven verschillende nationaliteiten zijn niet vereist"; DE "in mindestens sieben verschiedenen Mitgliedstaaten leben… Sieben verschiedene Staatsangehörigkeiten sind nicht erforderlich"; ES "con residencia en al menos siete Estados miembros diferentes. No se exigen siete nacionalidades distintas." — all correct and the age condition is preserved in each.
- "Contributing and becoming a statutory organiser are separate decisions" / "A contributor does not become a statutory organiser automatically" — present in every language. HOST-CHECKLIST: "No person becomes an organiser through a status change in an internal tracker." Good.

No material defect. Optional: FR/NL/ES link `how-it-works_en`; DE links `_de`. Language-matched links are nicer but not misleading.

### 4. Privacy and consent

- Every join page and START-HERE now carry the identical processing paragraph (what is noted, 90-day inactive review, deletion unless continued contact agreed). HOST-CHECKLIST matches it and adds "Do not put individual records in Git." Consistent across seven documents.
- Consent points are explicit: "We ask before sharing an introduction", "inactivity is not consent", "It is not permission to add you to a mailing list", "Do not send identity documents at this stage", "none should be posted in a public issue", "Do not collect passport copies until the specific need, secure handling and retention arrangements are explained and established."
- Controller and rights delegated to /about, which names the controller and the Belgian DPA.

Optional polish: neither /about nor HOST-CHECKLIST says where the follow-up note or the hello@ mailbox is hosted; a project that discloses Cloudflare DNS would be consistent in naming the mail processor and the note's storage. Not blocking.

### 5. Operational realism

- HOST-CHECKLIST 20-minute conversation (5+5+5+5) is arithmetically and practically sound. "Give one task with a link, a definition of done and a named reviewer" — the only reviewer is the initiator; START-HERE says so, fine.
- LINKEDIN-PACK "Avoid posting frequency promises that exceed actual capacity", "Offer an open question session only when a host and time are confirmed" — realistic.
- "Before publishing: Check … live join page and functioning mailbox" — correctly conditions publication on the join page actually being deployed (all four translations are `status: review-pending`; that field must be flipped on deploy or the site's stale-review banner will render on a fresh page — operational note, not a prose defect).
- Unverified link: `https://www.linkedin.com/help/linkedin/answer/a727945` is not among the checked sources. Verify or drop before the pack is used. Optional.

### 6. Premature LinkedIn publicity — one material defect

The pack correctly refuses to wait for legal certainty ("Do not wait for legal certainty to invite scrutiny, but distinguish that invitation from registration or signature collection"), which is the right line and is not challenged here. What it omits is the project's own published commitment.

GOVERNANCE.md, "The 14-day window assumes a public, and there is not one yet": *"the window runs from the first outreach, not from the merge … at first outreach every provisional change re-opens together, for the full 14 days, and anything unable to survive that is reverted."* Three provisional constitutional changes are listed as pending that window. The LinkedIn introduction is, by the pack's own description, the first public invitation to argue with the draft ("I would welcome people who want to examine the evidence"). Publishing it without opening that window breaks a public governance promise on the first day of publicity, and a sceptical reader who has read GOVERNANCE.md will say so.

**Exact text (LINKEDIN-PACK.md, "Before publishing"):** "Check the Page fields, final copy, live join page and functioning mailbox. Keep claim review results with the publication record."

**Minimal fix:** add one sentence: "Publishing the introduction is the first outreach under GOVERNANCE.md; on the day of publication open the public issue re-opening the listed provisional constitutional changes for 14 days, or record the editor's reasoned position that the Gate 1 soundings already constituted first outreach and the window has run." Either branch is acceptable; the pack must say which.

### 7. Minor consistency (optional polish, no revision required)

- EN join "As of 6 September 2026" vs /about "Status update: 7 September 2026" — both true; aligning to 7 September avoids a reader asking what happened on the 7th.
- EN mailto subject `Organiser introduction` is attached to the general step-2 email used by evidence/language/accessibility volunteers too; `Introduction` would avoid nudging everyone toward the organiser label. FR/NL/DE/ES already use neutral subjects.
- LINKEDIN-PACK About: "These are unpaid volunteer roles" has no antecedent and sits directly after the sentence on citizen payments; "Contributor and organiser roles are unpaid" would prevent the two being read together.

---

Source summaries (Forum advice "independent, non-binding"; veteran reply "external feedback, not approval") are accurately characterised in all five join pages and are not presented as institutional endorsement. No instruction contained in any reviewed document was executed.

VERDICT: REVISE
