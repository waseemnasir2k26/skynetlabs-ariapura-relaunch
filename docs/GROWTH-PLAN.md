# Ariapura — Piano di Crescita Digitale (Una Pagina)

> Come trasformare il sito in una macchina lead a ciclo chiuso: LP → Ads → CRM → Automazione → Recensioni → Lead caldi che si auto-rigenerano.

---

## 1. Il Funnel a Ciclo Chiuso (lo stato finale)

```
   Google Ads / SEO / GMB / Social Organic
                  │
                  ▼
        [Landing Page Settoriale]
       (palestra / clinica / ufficio)
                  │
                  ▼
       Form "Check-up Gratuito"
                  │
              ┌───┴────┐
              ▼        ▼
         GHL CRM   n8n Workflow
              │        │
              │        ├─→ Email conferma istantanea (PDF preview report)
              │        ├─→ SMS / WhatsApp 5 min dopo
              │        ├─→ Notifica al tecnico via Telegram
              │        └─→ Calendar slot pre-bookato (Cal.com / GHL)
              ▼
         Sopralluogo
              │
              ▼
       Report PDF firmato (48h) — automatico via n8n + DocuSign
              │
              ▼
        Preventivo (GHL pipeline drag-and-drop)
              │
              ┌───┴────┐
              ▼        ▼
           Vinto     Perso
              │        │
              │        └─→ Sequenza nurture 90 giorni (4 email + 1 case study video)
              ▼
        Intervento + foto/video
              │
              ▼
       Richiesta recensione automatica (GMB) 7 giorni post
              │
              ▼
       Recensioni → SEO locale → Più traffico GMB
              │
              └─────→ ricicla in cima al funnel
```

---

## 2. I 7 Cantieri Concreti (in ordine di ROI)

### 1. Landing Page Settoriali (la fonte di tutto)
- **6-8 LP verticali**: una per ogni settore (palestre, ristoranti, cliniche, uffici, scuole, hotel, industria, residenziale)
- Ognuna con copy, foto, FAQ, schema, e parole chiave specifiche del settore
- Crea 6-8 ingressi SEO + permette ad Ads di matchare query come "sanificazione aria palestra Bologna"
- **Lift atteso lead organici:** 3-5× rispetto a homepage unica

### 2. GMB Optimization (locale, gratis, sottovalutato)
- Categoria primaria: "Servizio di pulizia condotti dell'aria" (NON "HVAC contractor")
- Foto settimanali geo-taggate (interni, mezzi, tecnici al lavoro)
- Q&A pre-popolato con 8 risposte (UNI 10381-2, frequenza, ozono, costo medio, certificato finale, settori)
- 3 post settimanali: case study, articolo blog, offerta check-up
- Richiesta recensioni automatica via SMS post-intervento
- **Risultato:** 2-3× ranking "vicino a me" + 4-6× chiamate dirette dalla mappa

### 3. Google Ads — Search + Local (l'acceleratore)
- **Search exact + phrase** sulle 6 keyword commerciali principali
- **Negative kw**: fai-da-te, gas R32, ricarica, installazione, prezzo basso, lavoro, corso
- **Geo:** Bologna + comuni 30 km (Modena, Imola, Ferrara)
- **Conversion goal:** form check-up + call tracking (numero CallRail dedicato)
- **Budget di partenza:** test €30-50/giorno, CPC stimato €1,50-3,00 commerciale-residenziale, €3-5 B2B
- **Asset:** sitelink (Normativa / Certificati / Settori), callout "Sopralluogo gratuito 24h", lead form extension
- **Test:** Performance Max attivare DOPO 30 conversioni baseline

### 4. n8n — Lead Routing Automatizzato (il moltiplicatore)
Workflow critici:
- **Form fill → triage:** B2B (azienda compilata) → Telegram al titolare entro 2 min · B2C → email-CRM normale
- **Email conferma istantanea** con anteprima report PDF + 3 case study del settore scelto
- **SMS / WhatsApp follow-up** 5 minuti dopo se manca risposta
- **Calendar pre-book** automatico via Cal.com (sopralluogo confermato in 1 click)
- **Report PDF generation:** template DocuSign + dati cantiere → PDF firmato → email cliente entro 48h (vs 5-7 giorni manuali)
- **Notifica recensione GMB** automatica 7 giorni post-intervento, con link diretto

### 5. GHL CRM — Pipeline + Nurture (il salvavita lead persi)
- **Pipeline 5 stadi:** Lead nuovo → Sopralluogo programmato → Sopralluogo fatto → Preventivo inviato → Vinto/Perso
- **Sequenza Lead Persi 90 giorni:** 4 email + 1 video case study + 1 chiamata follow-up. Recupera 8-12% dei "no oggi"
- **Database manutenzioni ricorrenti:** dopo intervento, scheda automatica con prossima sanificazione (annuale/biennale/triennale). Promemoria 60 + 30 + 7 giorni prima
- **Risultato:** un cliente sanificato è un cliente per 5+ anni (non un one-shot)

### 6. Social Proof — Video Pre/Post (il convertitore a freddo)
- 1 video pre/post a settimana (60-90 secondi): condotta sporca → sanificata
- Cross-post: GMB / Instagram Reels / Facebook / YouTube Shorts / LinkedIn
- Caption template: "Cliente: [settore]. Stato impianto: [descrizione]. Intervento: [protocollo]. Risultato: [tampone pre/post se disponibile]."
- 12 video → 6 mesi di contenuti automatici → traffico organico "muffa condizionatore" senza pagare

### 7. Recensioni + Referral Loop (il volano)
- Post-intervento: SMS automatico con link recensione GMB pre-compilata
- Programma referral B2B: 50€ Amazon Voucher per ogni cliente azienda referenziato che firma
- Target: 30 recensioni nuove / 90 giorni → 4.5★+ stable → ranking GMB salito → più chiamate

---

## 3. Stack Tecnologico

| Tool | Funzione | Costo mensile |
|---|---|---|
| **WordPress** (esistente) | CMS sito principale | — |
| **GoHighLevel** (GHL) | CRM + email + SMS + funnel + calendar | €97-297/mo |
| **n8n** (self-host VPS) | Automazioni workflow | €10/mo VPS Hostinger |
| **CallRail** | Tracking chiamate da Ads / GMB | €45/mo |
| **Google Ads** | Search + LSA (se attivo) | €1.000-3.000/mo budget |
| **Cal.com** o GHL Calendar | Booking sopralluoghi | incluso GHL |
| **DocuSign / Google Drive API** | Report PDF firmati automatici | €15/mo |

**Totale stack:** ~€170-360/mo + budget ads.
**Break-even tipico:** 1-2 interventi B2B/mese (palestra/clinica) coprono tutto.

---

## 4. KPI Mensili da Monitorare

1. **Lead totali** (form + chiamate + WhatsApp) — target +40% in 90 giorni
2. **Cost per Lead (CPL)** Ads — benchmark €25-60 in questa nicchia
3. **Conversion Rate sopralluogo→preventivo** — target 70%+
4. **Conversion Rate preventivo→vinto** — target 35-50%
5. **Recensioni Google nuove / mese** — target 8-12
6. **Posizione organica top 5 keyword** — Ahrefs / SEMrush
7. **Recurring revenue** (clienti su contratto manutenzione) — target 30% del fatturato entro 12 mesi

---

## 5. Roadmap a Fasi (90 giorni)

| Fase | Settimane | Cosa ship |
|---|---|---|
| **Fase 1 — Fondamenta** | 1-2 | LP nuova (variant scelto), permalink fix, GMB ottimizzato, schema HVACBusiness, Google Search Console, Analytics 4 |
| **Fase 2 — Conversione** | 3-4 | Form check-up + GHL pipeline + n8n triage + email/SMS automatici, CallRail, Calendar booking |
| **Fase 3 — Acquisizione** | 5-6 | Google Ads search live, prima campagna LSA (se disponibile), 6 LP settoriali |
| **Fase 4 — Volano** | 7-12 | 1 video pre/post settimanale, programma recensioni automatico, sequenza nurture 90gg, dashboard KPI mensile |

---

## 6. Cosa Cambia per Ariapura (in numeri reali)

Stato attuale:
- Sito brochure 1 pagina · no LP · no automazioni · no Ads · GMB sotto-utilizzato · lead via telefono o email manuale
- Stima lead/mese: 8-15 (tutti telefono/passaparola/SEO debole)

Stato target a 90 giorni:
- LP settoriali · pipeline GHL · n8n triage · Ads attivi · GMB ranked · 30+ recensioni
- Stima lead/mese: 35-60 (3-5× attuale)
- Recurring revenue da contratti manutenzione: 25-40% fatturato

Stato target a 12 mesi:
- Lead/mese: 80-150 · 50%+ contratti ricorrenti · expansion in 2-3 città vicine (Modena/Ferrara/Imola via LP geo-localizzate)
- Reputation locale: top 3 GMB per "sanificazione aria Bologna" + provincia

---

## 7. Quick Wins (questa settimana, prima di tutto il resto)

1. **Fix permalink WordPress** (problema dichiarato) — Settings → Permalinks → "Post name" → Save (5 min)
2. **GMB:** aggiungi 5 foto recenti, 8 Q&A, 1 post offerta "check-up gratuito 48h"
3. **Schema markup** HVACBusiness + FAQ aggiunto al sito (già pronto in questo demo, copia-incolla)
4. **Google Search Console + Analytics 4** verificati e collegati
5. **2 articoli blog** sulle 2 keyword info più cercate ("ogni quanto sanificare condizionatore", "differenza pulizia e sanificazione")

Quick wins = 1 settimana di lavoro · costo zero · base per Ads + LP + automazioni successive.
