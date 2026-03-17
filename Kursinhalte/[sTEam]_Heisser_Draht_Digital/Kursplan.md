# Heisser Draht Digital: Vom Draht zum Code

![Heisser Draht Digital](media/images/banner.png)

> **S T E A M - P R O F I L**
> [ ❌ ] 🧪 **S**cience (Wissenschaft)
> [ ✅ ] 💻 **T**echnology (Technologie)
> [ ✅ ] ⚙️ **E**ngineering (Ingenieurswesen)
> [ ❌ ] 🎨 **A**rts (Kunst)
> [ ❌ ] 📐 **M**ath (Mathematik)

**📋 Metadaten**
* **Autor:** ZWEIFEL Mike (mike.zweifel@zigerschlitzmakers.ch)
* **Version:** v1.0.0
* **Erstellt am:** 2024-02-13
* **Letzte Änderung:** 2026-03-12
* **Zielgruppe:** 9-12 Jahre
* **Format:** 🔄 Gemischt
* **Schwierigkeit:** Mittel (Kombination aus Handwerk und Programmierung)
* **Sicherheitsstufe:** Gelb (Draht biegen erfordert Feinmotorik, leichtes Verletzungsrisiko an spitzen Drahtenden)

---

## 📖 Kurzbeschreibung
Der klassische Jahrmarkt-Klassiker "Heißer Draht" bekommt ein digitales Upgrade! Die Kinder biegen ihren eigenen Hindernisparcours aus Kupferdraht und schließen ihn an einen *Calliope mini* an. Anschließend programmieren sie den Mikrocontroller so, dass er Berührungen erkennt, Fehler zählt und die Zeit misst.

## ❓ Leitfragen (Essential Questions)
* Wie merkt der Computer überhaupt, dass sich die zwei Drähte berühren? (Stichwort: Stromkreis schließen)
* Warum müssen wir manchmal Code schreiben, um mechanische Dinge zu steuern?

## 🎯 Lernziele (Was nehmen die Kids mit?)
* **Fachlich:** Aufbau eines geschlossenen Stromkreises. Grundlagen der Programmierung (Schleifen, Wenn-Dann-Bedingungen, Variablen für Zeit und Fehler).
* **Methodisch:** Code-Blöcke logisch anordnen (MakeCode) und Programme auf einen Mikrocontroller flashen.
* **Sozial/Persönlich:** Handwerkliches Geschick beim Drahtbiegen, sportlicher Ehrgeiz und Fairness beim anschließenden Turnier.

## 🤝 Inklusion & Differenzierung
* **Für schwächere Kids / Motorische Einschränkungen:** Einen fertigen Parcours oder vorgebogene Drähte zur Verfügung stellen. Das Programmieren auf die reine Fehlererkennung (Piepton) beschränken.
* **Für Fortgeschrittene / Hochbegabte:** Komplexe Zeitmessung einbauen, Highscore-Speicherung programmieren, oder Start-Animationen und eigene Soundeffekte auf dem Calliope komponieren.

## 🏢 Anforderungen an Räumlichkeiten
- PC-Raum oder Laptops für alle Teilnehmer.
- Arbeitsflächen, auf denen gebastelt (Karton, Draht) werden kann.

## 🛠️ Anforderungen ans Material vor Ort
**Pro Teilnehmer/Team (2-3 JuniorMakers pro Team):**
- 1 PC / Laptop mit Internetzugang
- 1 Calliope mini mit USB-Kabel
- 3 Krokodilklemmen
- 1 m dünner Kupferdraht für den Parcours
- 20 cm dickerer Kupferdraht für den Griff
- Elektrisches Isolierband
- Karton und Holzreste (für die Basis)
- Klebeband / Heissleim

**Für den Mentor (Allgemein):**
- Zangen zum Drahtschneiden.

## ⏱️ Zeitaufwand
- **Vorbereitungszeit (Mentor):** 15 Minuten (Calliope und Laptops richten, Materialpakete schnüren).
- **Nachbereitungszeit (Aufräumen):** 10 Minuten.
- **Kursdauer:** 100 Minuten (Originalplan leicht gestrafft auf unser Standard-Format)

---

## 🚀 Detaillierter Ablauf (100 Minuten)

| Zeit | Phase | Beschreibung | Fokus / Mentor-Tipps |
|------|-------|--------------|----------------------|
| **16:40 - 16:50** | Einleitung | Vorstellung des "Heißen Drahts". Wie machen wir ihn digital? Einführung in den Calliope mini (LED-Matrix, Pins, USB). | Erklären: Pin (-) an den Griff, Pin (0) an den Parcours = Kontakt schließt den Kreis. |
| **16:50 - 17:15** | Praxis Level 1 | **Programmieren:** Auf `makecode.calliope.cc` ein einfaches Programm schreiben, das bei Kontakt (Pin 0 gedrückt) ein X auf der Matrix zeigt oder piepst. | Simulator nutzen! Das Programm muss erst im Browser funktionieren, bevor es auf den Calliope geladen wird. |
| **17:15 - 17:35** | Maker-Phase | **Bauen:** Den Kupferdraht biegen und auf dem Karton fixieren. Isolierband für Start/Ziel-Zonen (Ruhezonen) anbringen. Krokodilklemmen anschließen. | Drahtenden mit Klebeband sichern, Verletzungsgefahr minimieren. |
| **17:35 - 17:45** | Pause | Durchatmen! | Mentor bereitet die Laptops für Level 2 vor. |
| **17:45 - 18:05** | Experten-Level | **Level Up:** Variablen einbauen! Fehlerzähler programmieren (Wenn Kontakt -> Variable `Fehler` + 1). Optional: Zeitmessung hinzufügen. | Hochbegabte können LED-Farben oder Soundeffekte für verschiedene Fehleranzahlen programmieren. |
| **18:05 - 18:20** | Reflexion & Turnier | **Das große Finale:** Die Teams tauschen Plätze und spielen die Parcours der anderen. Siegerehrung! | Fokus auf Fairness. Feedbackrunde: Wo hing der Code, wo war der Draht zu schwer? |

---

## 💡 Weitere nützliche Informationen
* **Mögliche Fehlerquellen:** Der Calliope wird vom PC nicht erkannt (USB-Kabel prüfen, manche sind nur Ladekabel, keine Datenkabel!). Die Krokodilklemmen haben keinen guten Kontakt zum Kupfer (eventuell Lackschicht auf dem Draht?).
* **Alltagsbezug:** Jede Taste auf der Computertastatur, jeder Lichtschalter und jeder Touchscreen basiert auf dem Prinzip, einen Kontakt herzustellen und ein Signal an einen Chip (wie den Calliope) zu senden.
* **Links & Quellen:** 
  - [MakeCode Calliope Editor](https://makecode.calliope.cc)