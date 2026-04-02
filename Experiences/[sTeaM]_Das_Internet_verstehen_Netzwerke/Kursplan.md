![Banner](media/images/banner.png)

# Das Internet verstehen: Wir bauen Computernetzwerke


> **S T E A M - P R O F I L**
> [ ❌ ] 🧪 **S**cience (Wissenschaft)
> [ ✅ ] 💻 **T**echnology (Technologie)
> [ ❌ ] ⚙️ **E**ngineering (Ingenieurswesen)
> [ ❌ ] 🎨 **A**rts (Kunst)
> [ ✅ ] 📐 **M**ath (Mathematik)

**📋 Metadaten**
* **Autor:** ZWEIFEL Mike (mike.zweifel@zigerschlitzmakers.ch)
* **Version:** v1.0.0
* **Erstellt am:** 2026-03-13
* **Letzte Änderung:** 2026-03-13
* **Zielgruppe:** 9-12 Jahre
* **Format:** 🖥️ 100% PC
* **Kursstatus:** In Entwicklung
* **Schwierigkeit:** Mittel
* **Sicherheitsstufe:** Grün (Unbedenklich - 100% PC-Kurs)

---

## 📖 Kurzbeschreibung
Woher weiß das YouTube-Video, welchen Weg es zu meinem Handy nehmen muss? In diesem Kurs lüften wir das Geheimnis des Internets. Mit dem interaktiven Online-Simulator webnetsim.de bauen die Kids ihr eigenes virtuelles Computernetzwerk auf. Sie lernen, was Router, Switches und Server sind, vergeben IP-Adressen und beobachten, wie Datenpakete durch die Leitungen flitzen.

## ❓ Leitfragen (Essential Questions)
* Wie finden Computer im Internet zueinander, ohne sich zu "verlaufen"?
* Was passiert genau, wenn ich eine Webseite aufrufe?

## 🎯 Lernziele (Was nehmen die Kids mit?)
* **Fachlich:** Die Funktion von Clients, Servern, Switches und Routern verstehen. Das Konzept von IP-Adressen und Datenpaketen begreifen.
* **Methodisch:** Einen Netzwerksimulator bedienen, Geräte virtuell verkabeln und Verbindungstests (Ping) durchführen.
* **Sozial/Persönlich:** Logisches und strukturiertes Problemlösen (Wo hängt das Datenpaket fest?).

## 🤝 Inklusion & Differenzierung
* **Für schwächere Kids:** Nur ein kleines lokales Netzwerk (LAN) mit 2 PCs und einem Switch aufbauen. Die IP-Adressen (z.B. 192.168.0.1) vorgedruckt auf Zetteln austeilen.
* **Für Fortgeschrittene / Hochbegabte:** Zwei verschiedene Netzwerke mit einem Router verbinden und das Routing (den Weg der Pakete) konfigurieren. Einen eigenen virtuellen Webserver aufsetzen.

## 🏢 Anforderungen an Räumlichkeiten
- PC-Raum oder Laptops für alle Teilnehmer (100% am PC).
- Stabile Internetverbindung.

## 🛠️ Anforderungen ans Material vor Ort
**Pro Teilnehmer/Team (1-2er Teams):**
- 1 PC/Laptop mit Browser.
- Zugang zu `https://webnetsim.de/`.

**Für den Mentor (Allgemein):**
- Beamer/Bildschirm zum Vorzeigen.

## ⏱️ Zeitaufwand
- **Vorbereitungszeit (Mentor):** 10 Minuten (PCs starten, Browser-Tabs öffnen).
- **Nachbereitungszeit (Aufräumen):** 5 Minuten.
- **Kursdauer:** 100 Minuten

---

## 🚀 Detaillierter Ablauf (100 Minuten)

| Zeit | Phase | Beschreibung | Fokus / Mentor-Tipps |
|------|-------|--------------|----------------------|
| **16:40 - 16:50** | Einleitung | **Die digitale Post:** Analogie zum Postsystem erklären. IP-Adresse = Hausnummer. Router = Postverteilzentrum. Datenpaket = Brief. | Nicht zu tief in Subnetzmasken eintauchen, das verwirrt. Fokus auf die IPs. |
| **16:50 - 17:20** | Praxis Level 1 | **Das erste LAN:** Auf webnetsim.de zwei "Clients" (PCs) und einen "Switch" platzieren und mit Kabeln verbinden. Jedem PC eine IP (192.168.0.1 und 192.168.0.2) geben. Einen Ping senden! | Den Kids zeigen, wie sie die Simulationsgeschwindigkeit anpassen können, um die Pakete fliegen zu sehen. |
| **17:20 - 17:35** | Praxis Level 2 | **Der Server kommt:** Einen Server zum Netzwerk hinzufügen (z.B. "Webserver"). Eine Webseite darauf speichern und vom Client aus über die IP abrufen. | Das "Aha"-Erlebnis: Das Internet besteht eigentlich nur aus fremden Computern (Servern)! |
| **17:35 - 17:45** | Pause | Bildschirm-Pause! Aufstehen und strecken. | |
| **17:45 - 18:05** | Experten-Level | **Die Brücke ins Nachbarnetz:** Wie spreche ich mit einem anderen Netzwerk? Einen "Router" einbauen, der zwei Switches (zwei verschiedene Netzwerke, z.B. 192.168.0.x und 192.168.1.x) verbindet. | Das erfordert Konzentration: Welcher Port am Router hat welche IP? (Gateway-Konzept vereinfacht erklären). |
| **18:05 - 18:20** | Reflexion | **Zusammenfassung:** Wenn ihr Zuhause im WLAN seid, wer ist der Switch? Wer ist der Router? (Oft in einer "FritzBox" kombiniert). | Alle PCs herunterfahren und Arbeitsplätze aufräumen. |

---

## 💡 Weitere nützliche Informationen
* **Mögliche Fehlerquellen:** Tippfehler bei den IP-Adressen (z.B. Komma statt Punkt). Vergessen, die Kabelverbindungen in der Simulation herzustellen.
* **Alltagsbezug:** Jeder Haushalt hat einen Router. Jedes Smartphone hat eine IP-Adresse, wenn es im WLAN ist.
* **Links & Quellen:** 
  - [WebNetSim - Netzwerksimulator](https://webnetsim.de/)