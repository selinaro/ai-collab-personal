# Befunde: wo genau, was fehlt, wie es richtig wäre

audience=personal, scope=universal · 2026-11-17 (Selina, PEP-Session)

**Regel:** Jeder Befund nennt drei Dinge: **wo genau** (Seite › Set › Variante › Ebene/Feld), **was** dort falsch ist oder fehlt (Ist-Wert wörtlich), und **wie es richtig wäre** (Soll-Wert oder konkreter Vorschlag).

**Anlass:** Ich schrieb zur Toolbar «Name des Sets ist unvollständig». Selina wusste, was gemeint war, musste aber suchen. Richtig wäre gewesen: «Seite Toolbar › Set heisst `.Building Blocks`, es fehlt der Teil nach dem Schrägstrich → z. B. `.Building Blocks/Toolbar/Menu-Items`».

**Why:** Selina setzt die Befunde in Figma von Hand um; jede ungenaue Angabe kostet sie Suchzeit.

**How to apply:** Vor dem Senden jeden Befund prüfen: Könnte Selina ihn umsetzen, ohne etwas zu suchen oder nachzufragen? Keine Sammelbegriffe wie «unvollständig», «uneinheitlich», «teilweise» ohne die konkrete Stelle und den Sollwert. Gilt für die gesamte Zusammenarbeit, nicht nur Figma. Verwandt: [[figma-orte-per-name-statt-knoten-id]], [[aenderungen-ausweisen-und-belegen]].

## Ergänzung 26.11.2026 (PEP Ready-Check, Selina: «Bitte merke dir das»)

- **Abstände, Radien, Strichstärken:** immer den vollen Ebenenpfad bis zur betroffenen Ebene nennen (Seite › Set › Variante › … › **Ebenenname**), dazu die Eigenschaft (Padding oben/unten/links/rechts oder Abstand zwischen Elementen) und wie viele Varianten betroffen sind. Selina soll nicht suchen müssen.
- **Sollwert ist immer eine konkrete Variable mit Wert**, z. B. «→ `Radius Component/Menu` (4)», nie nur «eine Radius-Variable». Gilt auch, wenn die Antwort «keine Variable nötig» ist.
- **Vor dem Melden am aktuellen Stand nachmessen** (Zeitpunkt der Abfrage nennen, wenn Selina parallel arbeitet) und Scheinbefunde aussortieren: Abstand bei «Space between» oder mit nur einem Kind wirkt nicht; Strichstärke auf einer Instanz (z. B. Slot) gehört zur Hauptkomponente; Bindung auf einer Ellipse-Ecke wirkt nicht.
- Zahlen nicht hochrechnen: «alle 112 Varianten» nur, wenn alle 112 gezählt sind.
