---
tags: [changelog, portfolio-entwicklung]
Datum: 2026-06-11
---

# 📋 Änderungsprotokoll – Portfolio-Erweiterung

**Datum:** 11. Juni 2026  
**Anlass:** Strukturerweiterung auf Basis Analyse & Feedback

---

## Überblick der Änderungen

### ✅ Neu hinzugefügt

#### `08_Lehrdesigns/` *(neuer Ordner)*
Eigener Bereich für didaktische Methoden und Lehrdesigns. Ermöglicht es, methodisches Wissen systematisch aufzubauen, mit Lehrveranstaltungen zu verknüpfen und über die Zeit zu reflektieren.

| Datei | Inhalt |
|---|---|
| `Übersicht Lehrdesigns.md` | Zentrale Navigations- und Entscheidungshilfe |
| `Service-Learning.md` | Methode mit Ablauf, Erfahrungen, Literatur |
| `Flipped-Classroom.md` | Methode mit Ablauf, Erfahrungen, Literatur |
| `Problem-Based-Learning.md` | Methode mit Ablauf, Erfahrungen, Literatur |
| `Peer-Learning.md` | Methode mit Ablauf, Erfahrungen, Literatur |

**Nächste Schritte:** Eigene Erfahrungen in die Methoden-Notizen eintragen; weitere Methoden nach Bedarf ergänzen (z. B. Design Thinking, Projektarbeit, Fallstudien).

---

#### `Templates/Template – Lehrdesign.md` *(neues Template)*
Vorlage für neue Methoden-Notizen: Kernidee, Grundelemente, Lernziele, Ablauf, eigene Erfahrungen, Herausforderungen, Literatur.

---

#### `01_Lehrphilosophie/Versionen/` *(neue Unterstruktur)*
Versionierungssystem für die Lehrphilosophie.

| Datei | Inhalt |
|---|---|
| `CHANGELOG.md` | Dokumentiert Veränderungen der Lehrphilosophie mit Datum und Auslöser |

**Empfohlener Workflow:** Am Semesterende aktuelle `Lehrphilosophie.md` als Snapshot hierher kopieren (`Lehrphilosophie_JJJJ-SS.md`) und CHANGELOG aktualisieren.

---

#### `06_Materialien/` *(Unterordner angelegt)*
Die in der Übersichtsdatei beschriebene Ablagestruktur wurde als tatsächliche Ordner angelegt:

- `Lehrpläne/`
- `Aufgaben & Prüfungen/`
- `Präsentationen/`
- `Medien & Videos/`
- `Vorlagen & Templates/`

---

#### `09_Archiv/` *(neuer Ordner)*
Ablageort für abgeschlossene Semester. Enthält `README.md` mit Archivierungs-Workflow.

---

## Vollständige Struktur (Stand 2026-06-11)

```
Teaching-Portfolio/
│
├── 00_START/
│   ├── 🏠 Dashboard.md
│   ├── 📖 Erste Schritte.md
│   └── 📋 Änderungsprotokoll.md    ← diese Datei
│
├── 01_Lehrphilosophie/
│   ├── Lehrphilosophie.md
│   └── Versionen/                  ← NEU
│       └── CHANGELOG.md
│
├── 02_Lehrveranstaltungen/
│   └── Übersicht Lehrveranstaltungen.md
│
├── 03_Reflexionen/
│   └── Reflexions-Log.md
│
├── 04_Feedback/
│   └── Feedback-Übersicht.md
│
├── 05_Entwicklung/
│   └── Entwicklungsplan.md
│
├── 06_Materialien/
│   ├── Materialien-Übersicht.md
│   ├── Lehrpläne/                  ← NEU
│   ├── Aufgaben & Prüfungen/       ← NEU
│   ├── Präsentationen/             ← NEU
│   ├── Medien & Videos/            ← NEU
│   └── Vorlagen & Templates/       ← NEU
│
├── 07_Portfolio-Ausgabe/
│   └── Präsentationsportfolio.md
│
├── 08_Lehrdesigns/                 ← NEU
│   ├── Übersicht Lehrdesigns.md
│   ├── Service-Learning.md
│   ├── Flipped-Classroom.md
│   ├── Problem-Based-Learning.md
│   └── Peer-Learning.md
│
├── 09_Archiv/                      ← NEU
│   └── README.md
│
└── Templates/
    ├── Template – Lehrveranstaltung.md
    ├── Template – Reflexionseintrag.md
    ├── Template – Feedback-Auswertung.md
    └── Template – Lehrdesign.md    ← NEU
```

---

## Empfohlene nächste Schritte

1. **Sofort:** Eigene Lehrveranstaltungen in `02_Lehrveranstaltungen/` eintragen (Template nutzen)
2. **Diese Woche:** `01_Lehrphilosophie/Lehrphilosophie.md` mit ersten Inhalten füllen
3. **Semesterbeginn:** Ersten Reflexionseintrag in `03_Reflexionen/Reflexions-Log.md` anlegen
4. **Laufend:** Genutzte Methoden in `08_Lehrdesigns/` mit eigenen Erfahrungen ergänzen
5. **Semesterende:** Snapshot der Lehrphilosophie in `Versionen/` ablegen, Semester archivieren

---

*Erstellt mit Unterstützung von Claude (Anthropic) am 11. Juni 2026.*
