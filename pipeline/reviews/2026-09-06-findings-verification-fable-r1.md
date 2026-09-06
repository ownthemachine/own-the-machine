---
gate: findings-verification
target: regulation
commit: 0aeaada
verdict: REVISE
disposition: assessed-repairs-pending
date: 2026-09-06
---

# Review

> Reviewer: `vertex/claude-fable-5.1@eu` · router router.eu.requesty.ai · geolocation eu · retention 30d · trained-on false · lab anthropic
> 2026-09-06T21:46:35+00:00 · tokens in=116045 out=32623
> Prompt: findings-verification.md · Verbatim model output below ; do not edit.

> Bundle SHA-256: `02d22ea9ae2cd26b50ad50b3375bbe4c1d0a97501d8229cd209f9a78fb0357ac`
> Prompt SHA-256: `27fb4afcbfe3fbbf1404d8b046adb0a19d8e31cb1b89b59ed571569e1fbf6633`

# Independent verification: outstanding legal findings, baseline 0aeaada

**Method.** Every earlier model finding is treated as an allegation. Each is tested against the operative text supplied (articles, annexes, recitals), then against the accompanying documents. Quotations are verbatim from the bundle. No court-outcome percentages are given; where earlier reviews gave them, they are neither adopted nor rebutted here. Treaty and Charter validity are outside this audit. Routing and retention for this run are recorded by the runner's provenance line; the reviewer cannot verify router metadata from inside the run and makes no claim about it.

**Change classes referenced** (GOVERNANCE.md): Editorial (editor's read); Prose (memorandum or recital wording: lint + gates 1 and 6); Substantive (any enacting term: lint + all six gates); Constitutional (four tests, DC table, GOVERNANCE.md: full pipeline + public issue, provisional until first outreach).

---

## Q1. Article 5(4)(e) against issuance, extraction crystallisation, the long-stop and execution

**Classification: PARTIALLY CONFIRMED.** The narrow finding stands; the broad one ("contradicts 5(1), 5(3), 5(5) and 5(11)") does not.

**Operative text.**
- Art. 5(4)(e): "The citizens' capital warrant shall: … (e) impose no obligation on the covered undertaking prior to a liquidity event other than the notification obligation in paragraph 6."
- Art. 5(1): "Within three months of its designation, a covered undertaking shall issue to the Reserve a citizens' capital warrant."
- Art. 5(3): "The citizens' capital warrant shall also crystallise, and shall be exercisable on the same terms, where either of the following occurs before a liquidity event".
- Art. 5(5), fifth sentence: "The covered undertaking shall execute the subscription within 20 working days of the delivery of the valuation"; third sentence: "… in the case of crystallisation under paragraph 3, no later than three months after the date of crystallisation."
- Art. 6(3): "The costs of the valuation shall be borne by the covered undertaking."
- Art. 2(6): 'liquidity event' is a closed list (admission to trading, change of control, 20 % transfer). Paragraph 3 crystallisation is not within it.

**Warrant-imposed obligations versus statutory duties.**
1. *Issuance (5(1)).* The duty to issue is a statutory duty of the undertaking and is logically antecedent to the instrument; the warrant cannot impose the obligation to create itself. Paragraph 4(e) is a description of what the warrant, once issued, imposes. No conflict. The same holds for 5(11)/(12) transferee issuance duties, which are statutory.
2. *Notification (5(6)).* Statutory ("A covered undertaking shall notify"), but 4(e) attributes it to the warrant. Harmless mis-attribution, but it shows the drafter treated 4(e) as a catalogue of everything the undertaking owes before an event, which is exactly why the omission below bites.
3. *Extraction and seven-year crystallisation (5(3)) with execution (5(5)) and valuation cost (6(3)).* These are the correlatives of the warrant's own entitlement ("shall entitle the Reserve … upon crystallisation under paragraph 3 … to subscribe"). On paragraph 3 crystallisation, which by its terms occurs "before a liquidity event", the undertaking must execute within 20 working days of the valuation, procure equivalent effect within three months, and bear the valuer's costs. Each is an obligation flowing from the warrant, prior to any liquidity event as defined, and none is the paragraph 6 notification. Paragraph 4(e) literally denies their existence.

**Strongest defence.** (i) Paragraph 3 says "exercisable on the same terms", and paragraph 2 pairs "the first liquidity event … or … crystallisation under paragraph 3, whichever occurs first", so the article as a whole treats paragraph 3 crystallisation as the functional equivalent of a liquidity event; 4(e) should be read as "prior to crystallisation". (ii) Recital 10 confirms the dormancy is "until one of those points is reached". (iii) Specific provisions (5(3), 5(5)) prevail over the general dormancy statement, and 4(e) predates paragraph 3 (drafting notes: paragraphs 3, 4(b), 10–12 added 21 August 2026).

**Why it only partly succeeds.** The drafter used the defined term 'liquidity event' in 4(e) while distinguishing it from paragraph 3 crystallisation in the very next line of paragraph 3 ("before a liquidity event"). A recital cannot cure an article (C-162/97 Nilsson, per DRAFTING-RULES), and an ambiguity papering over the sequence of drafting is read restrictively against the drafter (C-6/98 ARD, same source). The defence gives a court a route to the intended reading; it does not remove the undertaking's textual plea.

**Surviving issue and consequence.** A covered undertaking facing execution after paragraph 3 crystallisation has a drafter-supplied defence in the article itself. The consequence is contested enforcement and delay in the paragraph 3 cases, not invalidity of the trigger. Article 6(5) does not help, since refusal to execute is not a "challenge to the valuation".

**Directly related discovery (see also section 6).** Article 5(6) requires notification only of an "impending liquidity event". There is no duty to notify, or to report the data for, crystallisation under 5(3)(a): the extraction figures are the undertaking's own, the Reserve has "no rights of information beyond those provided in this Regulation" (5(4)(a)), and the valuer's 20-working-day clock in 6(3) runs from a date the Commission may not know has occurred. The seven-year date is known; the extraction date is not.

**Minimal repair.** Substitute in 4(e): "impose no obligation on the covered undertaking prior to the first liquidity event following issuance or crystallisation under paragraph 3, whichever occurs first, other than those laid down in paragraph 6". Add to 5(6) a duty to notify the Reserve and the Commission within a fixed period after the end of any financial year in which the condition in 5(3)(a) is met, with the extraction computation. Policy unchanged: dormancy (DC-12, DC-3) is preserved; the only added burden is an annual self-assessment of extraction, which the undertaking already must be able to compute to know whether it has crystallised.

**Validation scenarios.** (1) Private undertaking, extraction crosses 25 % of covered turnover in year 3: crystallisation date, notification, valuer appointment, execution and cost allocation all follow without recourse to 4(e). (2) Seven-year long-stop on an already-listed undertaking (Art. 17(2)): same chain, no liquidity event ever occurs. (3) Ordinary liquidity event: 4(e) still describes dormancy correctly. (4) Transferee under 5(11) whose own warrant crystallises under 5(3). **Review class: Substantive.**

---

## Q2. Article 3(8), second sentence: genuine hiring, pay rises, genuine value reductions

**Classification: CONFIRMED as a text defect; PARTIALLY CONFIRMED as to practical consequence** (a substance test exists elsewhere that a court could import, but the sentence as written exceeds it).

**Operative text.**
- Art. 3(8), first sentence: "shall not segment, divide, combine or restructure its activities, or acquire or dispose of undertakings, where the main purpose or one of the main effects thereof is to avoid meeting the thresholds".
- Second sentence: "The Commission shall disregard any such arrangement when applying this Regulation, and shall likewise disregard any transaction, arrangement or attribution the main purpose or one of the main effects of which is to increase the compensation of labour, or to reduce the fair market value, referred to in point (b) of paragraph 2."
- Recital 7: compensation of labour "cannot be increased without genuine payment for genuine work, so that an undertaking reduces its decoupling ratio only by remunerating labour, which is consistent with the objectives of this Regulation."
- Annex I point 3, second paragraph: "Compensation paid under arrangements whose main purpose or effect is to raise the undertaking's compensation of labour without a corresponding supply of labour to the undertaking shall be disregarded. Article 3(8) applies."
- Art. 2(8): 'compensation of labour' means the figure "calculated in accordance with point 3 of Annex I".

**Strongest defence.** (i) "Likewise" ties the second limb to the avoidance character of the first. (ii) Article 2(8) incorporates Annex I point 3, which supplies the substance qualifier "without a corresponding supply of labour"; 3(8) is the Commission's power to enforce that definitional exclusion, not a free-standing command to disregard wages. (iii) Recital 6 ("restricts no restructuring undertaken for genuine commercial reasons") and recital 7 fix the purpose. (iv) An absurd literal result (every pay rise disregarded) is one a court will avoid.

**Why it fails on the text.** "Likewise" qualifies the verb (disregard in the same manner), not the condition, which is separately and completely stated: "the main purpose or one of the main effects of which is to increase the compensation of labour". A general pay rise or a hiring wave has that as its main effect by definition. Annex I point 3 excludes only compensation "without a corresponding supply of labour"; 3(8) reaches compensation with such supply. The article is broader than the definition it is said to police, and the drafting notes to Article 3 confirm the breadth is deliberate ("effects-based … so it reaches an acquisition whose commercial logic is genuine but whose main effect is staying under the ratio"), which is the opposite of recital 7's promise. The same literal command covers "reduce the fair market value": a genuine arm's-length down-round or an unfavourable but honest independent valuation has as its main effect a reduction in the Annex I point 4 figure, and the Commission "shall disregard" it, imputing a stale higher value. Recital 7 cannot narrow the article (Nilsson), and the sentence is not ambiguous enough on its face for the restrictive reading to run the drafter's way (ARD).

**Consistency with recital 7.** Inconsistent. Recital 7 also asserts the position can be established "from its own audited accounts alone", which 3(8) makes untrue for any undertaking that has raised pay, since it cannot know what the Commission will disregard.

**Surviving issue and consequence.** Legal-certainty challenge to designation decisions relying on 3(8); reputational exposure (the FAQ faithfully restates the article and thereby advertises the conflict, as the hostile review noted); and an unintended hit to the proportionality narrative, since recital 7's "route down" is the fairness argument.

**Policy choice that cannot be made by copy edit.** The first sentence already covers acquisitions and disposals of undertakings on the effects basis. The second limb is therefore only needed for non-acquisition transactions (pay, attribution, valuation). Narrowing the second limb with a substance test does not reopen acquisition-dilution, which the first sentence and Art. 4(3) still address. But the editor must confirm that acquisition of a labour-heavy business is to remain disregardable on an effects basis even where the acquired employees genuinely work for the group, because that is a departure from recital 7 that the recital, not the article, currently conceals.

**Minimal repair.** Second sentence: "…shall likewise disregard, when applying point (b) of paragraph 2, any transaction, arrangement or attribution the main purpose or one of the main effects of which is to increase the compensation of labour without a corresponding supply of labour to the undertaking, or to reduce the fair market value otherwise than by reference to a transaction or valuation meeting the conditions of point 4 of Annex I." Move the anti-avoidance command out of Annex I point 3 into the article (JPG G22; the legal-form rounds already flagged "unchanged Annex I drafting issue"), leaving the annex descriptive. Related: Annex I point 3 counts share-based compensation "at grant value"; for a private undertaking the grant value is self-set, and the substance test would not catch an inflated grant valuation. Require grant value to be consistent with fair market value under point 4. Changes: DC-11 (substance-over-form) is served, not altered; recital 7 becomes true.

**Validation scenarios.** (1) 20 % across-the-board pay rise, headcount constant: counted. (2) 5 000 engineers hired at market pay: counted. (3) Cash bonus pool converted to RSUs at an internal grant valuation three times the last round price: caught by the grant-value alignment, not by the substance test alone. (4) Arm's-length down-round, 2 %+ to independent investors: recognised. (5) Commissioned valuation applying illiquidity and control discounts inconsistent with a transaction six months earlier: disregarded. (6) Payments to a captive staffing affiliate supplying no labour: disregarded. (7) Acquisition of a 40 000-employee services business: editor's policy decision above. **Review class: Substantive** (Annex I change also Substantive; recital 7 wording Prose).

---

## Q3. Positive governance for the Reserve

**Classification: CONFIRMED as an essential design omission; the choices required are DESIGN DECISIONS.**

**What the text provides, article by article.**
- Art. 8(1): "shall have legal personality and shall enjoy in each Member State the most extensive legal capacity accorded to legal persons". Capacity, not organs.
- Art. 8(2)–(3): fiduciary purpose and financing.
- Art. 8(4), (6): "shall retain … shall make the remainder available"; "shall publish annually audited accounts". No auditor, no approving organ.
- Art. 8(7): outside MiFID, AIFMD, IORP II. Removes external supervision without substituting any.
- Art. 8(8) and Art. 15: delegation limited to "amend the methodology laid down in Annex II". Art. 15(2), (3), (6) name only Art. 3(9) and 8(8).
- Art. 9: prohibitions and a management objective; no addressee organ, no supervisor, no sanction for breach.
- Art. 16: committee exists; implementing powers are conferred only by Art. 6(1) (valuer list, criteria, rotation). Recital 32 confirms the scope: "the establishment of the list of independent valuers and their appointment".
- Acts requiring attributable authority: Art. 5(5) "the Reserve shall pay up the shares in full in cash"; Art. 6(4) "the Reserve shall transfer back … or cancel"; Art. 9(1)(d), (e), (g) diversification, borrowing, currency hedging; Art. 10(6) "The Reserve shall declare a distribution"; Art. 10(7) publication; Art. 11 dealings with national vehicles; Arts. 7, 12(4) litigation in which the Reserve is party; Annex II point 2 "administrative costs of the Reserve" and point 4 charges "quoted to the Reserve".
- Missing entirely: governing organ(s), appointment and dismissal authority, term, independence and instruction rules, seat, applicable law for contracts and staff, representation in law and before courts, statutory auditor and the interface with Union audit, reporting and accountability to Parliament and Council, transparency and data-protection regime for a Union body (recital 33 covers national vehicles under Regulation (EU) 2016/679 only), liability, and any supervisor for Article 9.

**Power to supply later.** None exists. Article 15 delegates two annex methodologies; Article 16 attaches to one implementing task. Article 291(2) TFEU implementing powers require conferral in the basic act (source: scope document's external check), and Article 290 reserves essential elements to the legislative act; DRAFTING-RULES lists "the reserve's ownership structure" among elements that "may never be delegated". Who holds authority over EUR-trillion-scale holdings for citizens is essential in that sense, so even a new empowerment could not carry it. A separate Council Regulation on Article 352 is what the severability memorandum contemplates for Layer 3, but no such text is drafted.

**Strongest defence.** DC-24: the mechanism is self-executing; vesting is by operation of law, the retention is arithmetic (Annex II), the distribution trigger is arithmetic (10(6)), and the Reserve is deliberately passive (DC-13, recital 23); founding articles in Union acts sometimes establish a body and leave statutes to follow.

**Why it fails.** An automated rule still needs someone to sign the accounts, pay the nominal subscription, hold custody, instruct payments to national vehicles, decide hedging and diversification within Art. 9, and appear in court under 6(4), 7 and 12(4). Legal capacity under national law (8(1)) supplies no organ. The memorandum's own §4 benchmarks "the Reserve's own running costs" against the Norwegian fund, presupposing an administration the articles never create. And the absence is not stylistic: Article 12 raid-proofs assets against public bodies while leaving open who controls them, which is the one channel Chapter VI does not address.

**Distinguishing from campaign staffing.** The EUR 300 000 staffing assumption in the launch plan concerns the campaign organisation, not the Reserve. Nothing here implies salaried campaign staff. It implies that a statutory body with legal personality must have organs.

**Choices that cannot be decided by copy edit (flagged, not decided).**
1. Form and composition of the governing organ: independent board of trustees; Member State representative board on the decentralised-agency pattern (the 2012 Common Approach on decentralised agencies — external verification); Commission-administered; or a two-tier board plus executive.
2. Appointing authority and process: Commission, Council, Parliament hearing, national vehicles, holders. Each is a potential raid channel and interacts with DC-19 to DC-23.
3. Independence: prohibition on seeking or taking instructions from institutions, Member States or undertakings, mirroring Art. 12(3)'s spirit.
4. Accountability route: the Reserve is outside the general budget (8(2)), so the ordinary discharge does not apply; whether the Court of Auditors audits it (Article 287 TFEU covers bodies set up by the Union — external verification) and whether it reports annually to Parliament and Council must be chosen.
5. Seat, staff regime and applicable law; whether administrative costs are capped in law or only disclosed.
6. Whether holders or national vehicles have any representative voice at Reserve level. DC-32 and DC-41 concern the Reserve's conduct toward undertakings; they do not decide governance of the Reserve itself.
7. Legal-basis consequence: an Article 114 body (ENISA C-217/04, ESMA C-270/12, per the severability memorandum) or the Article 352 layer; the escrow fallback in decomposition rule 1 must not be foreclosed.

**Minimal repair direction.** A new article in Chapter IV (organs; appointment; independence; representation; seat; accounts, audit and annual report; applicable law and liability), a motivating recital, memorandum §5.3 and severability Layer 3 updated, and a public issue before merging because the appointment choice is itself a raid-proofing choice. **Review class: Substantive, with the public issue GOVERNANCE.md reserves for constitutional matters recommended on the political choice** (it touches DC-19 to DC-23 in effect, though not the DC table text).

**Validation scenarios.** (1) First crystallisation: who receives the valuation, authorises payment of the nominal amount, and holds the shares. (2) Art. 6(4) reversal ordered by a court: who is the party and executes the transfer-back. (3) Holder's Art. 12(4) action: who is served. (4) Year-end: who approves accounts, who audits, who computes and certifies the Annex II retention. (5) Art. 9(1)(g) hedging and 9(1)(d) diversification: who decides, under what mandate, and who can sanction a breach. (6) Attempted capture: a Member State or institution seeks to instruct the organ or fill vacancies for that purpose. (7) Layer 3 severed: the escrow fallback remains drafted-compatible.

---

## Q4. Article 13 coverage of refusal to execute; third-country cases; transferees

**Classification: CONFIRMED** (punitive gap for the execution duty of Union-law undertakings; transferees outside the Article 13 addressee on the text), with the civil route intact.

**Third-sentence trace.** Article 5(5) has five sentences. First: vesting by operation of law. Second: number of shares by valuation, "the subscription shall be executed accordingly". Third: "Where the law governing the covered undertaking does not give effect to the first sentence, the covered undertaking shall take all measures necessary to procure a subscription of equivalent effect…". Fourth: dilution cap. Fifth: "The covered undertaking shall execute the subscription within 20 working days of the delivery of the valuation". Article 13(1)(b) reaches only "the measures required by the third sentence of Article 5(5)", i.e. the third-country procurement obligation. The fifth-sentence execution duty is in no point of 13(1). Article 13(2) periodic penalty payments compel compliance only "with the obligations referred to in paragraph 1". Article 13(3) market prohibition is confined to undertakings "not established in the Union" and to points (a) and (b).

**Strongest defence.** The right "shall vest by operation of law" (first sentence); the Regulation is "binding in its entirety and directly applicable" (Art. 18(3)); Art. 5(7) removes the general-meeting, pre-emption and expert-report obstacles; so for a Union-law undertaking execution is ministerial and the Reserve, a legal person, can obtain an order in the courts of the Member State. The DMA-pattern fine list targets conduct requiring a Commission finding; the vested right needs none.

**Assessment.** The defence establishes that enforcement exists; it does not close the gap. The Commission can fine an undertaking 10 % of worldwide turnover for failing to issue a dormant instrument and cannot fine or coerce it for refusing to deliver the shares that instrument entitles the Reserve to. National-law specific performance of a share issuance varies by Member State and takes time; there is no Union-level coercion in the interval. The asymmetry is the survival point, not an absence of remedy.

**Third-country cases.** Covered where the governing law does not give effect to vesting: (b) plus (2) plus (3). Two edges remain. (i) Whether foreign law "does not give effect" is a threshold fact an undertaking can contest, and if it argues its law does give effect and then refuses execution, it is outside (b) and therefore outside (3). (ii) The third sentence reads "shall take all measures necessary to procure", a conduct formula, while recital 14 and DC-33 describe "an obligation of result"; the text should say which.

**Transferees.** Article 13 addresses "a covered undertaking", defined in 2(2) as "an undertaking designated pursuant to Article 3". A 5(11) transferee issues "as if it were a covered undertaking" and its obligations arise "irrespective of whether the transferee meets the conditions laid down in Article 3"; a 5(12) transferee has obligations "under this Article" attached. Neither is designated; neither is within 13 on its own words. Partial mitigation: Art. 2(1) 'undertaking' includes linked enterprises, so a group-member transferee is part of the covered undertaking as an economic unit and a fine on the group is arguable. That does not reach an unconnected transferee at undervalue under 5(11), and whether natural-person-controlled post-restructuring vehicles under 5(12) are "linked" turns on Recommendation 2003/361 Annex Art. 3(3) (external verification).

**Surviving issue and consequence.** No Union punitive or coercive tool for the obligation that carries the value, for Union-law undertakings; transferees escape Article 13 except by the Art. 2(1) argument. The obligation itself, and civil enforcement, exist.

**Minimal repair.** 13(1)(b): "fails to comply with the third or fifth sentence of Article 5(5)"; new point: "fails to comply with Article 5(11) or Article 5(12)"; addressee clause: "on a covered undertaking, or on an undertaking to which obligations attach under Article 5(11) or (12)"; 13(3) reference updated accordingly; recital 29 ("core obligations") updated. Policy effect: widens 10 %-of-turnover exposure to execution refusal and to transferees, which is a deliberate enlargement of the punitive perimeter and should be justified in recital 29. **Review class: Substantive.**

**Validation scenarios.** (1) Union-law undertaking lists, valuation delivered, no share registration by day 21: fine and periodic penalty available. (2) Third-country parent, long-stop, nothing procured within three months: (b), (2), (3). (3) Third-country parent asserts its law gives effect to vesting, then refuses execution: covered. (4) Unconnected transferee at undervalue never issues: reachable. (5) Same-controller post-restructuring vehicle fails to issue afresh: reachable without reliance on "linked enterprise". (6) Transferee's own warrant crystallises: the 5(2)–(5) regime applies to it (see section 6 on that ambiguity).

---

## Q5. Memorandum descriptions against the operative text; French counterpart

Each alleged error was checked individually. All eight substantive descriptions are mirrored in the French file; the French additionally lacks one English paragraph.

**5(a) Post-designation value only. CONFIRMED.**
EN §2.4: "the obligation is prospective and attaches only to value formed after designation." FR: "ne s'attache qu'à la valeur constituée après la désignation." Art. 5(2): "subscribe at nominal value for newly issued shares representing 3 % of the fully diluted capital of the covered undertaking determined immediately before that event." The base is the whole capital at crystallisation, including value formed before designation and before entry into force; Art. 17(3) excludes only *events* completed before entry into force. Recital 18 avoids the claim ("one-time dilution, capped at a stated percentage, borne at a moment of realised gain"). Defence: "prospective" is true of the trigger; it does not rescue "value formed after designation". Consequence: the proportionality reasoning offered to a reviewer describes an interference the article does not make; the same phrasing sits in DC-1 ("Prospective warrants on future value") and objection 1 ("prospective warrant on future value creation"). Repair: correct the memorandum to the article ("prospective in trigger; the dilution falls on the capital as valued at crystallisation") — Prose class; reconcile DC-1's wording — Constitutional class (DC table). The alternative, changing the subscription base to post-designation value, is a redesign that would contradict DC-45/46 sizing and recital 18's nominal-value reasoning; it is flagged, not recommended.

**5(b) Owners' realisation only. CONFIRMED.**
EN §2.4: "it crystallises only when the undertaking's own owners realise value"; §3.3 Option 4: "crystallising only at the owners' own realisation." FR mirrored ("ne se cristallise que lorsque les propriétaires mêmes … réalisent de la valeur"; "ne se cristallisant qu'à la réalisation par les propriétaires eux-mêmes"). Art. 5(3)(b): "seven years have elapsed since the issuance of the warrant"; recital 10: "or the mere elapse of that period". §3.3 Economic impacts states the three triggers correctly, so the memorandum contradicts itself. Repair: "on the owners' own realisation of value or, failing that, at the seven-year long-stop". Prose class.

**5(c) Notification only. CONFIRMED.**
EN §3.4: "imposes a notification duty on undertakings meeting the thresholds and nothing on anyone else." FR mirrored ("n'impose rien à quiconque d'autre"). Against: Arts. 5(1), 5(5), 5(6), 6(3) on designated undertakings; 3(6) below-threshold designees; 5(11)/(12) transferees; Art. 11(1), (4) on Member States; Art. 11(2), (3), (5) on national vehicles. Defence: §3.4 is the compliance-burden section and the first clause is about the pre-designation stage. The absolute "nothing on anyone else" defeats it. Repair as stated in Q5(c) of the scope: name the designated undertakings, transferees and Member States. Prose class.

**5(d) Outside the nine unaffected. PARTIALLY CONFIRMED.**
EN §3.3: "The instrument has no effect on any undertaking outside that set". FR: "n'a aucun effet sur les entreprises extérieures à cet ensemble". The "nine" and "EUR 20,5 trillion" are dated estimates (August 2026 figures) and are treated as such. The defect is "no effect": Art. 3(3) binds any undertaking that later crosses the thresholds, 3(6) reaches below them, 5(11) reaches transferees "irrespective of whether the transferee meets the conditions laid down in Article 3". Repair: "no present obligation on undertakings outside that set, subject to Article 3(6) and to Article 5(11) and (12); the set moves with the figures". Prose class. Minor FR divergence: EN "in the thirties", FR "compris entre trente et quarante".

**5(e) Audited accounts only. PARTIALLY CONFIRMED.**
EN §3.4: "Both figures in the designation test are already in audited accounts, so compliance requires no new measurement." FR mirrored. Compensation of labour is an audited figure by construction (Annex I point 3). Fair market value is not: Annex I point 4 takes the latest of a 2 % transaction price, "an independent valuation prepared … within the preceding 12 months", or six-month average market capitalisation; none is an audited-accounts line, and the second is a new measurement. Union turnover attribution (point 1) and segment attribution (point 2, "consistent and documented basis") also require work beyond the accounts for the notification (point 5(b)). Defence: for listed undertakings the statement is nearly true; recital 7 makes the same overstatement ("from its own audited accounts alone"). Repair: memorandum sentence and recital 7 wording. Prose class (recital wording is Prose under GOVERNANCE.md).

**5(f) Age of majority. PARTIALLY CONFIRMED (imprecision, not a different criterion).**
EN §3.3: "distributions being made from the age of majority under Article 10". FR: "à compter de l'âge de la majorité". Operative criterion, Art. 10(1): "has attained the age of 18 years"; recital 25 the same. The article fixes an autonomous, uniform numerical age not tied to national majority rules. Whether every Member State's age of majority is 18 is not established from the bundle (external verification); even if it is, the memorandum describes the criterion as if it were derivative of national law, which it is not. Repair: "from the age of 18 years under Article 10(1)". Editorial. (The drafting note's "age threshold" open point is a policy matter, not a memorandum error.)

**5(g) Fee cross-reference 10(6) versus 11(3). CONFIRMED.**
EN §4: "Article 10(6) caps the fees national vehicles may levy so that administration cannot erode the entitlement." FR: "l'article 10, paragraphe 6, plafonne les frais que les véhicules nationaux peuvent prélever". Art. 10(6) is the distribution trigger ("not less than ten times the average cost of executing one payment"); the cap is Art. 11(3): "shall not exceed the costs actually incurred … and in any event 0,3 % annually". No defence. Editorial, both languages.

**5(h) Five acquis interfaces. CONFIRMED.**
EN §1.2: "Five acquis interface points remain open and are listed in section 5.4." §5.4: "Five acquis interface points, including the interaction with Directive (EU) 2024/2810" — one named, four unenumerated. FR: "sont énumérés à la section 5.4", same defect. Objection 20 refers to "the acquis interface points already recorded on the list before filing"; that list is not in the bundle, so the five cannot be verified here (external verification against the review ledger). Repair: enumerate the five in §5.4 from the ledger, or amend §1.2 to "noted in section 5.4 and recorded in the review ledger". Prose class; content requires the ledger.

**5(i) French counterpart alignment. CONFIRMED (drift).**
Header: "Le texte anglais fait foi … Source: explanatory-memorandum.md". EN §2.1 contains the paragraph beginning "The preamble of the draft cites Article 114 alone. A single act cannot carry two legislative procedures…"; FR §2.1 has no counterpart. The EN paragraph cites "the legal-form and legal-basis gates of 6 September 2026 (pipeline/reviews)", which are not in the bundle (external verification). All other checked items (a)–(h) are mirrored faithfully, so the French is aligned in error as well as in substance. Minor terminology: FR §3.2 "demande relative à la recevabilité" for EN "registrability enquiry"; given the file's insistence on distinguishing Forum advice from any admissibility act, "enregistrabilité"/"enregistrement" would be safer. Repair: re-sync after the EN corrections above land; the staleness banner keyed to source-commit cannot be verified from the bundle. Prose class with translation checks.

---

## 6. Directly related new discoveries (separated from the five questions)

1. **No notification or information duty for 5(3)(a) crystallisation** (from Q1). The extraction data are the undertaking's; 5(6) covers liquidity events only; 5(4)(a) denies the Reserve further information rights. The 6(3) valuer clock and the 5(5) three-month procurement deadline can run from a date nobody but the undertaking knows.
2. **Third-sentence deadline precedes the valuation it depends on** (from Q4). 5(5) third sentence requires procurement "no later than the completion of the liquidity event", but the share count is fixed by a valuation delivered "within 20 working days of the completion" (6(3)) and execution follows within a further 20 working days (fifth sentence). Round 2 moved the valuation after completion without adjusting the third sentence. Readable as "put the arrangement in place by completion", but it should say so.
3. **Transferee regime beyond issuance is not expressly extended** (from Q4). 5(11) and 5(12) attach "the obligations … under this Article" and issuance "as if it were a covered undertaking"; paragraphs 2 to 6 speak of "the covered undertaking". Whether crystallisation, valuation cost and execution apply to a transferee's warrant is inferable, not stated.
4. **Annex I point 3 still carries an autonomous command** ("shall be disregarded"), which JPG G22 and the drafting notes say was to move to the article (from Q2). The Q2 defence leans on this paragraph, so its placement matters.
5. **Article 9 has no supervisor and Article 8(7) removes the sectoral ones** (from Q3). Conduct rules with no addressee organ and no enforcement route.
6. **"Passive" wording** persists in memorandum §2.4 (EN "the holding is passive"; FR "la détention est passive") and recital 23 ("a passive owner"), against DC-41 ("The word to avoid is passive") and the site correction already made. Prose class.
7. Objection 15's "roughly EUR 400 … by year thirty" is a dated cautious-scenario estimate, consistent with EVIDENCE §7's cautious curve (EUR 1 200 by year fifty) and not contradicted by objection 21's EUR 8 400 on the amended designation set; not a defect, but it states a payout figure without the stake beside it in the same breath, which DC-31 forbids in the project's own material.

Not investigated here: property-rights validity, fiscal characterisation, Article 12(4) remedy paraphrase, threshold-avoidance routes beyond 3(8) — all outside the five questions.

---

## 7. Implementation order

1. **Memorandum corrections independent of drafting decisions** (Q5(b), (c), (d), (e) sentence, (f), (g), (h), plus "passive" wording): Prose/Editorial class; lint + gates 1 and 6. Q5(a) corrected to the article now; DC-1 wording reconciliation opened as a Constitutional-class item.
2. **French re-sync** (Q5(i)) immediately after step 1, including the missing §2.1 paragraph; translation checks.
3. **Article 5/13 package** (Q1 repair to 5(4)(e); 5(6) extraction notification; 13(1)(b) and transferee addressee; third-sentence timing; transferee regime clarification; recitals 10, 14, 29): one Substantive PR, full pipeline.
4. **Article 3(8) and Annex I point 3** (Q2, grant-value alignment, recital 7 wording): Substantive PR, full pipeline, with the acquisition policy decision recorded in the issue.
5. **Reserve governance article** (Q3): open the public issue first with the seven choices listed; draft after the appointment and accountability decisions are made; Substantive PR with the constitutional-style window because it decides a raid channel; update recital, memorandum §5.3 and §4, severability Layer 3.
6. Final memorandum and French pass after steps 3–5 land.

---

## Verdict

Verified scoped defects exist in the operative text (Q1 narrow conflict and notification gap; Q2 over-broad disregard command; Q4 execution and transferee gap in Article 13) and an essential design omission exists (Q3 governance). The memorandum and its French counterpart misdescribe the instrument on the points checked.

VERDICT: REVISE

---

## Assistant disposition (outside verbatim model output)

Diagnostic findings assessed; no operative amendment made. The REVISE verdict is retained. See [the assessment](../findings/2026-09-06-findings-assessment.md) for accepted findings, qualifications, declined suggestions and repair order. Predictions about institutional rejection, categorical enforcement exclusions and unverified external legal assertions are not adopted as settled law. Proposed replacement wording is not approved merely because the underlying defect is accepted. Final editorial review remains with David Vanheeswijck.
