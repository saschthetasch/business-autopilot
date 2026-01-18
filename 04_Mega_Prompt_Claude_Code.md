# MEGA-PROMPT: Business Autopilot Landingpage für Claude Code

**Ziel:** Erstelle eine vollständige, responsive, hochkonvertierende Landingpage für den "Business Autopilot" Kurs. Das Design soll von DataFast inspiriert sein (minimalistisch, modern, dunkler Hintergrund), aber mit eigenem Branding und Copywriting.

---

## 1. TECHNISCHE SPEZIFIKATIONEN

**Format:** Einzelne HTML-Datei mit eingebettetem CSS (Tailwind CDN)
**Responsiveness:** Perfekt auf Desktop, Tablet, Mobile
**Interaktivität:** Email + Vorname Formular (keine Backend-Funktionalität nötig, action="#")
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

## 3. SEITENSTRUKTUR & INHALT

### SEKTION 1: HERO

**Layout:** Zentriert, großer Hero mit Formular

**Headline:** `From Founder to Autopilot Operator in 14 Days.`

**Sub-Headline:** `Learn the 3-pillar framework that turns your business into a self-running machine. No developers needed. No coding required. Just pure automation.`

**Formular:**
- Feld 1: Email (type="email", placeholder="your@email.com")
- Feld 2: First Name (type="text", placeholder="Your name")
- Button: "Become an Autopilot Operator" (Grün, mit Pfeil →)

**Unter dem Formular:**
- `Get exclusive early-bird access + 40% launch discount`
- `🚀 Join 200+ entrepreneurs building their autopilot business.`
- Avatar-Bilder (Platzhalter für echte Gründer)

**Styling:**
- Großer, kühner Text
- Viel Whitespace
- Formular-Felder: Dunkler Hintergrund, heller Text, subtile Border
- Button: Grün, Hover-Effekt (leicht heller)

---

### SEKTION 2: PROBLEM-KONTRAST

**Layout:** Zwei Boxen nebeneinander (Desktop), untereinander (Mobile)

**Headline:** `Are You Still Working IN Your Business?`

**Box 1: The Overwhelmed Founder**
- Border-Farbe: Rot `#EF4444`
- Icon oben rechts: Rotes ❌
- Hintergrund: Dunkelgrau mit rotem Tint
- Inhalt (als Liste mit Bullets):
  - Endless strategy docs that nobody reads.
  - Waiting weeks for a simple code change.
  - Juggling 10+ SaaS tools that don't talk to each other.
  - Your title is "Founder", but your job is "Professional Firefighter".
  - Stuck at your current revenue ceiling.

**Box 2: The Autopilot Operator**
- Border-Farbe: Grün `#10B981`
- Icon oben rechts: Grünes ✅
- Hintergrund: Dunkelgrau mit grünem Tint
- Inhalt (als Liste mit Bullets):
  - AI generates your complete business strategy in minutes.
  - Ship new features in a single afternoon with Claude Code.
  - One central system of autonomous agents. Everything connected.
  - Your only job: Making the big decisions.
  - Scaling is automatic. Your workload stays the same.

**Styling:**
- Boxen: Gleiche Höhe, symmetrisch
- Text: Weiß, 16px
- Bullets: Mit Icon-Präfix (✗ vs ✓)
- Hover-Effekt: Subtile Skalierung oder Glow

---

### SEKTION 3: DIE 3 VIBES – DAS FRAMEWORK

**Layout:** Drei Karten nebeneinander (Desktop), untereinander (Mobile)

**Headline:** `The 3-Vibe Framework: Your Path to Automation`

**Karte 1: Vibe Coding**
- Icon: Code-Icon (Farbe: Orange/Cyan)
- Headline: "Build Like a Founder, Not a Developer"
- Content:
  - You describe what you want. Claude Code builds it.
  - No syntax errors. No debugging hell. Just results.
  - Ship features in hours, not weeks.
  - Your AI developer works 24/7.

**Karte 2: Vibe Automation**
- Icon: Automation/Workflow-Icon (Farbe: Orange/Cyan)
- Headline: "Connect Everything. Automate Everything."
- Content:
  - N8N workflows that run themselves.
  - Lead qualification, customer onboarding, support – all automated.
  - Your business runs while you sleep.
  - No manual data entry. No repetitive tasks.

**Karte 3: Vibe Operation**
- Icon: Strategy/Brain-Icon (Farbe: Orange/Cyan)
- Headline: "Strategic Clarity. Flawless Execution."
- Content:
  - Manus AI handles your business planning and operations.
  - Market research, competitor analysis, marketing copy – all automated.
  - You get strategic insights without the busywork.
  - Focus on growth. Let AI handle the rest.

**Styling:**
- Karten: Gleiche Größe, mit subtler Border oder Shadow
- Icons: 64px, Farbe wechselt zwischen den Karten
- Hover-Effekt: Karte hebt sich leicht an (transform: translateY(-4px))

---

### SEKTION 4: TRANSFORMATION TIMELINE

**Layout:** Horizontale Timeline mit 4 Meilensteinen

**Headline:** `Your 4-Week Transformation`

**Meilenstein 1: Week 1 – The Blueprint**
- Icon: Blueprint-Icon
- Headline: "Master Your Business Strategy with Vibe Operation"
- Description: "Learn how to use Manus AI to create a complete business plan, market research, and operational strategy in minutes."

**Meilenstein 2: Week 2 – The Engine**
- Icon: Engine/Rocket-Icon
- Headline: "Build Your Core Product with Vibe Coding"
- Description: "Use Claude Code to ship your first feature. No coding background needed."

**Meilenstein 3: Week 3 – The Automation Layer**
- Icon: Workflow-Icon
- Headline: "Connect Everything with Vibe Automation"
- Description: "Build your first N8N workflow. Watch your business start to run itself."

**Meilenstein 4: Week 4 – Autopilot Operator**
- Icon: Star/Crown-Icon
- Headline: "You're an Autopilot Operator"
- Description: "Your business is now automated. Your workload is down 80%. Your revenue is up."

**Styling:**
- Horizontale Linie verbindet die Meilensteine
- Kreise an jedem Meilenstein mit Icon
- Auf Mobile: Vertikale Timeline statt horizontal
- Farben: Wechsel zwischen den Meilensteinen

---

### SEKTION 5: FOUNDER STORY

**Layout:** Bild links, Text rechts (Desktop); Bild oben, Text unten (Mobile)

**Headline:** `I Fired Myself From My Own Company.`

**Bild:** Platzhalter für professionelles Foto (z.B. 400x400px)

**Text:**
"Two years ago, I was drowning. My business had potential, but I was working 80-hour weeks on tasks that didn't matter. Strategy docs, code changes, customer onboarding – I was doing it all.

Then I realized something: I wasn't building a business. I was building a job for myself.

So I started experimenting with AI. Not just ChatGPT, but a real system. A framework. I used Manus AI for strategy, Claude Code for development, and N8N for automation.

Within weeks, my business transformed. I went from 80-hour weeks to 20-hour weeks. My revenue tripled. My stress disappeared.

That framework – the 3 Vibes – is what I'm sharing in Business Autopilot. It's the system I wish I had when I started.

This isn't a course about theory. It's a practical, step-by-step guide to building a business that doesn't need you to run it."

**Styling:**
- Bild: Rounded corners, subtler Shadow
- Text: Größere Schrift (18px), gutes Zeilenabstand (1.6)
- Absätze: Guter Abstand zwischen ihnen

---

### SEKTION 6: SOCIAL PROOF / TESTIMONIALS

**Layout:** 3 Testimonials nebeneinander (Desktop), untereinander (Mobile)

**Testimonial 1:**
- Quote: "My revenue tripled while my workload went down 80%."
- Name: Sarah
- Title: Digital Entrepreneur
- Full Quote: "I went from managing everything myself to having a fully automated business. Business Autopilot is the framework I needed."
- Avatar: Platzhalter

**Testimonial 2:**
- Quote: "I shipped my first feature in 2 hours. With Claude Code."
- Name: Marcus
- Title: Founder
- Full Quote: "No coding background. No developers. Just me and Claude. Business Autopilot made it possible."
- Avatar: Platzhalter

**Testimonial 3:**
- Quote: "Finally, a system that actually works."
- Name: Elena
- Title: Agency Owner
- Full Quote: "I've tried every automation tool out there. Business Autopilot is the only one that ties everything together."
- Avatar: Platzhalter

**Styling:**
- Boxen: Mit subtler Border oder Background-Farbe
- Quote: Größer, Bold, Farbe: Grün
- Name & Title: Grauer Text
- Avatar: Kreisförmig, 48px

---

### SEKTION 7: FAQ

**Layout:** Accordion-Style (klickbar, expandiert/kollabiert)

**Q1: Do I need coding experience?**
A: No. The entire framework is designed for non-technical founders. You'll learn how to communicate with AI, not how to code.

**Q2: What if I already use some of these tools?**
A: Perfect. Business Autopilot teaches you how to connect them into one cohesive system. Most people use these tools in isolation. We show you how to make them work together.

**Q3: How long does it take to see results?**
A: You'll see results in the first week. By week 4, your business should be significantly more automated.

**Q4: Is this just another "AI hype" course?**
A: No. This is a practical, step-by-step framework based on real experience. We focus on implementation, not theory.

**Q5: What if I get stuck?**
A: You'll have access to our community and support. Plus, we teach you how to use AI to debug and solve problems yourself.

**Styling:**
- Fragen: Bold, 18px
- Antworten: Regular, 16px, versteckt bis expandiert
- Chevron-Icon: Rotiert bei Expansion
- Hover: Subtile Hintergrund-Änderung

---

### SEKTION 8: FINAL CTA

**Layout:** Zentriert, großer Call-to-Action

**Headline:** `The Future of Entrepreneurship is Here. Are You In?`

**Sub-Headline:** `Business Autopilot launches in [X weeks]. Join the waitlist today to lock in your exclusive 40% launch discount and get a free ticket to the live 'Build Your First Automation' workshop. Spots are limited.`

**Formular (identisch zu Hero):**
- Email-Feld
- First Name-Feld
- Button: "Become an Autopilot Operator"

**Unter dem Button:**
- `No credit card required. Exclusive early-bird access for waitlist members.`

**Styling:**
- Ähnlich wie Hero-Sektion, aber mit etwas anderen Farben/Akzenten
- Dringlichkeit durch Messaging

---

### SEKTION 9: FOOTER

**Content:**
- Logo/Branding
- Links: Pricing, FAQ, Reviews, Contact
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
- **Meta Tags:** Title, Description, OG-Tags
- **Heading Hierarchy:** H1, H2, H3 korrekt verwendet
- **Alt Text:** Für alle Bilder

---

## 7. COPYWRITING-RICHTLINIEN

Alle Texte sind bereits oben angegeben. Bitte verwende sie genau wie vorgegeben. Die Tonalität sollte sein:
- Direkt & ehrlich
- Transformation-fokussiert
- Actionable
- Authentisch
- Motivierend (aber realistisch)

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
- **Impressum:** Link im Footer (falls erforderlich)
- **Newsletter-Opt-in:** "Ich akzeptiere, dass ich E-Mails erhalten werde"

---

## 10. ABSCHLIESSENDE ANMERKUNGEN

Diese Landingpage sollte:
1. **Hochkonvertierend sein:** Fokus auf Lead-Capture
2. **Transformation verkaufen:** Nicht das Produkt, sondern das Ergebnis
3. **Vertrauen aufbauen:** Durch Social Proof, Testimonials, Klarheit
4. **Dringlichkeit schaffen:** Durch Messaging und Design
5. **Einfach zu navigieren sein:** Klare Struktur, keine Ablenkung

Das Design sollte von DataFast inspiriert sein (minimalistisch, modern, dunkler Hintergrund), aber mit eigenem Branding und Copywriting für Business Autopilot.

**Viel Erfolg bei der Umsetzung!**
