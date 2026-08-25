# Archival and citability

Two independent archives, doing two different jobs. Neither depends on this
repository, GitHub, or the campaign's own infrastructure surviving.

## Software Heritage: preservation, live since 25 August 2026

The universal source archive run from Inria for UNESCO. All three
repositories were submitted on 25 August 2026 and crawled the same day:

| repository | snapshot SWHID |
|---|---|
| own-the-machine | `swh:1:snp:676f77f906103a43786a1c4cc6063be4693a1f23` |
| own-the-machine-site | `swh:1:snp:54545284f7481c84e0fbdca537eb112c0b9a022b` |
| own-the-machine-tools | `swh:1:snp:1d301315f98c97de909c17f3a1052314df8c0dc3` |

A SWHID is intrinsic: it is computed from the content, so it can be
verified against any copy, and it resolves at
`https://archive.softwareheritage.org/<swhid>`. Anyone can re-archive at
any time, no account needed, through Save Code Now
(`archive.softwareheritage.org/save/`); do so after any milestone commit,
and record the new snapshot id here. The archive also re-visits known
origins on its own schedule.

## Zenodo: citability, prepared, one login from live

Zenodo (CERN) issues DOIs, which is what officials, journalists and
academics actually cite. The metadata is already in the repository:
`.zenodo.json` drives the deposit, `CITATION.cff` drives GitHub's cite
button. What remains needs the initiator's own login, once:

1. Log in at zenodo.org with the GitHub account.
2. GitHub settings page on Zenodo: flip the switch for
   `ownthemachine/own-the-machine`.
3. Create a GitHub release (tag `v0.1.0` or similar) of the commit to be
   citable. Zenodo archives it automatically and mints two DOIs: a version
   DOI for that release and a concept DOI that always resolves to the
   latest.
4. Record both DOIs here and in versions/README.md; put the concept DOI on
   the site's versions page.

Tag a new release at each substantive milestone (the freeze at
registration, above all), so the version DOI trail matches the ledger.

## Which is best

Neither; they are complementary and both are free. Zenodo is the citable
face: a DOI on a landing page, which is the identifier the audiences this
campaign needs will actually use. Software Heritage is the deep archive:
content-addressed, verifiable, already holding the history regardless of
what happens to GitHub or to Zenodo. The DOI points to a version; the
SWHID proves the bytes.
