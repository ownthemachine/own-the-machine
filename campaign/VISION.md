# Own the Machine: the vision

18 August 2026, stated by David after reading the feasibility analysis:

> A draft regulation that is high quality and open source, with a full
> campaign. The book is the research of what is the best architecture with all
> the challenges; the legislation proposal is the roadmap to implementation.
> Everything open source, including the website.

## Why open source is the load-bearing decision, not a preference

The feasibility memo ended on a one-way door: filing an ECI converts the
analyst into an organiser. Open-sourcing the law is the third option that
dissolves it. **A regulation with a public commit history is authorship
without custody.** David remains the person who published the architecture;
the campaign belongs to whoever forks it. If a union federation, a party
group or seven citizens in seven states pick it up, the ECI happens without
the book's credibility being staked on a signature count. If nobody does,
the artefact still stands as the book's implementation chapter, versioned
and improvable in public.

It also converts the ECI's worst statistic into a feature. Nine in ten
initiatives fail at collection; an open-source law cannot fail that way,
because collection is not its success condition. Adoption is, and adoption
has many doors: an ECI is one, an Article 225 rapporteur looking for a
pre-drafted text is another, a national party manifesto is a third.

## The mapping

| Book | Regulation |
|---|---|
| The diagnosis (ch 1-5) | Recitals: the evidence base, now with European numbers |
| The four tests (assets not flows, universal, raid-proof, in time) | The design articles |
| Ch 6, architecture of access | The instrument: the warrant/reserve mechanism |
| Ch 8, Norway and Alaska + Denmark's LD | The fund's governance and the individual claim |
| Ch 9, the Bebchuk trap + Greece's HCAP | The voting and passivity provisions |
| Ch 10, when the market falls + Poland Art. 23(1), Spain's 97% | The raid-proofing clauses, drafted against the actual raid statutes |
| Ch 11-13, the honest limits | The explanatory memorandum's own counter-arguments section |

The Regulation should do what the Stable does: carry its own counter-evidence.
A draft law whose memorandum states the strongest case against itself is as
unusual in Brussels as the Stable is on LinkedIn, and for the same reason.

## The third layer: the explanation, added by David 18 August

> We use the argumentation of the book in general public explanations, FAQ,
> etc., to guide the European people.

So the full stack is three layers, each with a different reader:

| Layer | Reader | Register | Already exists as |
|---|---|---|---|
| The book | someone willing to read 378 pages | evidence, hedged | the book |
| The regulation | lawyers, MEP staff, the Legal Service | EU legal drafting | to be written |
| **The explanation** | **a citizen deciding whether to sign** | **plain language, 24 languages** | **the Questions essays and the leesgids, in prototype** |

The third layer is not new work in kind. The Questions series is exactly this
genre: one real question, a thousand plain words, no economics degree needed,
gated and translated. The reading guide already ends with the four tests phrased
as a citizen's instrument: "you can apply them yourself to any plan you hear
about in the news." A campaign FAQ is those two formats pointed at one specific
plan, ours.

What the explanation layer needs that the essays did not:

- **Answers to the hostile questions first.** "Is this not just a tax?" "Why
  would companies stay in Europe?" "What happens to my pension?" "Who controls
  the fund and why would politicians not spend it?" The Polish and Spanish raid
  evidence, Denmark's LD and the Estonian exit are the answers, and they are
  already written up in docs/research.
- **The Stable's honesty discipline, kept under campaign pressure.** The FAQ
  states the strongest objection fairly before answering it, and says plainly
  what the instrument cannot do (the positional-goods chapter). Guidance that
  hides the weak points is campaign copy, and campaign copy is what every other
  initiative produces. The differentiator is the same one the book has.
- **All 24 languages, prioritised by ECI thresholds**, not alphabetically:
  the seven committee countries first, then the largest remaining quotas.
- **The simulator embedded beside the FAQ**, so "what would this mean for me"
  is answered by the reader's own inputs rather than by a promise.

## Licensing, decided early because retrofitting is painful

- **Legal text and memorandum:** CC BY-SA 4.0, same as the Questions essays.
  Share-alike matters: a fork that improves the law must stay open.
- **Website and simulator code:** AGPL-3.0 for the platform, so a hosted fork
  stays open too. MIT for small embeddable pieces (the simulator widget) where
  spread beats copyleft.
- **Data (simulation parameters, evidence tables):** CC0 with a citation
  request, so academics can use them without friction.

## Repo skeleton (to create in the dedicated session)

```
own-the-stable/
  regulation/            the law itself, one file per article, EN master
    recitals/
    articles/
    memorandum/          incl. counter-arguments.md, evidence.md
  translations/          24 langs, machine-first + gate, EU legal register prompt
  simulator/             client-side, no backend, embeddable
  site/                  campaign hub; links OUT to COCS, collects nothing
  evidence/              imported from the book repo's research notes
  campaign/              organiser kit, thresholds, ECI-forum correspondence
  GOVERNANCE.md          how changes to the law are proposed and merged
  LICENSING.md
```

GOVERNANCE.md is the novel part and deserves real thought: who merges changes
to a draft law, and by what test? The book's four tests are the natural merge
criteria: a PR that makes the instrument less universal or less raid-proof
fails review by definition.

## What Gate 0 produces (the dedicated session)

1. The repo, private until the text is defensible.
2. Articles drafted from the four tests; memorandum assembled from
   docs/research/EUROPE.md and the three strand notes.
3. The counter-arguments chapter, written first, not last.
4. The admissibility question framed for the ECI Forum's free legal advice:
   warrant versus levy, Art. 114 versus 115, partial-registration fallback.
5. The simulator spec cut down to what FR-3 should have been: client-side,
   exportable, honest about parameter uncertainty.

Explicitly NOT in Gate 0: any announcement, the domain going live, committee
recruitment, filing anything. The text earns its public moment by being good.

## Constraints carried over from the feasibility memo

- All signatures live on the Commission's COCS; the site links out and
  collects nothing. This is settled law since 2023, not a choice.
- The realistic registration outcome is partial; draft the ask in severable
  layers so the Legal Service can trim without gutting.
- Base rate honesty stays in the public memorandum: one in ten ECIs reaches a
  million; none has yet produced its statute. The open-source framing is the
  hedge against exactly this.
