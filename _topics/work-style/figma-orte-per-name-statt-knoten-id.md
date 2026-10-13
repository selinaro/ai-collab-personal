---
name: figma-orte-per-name-statt-knoten-id
description: Figma-Fundstellen im Chat mit Seite + Komponentenname + Variante + Ebenenpfad nennen, nie mit Knoten-IDs (z. B. 79037:101723)
metadata:
  type: feedback
---

Figma-Fundstellen nennt Claude im Chat so, wie Selina sie in Figma findet: **Seite → Komponente (Set) → Variante → ggf. Ebenen-/Frame-Pfad**, z. B. «Seite ‹Table›, Komponente `Table`, Ebene `Table + Scrollbars` → `Scrollbar`». **Keine Knoten-IDs** (`79037:101723`, `I65053:…`) im Chat — die sieht sie in Figma nicht.

**Why:** Selina 13.10.2026: «Gerne nicht mehr die Instanz-Nummer nennen. Die kenne/sehe ich in Figma nicht. Lieber eine klare Benennung vom Komponentennamen + Variante falls vorhanden.»

**How to apply:** IDs nur intern (Skripte, Memory-Notizen) verwenden; im Chat in Namen übersetzen. Bei verschachtelten Instanzen den Master nennen, von dem sie erben, plus Anzahl betroffener Stellen. Verwandt: [[interne-ids-erklaeren]], [[figma-variablennamen-statt-hex]].
