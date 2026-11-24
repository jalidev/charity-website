# Tadamon — Charity Website Demo (Arabic / English / French)

A trilingual charity website in a single HTML file: full Arabic/English/French switching with proper right-to-left layout for Arabic, vision/mission/goals sections, impact numbers, activities and a donate call to action. No dependencies.

![Stack](https://img.shields.io/badge/stack-vanilla%20JS-c8f542) ![Deps](https://img.shields.io/badge/dependencies-0-c8f542)

## Features

- **Three languages** — Arabic (RTL), English and French, switchable from the header; the choice persists via `localStorage`
- **True RTL** — `dir` flips on the document, with logical CSS properties (`margin-inline-start`, `border-block`) so the layout mirrors correctly
- **Sections** — hero, impact counters, vision/mission/goals cards, activities list, donate CTA
- **SVG-only artwork**, scroll-reveal with in-view fallback

## Run it

```bash
open index.html
```

Demo content for a fictional charity. Copy in all three languages is sample text.

---

*Demo project by [Jameel Ali](https://github.com/jalidev).*
