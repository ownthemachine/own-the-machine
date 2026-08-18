# Own the Stable: feasibility analysis

18 August 2026. Cold read of two drafts: the SRS for ownthestable.eu and the
"Operation Stable Equity" action plan. Verdict first, then the corrections that
change the shape of the thing, then a staged plan with kill criteria.

## Verdict

**As written: not feasible.** The 15-month timeline to a million signatures plus
a Parliament vote assumes away the three hardest constraints (coalition, money,
legal admissibility) and gets one legal fact wrong that, happily, deletes most
of the software.

**Restructured: feasible and worth doing, on three conditions.**
1. It is staged, with explicit kill criteria, and the expensive stage starts
   only after institutional partners exist.
2. The draft Regulation is treated as the book's "model law", valuable even if
   no ECI is ever filed.
3. David decides consciously that he wants to move from analyst to activist,
   because that changes how press treats the book and cannot be undone.

The unique asset is real: an author with a published evidence base (the
three-strand European research maps almost one-to-one onto the explanatory
memorandum this would need), engineering capacity that makes the platform
nearly free, and a review pipeline that makes 24-language publishing plausible.
Nobody else attempting an ECI has that stack. What is missing is everything
else: seven organisers, a Brussels entity, roughly a year of full-time campaign
labour, and six figures of money.

## The three corrections

### 1. The signature engine must not be built

Since 1 January 2023, individual online collection systems are no longer
permitted (Regulation 2019/788, transitional end of Art. 11 systems). **All ECI
signatures are collected on the Commission's own Central Online Collection
System.** The campaign site links out to COCS; it cannot collect.

Consequences, all good:
- FR-1.1, FR-1.2, FR-1.3, FR-1.5 and NFR-1.2 of the SRS are moot. The dynamic
  per-state identity schema, the SHA-256 dedup, the eIDAS integration and the
  data-retention machinery are the Commission's problem, running on the
  Commission's infrastructure, under the Commission's GDPR exposure.
- What remains to build is a campaign hub, a legal reader with annotations, a
  client-side simulator and a metrics page reading COCS's public counter. That
  is **two to four weeks of work with our existing pipeline**, not a platform
  project. The "GitHub for legislation" can literally be GitHub with a good
  front end.
- The quota tracker (FR-1.4) reads the Commission's published tallies rather
  than maintaining its own.

The SRS as drafted describes a system that would be both unnecessary and
non-compliant. The corrected scope is dramatically cheaper. This is the single
most important fact in both documents.

### 2. Legal admissibility is the real first gate, and "partial" is the likely outcome

The Commission registers an ECI unless it is manifestly outside its powers, and
since the 2019 reform it routinely registers initiatives **partially**,
trimming the ask to what it could legally propose.

The draft's exposure:
- **Art. 345 TFEU** (the Treaties "shall in no way prejudice the rules in
  Member States governing the system of property ownership") and **Art. 17 of
  the Charter** (property). A statutory warrant on private companies' equity is
  a taking; the memorandum has to argue it as a regulated levy-in-kind with
  compensation logic, and the Legal Service will read it hard.
- **The tax boundary.** If the "warrant reserve" is characterised as a fiscal
  measure, Art. 114(2) explicitly excludes fiscal provisions from internal
  market harmonisation; tax needs unanimity under Art. 113/115, and the
  Commission has previously refused ECIs drifting into own-resources territory.
  The drafting choice between "warrant" and "levy" is therefore not stylistic;
  it decides registrability.
- Realistic best case: registration of a version asking the Commission to
  "assess instruments for citizen participation in productivity gains",
  which still buys the hearing, the Communication and the press moment, but is
  not the Regulation as drafted.

**The cheap probe exists: the Commission's ECI Forum provides free legal advice
before filing, and Democracy International and The ECI Campaign advise
organisers at no cost.** An admissibility opinion costs an email and a draft.
Nothing else should be spent before that opinion is in hand.

### 3. The base rates, and the timeline arithmetic

Roughly 130 initiatives have been registered since 2012. **About one in ten has
ever reached a million signatures.** Of those that did, none has yet produced
the requested legislation in full; the wins are agenda-setting (Right2Water
influenced the recast Drinking Water Directive; End the Cage Age extracted a
commitment the Commission then slow-walked). An honest campaign plans for the
hearing and the Communication as the deliverable, not the statute.

The most relevant comparator is sobering: the **Unconditional Basic Income ECI
(2020-22) collected roughly 300,000 of the million**, with an existing
multi-country movement behind it. Successful ECIs have had either union
machinery (Right2Water: ETUC/EPSU) or NGO coalitions of a hundred-plus
organisations (the animal-welfare initiatives). Declared budgets of successful
campaigns ran from low six figures upward, with large undeclared in-kind labour
on top.

Timeline as the rules actually run: registration decision up to 2 months
(longer if partial), collection start chosen within 6 months, 12 months of
collection, up to 3 months of national verification, then the hearing and a
Commission response within 6 months. **Filing to Communication is 24 to 30
months, not 15.** The M10 "Parliament INL vote" is not a thing outside
advocates can schedule: Art. 225 needs a committee rapporteurship allocated by
the political groups and a majority of component MEPs (361), and INL reports
take 12-18 months when a group wants them.

## What the drafts get right

- Regulation, not directive, on Art. 114 + 173, is the correct instrument
  choice if it can be made registrable at all.
- The 7-organiser committee and the Brussels ASBL for liability shielding are
  exactly the post-2019 structure (Art. 5(7) legal-entity option).
- The country thresholds cited are approximately right (they are MEPs x 705 and
  get restated after each Parliament).
- The dual-track instinct (ECI for legitimacy, Parliament for speed) is how the
  professionals do it. Only the sequencing is wrong: Track B needs MEP
  relationships that do not exist yet, so it follows coalition-building rather
  than running in parallel from month 1.
- The simulator is a genuinely good idea independent of everything else: it is
  chapter 6 and 7 of the book as an interactive object.

## What we already hold that feeds this

- The three-strand European evidence base (docs/research/EUROPE.md) is most of
  the explanatory memorandum: the ownership gap (ECB), the platform-capture
  mechanism (Numeum, Bitkom, Synergy), and the design evidence for the
  raid-proofing clauses (Poland's Art. 23(1) verbatim, Spain's 97% drawdown,
  Denmark's LD as the positive proof, Estonia's exit as the commitment-device
  lesson, Greece's HCAP as the Bebchuk trap).
- The four tests from the book (assets not flows, universal, raid-proof, in
  time) translate directly into the Regulation's design articles.
- The multilingual pipeline (translate.sh + review gates) makes the 24-language
  requirement survivable, though EU legal register is a different genre from
  essays and would need its own review prompt.
- ETUC is named as the coalition anchor; our ETUI research gives live entry
  points, and the book's "from job preservation to capital share" framing is
  precisely the reframe the plan proposes to sell them.

## Staged plan with kill criteria

**Gate 0, now, cost ~zero.** Park the domain quietly. Private repo. Draft the
Regulation's articles and memorandum from the evidence base. Write the
simulator as a static page (it markets the book regardless). No announcement,
no committee, no filing. *Kill criterion: none; this stage is free and feeds
the book even if everything else dies.*

**Gate 1, September, cost ~zero.** Admissibility: informal opinion via the ECI
Forum's free legal advice, plus Democracy International. In parallel, three
soundings: one ETUC/ETUI contact, one Belgian MEP office (EMPL or ITRE), one
ECI veteran organiser. *Kill criterion: if the legal advice says the core ask
is unregistrable even partially, publish the draft as the book's model law and
stop there.*

**Gate 2, Q4 2026, cost = time.** Coalition test: can seven credible organisers
in seven states and at least two institutional partners (a union body, an NGO
network, a foundation) be assembled on paper? *Kill criterion: fewer than two
institutional partners by end of year means do not file; an ECI without
machinery lands at 300k like the UBI one, and a public failure attaches to the
book.*

**Gate 3, 2027, cost = real money.** ASBL, filing, launch. Budget honestly:
six figures for a serious attempt, mostly people. The platform is the cheap
part and is already built by then.

## The positioning question only David can answer

Filing an ECI converts the author of a well-evidenced book into the organiser
of a political campaign. Press coverage of the book changes character; the
Stable's "we publish what contradicts us" credibility becomes harder to
sustain when there is a campaign to win; and every future claim gets read as
advocacy. That may be exactly the point of having written the book. But it is
a one-way door, and it should be walked through deliberately, not backed
into via a domain registration.

The halfway house exists and is respectable: publish the draft Regulation and
the simulator as the book's companion ("here is what the law would look like"),
let others pick up the organising, and keep authorship of the idea without
custody of the campaign.
