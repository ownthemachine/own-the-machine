# Validation record

7 September 2026; local branch `feat/generational-repair-package`.

- Tools: `python3 -I -m unittest discover -s tests -v`: 14 passed.
- Reference model: `python3 -I -m unittest discover -s reference -v`: 13 passed.
- Law: `lint-legislation.py`: zero errors, seven existing terminology warnings.
- DC coverage: `check-dc-coverage.py regulation/memorandum/counter-arguments.md
  pipeline/reviews/2026-09-07-dc-compliance-generational-r2.md`: all 46 assessed.
  A bookkeeping rerun initially supplied GOVERNANCE.md, which contains no DC
  table; the checker correctly failed. The correct source above then passed.
- Provenance: all 12 raw review bodies match their recorded SHA-256 after
  extracting the unmodified body from the metadata/disposition wrapper. All
  12 exact prompt files and submitted compressed source bundles match the
  review hashes. Initial language snapshot r1 was not submitted.
- Site: `npm run build` passed, generating 191 pages and 190 sitemap URLs.
- Site: `npm run check:release` passed: translation structure, Markdown links
  and tables, labels, one-sheet briefs in all five languages, contents lists
  and page reachability. This is not native-speaker editorial certification.
- The final fidelity gate covers corrected English copy, changed translations,
  Article 10 payout summaries in all five languages, and simulator disclosures.
  Source metadata was stamped after that review; no prose changed afterward.
- Plain summaries for Articles 1, 2 and 7 retain their earlier source stamps
  and therefore display stale-source banners in all five languages. Their
  text was not refreshed as part of the selected summary rewrites. This is
  visible review debt, not a failed structural check or native-language sign-off.
- Existing public simulator arithmetic was not replaced with the candidate
  reference model. The reference scenarios are arbitrary-unit demonstrations,
  not validated payout forecasts or evidence that the current percentage meets
  Article 1's objective.

Operative repairs: law bfe309a; explanatory/form closure: law 7b33a2d;
review ledger and decisions: law ea0aa72. Reference model and complete DC
coverage: tools 4f65799; future legal prompt safeguards: tools 32709fb.
English/site specification: site 86600a2; translation alignment: site 8ee18bd.
Generated draft downloads are committed separately afterward.

The working tree snapshots, rather than HEAD alone, identify the submitted
review material. No release clearance follows from these tests: legal-basis,
hostile-counsel and acquis gates retain REVISE. See REVIEW-STATUS.md.
