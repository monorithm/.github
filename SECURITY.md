# Security policy

This file is the organization default. A repository with its own `SECURITY.md`
overrides it.

## Reporting a vulnerability

**Do not open a public issue.** Email
[hq@harnicode.com](mailto:hq@harnicode.com) with:

- what the vulnerability is, and which repository and version it affects
- how to reproduce it, as concretely as you can
- what an attacker could do with it

You will get an acknowledgement within three working days, and an assessment
with an expected fix timeline within ten. We will tell you when a fix ships, and
credit you in the release notes unless you would rather we did not.

Please give us a reasonable window to release a fix before disclosing publicly.

## Scope

Anything in this organization. The open-source Flutter packages
([monolens](https://github.com/monorithm/monolens),
[monowave](https://github.com/monorithm/monowave),
[monokit](https://github.com/monorithm/monokit)) are the most likely place for a
report, since they run inside other people's applications: a crash on malformed
input, a path traversal in a file operation, or anything that lets untrusted
media reach memory it should not.

Documentation sites and the org site are in scope for content injection and
supply-chain issues, not for missing security headers on a static site.
