# The warrant percentage: what the model can and cannot justify

Objection 21 asks why the warrant is three per cent and not one or ten. This
file records the computation behind the answer, because the answer turns on a
property of the published model rather than on a judgement, and anyone should
be able to check it.

## What was computed

The simulator on the campaign site implements the Annex II arithmetic as
amended on 19 August 2026: real-capital retention, a three-year smoothing
collar floored at 2 % of capital, no leverage, constant euros, a fifty-year
horizon, designated value crystallising as a continuing flow. The warrant
percentage enters it in exactly one place, as the share of each crystallising
flow that is added to the Reserve's capital.

The model was rerun with that percentage as a free parameter, across the three
scenarios the simulator itself offers: its default, its sceptic preset and its
forecast preset. Euro figures are annual distribution per adult citizen, in
constant euros, on 350 million adults.

| Scenario | 0.5 % | 1 % | 2 % | 3 % | 5 % | 10 % |
|---|---|---|---|---|---|---|
| default, year 20 | 0.59 | 1.18 | 2.35 | 3.53 | 5.88 | 11.75 |
| default, year 50 | 7.89 | 15.77 | 31.54 | 47.32 | 78.86 | 157.72 |
| sceptic, year 50 | 0.49 | 0.97 | 1.94 | 2.91 | 4.86 | 9.71 |
| forecast, year 50 | 61.69 | 123.39 | 246.78 | 370.16 | 616.94 | 1233.88 |

## The result

The model is exactly linear in the percentage. Trebling it trebles the
distribution at every horizon in every scenario, to four decimal places, and
the same holds for the accumulated stake. There is no threshold, no kink and
no discontinuity anywhere on the curve.

This is not a defect in the model. It is what the arithmetic of a
capital-preserving fund fed by a proportional share of a flow must do. But it
has a consequence the memorandum has to state: **no percentage can be derived
from the dividend side.** There is no figure at which the instrument starts
working and below which it does not, so no figure can be shown to be the
minimum necessary to make it work.

## Why that matters legally

Necessity under Article 52(1) of the Charter asks whether a less intrusive
measure would achieve the objective. Article 1 states the objective
qualitatively: the participation of citizens in the capital value created by
hyper-automated undertakings. One per cent produces participation. So does
one tenth of one per cent. An opponent therefore does not need to argue that
three per cent is excessive; they need only observe that a smaller figure
achieves the objective as the instrument states it.

The conclusion recorded in objection 21 is that this is a defect in Article 1
rather than in the memorandum, and that it is repaired by giving the objective
a quantity a percentage can be tested against, not by arguing harder about
three per cent.

## Reproducing it

Port the fifty-year loop from the site repository's
`src/scripts/simulator.ts`, replace the literal `0.03` with a parameter, and
run it over the three presets in the same file. The presets are: default
(revenue EUR 150bn, lag 7 years, real return 4 %, growth 5 %), sceptic (50,
15, 2, 0) and forecast (600, 5, 4, 8). Nothing else in the model changes.

Computed 22 August 2026 against simulator.ts as at site commit e1b0974.
