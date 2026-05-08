# Ariapura · Pitch Log

## Brief (verbatim)

> Italian Digital Relaunch for Ariapura — HVAC sanitation, ariapura.org. Italian-speaking expert. 4 phases:
> 1. Fix WordPress permalink issues + errors
> 2. Transform homepage into high-conversion LP
> 3. Optimize GMB for local SEO
> 4. Setup Google Ads
>
> Client provides logo, basic texts, real photos. Asks for examples of similar funnels. Free check-up offer central.

## Demo

URL: https://skynetlabs-ariapura-relaunch.vercel.app
Repo: https://github.com/waseemnasir2k26/skynetlabs-ariapura-relaunch

**3 variants in single index.html, sticky top-right switcher, hash-persistent (#v1 #v2 #v3):**
- V1 Clinical Air — graphite + ivory + air-blue · Fraunces + Inter
- V2 Eco-Medico — forest + bone + brass · Cormorant + Manrope
- V3 Industrial-Luxe — charcoal + warm white + mint + terracotta · Fraunces + DM Sans

## Wedge vs niche

Italian HVAC sanitation = 2 tier (top corporate + bottom tradesman). Mid-tier (€2-8K/intervento per studi medici, palestre, ristoranti) is open. Wedge:
1. Clinical-medical aesthetic (not navy-corporate, not Wix-tradesman)
2. Sectorial funnel: 6-8 LP verticali planned (Phase 2)
3. Concrete deliverable for "check-up gratuito" (sopralluogo + video-ispezione + tampone + 48h report)
4. HVACBusiness + FAQ schema (current site missing)
5. GHL + n8n automation loop (no top-tier competitor has this)

## Real data baked in (no inventions)

- Sede: Via Lame 261, Castel Maggiore (BO)
- Tel: +39 051 082 8717
- Email: info@ariapura.org
- Orari: Lun–Ven 09:00–13:00 / 14:30–17:30
- Founder: Alex · 30+ anni
- 3 servizi: Sanificazione · Manutenzione · Filtri Elettrostatici
- 4-step process: Consulenza → Accordo → Esecuzione → Controllo Qualità
- Hero hook: "9 su 10 non sa cosa respira"
- Certificazioni dichiarate: FGAS + ACCREDIA (no AIISA/NADCA/ISO claim — those weren't on the site, won't fake)

## Bonus deliverable

`docs/GROWTH-PLAN.md` — one-page closed-loop funnel: LP → Ads → CRM → n8n → Reviews → SEO. Includes:
- 7-cantieri ROI list
- Tech stack (GHL + n8n + CallRail + Cal.com) w/ costs
- KPI dashboard (7 metrics)
- 90-day roadmap (4 phases)
- 5 quick wins for week 1
- Lead/mese projection: 8-15 → 35-60 (90gg) → 80-150 (12 mesi)

## 7 Scope Qs Sent (Italian, no pricing)

1. Quale variante (V1 / V2 / V3)?
2. Logo + palette + font esistenti?
3. Foto reali interventi + ritratto Alex?
4. Lista comuni serviti (Bologna + Modena/Ferrara/Imola)?
5. Stack già in casa: GHL · n8n · CallRail · GSC · GA4 · Ads?
6. P.IVA + ragione sociale (mancante footer)
7. Espansione 12 mesi a 2-3 città vicine?

## Note · Pre-send checklist

- Replace `REPLACE_WITH_WEB3FORMS_KEY` (3× in index.html) once client picks variant
- Wire form to GHL webhook (post-handoff)
- Confirm P.IVA before live
- Flip robots.txt from noindex → index after staging on real domain
- Lighthouse mobile target ≥90 before final deploy
