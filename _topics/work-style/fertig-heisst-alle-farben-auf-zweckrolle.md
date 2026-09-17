---
audience: personal
scope: universal
topic: work-style
---

# «Fertig verdrahtet» heisst: jede Farbe hängt an einer sinnvollen Zweckrolle — und jede andere Eigenschaft auch

Eine Komponente melde ich erst dann als **fertig verdrahtet**, wenn ich an jeder Variante
jede Farbbindung geprüft habe und jede an einer Rolle hängt, die ihren Zweck benennt
(z. B. `*Surface/State/Control/selected-hover`, nicht `surface-primary-shade960`).
Wertgleiche Bindungen auf Basis- oder Shade-Rollen sind **offene Arbeit**, auch wenn sich
kein Pixel ändert. Sie stehen im Bericht explizit als «offen, wertgleich», nicht als
«nur Hygiene» und nie unter «fertig».

**Why:** Selina kommuniziert Fertigmeldungen nach aussen (Webex an Karin/Luca, ✅ auf der
Prio-Seite). Stellt sich danach heraus, dass Bindungen fehlen, fühlt sich «ist fertig»
für sie und für die Empfänger «nach nicht ganz wahr» an. Korrektur 8.9.2026 (Polypoint):
Checkbox war als fertig gemeldet, die Ringe hingen aber noch auf Shade-Rollen — die neue
Familie `Control` muss dort noch verdrahtet werden.

**Erweiterung 17.9.2026 (Selina, Polypoint):** «Fertig» heisst, dass von einer Komponente **alle** Elemente verdrahtet sind — Text, Füllung, Kontur, Radien, Farben, Abstände, Typografie. Eine reine Farbprüfung reicht für ein ✅ auf einer Prio-Liste nicht. Folge: Häkchen, die nur auf Farbprüfungen beruhten (Fields, Select, Input, Checkbox), gelten erst nach einem Voll-Audit über Strichstärken, Radien, Abstände und Textstile als belastbar. Werte ohne Token (z. B. Abstand 10, −1) im Bericht als «Ausnahme ohne Token» ausweisen, nicht verschweigen.

**How to apply:**
- Vor jeder Fertigmeldung Knotenprüfung aller Varianten; Bindungen nach drei Klassen
  ausweisen: zielkonform · wertgleich offen · sichtbar offen.
- Fehlt eine Zweckrolle noch im System, ist die Komponente «fertig bis auf Familie X»,
  nicht «fertig».
- Gilt genauso für Icons, Text, Konturen und Strichstärken wie für Flächen.
- Verwandt: [[figma-variablennamen-statt-hex]], [[laufendes-merken]].
