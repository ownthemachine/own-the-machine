# Contributing

This is a draft law, so contribution works slightly differently from code.

**Read first:** regulation/memorandum/counter-arguments.md. It is the
strongest case against this Regulation and the constraints table at its end
governs every article. If your objection is there, sharpen it. If it is not,
that may be the most valuable PR you can make: objections are contributions.

**Propose amendments** by issue first (motivation, affected articles, which
of objections 1-18 it engages), then PR. See GOVERNANCE.md for merge
criteria and change classes.

**Translations** follow translations/README.md: machine-first draft, then
the adversarial gate with full-document context, then a native read. Legal
register, not essay register. The English text is the draft; translations
are for understanding.

**Style:** British English in prose; EU legislative drafting conventions in
regulation/ (see pipeline/DRAFTING-RULES.md); no em-dashes anywhere; run the linter from the
[tools repo](https://github.com/ownthemachine/own-the-machine-tools) before
pushing.

**What we will not merge:** anonymous-source claims in the evidence base,
weakening of the four tests, tracking of any kind in site code, campaign
copy dressed as analysis.

## Keeping private things out of a public repository

These repositories are public. Everything in them is public, and so is every
commit message, which is rendered on the hosting platform and copied into
every clone.

Two things reached them that should not have: a file naming living people
with contact details and private assessments of them, and a session
identifier in every commit message. Both were found by a person reading,
which is not a control.

`.githooks/scan.py` is the control. It runs on every commit, over the staged
content and over the message, and refuses anything matching a short list:
local account names and absolute paths, scratch and job directories, session
identifiers, the names of unrelated private projects, and credentials. The
hooks are versioned rather than living in `.git/hooks`, so a clone gets them:

    git config core.hooksPath .githooks

Run it by hand over any file with `python3 .githooks/scan.py FILE`, or over
what is staged with `python3 .githooks/scan.py --staged`.

If a match is genuinely a false positive, `git commit --no-verify` bypasses
it. Every use of that flag is a decision to publish something the control
objected to, so it should be rare and deliberate.

The co-authorship trailer is deliberately allowed. This project's own rule is
that authorship is a feature when declared and a liability when discovered,
and that applies to machine authorship as much as to the book.
