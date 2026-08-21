---
gate: legal-form, dc-compliance, legal-basis, hostile-counsel, acquis-coherence, layer-fidelity
target: the full instrument after the recitals were rewritten
commit: df9b08b
verdict: PUBLISH on legal-form, dc-compliance and layer-fidelity; REVISE on acquis-coherence; standing findings on legal-basis and hostile-counsel
disposition: merged-with-fixes, residue recorded
date: 2026-08-21
---

# Editor disposition (21 August 2026)

All six gates were run on the whole instrument, which had not happened
since the articles were amended on 21 August. The ledger had been showing
verdicts taken at cb3da17 against a text that had moved twice since, which
is worth as much as a green check on a stale premise, that is to say
nothing. This record closes that.

## What the gates found and what was done

**layer-fidelity** found three, all accepted, and two of them were real
bugs in the enacting terms rather than in the description:

* Article 17(2) stated exhaustively when an already-listed undertaking's
  warrant crystallises, which made it a lex specialis excluding Article
  5(3). The transitional provision would have exempted precisely the
  undertakings the extraction trigger and the long-stop exist to reach.
  An earlier pass had concluded the drafting note was stale and the
  article sound; the gate was right and that conclusion was wrong.
* Article 4(3) lapsed an uncrystallised warrant five years after repeal
  "if no liquidity event has occurred". A warrant that had properly
  crystallised under Article 5(3) would have lapsed anyway, because no
  liquidity event took place. The condition is now crystallisation.
* Layer 2 of the severability memorandum still described the warrant as
  crystallising on a liquidity event alone.

**legal-form** found four, all accepted: Article 8(5) referred the
withholding figure to Article 14(1), the indicators, rather than Article
14(2), the report; the Charter recital omitted Article 34; a recital used
the mandatory "must"; and a recital stated a disapplication in the
indicative, which is an operative command in a place that may not carry
one.

**acquis-coherence** found two in the first run, both accepted: Article
5(7) did not disapply Article 73 of Directive (EU) 2017/1132, which is the
provision extending the pre-emption regime to securities carrying a right
to subscribe for shares, in other words to this warrant; and Article 5(8)
exempted the shares from the prospectus regime without exempting the
issuance of the warrant itself.

**hostile-counsel** produced the standing attacks on characterisation,
which the severability memorandum already records and answers by layering,
and one structural kill that was not standing and was not known:

> Article 5(11) required a transferee to issue its own warrant while the
> transferor's obligations continued "unaffected". A group dividing its
> automated assets among five subsidiaries would have owed 3 % from each
> of them and 3 % from the parent. The multiplier broke Article 7(2) and
> the 3 % ceiling, which is the proportionality anchor of the entire
> instrument and the sentence every defence of it rests on.

This was fixed rather than recorded. The transferor now remains bound in
respect of the automated assets it retains, the aggregate subscription
across the covered undertaking and every transferee is capped at the
stated percentage of their combined fully diluted capital, Article 7(2)
states the same cap on the same aggregate basis, and the anti-avoidance
recital now says plainly that anti-avoidance is not to become a
multiplier. Note how the defect surfaced: DC-37 had described this
provision as attaching "pro rata to value", which was the rule before the
article was amended. Correcting the table to describe what the article
actually said is what made the multiplier visible. A Design Consequence
that misdescribes its article does not merely mislead a reader, it hides
the bug from the drafters.

**legal-basis** produced the standing Tobacco Advertising finding, which
is recorded in severability.md and is the reason the instrument is
layered, plus four technical points. Two were accepted: Article 13(1)(e)
attached a fine of up to 10 % of turnover to an attempt to circumvent,
which is unconsummated intent and poor ground under Article 49(1) of the
Charter, and now attaches to circumvention and to non-compliance with a
decision; and Article 11(4) obliged a national vehicle to accept the
residents of a Member State that had designated none, with compensation
merely permitted, so the Member State of residence now reimburses
verifiable net costs above the ceiling. One was already answered in the
text and the gate had missed it: the recital on the Reserve's portfolio
already states that the exclusion of sovereign debt restricts no movement
of capital by any other person.

**dc-compliance** returned PUBLISH, on the second run as on the first.

## Open, recorded rather than fixed

Two things were left, deliberately, because both are drafting decisions
that should be taken deliberately and not at the end of a long pass.

1. **Article 5(11) and the sub-threshold transferee.** The legal-basis
   gate says an undertaking below the Article 3(2) gateway that receives
   automated assets must issue 3 % of its whole capital, which is
   disproportionate as to its unrelated activities. The aggregate cap
   added today limits the group's total exposure but does not answer the
   distribution of it between entities. Pro-rating was rejected in an
   earlier round as inoperable against an indivisible equity, so
   reopening it is a decision, not a correction.
2. **Five further acquis interface points** raised on the second run:
   Article 85 of Directive (EU) 2017/1132; an unconditional prospectus
   exemption for the admission of shares issued to the Reserve, which
   matters because those shares are non-voting and will often be a new
   class, so the "same class already admitted" condition will not be met;
   segregation of holders' accounts from occupational pension assets
   where a national vehicle is an institution under Directive (EU)
   2016/2341; the reference date for fair market value in Article 3(2)(c);
   and services of general economic interest entrustment for the national
   vehicles under Article 11(3).

Neither is a reason to hold the text back from a Gate 1 conversation.
Both are the next drafting pass.
