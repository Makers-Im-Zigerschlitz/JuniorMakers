# JuniorMakers – Corporate Identity & Mastervorlage

Schluss mit dem Wilden Westen der Kursplanung! Dieses Dokument definiert den Standard, wie künftige und bestehende JuniorMakers-Kurse strukturiert, formatiert und abgelegt werden. Das Ziel: Jeder Betreuer oder Mentor muss innerhalb von 60 Sekunden erfassen können, worum es geht, was er braucht und wie der Ablauf aussieht.

---

## 1. Ordner- und Dateistruktur
Jeder Kurs erhält einen **eigenen Hauptordner** im Verzeichnis `JuniorMakers`. 

**Der STEAM-Tag im Ordnernamen:**
Damit wir sofort sehen, welche Disziplinen ein Kurs abdeckt, stellen wir dem Ordnernamen einen `[STEAM]`-Tag voran. Relevante Disziplinen werden **GROSS**, nicht relevante **klein** geschrieben.
*Beispiel: Ein Kurs über Robotik deckt Science, Technology und Engineering ab, aber nicht Arts oder Math.* -> `[STeam]_Robotik_Basics`
*Beispiel: Der Fibonacci-Kurs deckt Science und Math ab.* -> `[SteaM]_Fibonacci_und_die_Natur`

Die Struktur sieht zwingend so aus:

```text
📁 [[STeam]_Kursname]
 ├── 📄 Kursplan.md               <-- Das zentrale Dokument (die Mastervorlage)
 └── 📁 media                     <-- Alle Medien kommen hier rein, NIEMALS ins Root!
      ├── 📁 images               <-- Fotos, Diagramme (.png, .jpg)
      ├── 📁 videos               <-- Videoclips (.mp4)
      └── 📁 docs                 <-- PDFs, Arbeitsblätter (.pdf)
```

**Namenskonventionen:**
- Keine Leerzeichen in Dateinamen für Bilder/Medien verwenden (stattdessen Unterstriche `_` oder Bindestriche `-`).
- Verlinkungen im Markdown erfolgen relativ: `![Beschreibung](media/images/bild.png)`.

## 2. Richtlinien für Grafiken & Medien (Corporate Identity)
Damit die Unterrichtsmaterialien professionell und begeisternd wirken, gelten für neu generierte oder erstellte Grafiken folgende Stilvorgaben:
- **Stil:** Cyberpunk / Sci-Fi / Futurismus. Denke an leuchtende Schaltkreise, holografische Displays, coole Tech-Suits, leuchtende Werkzeuge (z.B. Neon-Schraubenschlüssel) und schwebende Blaupausen. Es soll episch, modern und nach "Zukunft" aussehen.
- **Farben:** Dunkle, atmosphärische Hintergründe (z.B. futuristische Werkstatt oder Cyberpunk-Stadt) mit knalligen Neon-Akzenten (Cyan, Magenta, leuchtendes Goldgelb). 
- **Format:** Bevorzugt 16:9 oder 21:9 (für Banner). PNG oder hochauflösende JPEGs.
- **Dateinamen:** Aussagekräftig formatieren, z.B. `YYYY-MM-DD-thema-detail.png`.

### KI-Bildgenerierung (Prompt-Vorlage)
Wir nutzen für unsere Grafiken **Gemini 3 Pro Image**. 
Damit alle Bilder über verschiedene Kurse hinweg denselben genialen Vibe haben, nutze bitte diesen Basis-Prompt und passe nur den in Klammern gesetzten Teil an dein Kursthema an:

> **Der JuniorMakers Basis-Prompt (Englisch funktioniert am besten):**
> "A cool cyberpunk sci-fi illustration for a STEM educational program called 'JuniorMakers'. [HIER DEIN MOTIV EINSETZEN, z.B. 'It shows futuristic maker kids holding a glowing neon DNA helix' oder 'a close-up of a glowing neon microchip being soldered by a robotic arm']. Features high-tech elements with glowing neon circuitry (cyan and magenta), floating holographic screens and blueprints. Dark futuristic background with neon lights. Very highly detailed, digital art, epic sci-fi style."

---

## 3. Richtlinien für Kurstitel & Metadaten

### Kurstitel (Der "Hook")
Der Titel ist das Erste, was die Kids (und Eltern) sehen. Er darf nicht wie ein langweiliges Schulfach klingen.
- ❌ **Falsch (Öde):** "Informatik", "Stromkreise", "Biologie"
- ✅ **Richtig (Spannend):** "Code-Knacker: Die Geheimsprache der Computer", "Strom aus dem Bleistift", "Fibonacci und der Code der Natur"
- **Formel:** [Cooler/Geheimnisvoller Begriff]: [Was wir tatsächlich machen]

### Versionierungsschema (vX.Y.Z)
Wir verwenden semantische Versionierung:
- **Major (X.0.0):** Komplett neues Kurskonzept, massiver Umbau des zeitlichen Ablaufs oder grundlegende Änderung der Zielgruppe.
- **Minor (1.Y.0):** Neue Experimente hinzugefügt, Zeiten deutlich angepasst, neue Medien (Bilder/Videos) hinterlegt oder Level-Aufgaben geändert.
- **Bugfix (1.0.Z):** Tippfehler korrigiert, tote Links aktualisiert, kleine Unklarheiten in der Anleitung behoben.

### Schwierigkeitsgrad
Hilft dem Mentor einzuschätzen, wie viel Hilfestellung die Kinder benötigen:
- **Leicht (1/3):** Kein Vorwissen nötig. Alle Experimente gelingen fast immer auf Anhieb. Motorische Anforderungen sind gering.
- **Mittel (2/3):** Etwas Konzentration und Feinmotorik gefragt. Erste Transferleistungen nötig (z.B. Formeln anwenden, kleine Fehler im Aufbau selbst finden).
- **Schwer (3/3):** Hoher Frustrationswiderstand nötig. Komplexe logische Abläufe (z.B. fortgeschrittenes Programmieren) oder anspruchsvolle handwerkliche Tätigkeiten. Vorwissen von Vorteil.

### Sicherheitsstufen
- 🟢 **Grün (Unbedenklich):** Keine Verletzungsgefahr. Normale Bastelmaterialien (Papier, stumpfe Scheren, Stifte, ungefährliche Flüssigkeiten wie Wasser).
- 🟡 **Gelb (Betreuung nötig):** Leichte Verletzungsgefahr oder Sachschaden möglich. Einsatz von spitzen/scharfen Gegenständen (Cutter, Nadeln), schwachem Strom (Batterien < 12V), oder leicht färbenden/ätzenden Stoffen (z.B. Zitronensäure). Der Mentor muss aktiv beaufsichtigen.
- 🔴 **Rot (Gefahrenstoffe/Werkzeuge):** Hohe Verletzungsgefahr. Einsatz von Heißklebepistolen, Lötkolben, 230V-Netzstrom, echten Chemikalien oder schweren Werkzeugen (Bohrmaschine). 1-zu-1 Betreuung oder strenge Sicherheitsausrüstung (Schutzbrille) zwingend erforderlich.

---

## 3. Die Mastervorlage (Zum Kopieren)
*Kopiere den Text ab hier für neue Kurse.*

```markdown
# [Titel des Kurses, z.B. Magische Magneten]

> **S T E A M - P R O F I L**
> [ ✅ ] 🧪 **S**cience (Wissenschaft)
> [ ❌ ] 💻 **T**echnology (Technologie)
> [ ✅ ] ⚙️ **E**ngineering (Ingenieurswesen)
> [ ❌ ] 🎨 **A**rts (Kunst)
> [ ❌ ] 📐 **M**ath (Mathematik)

**📋 Metadaten**
* **Autor:** NACHNAME Vorname (email@adresse.ch)
* **Version:** [vX.Y.Z - z.B. v1.0.0]
* **Erstellt am:** [JJJJ-MM-TT]
* **Letzte Änderung:** [JJJJ-MM-TT]
* **Zielgruppe:** [z.B. 9-12 Jahre]
* **Format:** [ 🖥️ 100% PC / 🛠️ 100% Offline / 🔄 Gemischt ]
* **Kursstatus:** [In Entwicklung / Durchgeführt / Mehrfach erprobt und bewährt]
* **Schwierigkeit:** [Leicht / Mittel / Schwer]
* **Sicherheitsstufe:** [Grün / Gelb / Rot - mit kurzer Begründung]

---

## 📖 Kurzbeschreibung
[2-3 Sätze: Was machen die Kids in diesem Kurs? Was ist der "Wow"-Faktor?]

## ❓ Leitfragen (Essential Questions)
* [Die große Einstiegsfrage: z.B. "Warum leitet Bleistift Strom, aber Papier nicht?"]
* [Eine Transfer-Frage: z.B. "Wo in unserem Alltag finden wir diese Technologie?"]

## 🎯 Lernziele (Was nehmen die Kids mit?)
* **Fachlich:** [z.B. Verstehen eines geschlossenen Stromkreises]
* **Methodisch:** [z.B. Hypothesenbildung, Messen mit dem Multimeter]
* **Sozial/Persönlich:** [z.B. Teamwork beim Problemlösen, Frustrationstoleranz]

## 🤝 Inklusion & Differenzierung
* **Für schwächere Kids / Motorische Einschränkungen:** [Wie kann das Experiment vereinfacht werden?]
* **Für Fortgeschrittene / Hochbegabte:** [Siehe Experten-Level im Zeitplan, z.B. selbstständiges Variieren der Variablen]

## 🏢 Anforderungen an Räumlichkeiten
- [z.B. Waschbecken zwingend erforderlich]
- [z.B. Gut belüfteter Raum]
- [z.B. Abwischbare Tische]

## 🛠️ Anforderungen ans Material vor Ort
**Pro Teilnehmer/Team:**
- [Item 1]
- [Item 2]

**Für den Mentor (Allgemein):**
- [Item 1]
- [Item 2]

## ⏱️ Zeitaufwand
- **Vorbereitungszeit (Mentor):** [z.B. 20 Minuten]
- **Nachbereitungszeit (Aufräumen):** [z.B. 15 Minuten]
- **Kursdauer:** 100 Minuten

---

## 🚀 Detaillierter Ablauf (100 Minuten)

| Zeit | Phase | Beschreibung | Fokus / Mentor-Tipps |
|------|-------|--------------|----------------------|
| **20min** | Einleitung | [Spannender Hook, Erklärung des Themas] | [Worauf besonders achten?] |
| **40min** | Praxis Level 1 | [Basis-Experiment oder Aufgabe] | [Wo hakt es meistens?] |
| **10min** | Pause | [Hände waschen, Lüften] | [Material für Level 2 vorbereiten] |
| **15min** | Experten-Level | [Erweiterte Aufgabe / Variablen ändern] | [Wie kann man hochbegabte Kinder hier challengen?] |
| **15min** | Reflexion | [Ergebnisse präsentieren, Aufräumen] | [Welche offenen Fragen sollten gestellt werden?] |

---

## 💡 Weitere nützliche Informationen
* **Mögliche Fehlerquellen:** [Was geht erfahrungsgemäß oft schief?]
* **Alltagsbezug:** [Wo finden die Kids diese Technologie/Wissenschaft im echten Leben?]
* **Links & Quellen:** [Websites, Youtube-Videos als Referenz]
```

---

## 4. Fiktives Beispiel: Die Zitronen-Batterie

Das folgende fiktive Beispiel zeigt, wie die Vorlage in der Praxis ausgefüllt wird.

***

# 🍋 Erleuchtung durch Zitrusfrüchte: Die Zitronen-Batterie

> **S T E A M - P R O F I L**
> [ ✅ ] 🧪 **S**cience (Wissenschaft)
> [ ✅ ] 💻 **T**echnology (Technologie)
> [ ❌ ] ⚙️ **E**ngineering (Ingenieurswesen)
> [ ❌ ] 🎨 **A**rts (Kunst)
> [ ❌ ] 📐 **M**ath (Mathematik)

**📋 Metadaten**
* **Autor:** ZWEIFEL Mike (mike.zweifel@zigerschlitzmakers.ch)
* **Version:** v1.0.0
* **Erstellt am:** 2026-03-12
* **Letzte Änderung:** 2026-03-12
* **Zielgruppe:** 9-12 Jahre
* **Format:** 🛠️ 100% Offline
* **Schwierigkeit:** Mittel
* **Sicherheitsstufe:** Gelb (Scharfe Messer beim Zitronenschneiden, schwacher Strom)

---

## 📖 Kurzbeschreibung
Aus alltäglichen Lebensmitteln wird ein Kraftwerk! Die Kinder lernen die chemischen Grundlagen von Batterien kennen, indem sie aus Zitronen, Kupfermünzen und Zinknägeln eine eigene Stromquelle bauen, die stark genug ist, um eine LED zum Leuchten zu bringen.

## ❓ Leitfragen (Essential Questions)
* Warum leuchten unsere Lampen zuhause nicht mit Obst?
* Was macht eine Batterie eigentlich zu einer Batterie?

## 🎯 Lernziele (Was nehmen die Kids mit?)
* **Fachlich:** Verstehen der Prinzipien von Anode, Kathode und Elektrolyt in Batterien. Kenntnis von Reihenschaltung zur Spannungserhöhung.
* **Methodisch:** Systematisches Messen von Spannung mit einem Multimeter.
* **Sozial/Persönlich:** Hartnäckigkeit, wenn das erste Experiment scheitert. Teamwork bei der Verkabelung mehrerer Zitronen.

## 🤝 Inklusion & Differenzierung
* **Für schwächere Kids / Motorische Einschränkungen:** Größere Krokodilklemmen bereitstellen, die leichter zu greifen sind. Zitronen vom Mentor vorab tief einschneiden, damit Münzen leichter hineingesteckt werden können.
* **Für Fortgeschrittene / Hochbegabte:** Spannung und Stromstärke messen und berechnen lassen, wie viele Zitronen theoretisch nötig wären, um ein Smartphone (5V, 1A) zu laden.

## 🏢 Anforderungen an Räumlichkeiten
- Arbeitsflächen, die nass und säurehaltig werden dürfen (oder Unterlagen nutzen).
- Ein Waschbecken zum Händewaschen.
- Möglichkeit, den Raum für den finalen LED-Test etwas abzudunkeln.

## 🛠️ Anforderungen ans Material vor Ort
**Pro Teilnehmer/Team (2er Teams):**
- 4 frische, saftige Zitronen
- 4 Kupfermünzen (z.B. 5-Rappen-Stücke, blank poliert)
- 4 verzinkte Nägel
- 5 Krokodilklemmen-Kabel
- 1 rote oder blaue LED (möglichst 1,5V - 3V)

**Für den Mentor (Allgemein):**
- 1 scharfes Messer (nur vom Mentor bedient!)
- Papiertücher (viel davon!)
- 1 Multimeter zur Spannungsmessung

## ⏱️ Zeitaufwand
- **Vorbereitungszeit (Mentor):** 15 Minuten (Münzen polieren, Kabel entwirren).
- **Nachbereitungszeit (Aufräumen):** 20 Minuten (Klebrige Tische reinigen, Zitronen entsorgen).
- **Kursdauer:** 100 Minuten

---

## 🚀 Detaillierter Ablauf (100 Minuten)

| Zeit | Phase | Beschreibung | Fokus / Mentor-Tipps |
|------|-------|--------------|----------------------|
| **16:40 - 16:50** | Einleitung | Der Mentor beißt (optional!) in eine Zitrone. "Sauer macht lustig... und macht Licht!" Kurze Erklärung, wie Ionen in der Säure wandern. | Keine tiefen chemischen Formeln. Analogie nutzen: Die Zitrone ist wie ein Schwimmbad für kleine Stromteilchen. |
| **16:50 - 17:30** | Praxis Level 1 | Aufbau EINER Zitronen-Zelle. Nagel rein, Münze rein. Messen mit dem Multimeter. Reicht das für die LED? (Spoiler: Nein, ca. 0.9V). | Frustration vermeiden: "Wissenschaftler irren sich ständig. Wie kriegen wir mehr Power?" |
| **17:30 - 17:40** | Pause | Hände waschen, Plätze kurz abwischen. | Multimeter an Teams verteilen. |
| **17:40 - 18:05** | Experten-Level | Reihenschaltung! Die Kids verbinden 3-4 Zitronen (Kupfer zu Zink). Nun sollte die LED leuchten! Expertenfrage: Was passiert, wenn wir Äpfel statt Zitronen nehmen? | Hochbegabte können Berechnungen anstellen: "Wie viele Zitronen bräuchten wir, um Mikes Handy zu laden?" |
| **18:05 - 18:20** | Reflexion | Licht aus! Alle LEDs leuchten. Diskussion, warum wir trotzdem keine Zitronen-Autos haben. Gemeinsames Aufräumen. | Betonen: Der Stromkreis muss komplett geschlossen sein. Kupfer IMMER an das lange Bein der LED. |

---

## 💡 Weitere nützliche Informationen
* **Mögliche Fehlerquellen:** Die Münze und der Nagel berühren sich *innerhalb* der Zitrone -> Kurzschluss! Die LED ist falsch gepolt.
* **Alltagsbezug:** Jedes Handy, jedes E-Auto funktioniert nach diesem Prinzip (Anode, Kathode, Elektrolyt), nur eben mit Lithium statt Zitrone.
* **Links & Quellen:** 
  - Erklärvideo: `[Lokaler Pfad](media/videos/zitronenbatterie_erklaerung.mp4)`
  - Schaltplan: `![Schaltplan](media/images/schaltplan_zitrone.png)`
