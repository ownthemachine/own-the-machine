---
gate: layer-fidelity
target: campaign and website claim corrections
commit: ed351bc
verdict: REVISE
disposition: see-claims-disposition
date: 2026-09-06
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-06T18:59:28+00:00 · tokens in=139917 out=20135
> Prompt: otm-layer-fidelity-claims.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `9f52db9be44b15ee862f8cde7af0a4384118b9ef82b07555e1753a11653faf1b`
> Prompt SHA-256: `939b63c5e05bcb81a5b2f14b30267e0091dfb7a7665c58132ddd6811396968a8`

# Layer-fidelity review: claim corrections of 6 September 2026

Scope applied as instructed: the corrected plain-language pages (brief, faq, join, sign, press, about, contribute), the English dictionary, the registration text, campaign guidance (DISTRIBUTION.md, REVIEW-AND-LAUNCH-PLAN) and the tooling, read against the enacting terms, recitals and memoranda as reference. Unchanged legal defects are listed separately at the end and do not drive the verdict.

The headline: the five "Immediate" items in the launch plan's correction table are in fact corrected in the pages supplied (seven-year trigger now stated everywhere; thresholds described as a rebuttable presumption with an investigation route; tax answer now conditional; status dated and the Forum reply described as independent and non-binding; raid resistance stated as barriers, not invulnerability; Belgium 15,840 in both the sign page and DISTRIBUTION.md). DC-14 and DC-23 are respected on every page I checked. What remains is narrower, but two of the remaining items sit in the registration text, which is the one plain-layer document the Commission itself will read.

---

## 1. OVERCLAIM

### 1.1 Registration text calls the Reserve "passive"; the memorandum's own constraint forbids the word (registration prose)

Plain layer, campaign/REGISTRATION-TEXT.md §4:
> "The reserve would hold the resulting shares passively and without votes, insulated in both directions from Union and national budgets."

Memorandum layer, counter-arguments.md, DC-41 discussion:
> "The word to avoid is passive. The Reserve does assert claims: Article 5(4)(b) fixes its rank and Article 5(10) makes subordinating arrangements ineffective against it, and an opponent will call that anything but passive. The defensible claim is narrower: the Reserve holds no votes, appoints no one, and has no say in the management of the undertaking."

Articles: 5(4)(b) (ranking with the most favourable post-designation class), 5(10) (subordinating arrangements ineffective against the Reserve), 9(2) (management of holdings for preservation and growth).

Reader harm: the registration officer, and any covered undertaking's counsel who reads the register, is told the Reserve is inert. The articles give it a protected rank and an anti-subordination shield, and hostile counsel has already characterised those as a constraint on capital structure. The word hands the first credibility attack to the Commission's own file: the initiative says one thing in its registration text and its published objections say the opposite.

Minimal fix (plain layer, registration text): replace "passively and without votes" with "without votes, board seats or any say in management". Recital 23 and memorandum §2.4 use the same word; that is a pre-existing inconsistency inside the legal/explanatory layers and is listed below, not charged to this package.

### 1.2 Registration text: "nothing is payable in cash"; Article 5(5) requires a cash payment (registration prose)

Plain layer, REGISTRATION-TEXT.md §4:
> "Deliberately, nothing is payable in cash, nothing enters any public budget, and no undertaking is required to sell anything."

Article 5(5), last sentence:
> "the Reserve shall pay up the shares in full in cash at their nominal value upon execution."

Reader harm: the sentence is literally false as drafted. The direction of the flow (Reserve to undertaking, at nominal) is the opposite of the fiscal-characterisation worry and does no harm to the DC-4 argument, but a reviewer who checks the sentence against Article 5(5) finds a contradiction in the one paragraph meant to carry the non-fiscal claim. Brief and home get this right ("settled in shares; it does not itself generate cash for citizens").

Minimal fix (plain layer): "no undertaking pays anything in cash, nothing enters any public budget, and no undertaking is required to sell anything."

### 1.3 Dictionary and contribute page claim six gates run before "any text" merges; governance says otherwise (dictionary string, contribute page)

Plain layer, en.mjs `ledger.intro1`:
> "Before any text of this Regulation merges, it passes six adversarial gates"

and contribute.md:
> "Mechanical constraints ... and six adversarial review gates apply before merge."

Governance layer, GOVERNANCE.md change classes and pipeline/README.md "Which gates when":
> "Editorial changes: lint only. Prose changes: lint + gates 1 and 6. Substantive changes: lint + all six."

Reader harm: a reader who later finds a recital wording change merged on two gates concludes the site overstated its own process. The ledger is the credibility surface; a process claim on it that the governance file contradicts is the cheapest thing for a journalist to catch.

Minimal fix (plain layer): "Before any change to the enacting terms merges, it passes six adversarial gates; lighter changes run the gates their class requires (see GOVERNANCE)."

---

## 2. UNDERDISCLOSURE

### 2.1 The FAQ answers "when?" without the Article 10(6) interval rule (FAQ, brief, press)

Plain layer, faq.md "Do I get money? How much, and when?":
> "every EU citizen aged 18 or older would have an equal right to distributions when declared ... Amounts depend on the fund's realised income after costs and retention rules and could be zero."

Article 10(6):
> "The Reserve shall declare a distribution in each calendar year in which the distributable amount would provide each holder with not less than ten times the average cost of executing one payment to a holder ... and in any event not less often than once in every third calendar year in which the distributable amount is greater than zero. An amount not distributed by reason of this paragraph shall be retained ... and shall be distributed in the next distribution."

Reader harm: "when declared" tells the reader nothing about frequency. The articles say that in the early decades payment may arrive once every three years, with small amounts held back and rolled forward. A reader who signs expecting an annual payment (the simulator's chart is annual) has been told less than the instrument says about timing. Not a shading of size, which every page handles correctly, but a silent omission on the one question the FAQ heading itself asks. The simulator's assumption list already discloses that "payment-frequency rules" are not modelled, so the gap is the FAQ's alone.

Minimal fix (plain layer, FAQ; one sentence): "While amounts are small, the Reserve may declare a distribution only once every three years; anything not paid is held and added to the next payment (Article 10(6))."

---

## 3. TERM DRIFT

### 3.1 "Backstop" means two different things across layers

Plain layer (home col1, brief, FAQ, press, registration text, simulator assumptions):
> "the seven-year backstop from warrant issuance"

Legal/explanatory layer, recital 12 and the Article 5 and 17 drafting notes:
> "The seven-year long-stop answers a case the liquidity-event and extraction triggers do not reach"

Meanwhile the memorandum uses "backstop" for a different rule, Article 10(6): DC-40 "a hard backstop of one distribution in every three years", Article 10 notes "The three-year backstop is what stops a de minimis from becoming a reason never to pay."

Reader harm: a reader moving from the FAQ to the objections file meets "backstop" attached to the payout interval and "long-stop" attached to the warrant, and has to work out that the FAQ's "backstop" is the memorandum's "long-stop". Two concepts, one word, distributed across the layers.

Minimal fix (plain layer): use "seven-year long-stop" throughout, matching recital 12, or, if the campaign prefers the plainer word, add "(the 'long-stop' in the draft)" once on the FAQ and leave "backstop" to the distribution rule.

### 3.2 The contribute page misstates the fourth test

Plain layer, contribute.md:
> "it claims the stake in time, at the moment gains crystallise."

Governance layer, GOVERNANCE.md, fourth test: a change fails if it makes the instrument
> "later (moving obligations past the formation of the gains)."

and Article 3(7): "designation shall precede any liquidity event wherever the thresholds of paragraph 2 are met before that event."

Reader harm: the in-time doctrine is that the claim attaches before crystallisation (at designation, while the asset forms) and only converts at the event. "At the moment gains crystallise" describes the conversion and would, taken literally, pass a PR that moved the warrant obligation to the liquidity event, which is exactly what the fourth test exists to reject. Contributors read this page to learn the merge criteria.

Minimal fix (plain layer): "it claims the stake in time, before the gains are formed, and converts it only when they crystallise."

### 3.3 "Fund"/"dividend" beside "Reserve"/"distribution" (low)

Plain layer: faq.md one-sentence answer "a common fund"; FAQ heading "Who controls the fund?"; simulator title "The dividend, honestly"; the launch plan's suggested homepage line "a European fund".

Articles: 'Reserve' (Article 2(5)), 'distribution' (Article 2(12)); Article 8(7) provides it is not an investment fund or AIF; recital 21 "rather than a fund of the Union".

Reader harm: modest. "Fund" is the ordinary word and the memorandum itself compares to Norway's; but "European fund" in particular invites the "Union fund" reading recital 21 works to exclude, and "dividend" implies the regular corporate payout the articles do not promise. The tagline ("so the dividend follows") is a fixed communications asset and can stay.

Minimal fix (plain layer, optional but cheap): in explanatory prose use "the Reserve" on first mention with "(the fund)" once, and "distributions" rather than "dividend" outside the tagline; strike "a European fund" from the launch plan's suggested copy in favour of "a common Reserve owned by citizens".

---

## 4. Tooling and campaign guidance: checked, no fidelity finding

- review.sh, README, .env.example, tests and about.md "Where the review runs" agree with one another: EU and no-training checks stay on; the retention exception is explicit, per-run, Fable-only, stamped in provenance; Astra resolves only if listed and is never substituted. About.md's disclosure matches the README's. No page in the bundle claims Astra ran.
- DISTRIBUTION.md now carries 15,840 and the simulator-share rule (assumptions and both figures on every card, DC-31) matches the code, which emits stake beside payout at years 20 and 50.
- The launch plan's ECI facts match the bundle's checked facts. Its budgets are labelled scenarios. One housekeeping note: its §1 correction table describes defects the pages now fix (thresholds "MEPs × 750", Belgium 15,510, Forum "due 2 September"); under the project's own practice each row should carry a disposition so the plan does not read as a list of open defects.

---

## 5. Pre-existing, outside this package (reported, not charged)

1. **Article 5(4)(e) v Article 5(3).** 5(4)(e): the warrant shall "impose no obligation on the covered undertaking prior to a liquidity event other than the notification obligation in paragraph 6." But crystallisation under 5(3) occurs "before a liquidity event" and imposes execution (5(5)), valuation cost (6(3)) and issuance obligations; and 5(6) requires notification only of an impending liquidity event, never of an extraction crystallisation. The launch plan flags this for counsel; it is a genuine internal inconsistency in the enacting terms. Fix belongs in the articles ("prior to crystallisation").
2. **"Passive" in the legal and explanatory layers.** Recital 23 ("The Reserve should be a passive owner") and memorandum §2.4 ("the holding is passive") use the word DC-41 tells the campaign to avoid. Finding 1.1 above inherits this.
3. **Memorandum §4 cross-reference (EN and FR):** "Article 10(6) caps the fees national vehicles may levy" — the cap is Article 11(3); Article 10(6) is the distribution-interval rule.
4. **Memorandum §3.3** says distributions are made "from the age of majority"; Article 10(1) says 18, which is not the age of majority in every Member State.
5. **Stale drafting note, Article 5:** "it now measures against covered turnover and against capital actually paid in" survives in the same note that later records the paid-in limb was deleted. Non-normative, but the EXTERNAL-REVIEWS file records exactly this failure mode (stale summary hides a defect from the authors).
6. **FR memorandum** lacks the 6 September paragraph in §2.1 on the single-citation preamble and the two-act form for Article 352; it should carry the `banner.stale` string until refreshed.
7. **Simulator display floor:** `fmt` renders any value below 0.1 as "0.1", so the sentence can never show the zero the labels say is possible. Arithmetic is out of scope for this run; the display should be allowed to print 0.
8. Memorandum §2.1 cites "the legal-form and legal-basis gates of 6 September 2026 (pipeline/reviews)"; those files are not in the bundle and the claim is unverified here.

---

## Disposition

Findings 1.1, 1.2, 2.1 and 3.2 are contradictions between changed plain-layer pages and the instrument or its governance; 1.1 and 1.2 sit in the registration text itself. Each is a one-sentence fix in the plain layer; none requires touching an article. Until they are made, the corrected package is not publishable against the present draft.

VERDICT: REVISE

## Editor disposition (prepared for final editorial review)

The model output above is preserved verbatim. See
[the claim-correction disposition](https://github.com/ownthemachine/own-the-machine/blob/main/pipeline/reviews/2026-09-06-claims-disposition.md) for
accepted fixes, scope decisions, provenance qualifications and remaining
legal findings. A PUBLISH applies to this submitted snapshot only; it is not
legal approval or clearance of the entire instrument.
