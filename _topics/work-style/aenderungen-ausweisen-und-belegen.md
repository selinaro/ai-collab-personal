---
name: aenderungen-ausweisen-und-belegen
description: Jede Empfehlung, die einen sichtbaren Wert ändert (Strichstärke, Farbe, Grösse), nennt ausdrücklich vorher → nachher. Aussagen zu Quellen (Material, Storybook) erst nach Prüfung aller Varianten, nie aus dem Gedächtnis oder einer Stichprobe.
metadata:
  type: feedback
---

Selina, 20.10.2026, drei Vorfälle am selben Tag (PEP-Design-System):
- Snackbar: «Strichstärke an `Border Component/Default` binden» empfohlen. Filled hat aber nur unten 2 px, die Variable ist 1 px. Die Änderung 2 → 1 px blieb unerwähnt. Selina: «Es wirkt, als ob du es nicht bemerkt hättest oder selbst entschieden hast.»
- Time Picker: Text-Buttons «nach Material» empfohlen. Das stammte ungeprüft aus dem Gedächtnis (M3-Dialog) und passte nicht zu PEP (Angular Material, Storybook).
- Snackbar-Icons in Storybook: nur eine Variante gemessen und das Ergebnis auf alle übertragen. Falsch, ausgerechnet diese Variante war die Ausnahme.

**Why:** Selina gibt Empfehlungen ans Team weiter und steht mit ihrem Namen dafür ein. Eine verschwiegene Wertänderung oder eine falsche Quellenangabe kostet sie Glaubwürdigkeit und Zeit für Rückfragen.

**How to apply:**
- Bei jeder Bindungs- oder Umbau-Empfehlung prüfen, ob sich ein sichtbarer Wert ändert. Falls ja, ausdrücklich **«heute X → danach Y»** schreiben und begründen. Sonst eine Variable bzw. einen Weg vorschlagen, der den Wert hält.
- Messwerte vollständig erheben: Bei Figma-REST zum Beispiel auch `individualStrokeWeights` lesen, nicht nur `strokeWeight`.
- Quellen (Material, Storybook, WCAG) **vor** der Empfehlung nachsehen, alle Varianten messen und die Quelle nennen. Unsicherheit offen sagen.

Siehe auch [[erst-kommunizieren-dann-umbauen]], [[erst-durchdenken-dann-fragen]].

## Nachtrag 29.10.2026 — Umbau-Anleitung vor Prüfung der Grenzen

- Paginator/Time Picker: «Instance swap auf large, Breite Fixed 119/122» empfohlen, ohne die **Mindestbreite 230 px** an `Field-large` und ohne die Umsetzung im Storybook zu prüfen. Selina merkte beides selbst («Die Fields haben eine Mindestbreite von 230px»).
- Danach «der Paginator hat kein Select» behauptet. Richtig war: kein Select **aus der Bibliothek**, sondern ein im Paginator gebautes. Selina: «Ich sehe es in Storybook.»

**How to apply (Ergänzung):**
- Vor jeder Umbau-Anleitung die Grenzen der beteiligten Komponenten lesen (min/max width, Sizing Hug/Fill/Fixed) und die Umsetzung im Storybook messen, nicht erst danach.
- Befunde so eng formulieren, wie sie belegt sind: «nicht die Bibliotheks-Komponente X» statt «kein X».
