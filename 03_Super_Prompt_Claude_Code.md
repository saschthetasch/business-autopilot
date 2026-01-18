# Super-Prompt für Claude Code: Erstellung der "Agent Founder" Landingpage

**An:** Claude Code
**Von:** Manus AI
**Projekt:** Erstellung einer Landingpage für den "Agent Founder" Kurs

---

## 1. Projektziel

Deine Aufgabe ist es, eine vollständige, responsive Landingpage als einzelne HTML-Datei zu erstellen. Die Seite dient dazu, eine Warteliste für einen neuen Online-Kurs namens "Agent Founder" aufzubauen. Das Design und die Struktur sollen stark von der Website `codefa.st` inspiriert sein, aber mit eigenem Inhalt und einer auf das Thema "AI Agents" zugeschnittenen visuellen Identität.

## 2. Technische Spezifikationen

*   **Framework:** Bitte verwende **Tailwind CSS** für das Styling. Du kannst das CDN-Skript direkt in den HTML-Header einbinden, um eine einzelne, portable HTML-Datei zu erhalten.
*   **Struktur:** Eine einzelne `index.html`-Datei.
*   **Responsiveness:** Die Seite muss auf Desktop-, Tablet- und Mobilgeräten einwandfrei aussehen und funktionieren.
*   **Interaktivität:** Das einzige interaktive Element ist ein E-Mail-Eingabeformular für die Warteliste. Das Formular sollte vorerst keine funktionale `action` haben (`action="#"`).

## 3. Design & Visuelle Identität

*   **Grundthema:** Modernes Dark-Mode-Design. Hintergrundfarbe sollte ein sehr dunkles Grau sein (z.B. `#111827` oder ähnlich).
*   **Typografie:**
    *   **Headlines:** Eine serifenlose, kräftige Schriftart wie "Inter" oder "Manrope". Groß und mit starkem Gewicht (z.B. `font-bold` oder `font-extrabold`).
    *   **Fließtext:** Eine gut lesbare, serifenlose Schriftart wie "Inter". Normale Schriftstärke.
*   **Farbpalette:**
    *   **Primär-Akzent (für CTAs & Highlights):** Ein leuchtendes Grün (z.B. `#10B981`).
    *   **Sekundär-Akzent (für negative Beispiele):** Ein warnendes Rot (z.B. `#EF4444`).
    *   **Textfarbe:** Weiß oder ein sehr helles Grau (z.B. `#F9FAFB`).
    *   **Dezenter Text:** Ein mittleres Grau (z.B. `#6B7280`).
*   **Layout:** Viel Weißraum (negative space) verwenden. Sektionen klar voneinander trennen. Zentrierter Content mit einer maximalen Breite (z.B. `max-w-4xl` oder `max-w-5xl` im `mx-auto` Container).
*   **Icons:** Bitte verwende einfache, outline-basierte SVG-Icons, wo es passend ist (z.B. für die 3 Säulen oder die FAQ-Sektion).

## 4. Seitenstruktur & Copywriting (Sektion für Sektion)

_Bitte setze die folgende Struktur und die exakten Texte um._

### **Sektion 1: Hero-Sektion**

*   **Layout:** Zentriert, große Headline, gefolgt von Sub-Headline und CTA-Button.
*   **Headline:** `Scale Your Business in Weeks, Not Years.`
*   **Sub-Headline:** `Learn the framework to automate your entire business with specialized AI agents. No coding or giant budget required.`
*   **CTA-Button:** `Become an Agent Founder` (Grüner Button)
*   **Unter dem CTA:** `🚀 Join 150+ entrepreneurs on the inside.` (Dezenter grauer Text)

### **Sektion 2: Problem-Kontrast-Sektion**

*   **Layout:** Eine zentrierte Headline, darunter zwei Boxen nebeneinander (auf Desktop) bzw. untereinander (auf Mobilgeräten).
*   **Headline:** `Are You a Founder or Just a Busy Employee in Your Own Company?`
*   **Box 1: The Overwhelmed Founder**
    *   **Styling:** Dunklerer Hintergrund, mit einem roten Rand oder einem roten ❌-Icon oben rechts.
    *   **Inhalt (als Liste):**
        *   `Endless strategy docs that nobody reads.`
        *   `Waiting weeks for a simple code change.`
        *   `Juggling 10+ SaaS tools that don’t talk to each other.`
        *   `Your title is "Founder", but your job is "Professional Firefighter".`
*   **Box 2: The Agent Founder**
    *   **Styling:** Dunklerer Hintergrund, mit einem grünen Rand oder einem grünen ✅-Icon oben rechts.
    *   **Inhalt (als Liste):**
        *   `Gets a complete business strategy from an AI in minutes.`
        *   `Builds and ships new features in a single afternoon.`
        *   `Uses one central system of autonomous agents.`
        *   `Your only job: Making the big decisions.`

### **Sektion 3: Vorstellung des 3-Säulen-Frameworks**

*   **Layout:** Zentrierte Headline, darunter drei Boxen/Karten nebeneinander (Desktop) oder untereinander (Mobil).
*   **Headline:** `Your New Executive Team Doesn't Sleep.`
*   **Säule 1: The Strategist (Manus AI)**
    *   **Icon:** Ein Gehirn- oder Strategie-Icon.
    *   **Text:** `Your AI Chief of Staff for market research, business planning, and operational management.`
*   **Säule 2: The Engineer (Claude Code)**
    *   **Icon:** Ein Code- oder Zahnrad-Icon.
    *   **Text:** `Your on-demand AI developer that builds, debugs, and ships code with natural language.`
*   **Säule 3: The Orchestrator (N8N)**
    *   **Icon:** Ein Verbindungs- oder Workflow-Icon.
    *   **Text:** `Your AI automation expert that connects all your tools and builds workflows that run themselves.`

### **Sektion 4: Visuelle Timeline**

*   **Layout:** Eine horizontale Linie mit vier markierten Punkten (wie bei `codefa.st`).
*   **Headline:** `Your 4-Week Path from Overwhelmed to Automated.`
*   **Meilensteine:**
    *   **Week 1: The Blueprint** - `Master your business strategy with Manus AI.`
    *   **Week 2: The Engine** - `Build and launch your core product with Claude Code.`
    *   **Week 3: The Automation Layer** - `Connect everything with agentic N8N workflows.`
    *   **Week 4: You're an Agent Founder** - `Focus on scaling while your AI team runs the show.`

### **Sektion 5: Founder-Story**

*   **Layout:** Ein Bild des Gründers auf der einen Seite, Text auf der anderen.
*   **Headline:** `I Fired Myself From My Own Company.`
*   **Bild:** (Platzhalter für ein professionelles Foto)
*   **Text:** `(Hier die persönliche Geschichte einfügen, z.B.:) 
