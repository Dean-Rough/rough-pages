# Rough Pages

Public deployment surface for Rough-branded HTML artifacts. GitHub Pages serves from `main` branch at:

**https://dean-rough.github.io/rough-pages/**

## Contents

| Path | Purpose |
|------|---------|
| `fonts/` | Self-hosted brand fonts for all Pages artifacts |
| `the-goldfinch.html` | Goldfinch book flyer (Rough Editions) |
| `eala-bhan-deck.html` | Eala Bhan CAPEX deck |

## Conventions

- All HTML artifacts reference fonts locally: `fonts/FoundersGroteskXCond-Bold.otf`
- No external font CDNs — everything is self-contained in the repo
- Fonts mirror what's in `rough-design-system/fonts/`
- Push to main → goes live
- Images: use GitHub-hosted URLs or self-host in an `images/` directory

## Setup for New Sessions

```bash
git clone git@github.com:Dean-Rough/rough-pages.git
# Fonts are already in fonts/ — no need to download from Drive
```
