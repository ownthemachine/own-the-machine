---
gate: legal-form
target: Articles 2, 5, 6, 7, 8, 9, 10 and Annex II as amended against corporate structuring
commit: 8b0d54f
verdict: PUBLISH at round 6, REVISE thereafter on residual style; closed by editor disposition
disposition: merged-with-fixes
date: 2026-08-21
---

# Editor disposition (21 August 2026)

Nine rounds against the amendments answering an external structuring
review. The gate reached PUBLISH at round 6 and returned to REVISE only
as later substantive edits introduced new sentences for it to correct.

Applied: the whole of the renumbering (2a, 4a and (aa) are insertions
reserved for amending acts, so Article 5 now runs 1 to 12 and Article 8
1 to 8, with every cross-reference in the instrument moved with them);
the internal-consistency gaps where Articles 6 and 7 spoke only of
liquidity events and not of crystallisation; the relocation of the
one-warrant rule to the paragraph that imposes the obligation; named
addressees in place of agentless passives; the separation of the
non-voting rule for shares from the list of what the warrant does; and
the deletion from the enacting terms of a factual sentence about
third-country taxation, which moved to recital 16a.

Left open, with reasons. The gate's standing finding that Annex II
carries substantive limits which belong in the enacting terms is
correct and predates this work: the collar and the carry-forward have
been in the Annex since the first draft, and moving them is a
refactor of Article 8 and Annex II together, not a fix to the
structuring amendments. It is recorded here as the next form task
rather than smuggled into this one.

# Review (final round, verbatim)


> Reviewer: OpenRouter `google/gemini-3.7-flash` · 2026-08-20T23:38:12+00:00 · tokens in=8998 out=7443
> Prompt: legal-form.md · Verbatim model output below — do not edit.

### Finding 1: Autonomous Normative Rule in Annex

* **Verbatim quote:**  
  > "The distributable amount for a financial year does not exceed the greater of:  
  > (a) 125 % of the average of the distributable amounts for the three preceding financial years; and  
  > (b) 2 % of the capital of the Reserve at the end of that year." (Annex II, point 3)
* **Rule breached:**  
  Rule 7 (Cross-references and Annexes) and Joint Practical Guide (JPG) Guideline 22. Annexes must not contain autonomous substantive limits or normative commands that are not rooted in the enacting terms. Article 8(4) mandates retention only for preserving the real value of capital, leaving the multi-year collar and distribution cap as substantive obligations existing solely within the Annex.
* **Compliant redraft:**  
  Amend Article 8(4) to provide the enacting basis for the collar:  
  > "4. The Reserve shall retain from its realised income in each financial year the amount necessary to preserve the real value of its capital, calculated in accordance with the methodology and subject to the smoothing limits laid down in Annex II, and shall make the remainder available for distribution pursuant to Article 10(6). No distribution shall be financed by borrowing or by the disposal of holdings effected for the purpose of the distribution."

---

### Finding 2: Imprecise Internal Sentence Reference

* **Verbatim quote:**  
  > "Where the law governing the covered undertaking does not give effect to the first sentence, the covered undertaking shall take all measures necessary to procure a subscription of equivalent effect..." (Article 5(5))
* **Rule breached:**  
  Rule 7 (Cross-references) and JPG Guideline 16. References to specific sentences within an article must explicitly identify the paragraph to ensure unambiguous cross-referencing.
* **Compliant redraft:**  
  > "Where the law governing the covered undertaking does not give effect to the first sentence of this paragraph, the covered undertaking shall take all measures necessary to procure a subscription of equivalent effect..."

---

### Finding 3: Multiple Distinct Ideas in a Single Sentence

* **Verbatim quote:**  
  > "For the purposes of this paragraph, persons acting in concert with those who controlled the covered undertaking, and persons connected with them, shall be treated as those persons; and where any of them acquires control of the transferee, at any time while it holds the automated assets, the obligations under this Article shall attach to the transferee from the date of that acquisition." (Article 5(12), second subparagraph)
* **Rule breached:**  
  Rule 3 (Enacting terms: one idea per sentence) and JPG Guideline 4.1. An attribution rule (concert party definition) and an operative conditional obligation (deferred re-attachment trigger) are concatenated into a single sentence using a semicolon and conjunction.
* **Compliant redraft:**  
  > "For the purposes of this paragraph, persons acting in concert with those who controlled the covered undertaking, and persons connected with them, shall be treated as those persons. Where any of those persons acquires control of the transferee at any time while the transferee holds the automated assets, the obligations under this Article shall attach to the transferee from the date of that acquisition."

---

### Finding 4: Positive Mandate Embedded in a Negative Prohibition List

* **Verbatim quote:**  
  > "(e) borrow, save for temporary liquidity purposes not exceeding 2 % of the value of its assets and save for the payment of subscription amounts under Article 5(5), which borrowing shall be repaid from the first realised income of the Reserve;" (Article 9(1)(e))
* **Rule breached:**  
  Rule 3 (Enacting terms) and JPG Guideline 15. Subordinate points under a prohibitive lead-in ("The Reserve shall not:") must remain grammatically and conceptually negative. A positive obligation ("shall be repaid...") cannot be placed inside an exception within a negative list item.
* **Compliant redraft:**  
  Amend Article 9(1)(e):  
  > "(e) borrow, save for temporary liquidity purposes not exceeding 2 % of the value of its assets or for the payment of subscription amounts under Article 5(5);"  
  And insert as a second subparagraph to Article 9(1) (or as Article 9(3)):  
  > "Any borrowing contracted pursuant to point (e) of the first subparagraph shall be repaid from the first realised income of the Reserve."

---

VERDICT: REVISE
