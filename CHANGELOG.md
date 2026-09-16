# Changelog

All notable changes to this project are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [2026.09] - 2026-09-16

- Maintenance review of skynetlabs-ariapura-relaunch — the first speculative relaunch demo by SkynetLabs for ariapura.org, an Italian HVAC sanitation specialist in Bologna.
- Status: single static `index.html` carrying three design variants (V1 Clinical, V2 Eco-Medico, V3 Industrial-Luxe) behind a sticky top-right switcher. Stack is Tailwind CDN + vanilla JS with no build step, Italian copy throughout, HVACBusiness/Service/Offer/FAQPage JSON-LD, `sitemap.xml`, `robots.txt` and a `vercel.json`. Pitch material lives in `docs/` (RESEARCH, GROWTH-PLAN, CLIENT-MESSAGE, CLIENT-PITCH).
- This bundle has been superseded: the successor repo `skynetlabs-ariapura-cinema` states that it deprecates this one. Last commit here was 2026-05-08 (full content rebuild using verbatim ariapura.org copy).
- Reviewed September 2026: docs refreshed, versioned as v2026.09. No markup, asset or config changes in this release.
- Known gaps, all pre-existing: the Web3Forms key is still the literal `REPLACE_WITH_WEB3FORMS_KEY` placeholder; the README claims MIT but there is no LICENSE file; no CHANGELOG.md before this release; the README does not point readers at the successor repo.
