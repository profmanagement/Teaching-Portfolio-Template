# 🏠 Mein Lehrportfolio

> *„Das Portfolio ist kein Produkt – es ist ein Denkprozess."*
> — Siegel, Lohner & Arnold (2025)

---

## 📌 Schnellzugriff

| Bereich | Beschreibung |
|---|---|
| [[01_Lehrphilosophie/Lehrphilosophie\|📖 Lehrphilosophie]] | Meine pädagogischen Überzeugungen & Werte |
| [[02_Lehrveranstaltungen/Übersicht Lehrveranstaltungen\|📚 Lehrveranstaltungen]] | Alle Kurse, Syllabi, Lernziele |
| [[03_Reflexionen/Reflexions-Log\|🪞 Reflexionen]] | Laufende Lehrreflexionen & Journaleinträge |
| [[04_Feedback/Feedback-Übersicht\|💬 Feedback]] | Studierenden-, Peer- & Selbstfeedback |
| [[05_Entwicklung/Entwicklungsplan\|🚀 Entwicklung]] | Weiterbildungen, Ziele, Meilensteine |
| [[06_Materialien/Materialien-Übersicht\|🗂️ Materialien]] | Lehrproben, Medien, Innovationen |
| [[07_Portfolio-Ausgabe/Präsentationsportfolio\|🎯 Präsentationsportfolio]] | Kuratierte Version für externe Zwecke |
| [[08_Lehrdesigns/Übersicht Lehrdesigns\|🎨 Lehrdesigns]] | Didaktische Methoden & Erfahrungen |
| [[09_Archiv/README\|🗄️ Archiv]] | Abgeschlossene Semester |

---

## 🔄 Aktueller Status

- **Letztes Update:** `=date(today)`
- **Aktuelles Semester:** 
- **Fokusthema dieser Phase:** 

---

## 📊 Überblick

### Aktuelle Lehrveranstaltungen
```dataview
TABLE Semester, Format, Studierende
FROM "02_Lehrveranstaltungen"
WHERE Typ = "Lehrveranstaltung"
SORT Semester DESC
```

### Letzte Reflexionen
```dataview
TABLE Datum, Thema, Stimmung
FROM "03_Reflexionen"
SORT Datum DESC
LIMIT 5
```

### Lehrdesigns & Methoden
```dataview
TABLE status
FROM "08_Lehrdesigns"
WHERE file.name != "Übersicht Lehrdesigns"
SORT file.name ASC
```

---

## 🧭 Portfolio-Kompass

Drei Leitfragen, die ich regelmäßig beantworte:

1. **Was hat in letzter Zeit gut funktioniert** – und warum?
2. **Was würde ich beim nächsten Mal anders machen?**
3. **Was habe ich über meine Studierenden gelernt?**

---

## 🔗 Wissenslandkarte

*(Öffne die Graph-Ansicht in Obsidian: `Strg/Cmd + G`)*

Wichtige Verknüpfungen:
- [[01_Lehrphilosophie/Lehrphilosophie]] ← verknüpft mit allen Reflexionen
- [[04_Feedback/Feedback-Übersicht]] ← gespeist aus allen LV-Notizen
- [[05_Entwicklung/Entwicklungsplan]] ← verknüpft mit Reflexionen & Feedback
- [[08_Lehrdesigns/Übersicht Lehrdesigns]] ← verknüpft mit LV-Notizen & Reflexionen

---

*Erstellt nach: Siegel, Lohner & Arnold (2025). Reimagining Teaching Portfolios Through Personal Knowledge Management with Digital Tools for Thought. ZFHE, 20(3), 231–258. Sowie: Siegel, Stefan T. (2026, Mai). Professionalisierung der eigenen Lehrtätigkeit: Lehrkompetenz(en) erfassen, dokumentieren, evaluieren, validieren und präsentieren. Workshop im Rahmen des CAS HSG in Hochschuldidaktik – Teaching and Learning in Higher Education an der Universität St. Gallen (HSG).*
