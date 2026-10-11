<div align="center">

# Ludwig van Beethoven

### Privacy & OSINT tooling — I build quiet, hardened browsers.

Composer of code — and, allegedly, of symphonies.

[![EROICA v0.2.1](https://img.shields.io/badge/EROICA-v0.2.1-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/eroica)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-263238?style=flat&labelColor=0d1117)](https://www.python.org/)
[![Zero dependencies](https://img.shields.io/badge/dependencies-none-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/eroica)
[![License: MIT](https://img.shields.io/badge/License-MIT-263238?style=flat&labelColor=0d1117)](https://github.com/BeethovenDev/eroica/blob/main/LICENSE)

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

> `eroica new → launch → audit` — create an isolated profile, open the browser,
> and verify it hasn't drifted. Mozilla and Chromium families supported.

Other things on the bench: a few private hardening experiments (Windows),
fed by the same philosophy — *boring is anonymous, and fail closed but say so.*

## Stack

`Python` · `PowerShell` · Firefox & Chromium hardening internals ·
`user.js`/prefs · DNS-over-HTTPS & ECH · `argparse` · `pytest` · `mypy` ·
`ruff` · GitHub Actions · Git

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