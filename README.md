<div align="center">

# Ludwig van Beethoven

### Privacy & OSINT tooling — I build quiet, hardened browsers.

Composer of code — and, allegedly, of symphonies.

[![EROICA v0.3.0](https://img.shields.io/badge/EROICA-v0.3.0-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/eroica)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-263238?style=flat&labelColor=0d1117)](https://www.python.org/)
[![Zero dependencies](https://img.shields.io/badge/dependencies-none-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/eroica)
[![License: MIT](https://img.shields.io/badge/License-MIT-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/eroica/blob/main/LICENSE)

[![FIDELIO](https://img.shields.io/badge/FIDELIO-v0.1.0-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/fidelio)
[![DIABELLI](https://img.shields.io/badge/DIABELLI-v0.1.0-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/diabelli)
[![STACCATO](https://img.shields.io/badge/STACCATO-v0.1.0-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/staccato)
[![VELATA](https://img.shields.io/badge/VELATA-v0.1.0-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/velata)
[![APPASSIONATA](https://img.shields.io/badge/APPASSIONATA-v0.1.0-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/appassionata)
[![GROSSE FUGUE](https://img.shields.io/badge/GROSSE-FUGUE-v0.1.0-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/grosse-fuge)

</div>

---

## Current work

### [EROICA](https://github.com/BeethovenDev/eroica) — browser privacy hardening

Privacy hardening for any browser, named after the Third Symphony. It turns an
ordinary profile into a quieter, harder-to-fingerprint one by composing
**five symphonic movements** across **three additive tiers** — and it ships with
**zero runtime dependencies** and a strict-typed, fully tested core.

```text
I    First     Op. 21  foundations, quiet startup
III  Eroica    Op. 55  anti-fingerprinting
V    Fate      Op. 67  trackers & telemetry
VI   Pastoral  Op. 68  storage hygiene
IX   Choral    Op. 125 transport security (DoH, ECH, CRLite)
```

> `eroica new → launch → audit → check-ip` — create an isolated profile, open
> the browser, verify it hasn't drifted, and confirm what IP the world sees.
> Mozilla and Chromium families supported, plus optional Tor/SOCKS routing.

## The opus set — Op. 23 to Op. 133

All defensive, all **zero-dependency**, all strict-typed, all released:
a small philharmonic of quiet privacy tooling.

| Work | What it does |
| --- | --- |
| [FIDELIO](https://github.com/BeethovenDev/fidelio) | offline OPSEC self-audit — weighted privacy-risk scoring for accounts and habits |
| [DIABELLI](https://github.com/BeethovenDev/diabelli) | file-integrity watch — SHA-256 fingerprints and a `.diabellignore` |
| [STACCATO](https://github.com/BeethovenDev/staccato) | staged-diff secret scanner with entropy gates and allowlists |
| [VELATA](https://github.com/BeethovenDev/velata) | metadata autopsy & strip for JPEG, PNG, WebP, TIFF and PDF |
| [APPASSIONATA](https://github.com/BeethovenDev/appassionata) | passive TLS & HTTP transport-hygiene scan — one GET per host, 0-100 scores |
| [GROSSE FUGUE](https://github.com/BeethovenDev/grosse-fuge) | PII redaction pipeline — masking and salted pseudonyms for text, CSV, JSON |

```text
FIDELIO  „Fidelio“ sings     OPSEC audit, weighted, reportable
DIABELLI Variations           watch files, notice drift
STACCATO detached strokes     diff is a field; secrets don't land
VELATA   veiled              metadata ghosts removed from images
APPASSIONATA sustained storm  how loudly does your transport talk?
FUGUE    one theme, six voices PII fragments bound before release
```

Each tool exits non-zero exactly when it should, ships a human report and a
`--json` machine mode, and takes a strict-typed, fully unit-tested core. No
runtime dependencies, no telemetry, no phone-home.

Other things on the bench: a few private hardening experiments (Windows),
fed by the same philosophy — *boring is anonymous, and fail closed but say so.*

## Stack

`Python` · `PowerShell` · Firefox & Chromium hardening internals ·
`user.js`/prefs · DNS-over-HTTPS & ECH · SOCKS5 tunneling · `argparse` ·
`pytest` · `mypy` · `ruff` · GitHub Actions · Git

[![Type Checking](https://img.shields.io/badge/typing-strict-263238?style=flat&labelColor=0d1117)](https://mypy-lang.org/)
[![Linting](https://img.shields.io/badge/linting-ruff-263238?style=flat&labelColor=0d1117)](https://docs.astral.sh/ruff/)
[![Tests](https://img.shields.io/badge/tests-ci-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/eroica/actions)

## Approach

* **Boring is anonymous** — a config that keeps changing is itself a fingerprint.
* **Fail closed, but say so** — strict DoH and HTTPS-only fail closed; every
  tool ships an audit so you always know what changed.
* **No hidden magic** — settings are readable modules with a comment explaining
  *why*, not wrappers around wrappers.
* **Reverse nothing** — hardening only; no authentication or access-control
  bypasses, ever.

## Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=BeethovenDev&show_icons=true&hide_title=true&theme=transparent&ring_color=37474f&icon_color=546e7a&text_color=90a4ae)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=BeethovenDev&layout=compact&theme=transparent&text_color=90a4ae)

*Fresh account — most activity happens in the shadows of private repositories.*

## Reach out

* [EROICA discussions](https://github.com/BeethovenDev/eroica/discussions) —
  the best way to talk about hardening, OSINT workflows and browsers.
* That's it. No socials, no phone-home buttons on the profile page either.

---

<div align="center">

*“From the heart — may it go to the heart.”*

**Beethoven**

</div>