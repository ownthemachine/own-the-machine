# Archival and citability

Two independent archives, doing two different jobs. Neither depends on this
repository, GitHub, or the campaign's own infrastructure surviving.

## Software Heritage: preservation, live since 25 August 2026

The universal source archive run from Inria for UNESCO. All three
repositories were submitted on 25 August 2026 and crawled the same day:

| repository | snapshot SWHID |
|---|---|
| own-the-machine | `swh:1:snp:e956e375464118a72361c95400ef422fce5183e6` |
| own-the-machine-site | `swh:1:snp:54545284f7481c84e0fbdca537eb112c0b9a022b` |
| own-the-machine-tools | `swh:1:snp:1d301315f98c97de909c17f3a1052314df8c0dc3` |

A SWHID is intrinsic: it is computed from the content, so it can be
verified against any copy, and it resolves at
`https://archive.softwareheritage.org/<swhid>`. Anyone can re-archive at
any time, no account needed, through Save Code Now
(`archive.softwareheritage.org/save/`); do so after any milestone commit,
and record the new snapshot id here. The archive also re-visits known
origins on its own schedule.

## Zenodo: citability, live since 25 August 2026

Zenodo (CERN) issues DOIs, which is what officials, journalists and
academics actually cite. Release v0.1.0 is archived and both DOIs are
minted:

- **Concept DOI, cite this for "the draft, latest version":**
  [10.5281/zenodo.22094951](https://doi.org/10.5281/zenodo.22094951)
- Version DOI for v0.1.0:
  [10.5281/zenodo.22094952](https://doi.org/10.5281/zenodo.22094952)

`.zenodo.json` drives the deposit metadata, `CITATION.cff` drives GitHub's
cite button. Every future GitHub release is archived automatically and
mints a new version DOI under the same concept DOI. Tag a release at each
substantive milestone (the freeze at registration, above all), so the
version DOI trail matches the ledger. One recorded lesson: the first
processing run failed on metadata the loader would not accept; keep
`.zenodo.json` to the minimal well-known fields, lowercase licence id.

## Which is best

Neither; they are complementary and both are free. Zenodo is the citable
face: a DOI on a landing page, which is the identifier the audiences this
campaign needs will actually use. Software Heritage is the deep archive:
content-addressed, verifiable, already holding the history regardless of
what happens to GitHub or to Zenodo. The DOI points to a version; the
SWHID proves the bytes.
