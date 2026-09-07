# Candidate annual accounting specification

Decision proposal, not a replacement for Annex II yet. The reference is
`own-the-machine-tools/reference/reserve.py`; run its tests with
`python3 -I -m unittest discover -s reference -v` from the tools repository.
Run `python3 -I reference/reserve.py` for the illustrative ledger. No package
installation, private data or network call is needed.

## Proposed rules

1. Track gross assets, cash, subscription debt, unpaid administration costs,
   protected capital and deferred holder allocations separately. Deferred
   allocations are backed by reserved cash and cannot pay subscription costs.
2. A new subscription contributes the fair value of shares less the nominal
   amount paid. Borrowing for that nominal amount creates a liability; it is
   not investment income. Report the loan rather than assuming a willing lender.
3. Realised income pays subscription debt first, as Article 9(1)(e) requires,
   then outstanding and current administration costs. Unpaid costs remain a
   liability. The residual cash-income ceiling is never negative.
4. Increase the protected-capital benchmark for inflation and net new
   contributions. New contributions cannot conceal a loss on existing capital.
   Recognise losses immediately in this candidate; retain the recovery target
   through subsequent years. No distribution uses unrealised appreciation as
   cash. A failed preservation target is disclosed, not described as guaranteed.
5. New allocations are the least of residual cash income, net unallocated
   capital above the protected benchmark and the existing 125% trailing
   allocation collar with its 2% capital floor. A floor on that collar does
   not override the income or preservation ceilings.
6. Keep allocated but unpaid amounts separate from protected investment
   capital. Pay them when the cost threshold is met or on the third year
   with a positive new allocation since the previous payment. Zero-allocation
   years do not increment that counter. Never allocate the same cash twice.
7. After an allocation, protect any remaining unallocated gain as part of
   the next opening benchmark. Include unpaid allocations in the reported
   total beneficial stake, but exclude them from capital to be preserved
   again. Actual net assets can fall in a bad year; the target does not make
   assets immune to loss.

## Proposed Article 8(4) replacement for review

4. The Reserve shall determine the amount available for allocation in each
financial year in accordance with Annex II. It shall first apply realised
income to the borrowing referred to in Article 9(1)(e), then to outstanding
and current administrative costs, and then retain the amount necessary for
capital preservation. No negative amount shall be allocated. A preservation
shortfall or unpaid cost shall remain separately recorded for subsequent
years. New contributions shall not discharge a preservation shortfall on
previously held capital. Amounts already allocated to holders shall be
separately recorded and reserved for payment, and shall not be charged a
second capital-preservation retention. No distribution shall be financed
by borrowing or by a disposal of holdings effected for that purpose.

The final Annex II needs the corresponding formal definitions and cash
priority; this paragraph is not sufficient on its own. The reference code
is executable proposed arithmetic for that discussion, not delegated law.

## Differences requiring an editor decision

- Current Annex II recognises fair-value changes over five years. This
  candidate immediately recognises losses and preserves a recovery benchmark.
  It is deliberately conservative and can delay allocations. Approve this
  change or specify a coherent smoothed alternative before integration.
- Current Article 10 defers a distribution into capital. This candidate
  separates allocation from payment and ring-fences the allocated cash.
  An Article 10 amendment must establish when the personal monetary claim
  arises and how inheritance and late registration work.
- The prototype has one scalar holder count and year-end new contributions.
  It does not implement the proposed holder-day method, intra-year inflation
  weighting, foreign-exchange conversion, tax recovery, market liquidity or
  procurement. These are explicit boundaries, not assumed zero-cost services.
- The reference retains the numerical collar, not an assertion that old
  payout curves remain valid under a new accounting policy. DC-45/46 require
  a new sizing run before adopting a new methodology. Article 1's
  generational capital objective and the candidate 3% remain unchanged.

## Validation and acceptance examples

Thirteen executable tests cover cashless appreciation, loss recovery, fresh
capital against old losses, excess costs, priority of subscription debt,
nominal-value borrowing, protection of deferred cash, the third-positive-year
payment, zero-income years, no double charging of deferred amounts,
inflation, invalid inputs and 30 mixed years of independent cash/asset
conservation. The sample ledger shows both per-holder payout and net stake.
Numbers are arbitrary units for checking rules, not campaign projections.

This model illustrates why long-term capital can grow while a given year's
payment is zero. That is compatible with the book's thesis. It is not a
reason to introduce a tax or promise annual income growth.
