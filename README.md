# FlexxLink B2B Integration – LinkedIn-Karussell-Serie

**20 Topics × 7 Sprachen × 4 Slides = 560 Slides (140 Karussells)**

Die Serie „B2B Integration – So geht's besser" positioniert FlexxLink als Integrationslösung für Microsoft Dynamics 365 – ohne externe Middleware-Abhängigkeit, zu 100% in Dynamics 365 eingebettet.

---

## Inhalt dieses Archivs

```
flexxlink-b2b-series.zip
├── topic-01-status/
│   ├── carousel/                    ← 7 PDFs (je 4 Slides, 1080×1350 px)
│   │   ├── flexxlink-topic1-status-de.pdf
│   │   ├── flexxlink-topic1-status-en.pdf
│   │   ├── flexxlink-topic1-status-it.pdf
│   │   ├── flexxlink-topic1-status-fr.pdf
│   │   ├── flexxlink-topic1-status-dk.pdf
│   │   ├── flexxlink-topic1-status-no.pdf
│   │   └── flexxlink-topic1-status-se.pdf
│   └── posts/                       ← 7 LinkedIn-Posts in Langfassung
│       ├── flexxlink-topic1-status-de.txt
│       └── … (weitere Sprachen)
├── topic-02-validierung/
├── topic-03-api/
├── … (insgesamt 20 Topics)
└── topic-20-zusammenfassung/
```

**Separat:** `flexxlink-b2b-media.zip` enthält dieselben PDFs + Thumbnails (PNG) in flacher `docs/topic-XX/` Struktur – vorbereitet für GitHub-Pages-Deployment.

---

## Themenüberblick

| Nr | Slug | Titel | Fokus |
|----|------|-------|-------|
| 01 | status | Wissen, wo die Nachricht steckt | Integration Status Log |
| 02 | validierung | Validieren vor dem Buchen | Validation Framework |
| 03 | api | Eine Schnittstelle für jede Middleware | REST API, XML/JSON |
| 04 | performance | Tausende Nachrichten, volle Performance | Multi-Threading, Batch |
| 05 | partner | Jeder Partner tickt anders | Integration Parties |
| 06 | fehler | Wenn etwas schiefgeht | Retry-Logik, Error Handling |
| 07 | push | Proaktiv informiert werden | Push-API, Query-API |
| 08 | posting | Immer die gleichen Parameter | Posting Profiles |
| 09 | workspace | Alles auf einen Blick | B2B Workspace |
| 10 | middleware | Heute diese Middleware, morgen eine andere | Middleware-Unabhängigkeit |
| 11 | stammdaten | Existiert der Artikel wirklich? | Stammdaten-Matching |
| 12 | modi | Sync, Async oder Batch? | Verarbeitungsmodi |
| 13 | einvoice | E-Invoices lesbar machen | XSLT für XML-Rechnungen |
| 14 | zeit | Von Minuten zu Sekunden | Automatisierte Pipeline |
| 15 | audit | Lückenlose Nachverfolgung | Audit Trail, Compliance |
| 16 | bulk | Viele Nachrichten, eine Aktion | Bulk Actions |
| 17 | retry | Fehler? Automatisch nochmal | Auto-Reprocessing |
| 18 | xslt | Formate anpassen | Outbound-XSLT |
| 19 | warehouse | Lagerintegration ohne Umwege | Warehouse-Dokumente, LP |
| 20 | zusammenfassung | Eine Lösung für alles | Zusammenfassung / CTA |

---

## Technische Spezifikation

### Karussell-PDFs
- **Format:** 518,4 × 648 pts @ 150 dpi = **1080 × 1350 px** (LinkedIn Portrait 4:5)
- **4 Slides pro Karussell:**
  - S1 Hook (Teal): Aufhänger-Frage + Titel
  - S2 Lösung (Navy): Features / Vorteile
  - S3 Praxis (Indigo): Dashboard / Beispiel
  - S4 CTA (Orange): Rückfrage + Autor-Block
- **Farben:** Teal `#0D9488` → Navy `#1E3A5F` → Indigo `#4F46E5` → Orange `#FA6E32`
- **Schriftgrößen:** Fließtext min. 25 px, bis 47 px

### LinkedIn-Posts (Langfassung, ~800–1000 Zeichen)
Jeder Post folgt dieser Struktur:
1. **Hook** – Einstiegsfrage oder prägnantes Statement
2. **Problem-Beschreibung** – Was ist heute der Schmerzpunkt?
3. **Lösung mit Konkretisierung** – Wie löst FlexxLink es technisch?
4. **FlexxLink-Positionierung** – 100% Dynamics-365-Einbettung
5. **Serien-Marker** – „Beitrag X von 20 aus unserer Serie …"
6. **CTA** – 30-Tage-Testversion + Follow-Aufruf
7. **Hashtags** – #Dynamics365 #EDI #B2B #FlexxLink …

---

## Sprachen

| Code | Sprache | CTA |
|------|---------|-----|
| `de` | Deutsch | 30 Tage kostenlos testen |
| `en` | English | 30 days free trial |
| `it` | Italiano | Prova gratuita 30 giorni |
| `fr` | Français | Essai gratuit 30 jours |
| `dk` | Dansk | 30 dages gratis prøveperiode |
| `no` | Norsk | 30 dagers gratis prøveperiode |
| `se` | Svenska | 30 dagars gratis provperiod |

---

## Publishing-Plan (Buffer)

**Schedule:** 3 Posts pro Tag, Europe/Zurich
- 07:00, 12:00, 17:00

**Sprachrotation:** DE → EN → IT → FR → DK → NO → SE → (nächstes Topic)

**Gesamtdauer:** 140 Posts ÷ 3 pro Tag ≈ **47 Tage / ~7 Wochen**

---

## Autor-Block (auf Slide 4)

**Horst Fischer** · MCP · 30 Jahre Dynamics-Erfahrung
FlexxLink für Dynamics 365 · [soluvine.com](https://soluvine.com)

---

## Änderungshistorie

- **v1.0** – Alle 140 Karussells + Langfassung-Posts in 7 Sprachen fertig
  - Fix: Sprachmischungen in Topics 9–20 (IT/FR/DK/NO/SE) behoben
  - Fix: Schriftgrößen erhöht (min. 25 px, bis 47 px)
  - Fix: PDF-Format auf Lasernet-Standard (518,4 × 648 pts @ 150 dpi)
  - Fix: Post-Texte in Langfassung (~800–1000 Zeichen) statt Platzhalter
