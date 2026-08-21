# Frozen versions

This directory holds texts that can no longer change.

A file lands here when a version of the draft is filed with the European
Commission. From that point the filed text is what citizens are asked to
sign, and Regulation (EU) 2019/788 does not allow it to be amended, so the
copy kept here is verbatim and permanent. The living draft continues in
regulation/; the two are different things and the site says so on every
page that renders either.

## State

REGISTERED.json carries the machine-readable state and is the only place
the answer is recorded. The site reads it at build time. Today it says
there is no registered version, because there is not.

## Making a freeze

1. Create versions/<registration-number>/ and copy the filed text into it
   verbatim, exactly as submitted, including the annex as filed.
2. Add MANIFEST.json to that directory: the source commit, the filing date,
   the registration number, the Commission decision reference and the
   languages filed.
3. Set REGISTERED.json to point at it.
4. Never touch the directory again. A correction is a new version.

The rule these steps implement is in GOVERNANCE.md and takes precedence
over this file if the two ever disagree.
