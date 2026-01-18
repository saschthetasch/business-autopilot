# MEGA-PROMPT (DEUTSCH): Business Autopilot Landingpage für Claude Code

**Ziel:** Erstelle eine vollständige, responsive, hochkonvertierende Landingpage für den "Business Autopilot" Kurs in deutscher Sprache. Das Design soll von DataFast inspiriert sein (minimalistisch, modern, dunkler Hintergrund), aber mit eigenem Branding und deutschem Copywriting.

---

## 1. TECHNISCHE SPEZIFIKATIONEN

**Format:** Einzelne HTML-Datei mit eingebettetem CSS (Tailwind CDN)
**Sprache:** Deutsch
**Responsiveness:** Perfekt auf Desktop, Tablet, Mobile
**Interaktivität:** E-Mail + Vorname Formular (keine Backend-Funktionalität nötig, action="#")
**Performance:** Optimiert für schnelles Laden
**Browser-Kompatibilität:** Alle modernen Browser

---

## 2. DESIGN & VISUELLE IDENTITÄT

### Farbpalette
- **Primär (CTA & Highlights):** Leuchtendes Grün `#10B981` oder `#06B6D4` (Cyan)
- **Sekundär (Akzente):** Orange `#F97316` oder Rot `#EF4444`
- **Hintergrund:** Sehr dunkles Grau `#111827` oder `#0F172A`
- **Text:** Weiß `#FFFFFF` oder sehr helles Grau `#F9FAFB`
- **Dezenter Text:** Mittleres Grau `#9CA3AF`
- **Boxen/Karten:** Etwas heller als Hintergrund `#1F2937`

### Typografie
- **Headlines:** "Inter" oder "Manrope" (serifenlos, bold/extrabold, 32-48px auf Desktop)
- **Sub-Headlines:** "Inter" (serifenlos, semibold, 18-24px)
- **Body Text:** "Inter" (serifenlos, regular, 16px)
- **Buttons:** "Inter" (serifenlos, semibold, 16px)

### Layout
- **Max-Width:** `max-w-5xl` (1280px)
- **Padding:** Großzügig (40-60px vertikal zwischen Sektionen)
- **Whitespace:** Viel Raum zwischen Elementen
- **Alignment:** Zentriert, mit klarer Hierarchie

### Icons
- Verwende einfache SVG-Icons (outline-style)
- Für die 3 Vibes: Code-Icon, Automation-Icon, Strategy-Icon
- Größe: 48-64px

---

## 3. SEITENSTRUKTUR & INHALT (DEUTSCH)

### SEKTION 1: HERO

**Layout:** Zentriert, großer Hero mit Formular

**Headline:** `Vom Gründer zum Autopilot Operator in 14 Tagen.`

**Sub-Headline:** `Lerne das 3-Säulen-Framework, das dein Business in eine selbstlaufende Maschine verwandelt. Keine Entwickler nötig. Keine Programmierung erforderlich. Nur reine Automatisierung.`

**Formular:**
- Feld 1: E-Mail (type="email", placeholder="deine@email.de")
- Feld 2: Vorname (type="text", placeholder="Dein Name")
- Button: "Werde ein Autopilot Operator" (Grün, mit Pfeil →)

**Unter dem Formular:**
- `Exklusiver Early-Bird-Zugang + 40% Rabatt beim Launch`
- `🚀 Schließe dich 200+ Unternehmern an, die ihr automatisiertes Business aufbauen.`
- Avatar-Bilder (Platzhalter für echte Gründer)

**Styling:**
- Großer, kühner Text
- Viel Whitespace
- Formular-Felder: Dunkler Hintergrund, heller Text, subtile Border
- Button: Grün, Hover-Effekt (leicht heller)

---

### SEKTION 2: PROBLEM-KONTRAST

**Layout:** Zwei Boxen nebeneinander (Desktop), untereinander (Mobile)

**Headline:** `Arbeitest du noch IM Geschäft statt AM Geschäft?`

**Box 1: Der überlastete Gründer**
- Border-Farbe: Rot `#EF4444`
- Icon oben rechts: Rotes ❌
- Hintergrund: Dunkelgrau mit rotem Tint
- Inhalt (als Liste mit Bullets):
  - Endlose Strategy-Dokumente, die niemand liest.
  - Wochen Wartezeit für eine einfache Code-Änderung.
  - Jonglierst mit 10+ SaaS-Tools, die nicht miteinander reden.
  - Dein Titel ist "Gründer", aber dein Job ist "Professioneller Feuerwehrmann".
  - Stecken bleiben bei deiner aktuellen Umsatzgrenze.

**Box 2: Der Autopilot Operator**
- Border-Farbe: Grün `#10B981`
- Icon oben rechts: Grünes ✅
- Hintergrund: Dunkelgrau mit grünem Tint
- Inhalt (als Liste mit Bullets):
  - KI generiert deine komplette Business-Strategie in Minuten.
  - Shippe neue Features an einem Nachmittag mit Claude Code.
  - Ein zentrales System von autonomen Agenten. Alles verbunden.
  - Dein einziger Job: Die großen Entscheidungen treffen.
  - Skalierung läuft automatisch. Deine Arbeitszeit bleibt gleich.

**Styling:**
- Boxen: Gleiche Höhe, symmetrisch
- Text: Weiß, 16px
- Bullets: Mit Icon-Präfix (✗ vs ✓)
- Hover-Effekt: Subtile Skalierung oder Glow

---

### SEKTION 3: DIE 3 VIBES – DAS FRAMEWORK

**Layout:** Drei Karten nebeneinander (Desktop), untereinander (Mobile)

**Headline:** `Das 3-Vibe-Framework: Dein Weg zur Automatisierung`

**Karte 1: Vibe Coding**
- Icon: Code-Icon (Farbe: Orange/Cyan)
- Headline: "Baue wie ein Gründer, nicht wie ein Entwickler"
- Content:
  - Du beschreibst, was du willst. Claude Code baut es.
  - Keine Syntax-Fehler. Keine Debugging-Hölle. Nur Ergebnisse.
  - Shippe Features in Stunden, nicht Wochen.
  - Dein KI-Entwickler arbeitet 24/7.

**Karte 2: Vibe Automation**
- Icon: Automation/Workflow-Icon (Farbe: Orange/Cyan)
- Headline: "Verbinde alles. Automatisiere alles."
- Content:
  - N8N-Workflows, die sich selbst ausführen.
  - Lead-Qualifizierung, Kundeneinführung, Support – alles automatisiert.
  - Dein Business läuft, während du schläfst.
  - Keine manuelle Dateneingabe. Keine repetitiven Aufgaben.

**Karte 3: Vibe Operation**
- Icon: Strategy/Brain-Icon (Farbe: Orange/Cyan)
- Headline: "Strategische Klarheit. Fehlerlose Ausführung."
- Content:
  - Manus AI kümmert sich um deine Business-Planung und Operationen.
  - Marktforschung, Konkurrenzanalyse, Marketing-Texte – alles automatisiert.
  - Du erhältst strategische Erkenntnisse ohne die Kleinteiligkeit.
  - Konzentriere dich auf Wachstum. Lass KI den Rest erledigen.

**Styling:**
- Karten: Gleiche Größe, mit subtler Border oder Shadow
- Icons: 64px, Farbe wechselt zwischen den Karten
- Hover-Effekt: Karte hebt sich leicht an (transform: translateY(-4px))

---

### SEKTION 4: TRANSFORMATIONS-TIMELINE

**Layout:** Horizontale Timeline mit 4 Meilensteinen

**Headline:** `Deine 4-Wochen-Transformation`

**Meilenstein 1: Woche 1 – Der Blueprint**
- Icon: Blueprint-Icon
- Headline: "Meistere deine Business-Strategie mit Vibe Operation"
- Description: "Lerne, wie du mit Manus AI in Minuten einen kompletten Business-Plan, Marktforschung und operative Strategie erstellst."

**Meilenstein 2: Woche 2 – Die Engine**
- Icon: Engine/Rocket-Icon
- Headline: "Baue dein Kernprodukt mit Vibe Coding"
- Description: "Nutze Claude Code, um dein erstes Feature zu shippen. Keine Programmierkenntnisse erforderlich."

**Meilenstein 3: Woche 3 – Die Automatisierungs-Schicht**
- Icon: Workflow-Icon
- Headline: "Verbinde alles mit Vibe Automation"
- Description: "Baue deinen ersten N8N-Workflow. Beobachte, wie dein Business anfängt, sich selbst zu betreiben."

**Meilenstein 4: Woche 4 – Autopilot Operator**
- Icon: Star/Crown-Icon
- Headline: "Du bist ein Autopilot Operator"
- Description: "Dein Business ist jetzt automatisiert. Deine Arbeitszeit ist um 80% gesunken. Dein Umsatz ist gestiegen."

**Styling:**
- Horizontale Linie verbindet die Meilensteine
- Kreise an jedem Meilenstein mit Icon
- Auf Mobile: Vertikale Timeline statt horizontal
- Farben: Wechsel zwischen den Meilensteinen

---

### SEKTION 5: GRÜNDER-STORY

**Layout:** Bild links, Text rechts (Desktop); Bild oben, Text unten (Mobile)

**Headline:** `Ich habe mich selbst aus meinem eigenen Unternehmen gefeuert.`

**Bild:** Platzhalter für professionelles Foto (z.B. 400x400px)

**Text:**
"Vor zwei Jahren ertrank ich. Mein Business hatte Potenzial, aber ich arbeitete 80 Stunden pro Woche an Aufgaben, die nicht wichtig waren. Strategy-Dokumente, Code-Änderungen, Kundeneinführung – ich machte alles selbst.

Dann realisierte ich etwas: Ich baute kein Business. Ich baute mir einen Job.

Also begann ich, mit KI zu experimentieren. Nicht nur ChatGPT, sondern ein echtes System. Ein Framework. Ich nutzte Manus AI für Strategie, Claude Code für Entwicklung und N8N für Automatisierung.

Innerhalb von Wochen transformierte sich mein Business. Ich ging von 80-Stunden-Wochen zu 20-Stunden-Wochen. Mein Umsatz verdreifachte sich. Mein Stress verschwand.

Dieses Framework – die 3 Vibes – teile ich jetzt in Business Autopilot. Es ist das System, das ich mir gewünscht hätte, als ich anfing.

Das ist kein Kurs über Theorie. Es ist ein praktischer, Schritt-für-Schritt-Leitfaden zum Aufbau eines Business, das dich nicht braucht, um zu laufen."

**Styling:**
- Bild: Rounded corners, subtler Shadow
- Text: Größere Schrift (18px), gutes Zeilenabstand (1.6)
- Absätze: Guter Abstand zwischen ihnen

---

### SEKTION 6: SOCIAL PROOF / TESTIMONIALS

**Layout:** 3 Testimonials nebeneinander (Desktop), untereinander (Mobile)

**Testimonial 1:**
- Quote: "Mein Umsatz verdreifachte sich, während meine Arbeitszeit um 80% sank."
- Name: Sarah
- Title: Digital Entrepreneur
- Full Quote: "Ich ging von der Verwaltung von allem selbst zu einem vollständig automatisierten Business. Business Autopilot ist das Framework, das ich brauchte."
- Avatar: Platzhalter

**Testimonial 2:**
- Quote: "Ich habe mein erstes Feature in 2 Stunden gebaut. Mit Claude Code."
- Name: Marcus
- Title: Gründer
- Full Quote: "Keine Programmierkenntnisse. Keine Entwickler. Nur ich und Claude. Business Autopilot machte es möglich."
- Avatar: Platzhalter

**Testimonial 3:**
- Quote: "Endlich ein System, das wirklich funktioniert."
- Name: Elena
- Title: Agentur-Inhaberin
- Full Quote: "Ich habe alle Automatisierungs-Tools ausprobiert. Business Autopilot ist das einzige, das alles zusammenbringt."
- Avatar: Platzhalter

**Styling:**
- Boxen: Mit subtler Border oder Background-Farbe
- Quote: Größer, Bold, Farbe: Grün
- Name & Title: Grauer Text
- Avatar: Kreisförmig, 48px

---

### SEKTION 7: FAQ

**Layout:** Accordion-Style (klickbar, expandiert/kollabiert)

**Q1: Brauche ich Programmierkenntnisse?**
A: Nein. Das gesamte Framework ist für nicht-technische Gründer konzipiert. Du lernst, wie du mit KI kommunizierst, nicht wie du programmierst.

**Q2: Was ist, wenn ich bereits einige dieser Tools nutze?**
A: Perfekt. Business Autopilot lehrt dich, wie du sie in ein kohärentes System verbindest. Die meisten Menschen nutzen diese Tools isoliert. Wir zeigen dir, wie du sie zusammen arbeiten lässt.

**Q3: Wie lange dauert es, bis ich Ergebnisse sehe?**
A: Du wirst in der ersten Woche Ergebnisse sehen. Nach 4 Wochen sollte dein Business deutlich mehr automatisiert sein.

**Q4: Ist das nur ein weiterer "KI-Hype"-Kurs?**
A: Nein. Das ist ein praktisches, Schritt-für-Schritt-Framework, das auf echter Erfahrung basiert. Wir konzentrieren uns auf Umsetzung, nicht auf Theorie.

**Q5: Was ist, wenn ich steckenbleibe?**
A: Du hast Zugang zu unserer Community und Support. Außerdem lehren wir dich, wie du KI nutzt, um Probleme selbst zu debuggen und zu lösen.

**Styling:**
- Fragen: Bold, 18px
- Antworten: Regular, 16px, versteckt bis expandiert
- Chevron-Icon: Rotiert bei Expansion
- Hover: Subtile Hintergrund-Änderung

---

### SEKTION 8: FINAL CTA

**Layout:** Zentriert, großer Call-to-Action

**Headline:** `Die Zukunft des Unternehmertums ist hier. Bist du dabei?`

**Sub-Headline:** `Business Autopilot startet in [X Wochen]. Trag dich heute auf die Warteliste ein, um deinen exklusiven 40%-Rabatt beim Launch zu sichern und ein kostenloses Ticket zum Live-Workshop 'Baue deine erste Automatisierung' zu erhalten. Die Plätze sind begrenzt.`

**Formular (identisch zu Hero):**
- E-Mail-Feld
- Vorname-Feld
- Button: "Werde ein Autopilot Operator"

**Unter dem Button:**
- `Keine Kreditkarte erforderlich. Exklusiver Early-Bird-Zugang für Wartelisten-Mitglieder.`

**Styling:**
- Ähnlich wie Hero-Sektion, aber mit etwas anderen Farben/Akzenten
- Dringlichkeit durch Messaging

---

### SEKTION 9: FOOTER

**Content:**
- Logo/Branding
- Links: Preise, FAQ, Reviews, Kontakt
- Social Media Links (Twitter, LinkedIn, etc.)
- Copyright & Legal

**Styling:**
- Dunkler Hintergrund
- Grauer Text
- Subtile Border oben

---

## 4. INTERAKTIVE ELEMENTE

### Buttons
- **Primär (CTA):** Grün `#10B981`, Hover: Heller grün, Transition: 200ms
- **Sekundär:** Transparent mit Border, Hover: Gefüllt
- **Text:** Weiß, Bold, mit Pfeil-Icon (→)

### Formular-Felder
- **Hintergrund:** Dunkelgrau `#1F2937`
- **Border:** Subtil, `#374151`
- **Focus:** Border-Farbe: Grün, Glow-Effekt
- **Placeholder:** Grau `#9CA3AF`
- **Text:** Weiß

### Hover-Effekte
- **Karten:** Subtile Skalierung (1.02x) oder Glow
- **Links:** Farbe ändert sich zu Grün
- **Buttons:** Heller, Shadow-Effekt

### Scroll-Animationen (Optional)
- Fade-in beim Scrollen
- Subtile Parallax-Effekte auf Hero

---

## 5. MOBILE OPTIMIERUNG

- **Responsive Breakpoints:** 640px (sm), 768px (md), 1024px (lg)
- **Hero:** Formular stapelt sich vertikal auf Mobile
- **Boxen:** Zwei Spalten auf Desktop, eine auf Mobile
- **Timeline:** Vertikal auf Mobile
- **Testimonials:** Eine Spalte auf Mobile
- **Text:** Skaliert sich angemessen für kleine Bildschirme

---

## 6. PERFORMANCE & SEO

- **Lazy Loading:** Für Bilder
- **Minified CSS:** Tailwind ist bereits optimiert
- **Meta Tags:** Title, Description, OG-Tags (auf Deutsch)
- **Heading Hierarchy:** H1, H2, H3 korrekt verwendet
- **Alt Text:** Für alle Bilder (auf Deutsch)
- **Sprache:** `<html lang="de">`

---

## 7. COPYWRITING-RICHTLINIEN

Alle Texte sind bereits oben angegeben. Bitte verwende sie genau wie vorgegeben. Die Tonalität sollte sein:
- Direkt & ehrlich
- Transformation-fokussiert
- Actionable
- Authentisch
- Motivierend (aber realistisch)
- Deutsch & natürlich

Die **3 Vibes** sollten konsistent erwähnt werden.

---

## 8. ASSETS / PLATZHALTER

- **Hero-Bild:** Platzhalter (z.B. Gradient oder abstraktes Bild)
- **Founder-Foto:** Platzhalter (z.B. Avatar oder Placeholder-Bild)
- **Testimonial-Avatare:** 3x Platzhalter
- **Icons:** Verwende einfache SVG-Icons (Code, Automation, Strategy, etc.)

---

## 9. DATENSCHUTZ & LEGAL

- **Datenschutzerklärung:** Link im Footer
- **Impressum:** Link im Footer (erforderlich für deutsche Websites)
- **Newsletter-Opt-in:** "Ich akzeptiere, dass ich E-Mails erhalten werde"

---

## 10. ABSCHLIESSENDE ANMERKUNGEN

Diese Landingpage sollte:
1. **Hochkonvertierend sein:** Fokus auf Lead-Capture
2. **Transformation verkaufen:** Nicht das Produkt, sondern das Ergebnis
3. **Vertrauen aufbauen:** Durch Social Proof, Testimonials, Klarheit
4. **Dringlichkeit schaffen:** Durch Messaging und Design
5. **Einfach zu navigieren sein:** Klare Struktur, keine Ablenkung

Das Design sollte von DataFast inspiriert sein (minimalistisch, modern, dunkler Hintergrund), aber mit eigenem Branding und deutschem Copywriting für Business Autopilot.

**Alle Texte sind auf Deutsch. Verwende keine englischen Begriffe, wo deutsche Alternativen existieren.**

**Viel Erfolg bei der Umsetzung!**
