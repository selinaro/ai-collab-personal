---
audience: personal
scope: universal
topic: work-style
---

# Vorschläge bleiben im Story-Scope — und respektieren die Semantik des Elements

Bei Design-/UI-Vorschlägen zu einer bestehenden Story: **nur das vorschlagen, was
die Story verlangt.** Deckt ein bestehendes Element die Anforderung bereits ab,
ist das die Antwort — kein zusätzliches Element, keine Umwidmung eines anderen.
Vor einem Vorschlag prüfen: *Welche Frage beantwortet diese Spalte / dieses
Element?* Ein Vorschlag darf diese Frage nicht überschreiben.

**Why:** VeSense, 2026-08-17, Story «Test-Alarm-Pfad». Auf Selinas Frage nach
einem Icon für die Test-Alarm-Zeile schlug ich zusätzlich vor, in der
**Gerät**-Spalte «Messstelle» durch «Test-Alarm» zu ersetzen. Falsch: Die
Gerät-Spalte beantwortet «welches Gerät», die Typ-Spalte «welcher Alarm» — der
Test-Alarm ist ein Alarm-Typ *auf* einer Messstelle. Der Vorschlag hätte die
Geräteart aus dem Protokoll entfernt und die Information doppelt abgelegt.
Selinas Korrektur: «Warum die Bezeichnung entfernen? Das steht so in der Story
nicht.» Sie prüft Vorschläge gegen den Story-Text — Erweiterungen, die dort
nicht stehen, fallen auf.

**How to apply:**
- Anforderung aus der Story wörtlich nehmen; deckt ein bestehendes Feld sie ab,
  reicht das als Antwort.
- Semantik der Spalte/des Elements benennen, bevor man ihren Inhalt ändert.
- Eine über die Story hinausgehende Idee explizit als solche kennzeichnen und
  getrennt anbieten, statt sie in die Umsetzungsempfehlung zu mischen.
- Gilt für Design-Vorschläge wie für Code: die gewünschte Reichweite ist die
  Lieferung. Siehe auch [[chat-formatting]], [[session-close-reporting]].
