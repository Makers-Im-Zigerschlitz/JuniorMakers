# 🛠️ JuniorMakers Skill Card Template

Verwendung: Kopiere diesen Block pro Skill-Level und passe Felder an. Die YAML-Basis kann später 1:1 von der JuniorMakers HUD eingelesen werden.

```yaml
id: ROB-01                  # Familie-Kürzel + zweistellige Levelnummer
family: robotik             # machine-readable (robotik, elektronik, ...)
level: 1                    # 1–5
status: draft               # draft | active | deprecated
version: 0.1.0              # semver für spätere Updates
last_update: 2026-03-31

name: "Robotik · Level 1 – Aktoren Basics"
short_goal: "Baue und kalibriere einen autonomen Linienfolger"
summary: >-
  In diesem Level lernen die JuniorMakers, wie Servos, DC-Motoren und Sensoren
  zusammenspielen. Sie bauen einen einfachen Linienfolger und analysieren Fehlerbilder.

default_duration_minutes: 120
prerequisites:
  - ELE-03
  - DFA-02
  - SAFE-02
resources:
  - type: video
    title: "Linienfolger Quickstart"
    url: https://...
  - type: doc
    title: "Troubleshooting Guide"
    path: Experiences/[sTEam]_Strom_aus_dem_Bleistift/Kursplan.md
learning_path:
  - step: "Hardware Setup"
    checklist:
      - "Sensorbrücke montieren"
      - "Kalibrierung durchführen"
  - step: "Coding"
    checklist:
      - "PID-Basis implementieren"
      - "Failsafe definieren"
assessment:
  type: practical
  description: "Linienfolger absolviert Parcours A ohne Eingriff (<30 min)."
  rubric:
    - criterion: "Verkabelung & Sauberkeit"
      scale: 0-2
    - criterion: "Codequalität & Dokumentation"
      scale: 0-2
    - criterion: "Fehleranalyse"
      scale: 0-2
  proof_required:
    - photo
    - reflection_form
  pass_mark: 5
badge:
  name: "Actuator Apprentice"
  icon: media/badges/rob-01.png

mentor_notes: |
  *Vor dem Assessment Parcours aufbauen und Sensorwerte prüfen. Kids sollen
  bei Problemen zuerst selbst debuggen – Mentoren geben maximal drei Hinweise.*
reviewers:
  - role: mentor
    min_level: senior
  - role: peer
    optional: true
```

## Richtlinien
1. **Prerequisites** ausschließlich Skill-IDs (HUD validiert automatisch).
2. **Resources** können auf Experiences oder externe Medien verlinken.
3. **Assessment** stets messbar formulieren (Zeitlimit, Fehlerquote, etc.).
4. **Proof_required** legt fest, was im HUD hochgeladen werden muss.
5. **Versionierung** nutzen, sobald wir Skill Cards anpassen (Changelog im HUD).

## Mini-Beispiel (ausgefüllt)
```yaml
id: SAFE-02
family: sicherheit
level: 2
status: active
version: 1.0.0
last_update: 2026-03-31

name: "Sicherheit · Level 2 – Löten & ESD"
short_goal: "Sichere Lötstellen herstellen und ESD-Regeln anwenden"
summary: >-
  JuniorMakers demonstrieren korrekte THT-Löttechnik, ESD-Handhabung und können
  typische Fehlerbilder erkennen.
prerequisites: [SAFE-01]
resources:
  - type: pdf
    title: "Löt-Checkliste"
    path: Skills/resources/loet-check.pdf
assessment:
  type: practical
  description: "Löte in 20 min eine THT-Platine fehlerfrei."
  rubric:
    - criterion: "Lötpunktqualität"
      scale: 0-2
    - criterion: "ESD-Handling"
      scale: 0-2
    - criterion: "Selbstcheck"
      scale: 0-2
  proof_required: [photo]
  pass_mark: 5
badge:
  name: "Solder Certified"
  icon: media/badges/safe-02.png
```

> Ergänze nach Bedarf Felder (z. B. `materials`, `estimated_cost`). Sobald du deine Anpassungen fertig hast, kann ich die YAMLs in einzelne Skill-Dateien aufteilen und in die HUD-Pipeline einbinden.
