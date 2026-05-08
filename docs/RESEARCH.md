# Ariapura — Research Pack

## 1. Stato attuale (ariapura.org)

- **Brand:** Ariapura · "Soluzioni innovative per un'aria pulita e salubre, ogni giorno"
- **Sede:** Via Lame 261, 40013 Castel Maggiore (BO) · Bologna provincia
- **Telefono:** +39 051 0828717 · **Email:** info@ariapura.org
- **Orari:** Lun–Ven 09:00–13:00 / 14:30–17:30
- **Founder:** Alex · 30+ anni esperienza
- **CMS:** WordPress · permalink/errori segnalati
- **Hero attuale:** "Proteggi la tua salute" · CTA "Richiedi il Check Gratuito"
- **3 servizi:** Sanificazione · Manutenzione · Filtri Elettrostatici
- **Metodo:** 4 fasi (Consulenza → Accordo → Esecuzione → Controllo Qualità)
- **Stat hook:** "9 su 10 non sa cosa respira"
- **Certificazioni dichiarate:** FGAS · ACCREDIA
- **Social:** FB / YouTube / IG / LinkedIn
- **Blog:** attivo, 2+ post recenti

## 2. Niche Sameness Gap

Italian HVAC sanitation 2026 — niche dominata da **2 tier puliti, no middle**:

**Top tier** (Alisea, AirBio, Techno One, Aria Sicura, Sidabo): forte cert-stack (NADCA / AIISA / ISO), corporate navy/teal, lead form lungo, lead magnet PDF/video, settori sanitari/industriali.

**Bottom tier** (tradesman / Wix / siti generici): 1-pager brochure, "chiamaci", zero certificazioni visibili, foto stock.

**Middle tier vuoto:** premio mid-tier (€2-8K/intervento) per studi medici, palestre, ristoranti, uffici locali. Nessuno presidia bene.

**Wedge per Ariapura:**
1. Estetica clinical-medical (non navy-corporate, non Wix-tradesman)
2. **Funnel settoriale**: 6-8 LP verticali (palestre / ristoranti / cliniche / uffici / scuole / hotel / industria / residenziale)
3. **Check-up come deliverable concreto** (sopralluogo + video-ispezione + tampone + report 48h) — vince vs generico "preventivo gratuito"
4. **Schema HVACBusiness + FAQ** per ranking GMB + organic Bologna
5. **Automazione lead-to-revisita** (GHL + n8n) che i top tier ancora non hanno

## 3. Palette + Type Lock (3 direzioni)

| Variant | Palette (hex) | Type | Uso |
|---|---|---|---|
| **V1 Clinical** | Graphite `#0F1620` · Ivory `#F5F1EA` · Air-blue `#9FB8C8` · Deep teal `#1F3A4D` | Fraunces + Inter | Posizionamento medico-istituzionale |
| **V2 Eco-Medico** | Forest `#1B2A22` · Bone `#EFE8DA` · Brass `#A8884A` · Sage `#3F5A48` | Cormorant Garamond + Manrope | Premio + ESG narrative |
| **V3 Industrial-Luxe** | Charcoal `#1A1A1A` · Warm white `#E8DDD0` · Mint `#7DB8A4` · Terracotta `#B85A3E` | Fraunces + DM Sans | Modern industrial trust |

**Anti-patterns:** giallo CTA aggressivo, gradient blu Bootstrap, drone+text, stock-grin technician. Italian B2B punisce questi pattern.

## 4. SEO Italian Keywords (16 top)

| Termine | Intent | Tier IT |
|---|---|---|
| sanificazione impianti aria condizionata | commercial | mid |
| sanificazione condotte aerauliche | commercial | mid |
| pulizia condizionatori | trans/info | high |
| rimozione muffa condizionatore | commercial | mid |
| sanificazione split | commercial | mid |
| sanificazione UTA | B2B | low |
| manutenzione impianti aria | commercial | mid |
| check-up gratuito condizionatore | bottom-funnel | low |
| sanificazione aria uffici | B2B | low |
| sanificazione aria palestra Bologna | B2B local | low |
| sanificazione aria ristorante | B2B | low |
| sanificazione aria clinica | B2B | low |
| ogni quanto sanificare condizionatore | info | mid |
| differenza pulizia sanificazione condizionatore | info | low |
| normativa UNI 10381-2 | info | low |
| Accordo Stato-Regioni 2006 sanificazione | info | low |

**Local modifiers:** Bologna · Modena · Ferrara · Imola · Cesena · Forlì · "vicino a me" · "Castel Maggiore" · provincia BO

## 5. Schema Pick

**`HVACBusiness`** (subtype LocalBusiness) — match esatto categoria. Stack:
- `HVACBusiness` parent + `areaServed` + `priceRange` + `vatID`
- `Service` × 3 (sanificazione, manutenzione, filtri)
- `Offer` per check-up gratuito (price 0)
- `FAQPage` con 6 domande tecniche
- `hasCredential` per FGAS + ACCREDIA

## 6. EEAT Checklist (IT)

1. P.IVA visibile in footer (mancante attualmente)
2. Conformità UNI 10381-2 + UNI EN 15780 dichiarata
3. Attestato Accordo Stato-Regioni 2006 (formazione operatori)
4. FGAS + ACCREDIA visibili (già presenti, mantenere)
5. Polizza RCT/RCO con massimale visibile
6. ≥30 anni esperienza (Alex) — già monetizzato
7. Video-ispezione condotte robot (camera a colori)
8. Certificato finale di sanificazione + report fotografico
9. Tecnici con nome/foto (Alex già visibile)
10. Settori serviti con loghi clienti (mancante)

**Cert non claim:** non inventare AIISA / NADCA / ISO 9001 (Ariapura non li dichiara). Mantenere autentici FGAS + ACCREDIA + esperienza 30+ anni.

## 7. Google Ads Plan

- **Search exact + phrase** top 6 KW commerciali con geo Bologna + 30 km
- **Neg kw**: fai-da-te, ricarica gas, installazione, prezzo basso, lavoro, corso
- **CPC stimato:** €1,50-3,00 res · €3-5 B2B
- **Conversion goals:** form check-up · call tracking · WhatsApp click
- **Asset:** sitelink (Normativa / Certificati / Settori), callout (Sopralluogo gratuito 24h), lead form extension
- **PMax:** attivare dopo 30 conversioni baseline

## 8. Italian Tone of Voice

Lei (formale). Sobrio, preciso, autorevole. Niente superlativi. Niente exclamation marks. Numeri misurabili (UNI 10381-2, 48 ore, 30+ anni). Reference: Chiesi corporate, IMA Group, Sapio. Italian B2B punisce "amichevole-vendita".

## 9. Funnel Wedge: "Check-up Aeraulico Gratuito"

Non generico "preventivo gratuito". Deliverable concreto:
1. Sopralluogo on-site
2. Video-ispezione robotizzata di 1 ramo condotta
3. Tampone microbiologico campione (se utile)
4. Report PDF in 48 ore
5. Senza obbligo di acquisto

Battle vs niche convention: vince perché concreto + tempo-bounded + "nessun obbligo" rimuove friction.

## 10. Content Cluster (8 titoli IT)

1. "Ogni quanto sanificare il condizionatore? La risposta secondo UNI 10381-2"
2. "Pulizia o sanificazione condizionatore: la differenza che cambia la bolletta"
3. "Accordo Stato-Regioni 5 ottobre 2006: cosa obbliga davvero il datore di lavoro"
4. "Ozono o prodotti chimici per condotte aria? Pro, contro e cosa dice la norma"
5. "Muffa nello split: 5 segnali che l'impianto va sanificato (con foto reali)"
6. "Sanificazione UTA in palestra/ristorante/clinica: protocollo HACCP-compatibile"
7. "Quanto costa sanificare i canali dell'aria al m²? Range reali Italia 2026"
8. "Check-up gratuito: cosa include davvero (video ispezione + tampone)"
