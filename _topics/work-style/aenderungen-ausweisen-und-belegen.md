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
