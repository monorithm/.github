# Contributing

This file is the organization default. A repository with its own
`CONTRIBUTING.md` overrides it, and the ones that take outside contributions do
— start there.

## Before you open a pull request

Most repositories in this organization are **proprietary and publicly viewable
for reference only**; their `LICENSE` says so, and they do not accept outside
contributions. The open-source Flutter packages do:

- [monolens](https://github.com/monorithm/monolens) — camera capture and media editing
- [monowave](https://github.com/monorithm/monowave) — audio capture, peaks and editing
- [monokit](https://github.com/monorithm/monokit) — the Flutter implementation of the design language

If you are unsure which kind you are looking at, check the repository's
`LICENSE`.

## The shape of a good change

- **Open an issue first for anything non-trivial.** A bug report with a
  reproduction is welcome unannounced; a refactor is not.
- **One change per pull request.** A fix and a rename in one diff is two reviews
  pretending to be one.
- **Conventional commits**, enforced by commitlint through a lefthook hook.
  `feat!:` or a `BREAKING CHANGE:` footer for anything that changes a public
  surface.
- **Tests belong with the change.** A package here ships test doubles as part of
  its public surface precisely so that behaviour can be tested without hardware.

## Documentation

User documentation lives in the repo it describes, under `docs/`, and is
published to [monorithm.github.io](https://monorithm.github.io/) by
[monorithm.github.io](https://github.com/monorithm/monorithm.github.io). Pages
are plain markdown with no frontmatter — the first `#` heading is the title and
numeric filename prefixes set the order — so they read correctly both on GitHub
and on the site. The conventions are in
[that repo's README](https://github.com/monorithm/monorithm.github.io#writing).

Prose is one sentence per line and ASCII: `--` rather than an em dash.
