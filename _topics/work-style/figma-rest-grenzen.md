# Figma-REST: was es nicht zuverlässig zeigt

Zwei Fehlbefunde vom 3.11.2026 (PEP), beide aus der REST-Lesart:
- **Variantenreihenfolge:** Die Reihenfolge der `children` im Set ist nicht die sichtbare Anordnung im Canvas. Keine Reihenfolge-Befunde aus der Kinderliste ableiten. Selina: «Du liest wohl anders als ich das File. Ich sehe keinen Unterschied.»
- **Sichtbarkeit:** Ein Text kann `visible` sein, aber in einem ausgeblendeten Eltern-Element liegen. Vor einem Befund die Sichtbarkeit der ganzen Ahnenkette prüfen. (`.Documentation`-Header «Included Atoms» war ausgeblendet.)

**How to apply:** Reihenfolge nur aus Positionen (`absoluteBoundingBox`) beurteilen, wenn überhaupt; Sichtbarkeit rekursiv über alle Eltern prüfen. Vgl. [[figma-masse-runden-nicht-abschneiden]].
