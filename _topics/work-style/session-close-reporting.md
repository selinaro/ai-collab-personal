# Session-Close-Reporting (Selina, 2026-07-25; erweitert 2026-08-24)

Beim Session-Abschluss («Session closed» o. ä.) enthält die Abschluss-Antwort **zwei Teile, beide als echte Listen** (nie Fliesstext, vgl. [[chat-formatting]]):

1. **Gemerkt/Persistiert** — was in die ai-collab-Zellen geschrieben/aktualisiert wurde, als Liste (ein Punkt pro Eintrag).
2. **Stundenerfassung** — die erledigte Arbeit des Tages, damit Selina sie direkt in ihre Stundenerfassung übernehmen kann. **Format je Zeile: `Stichwort: Beschreibung in einem Satz`** — das Stichwort ist der Bezugspunkt (Jira-Key, Artefakt oder Thema), danach genau ein Satz, was gemacht wurde. Auf Deutsch.

Beispiel:

```
VES-469: Acceptance Criteria um Filter-Verhalten, Empty-State und Export ergänzt.
Figma: Alarmprotokoll-Tabelle um die Test-Alarm-Zeile und die Filter-Checkbox erweitert.
Backlog: Lücke bei der Ausbleiben-Erkennung des Test-Alarms identifiziert und mit Pascal geklärt.
```

**Why:** Selina rapportiert ihre Arbeitstage; die Zusammenfassung spart ihr das Rekonstruieren. Der Absatz-Stil beim Gemerkten war schwer scanbar. Das `Stichwort: Satz`-Format (2026-08-24 präzisiert) lässt sich zeilenweise in die Erfassung übernehmen.

**How to apply:** Gilt bei jedem Session-Close zusätzlich zum session-close-protocol (Distillation in ai-collab-Zellen bleibt unverändert); die beiden Listen kommen in die Chat-Abschlussantwort. Das laufende Persistieren während der Session regelt [[laufendes-merken]] — beim Close ist idealerweise nur noch Restliches nachzutragen.
