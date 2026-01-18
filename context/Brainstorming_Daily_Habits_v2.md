# Business Autopilot: Tägliche Habits (Version 2.0)

**Datum:** 15. Januar 2026  
**Status:** Überarbeitet basierend auf Praxis-Feedback  
**Prinzip:** Habits > Goals. Systems > Intensity.

---

## Das Problem mit Zielen

**Limitierend:** "Ich will 20k verdienen" → Was passiert nach 20k? Du hörst auf.  
**Besser:** "Ich will jeden Tag X machen, um meinen Umsatz zu steigen" → Kein Limit, nachhaltiges Wachstum.

**Prinzip:** Habits schaffen Systems. Systems schlagen Goals.

---

## VIBE OPERATION HABITS (Manus AI)

### Habit 1: KPI-Tracking & Morning Strategy Check

#### PREPARATION (Einmalig)

**Schritt 1: KPI-Definition-File erstellen**

Erstelle eine Datei `kpi_definitions.csv` oder eine Notion/Airtable-Tabelle mit folgenden Spalten:

| KPI | Ziel | Timerange | Last Check | Status |
|-----|------|-----------|------------|--------|
| Form Submits Landingpage | 100 | weekly | 2026-01-15 | 45/100 |
| Newsletter-Anmeldungen | 50 | weekly | 2026-01-15 | 23/50 |
| Website-Besucher | 1000 | weekly | 2026-01-15 | 567/1000 |
| Revenue | 5000€ | monthly | 2026-01-15 | 2300€/5000€ |
| Blog-Artikel publiziert | 4 | monthly | 2026-01-15 | 2/4 |
| Customer Support Tickets gelöst | 20 | weekly | 2026-01-15 | 15/20 |

**Schritt 2: Manus AI Scheduled Task einrichten**

```
Zeitpunkt: Jeden Morgen um 7:00 Uhr

Prompt:
"Analysiere meine KPIs aus der beigefügten Datei 'kpi_definitions.csv'.

Für heute relevante KPIs (basierend auf Timerange):
- Checke den aktuellen Status aus DataFast/Stripe/GitHub/etc.
- Vergleiche mit dem Ziel
- Berechne: Sind wir on track?
- Gib mir 3 konkrete Aktionen für heute, um die KPIs zu erreichen

Aktualisiere die 'Last Check' Spalte mit dem heutigen Datum.

Format:
📊 KPI-Status für [Datum]

🎯 Weekly KPIs:
- [KPI]: [Status] ([X%] erreicht) → [On Track / Behind / Ahead]

🎯 Monthly KPIs:
- [KPI]: [Status] ([X%] erreicht) → [On Track / Behind / Ahead]

💡 Top 3 Aktionen für heute:
1. [Aktion]
2. [Aktion]
3. [Aktion]
"

Lieferung: Per E-Mail als "Morning KPI Report"
```

#### HABIT (Täglich, 10 Min)

1. **Morgens:** KPI-Report kommt automatisch per E-Mail
2. **Review:** Lese den Report (5 Min)
3. **Action:** Wähle 1 Aktion aus und setze sie um (5 Min Planung)

**Warum es funktioniert:**
- Du trackst nur die KPIs, die wirklich wichtig sind
- Du siehst sofort, ob du on track bist
- Du bekommst konkrete Aktionen, keine vagen Insights
- State wird gehalten (Last Check verhindert Doppel-Checks)

---

### Habit 2: Content-Pipeline (Ideen → Konzepte → Posts)

#### PREPARATION (Einmalig)

**Schritt 1: Content-Ideen-Datenbank erstellen**

Erstelle eine Notion/Airtable-Datenbank mit folgenden Spalten:

| Idee | Quelle | Datum | Status | Konzept-Link | Post-Link |
|------|--------|-------|--------|--------------|-----------|
| Feature X gelauncht | GitHub Commit | 2026-01-15 | Idee | - | - |
| Kunde fragte nach Y | Support Ticket | 2026-01-14 | Idee | - | - |
| Konkurrent launched Z | Competitor Tracking | 2026-01-13 | Konzept | [Link] | - |

**Schritt 2: Event-Tracking mit N8N einrichten**

Erstelle N8N-Workflows, die automatisch Ideen sammeln:

**Workflow 1: GitHub Commits → Content-Ideen**
- Trigger: Neuer GitHub Commit mit Label "feature"
- Action: Füge Idee zur Datenbank hinzu mit Quelle "GitHub Commit"

**Workflow 2: Support Tickets → Content-Ideen**
- Trigger: Support Ticket geschlossen
- Action: Analysiere Ticket mit Manus AI: "Ist das eine gute Content-Idee?"
- If yes: Füge zur Datenbank hinzu

**Workflow 3: Käufe → Content-Ideen**
- Trigger: Neuer Kauf in Stripe
- Action: Füge Idee hinzu: "Kunde kaufte [Produkt] - Was war der Grund?"

**Workflow 4: CMS Updates → Content-Ideen**
- Trigger: Neuer Blog-Artikel publiziert
- Action: Füge Idee hinzu: "Follow-up zu [Artikel-Thema]"

**Schritt 3: Manus AI Scheduled Tasks einrichten**

**Task 1: Ideen → Konzepte (Montag 9:00)**
```
Prompt:
"Analysiere alle 'Idee'-Status-Einträge in meiner Content-Datenbank.

Wähle die 3 besten Ideen aus (basierend auf Relevanz, Aktualität, Impact).

Erstelle für jede Idee ein Content-Konzept:
- Hook (erster Satz)
- Hauptpunkte (3-5 Bullet Points)
- Call-to-Action
- Passende Plattform (LinkedIn, Twitter, Newsletter, Blog)

Aktualisiere den Status auf 'Konzept' und verlinke das Konzept."

Lieferung: Per E-Mail als "Weekly Content Concepts"
```

**Task 2: Konzepte → Posts (Dienstag-Freitag 9:00)**
```
Prompt:
"Nimm das nächste 'Konzept'-Status-Eintrag aus meiner Content-Datenbank.

Schreibe einen vollständigen Post basierend auf dem Konzept:
- [Plattform]: LinkedIn/Twitter/Newsletter/Blog
- Länge: [Passend zur Plattform]
- Ton: [Dein Brand Voice]

Aktualisiere den Status auf 'Post' und verlinke den Post."

Lieferung: Per E-Mail als "Daily Content Post"
```

#### HABIT (Täglich, 10 Min)

**Montag:**
1. Content Concepts kommen automatisch
2. Review: Sind die 3 Konzepte gut? (5 Min)
3. Feedback geben oder freigeben

**Dienstag-Freitag:**
1. Daily Content Post kommt automatisch
2. Review: Ist der Post gut? (5 Min)
3. Posten oder anpassen

**Warum es funktioniert:**
- **Ideen sammeln ist automatisiert** (aus deinem Business-Alltag)
- **Konzepte werden aus echten Events erstellt** (nicht aus der Luft gegriffen)
- **Posts sind vorgeschrieben** (du musst nur reviewen)
- **Pipeline ist klar:** Ideen → Konzepte → Posts

---

### Habit 3: Competitor Intelligence & Content-Angle-Mapping

#### PREPARATION (Einmalig)

**Schritt 1: Competitor-Liste erstellen**

Erstelle eine Datei `competitors.csv` mit:

| Competitor | Website | Twitter | LinkedIn | Newsletter | Content-Angle |
|------------|---------|---------|----------|------------|---------------|
| Competitor A | [URL] | [URL] | [URL] | [URL] | "Technical Deep-Dives" |
| Competitor B | [URL] | [URL] | [URL] | [URL] | "Beginner-Friendly Tutorials" |
| Competitor C | [URL] | [URL] | [URL] | [URL] | "Case Studies & Results" |

**Schritt 2: Manus AI Scheduled Task einrichten**

```
Zeitpunkt: Jeden Montag um 8:00 Uhr

Prompt:
"Analysiere die Content-Aktivitäten meiner Konkurrenten aus der beigefügten 'competitors.csv'.

Für jeden Konkurrenten:
1. Checke die letzten 5 Posts/Artikel (Website, Twitter, LinkedIn)
2. Identifiziere die Themen
3. Analysiere den Content-Angle
4. Überlege: Wie kann ich das Thema aus MEINEM Angle abdecken?

Erstelle eine Liste von Content-Ideen basierend auf Konkurrenz-Content:
- Thema: [Was der Konkurrent gemacht hat]
- Mein Angle: [Wie ich es anders/besser machen kann]
- Plattform: [Wo ich es posten sollte]

Füge diese Ideen automatisch zu meiner Content-Ideen-Datenbank hinzu mit Quelle 'Competitor Tracking'."

Lieferung: Per E-Mail als "Weekly Competitor Intelligence Report"
```

#### HABIT (Wöchentlich, 15 Min)

**Montag:**
1. Competitor Intelligence Report kommt automatisch
2. Review: Welche Ideen sind gut? (10 Min)
3. Markiere 2-3 Ideen als "Priority" in der Content-Datenbank (5 Min)

**Warum es funktioniert:**
- **Automatisches Tracking** der Konkurrenz
- **Content-Angle-Mapping** zeigt dir, wie du dich differenzierst
- **Ideen werden direkt in deine Pipeline eingefügt**
- Du bleibst immer up-to-date ohne manuelles Recherchieren

---

## VIBE CODING HABITS (Claude Code)

### Habit 4: Deep Work Coding Sessions

#### PREPARATION (Einmalig)

**Schritt 1: Kalender-Blocking**

Blocke in deinem Kalender:
- **Montag 14:00-16:00:** Deep Work Coding Session
- **Donnerstag 14:00-16:00:** Deep Work Coding Session

**Schritt 2: Feature-Backlog erstellen**

Erstelle eine Notion/Linear/GitHub Projects-Tabelle:

| Feature | Priority | Estimated Time | Status | Claude Prompt |
|---------|----------|----------------|--------|---------------|
| Dark Mode | High | 1-2h | Backlog | [Link] |
| FAQ Section | Medium | 1h | Backlog | [Link] |
| Testimonials Slider | High | 1-2h | Backlog | [Link] |

#### HABIT (2x pro Woche, 1-2h)

**Montag & Donnerstag:**
1. **Vorbereitung (5 Min):** Wähle 1-2 Features aus dem Backlog
2. **Deep Work (90 Min):** Baue die Features mit Claude Code
   - Keine Ablenkungen
   - Keine E-Mails
   - Nur Fokus auf Code
3. **Review (15 Min):** Teste die Features, deploye sie
4. **Update Backlog (10 Min):** Markiere als "Done", wähle nächste Features

**Warum es funktioniert:**
- **Deep Work statt Multitasking** (1-2h sind optimal für Flow)
- **Konsistenz:** 2x pro Woche = 8x pro Monat = 96 Sessions pro Jahr
- **Kein Context-Switching:** Du baust nur, wenn du im Flow bist
- Nach 1 Jahr: 96 Features gebaut

---

### Habit 5: Bug-Triage & Fix-Preparation

#### PREPARATION (Einmalig)

**Schritt 1: Ticket-System einrichten**

Nutze Linear/GitHub Issues/Notion mit folgenden Spalten:

| Bug | Severity | Reported | Status | Claude Prompt | Fix Session |
|-----|----------|----------|--------|---------------|-------------|
| Button nicht klickbar | High | 2026-01-15 | Triaged | [Prompt] | 2026-01-16 14:00 |
| Mobile Layout broken | Medium | 2026-01-14 | Triaged | [Prompt] | 2026-01-16 14:00 |

**Schritt 2: Bug-Reporting-Workflow einrichten**

Erstelle einen N8N-Workflow:
- Trigger: Neuer Bug-Report (E-Mail, Formular, Support-Ticket)
- Action 1: Füge Bug zum Ticket-System hinzu
- Action 2: Sende Benachrichtigung an dich

#### HABIT (Täglich, 15 Min)

**Jeden Morgen (nach KPI-Check):**
1. **Screen alle neuen Bugs** im Ticket-System (5 Min)
2. **Bewerte Severity:** High/Medium/Low (3 Min)
3. **Schreibe Claude Code Prompt** für jeden High/Medium Bug (5 Min)
   - Beispiel: "Fix: Button auf /pricing-Seite ist nicht klickbar. Checke onClick-Handler und CSS z-index."
4. **Füge Prompt als Kommentar** zum Ticket hinzu
5. **Plane Bug-Fixes** in den nächsten Deep Work Block ein (2 Min)

**Warum es funktioniert:**
- **Triage verhindert Bug-Chaos**
- **Prompts sind vorbereitet** → Deep Work Session ist effizienter
- **Bugs werden nicht vergessen** (im Ticket-System)
- **Planung im Kalender** → Bugs werden wirklich gefixt

---

## VIBE AUTOMATION HABITS (N8N)

### Habit 6: Workflow-Triage & Fix-Preparation

#### PREPARATION (Einmalig)

**Schritt 1: Workflow-Ticket-System einrichten**

Nutze das gleiche Ticket-System wie für Bugs:

| Workflow | Issue | Severity | Status | Fix Prompt | Fix Session |
|----------|-------|----------|--------|------------|-------------|
| Lead-Qualifizierung | Webhook failed | High | Triaged | [Prompt] | 2026-01-16 14:00 |
| Newsletter-Automation | Rate limit hit | Medium | Triaged | [Prompt] | 2026-01-18 14:00 |

#### HABIT (Täglich, 15 Min)

**Jeden Morgen (nach Bug-Triage):**
1. **Gehe in N8N rein** (2 Min)
2. **Prüfe alle Workflows:** Welche haben Fehler? (5 Min)
3. **Erstelle Tickets** für alle fehlgeschlagenen Workflows (5 Min)
4. **Schreibe Fix-Prompts** (für Claude Code oder manuelle Fixes) (3 Min)

**Warum es funktioniert:**
- **Tägliche Checks** verhindern, dass Workflows unbemerkt kaputt gehen
- **Tickets dokumentieren** alle Issues
- **Fix-Prompts** machen die Lösung einfacher

---

### Habit 7: Automation Audit & Optimization

#### PREPARATION (Einmalig)

**Schritt 1: Workflow-Dokumentation erstellen**

Erstelle eine Notion-Seite mit allen N8N-Workflows:

| Workflow | Zweck | Trigger | Actions | Last Check | Status |
|----------|-------|---------|---------|------------|--------|
| Lead-Qualifizierung | Neue Leads bewerten | Webhook | 5 Actions | 2026-01-15 | ✅ |
| Newsletter-Automation | Willkommens-E-Mail | Airtable | 3 Actions | 2026-01-14 | ✅ |

#### HABIT (Wöchentlich, 30 Min)

**Jeden Donnerstag Nachmittag:**
1. **Review alle Workflows** in N8N (10 Min)
2. **Checke Performance:** Welche Workflows sind langsam? (5 Min)
3. **Optimiere 1 Workflow:** Kann ich Steps reduzieren? Caching hinzufügen? (15 Min)
4. **Update Dokumentation** (5 Min)

**Warum es funktioniert:**
- **Wöchentliche Reviews** halten deine Automation gesund
- **Kontinuierliche Optimierung** macht Workflows schneller und zuverlässiger
- **Dokumentation** hilft dir, den Überblick zu behalten

---

## ÜBERGREIFENDE HABITS

### Habit 8: Dashboard Check (Nice-to-Have)

#### PREPARATION (Optional)

Richte einen N8N-Workflow ein (wie in v1 beschrieben), aber:

**Wichtig:** Der Owner sollte regelmäßig selbst ins Dashboard gehen, nicht nur Reports lesen.

#### HABIT (Täglich, 5 Min - Optional)

1. **Öffne DataFast** direkt (oder checke den automatischen Report)
2. **Schaue dir die Zahlen an:** Besucher, Conversions, Revenue
3. **Notiere 1 Insight**

**Warum es Nice-to-Have ist:**
- **Automatische Reports sind gut**, aber direkter Blick ins Dashboard gibt dir mehr Gefühl für die Daten
- **Du erkennst Muster**, die in Reports nicht sichtbar sind
- **Du bleibst connected** mit deinem Business

---

### Habit 9: Weekly Reflection Sunday

#### PREPARATION (Einmalig)

Erstelle ein Notion-Template für deine wöchentliche Reflexion:

```markdown
# Weekly Reflection - Woche [X]

## KPIs
- [KPI 1]: [Status] (Ziel: [X], Erreicht: [Y])
- [KPI 2]: [Status] (Ziel: [X], Erreicht: [Y])

## Was hat diese Woche gut funktioniert?
- [Punkt 1]
- [Punkt 2]

## Was hat nicht funktioniert?
- [Punkt 1]
- [Punkt 2]

## Was will ich nächste Woche anders machen?
- [Punkt 1]
- [Punkt 2]

## Habits-Check
- [ ] Habit 1: KPI-Tracking (7/7 Tage)
- [ ] Habit 2: Content-Pipeline (5/5 Tage)
- [ ] Habit 3: Competitor Intelligence (1/1 Woche)
- [ ] Habit 4: Deep Work Coding (2/2 Sessions)
- [ ] Habit 5: Bug-Triage (7/7 Tage)
- [ ] Habit 6: Workflow-Triage (7/7 Tage)
- [ ] Habit 7: Automation Audit (1/1 Woche)

## Learnings
- [Was habe ich diese Woche gelernt?]

## Next Week Focus
- [Top 3 Prioritäten für nächste Woche]
```

#### HABIT (Wöchentlich, 30 Min)

**Jeden Sonntag Abend:**
1. **Fülle das Reflexions-Template aus** (20 Min)
2. **Review alle Quellen:**
   - KPI-Reports der letzten Woche
   - Content-Pipeline-Status
   - Ticket-System (Bugs & Workflows)
   - GitHub Commits
   - DataFast-Dashboard
3. **Plane die nächste Woche** (10 Min)

**Warum es funktioniert:**
- **Wöchentliche Reflexion** hilft dir, aus Erfahrungen zu lernen
- **Habits-Check** zeigt dir, wo du konsequent warst
- **Learnings dokumentieren** macht dich langfristig besser
- **Next Week Focus** gibt dir Klarheit für die kommende Woche

---

## DAS AUTOPILOT-OPERATOR-RITUAL: WOCHENPLAN

### Montag

**Morgen (10 Min)**
- ✅ Habit 1: KPI-Report lesen + 1 Aktion wählen
- ✅ Habit 5: Bug-Triage + Prompts schreiben
- ✅ Habit 6: Workflow-Triage + Tickets erstellen

**Mittag (10 Min)**
- ✅ Habit 2: Content-Konzepte reviewen (kommen automatisch)
- ✅ Habit 3: Competitor Intelligence Report lesen

**Nachmittag (2h)**
- ✅ Habit 4: Deep Work Coding Session

---

### Dienstag

**Morgen (10 Min)**
- ✅ Habit 1: KPI-Report lesen + 1 Aktion wählen
- ✅ Habit 5: Bug-Triage + Prompts schreiben
- ✅ Habit 6: Workflow-Triage + Tickets erstellen

**Mittag (10 Min)**
- ✅ Habit 2: Daily Content Post reviewen + posten

---

### Mittwoch

**Morgen (10 Min)**
- ✅ Habit 1: KPI-Report lesen + 1 Aktion wählen
- ✅ Habit 5: Bug-Triage + Prompts schreiben
- ✅ Habit 6: Workflow-Triage + Tickets erstellen

**Mittag (10 Min)**
- ✅ Habit 2: Daily Content Post reviewen + posten

---

### Donnerstag

**Morgen (10 Min)**
- ✅ Habit 1: KPI-Report lesen + 1 Aktion wählen
- ✅ Habit 5: Bug-Triage + Prompts schreiben
- ✅ Habit 6: Workflow-Triage + Tickets erstellen

**Mittag (10 Min)**
- ✅ Habit 2: Daily Content Post reviewen + posten

**Nachmittag (2h)**
- ✅ Habit 4: Deep Work Coding Session
- ✅ Habit 7: Automation Audit (30 Min nach Coding)

---

### Freitag

**Morgen (10 Min)**
- ✅ Habit 1: KPI-Report lesen + 1 Aktion wählen
- ✅ Habit 5: Bug-Triage + Prompts schreiben
- ✅ Habit 6: Workflow-Triage + Tickets erstellen

**Mittag (10 Min)**
- ✅ Habit 2: Daily Content Post reviewen + posten

---

### Samstag & Sonntag

**Samstag:** Frei (kein Business)

**Sonntag Abend (30 Min):**
- ✅ Habit 9: Weekly Reflection

---

## ZEITAUFWAND PRO WOCHE

| Habit | Frequenz | Zeit/Session | Zeit/Woche |
|-------|----------|--------------|------------|
| Habit 1: KPI-Tracking | 5x/Woche | 10 Min | 50 Min |
| Habit 2: Content-Pipeline | 5x/Woche | 10 Min | 50 Min |
| Habit 3: Competitor Intelligence | 1x/Woche | 15 Min | 15 Min |
| Habit 4: Deep Work Coding | 2x/Woche | 2h | 4h |
| Habit 5: Bug-Triage | 5x/Woche | 15 Min | 75 Min |
| Habit 6: Workflow-Triage | 5x/Woche | 15 Min | 75 Min |
| Habit 7: Automation Audit | 1x/Woche | 30 Min | 30 Min |
| Habit 8: Dashboard Check | Optional | 5 Min | 25 Min |
| Habit 9: Weekly Reflection | 1x/Woche | 30 Min | 30 Min |
| **GESAMT** | | | **6h 50 Min** |

**Mit Dashboard Check:** 7h 15 Min/Woche  
**Ohne Dashboard Check:** 6h 50 Min/Woche

**Das sind weniger als 1,5 Stunden pro Tag** für ein vollständig automatisiertes Business!

---

## WARUM DIESE HABITS FUNKTIONIEREN

### 1. Klare Trennung: Preparation vs. Habit
- **Preparation** ist einmalig (Setup-Aufwand)
- **Habit** ist täglich/wöchentlich (minimaler Aufwand)

### 2. Automatisierung wo möglich
- KPI-Reports kommen automatisch
- Content-Ideen werden automatisch gesammelt
- Competitor-Tracking läuft automatisch

### 3. Deep Work statt Multitasking
- 2x 2h Coding-Sessions pro Woche sind besser als 10x 30 Min
- Fokus auf Flow, nicht auf Fragmentierung

### 4. Ticket-System für alles
- Bugs werden nicht vergessen
- Workflows werden dokumentiert
- Prompts sind vorbereitet

### 5. Reflexion als Meta-Habit
- Wöchentliche Reflexion optimiert alle anderen Habits
- Du lernst aus Erfahrungen
- Du bleibst auf Kurs

---

## NÄCHSTE SCHRITTE

1. **Woche 1:** Richte Preparation für Habit 1-3 ein (KPI-Tracking, Content-Pipeline, Competitor Intelligence)
2. **Woche 2:** Starte mit Habit 1-3 täglich/wöchentlich
3. **Woche 3:** Richte Preparation für Habit 4-7 ein (Coding, Bug-Triage, Workflow-Triage, Automation Audit)
4. **Woche 4:** Starte mit allen Habits
5. **Woche 5:** Erste Weekly Reflection → Optimiere Habits basierend auf Learnings

Nach 4 Wochen: **Du bist ein Autopilot Operator.**

---

**Hinweis:** Dieses Dokument wird später in ein Kursmodul umgewandelt.
