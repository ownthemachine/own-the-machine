# Website claim-correction release

7 September 2026. The initiator requested updating the website before the
next MEP approach. This continues the recorded claim-correction issue as a
public-prose release. It does not amend any enacting provision, constitutional
constraint or campaign gate in this turn. No new public issue was opened.

## What the public site presents

The site renders the current root regulation/ working draft, including the
previously reviewed Article 114 repair package. The separate integrated
Article 352 candidate is not substituted into the law or downloads. The
earlier substantive REVISE findings remain open. Publication makes the draft
inspectable; it is not a statement that the instrument passed substantive
review, was registered, was adopted or has legal force.

This release carries the earlier claim corrections into the live build:
all three warrant triggers, payment registration, possible zero payments,
limits on statutory protection, and transparent funding and organisational
status. New material includes a visible working-draft notice in all five
languages, a dated progress section, and explicit unvalidated-sizing warnings
on the objections, explanatory-memorandum and simulator pages and PDF/EPUB
covers. The homepage distinguishes Article 114 from the Article 352 option.

The sole new law-repository prose edit corrects the English and French
memoranda's outdated statement that the Forum enquiry is pending. Advice
was received and acknowledged on 27 August; the exchange is closed. That
advice is independent and non-binding, not approval of the proposed law.

## Reviews and dispositions

| Gate for this prose release | Round 1 | Round 2 |
|---|---|---|
| Form appropriate to public prose | PUBLISH | PUBLISH |
| Layer fidelity | PUBLISH | PUBLISH |
| Four-language fidelity and native readability | PUBLISH | PUBLISH |
| Hostile reader, Fable 5.1 | REVISE | PUBLISH |

Form preceded fidelity in each round. Translation and hostile checks ran
independently against the same immutable input. All adverse rounds remain
archived. Native readability here is a model assessment; the site does not
claim human native-reader certification.

Accepted from Fable round 1:

- Move the notice's CSS out of an HTML comment into its actual style block.
  Visual inspection independently caught the same defect.
- Correct the Forum enquiry status in both memoranda.
- Repair the English simulator sentence about the seven-year backstop.
- Identify the initiator as a Person in structured data, and align the
  legislation title with the downloadable draft. Schema terminology is not
  a legal determination about whether informal groups are organisations.
- Correct the simulator's initial display value and qualify its source-code
  comment: the legacy value/revenue multiple is an assumption, not a
  validated measurement of the current designated set.
- Render the sizing caveat on the explanatory and simulator screens as well
  as the objections screen. The first translation review over-described
  placement; the second review and rendered checks inspect the actual screens.

Pre-existing law-side attacks in the hostile review remain questions for
the substantive programme. The release does not adopt the model's external
legal assertions as verified holdings. A homepage summary about issuing a
warrant is read with the existing detailed explanation of automatic attachment
and later documentation; no new delay in the statutory claim is asserted.

Fable round 2 returns PUBLISH. Its non-blocking registration-record link
finding is addressed by exempting REGISTERED.json from source-commit pinning:
that link promises the latest registry record. The working-draft notice is
also retained on browser-printed pages, except the already qualified one-page
brief, with black-on-white print styling. These final presentation/link
repairs change no reviewed claim. The existing GATE1-LETTER.md contains the
dated acknowledgement; a missing date in the shorter review ledger does not
make the date unverified. Translation-staleness automation for site-native
pages and the future registration-state notice behaviour remain follow-up
items before registration. This release makes neither human translation
certification nor legal clearance claims.

## Engineering verification and provenance

- Site prose/rendering: site commit 6c886b9. Source memorandum correction:
  law 9f02181. Exact source snapshots are the r1/r2 SHA-256 bundle manifests.
- Prompts: tools 4126534 and 8b8b49a; each exact prompt and raw response is
  preserved with hashes. Gemini runs use EU/zero-retention/no-training;
  Fable uses an explicit per-run EU/30-day/no-training public-material
  exception. No Astra review is claimed.
- Build: 191 pages; sitemap: 190 URLs. Release checks cover translation
  structure, labels, five one-page printed briefs, reachable contents lists
  and navigation in all five languages.
- Browser audit: 20 page/theme samples, each checked at desktop and mobile
  widths; zero WCAG A/AA axe findings after contrast repairs, no horizontal
  overflow, runtime errors or third-party requests. Simulator controls work.
  These samples are not a certification of every page or every interaction.
- Contrast repairs darken light-theme gold and lighten dark-theme red.
  The initial failing checks are recorded as repaired, not omitted.
- CSP/runtime checks pass. PDF/EPUB regenerated; PDF cover visually inspected.
  Final generated artefact hashes and live verification belong in the site
  release record once deployed.
- Legislative lint: zero errors, seven existing terminology warnings.
- Source links resolve against the build's law commit, rather than silently
  pointing at main. Review records retain pending final editor dispositions.
- Privacy scan: law tracked files pass. The site scan flags the slash-separated
  editorial grouping of about, home and FAQ in an existing German review as if it
  were a home-directory path. It is not a private path; the raw review is
  preserved. Newly staged release files pass without bypassing commit hooks.

The earlier stale-source banners for plain summaries of Articles 1, 2 and 7
remain visible. They are disclosed translation/review debt, not silently
restamped as reviewed. The simulator remains an illustrative legacy model;
its arithmetic is not replaced with the unadopted reference-policy model.

## Deployment boundary

Use the existing Scaleway EU storage/CDN target. A verified rollback copy
of all 537 existing storage objects was prepared. Extensionless page objects
and same-named directories require distinct local backup names; a flat
object manifest preserves both. Previous immutable asset hashes are retained
during deployment so cached pages can still load their styles and scripts.

Public source branches must be available before the website links to their
commits. No merge to main, official filing, signature collection or message
to an MEP is part of this release. The letter remains unsent and its private
recipient/opening remains to be confirmed.

Deployment and public-response checks are recorded separately in the site
repository after completion; this preparation record does not claim them.
