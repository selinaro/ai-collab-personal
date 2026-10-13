---
name: figma-masse-runden-nicht-abschneiden
description: Figma-Masse aus der REST-API immer runden (bzw. mit Nachkommastellen prüfen), nie per int() abschneiden — Gleitkomma-Reste erzeugen Scheinbefunde
metadata:
  type: feedback
---

Masse aus der Figma-REST-API (Breite, Höhe, Abstände, Radien) **immer runden (`round(x, 2)`) oder mit Toleranz vergleichen, nie mit `int()` abschneiden.** Ein Befund «X px statt Y px» erst melden, wenn die Abweichung nach Rundung ≥ 0,5 px ist; bei Zweifel den Rohwert mit Nachkommastellen nennen und sagen, was Figma im UI anzeigt.

**Why:** 13.10.2026 meldete Claude zweimal «vertikale Scrollbar 13 px statt 14 px» im Table-Master. Tatsächlich war die Breite 13,99995 px (Gleitkomma-Rest vom früheren Drehen), Figma zeigt 14. Selina suchte lange nach einem Fehler, den es nicht gab: «hat für mich recht viel Zeit gebraucht. Bitte diesen Fehler vermeiden und die Kommastellen mehr beachten.»

**How to apply:** In allen Audit-/Mess-Skripten `round()` statt `int()`; Rotation ebenfalls mit Toleranz (|r| > 0,01). Vor jedem Mass-Befund Gegenprobe: Würde Figma im UI diesen Wert anzeigen? Verwandt: [[fertig-heisst-alle-farben-auf-zweckrolle]], [[figma-orte-per-name-statt-knoten-id]].
