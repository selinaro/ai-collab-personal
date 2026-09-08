---
audience: personal
scope: universal
topic: work-style
---

# Figma-Farben immer mit Variablennamen benennen, nicht mit Hex-Werten

Wenn ich über Farben in einem Figma-File spreche (Befunde, Umhänglisten, Antwortentwürfe,
Vergleiche mit Storybook), nenne ich die **Variable/Rolle** (z. B. `*Interaction/focus-ring`,
`surface-secondary-shade920`) — nicht den Hex-Wert. Hex nur als Zusatz in Klammern, wenn ich
wirklich etwas Gemessenes berichte (Kontrast) oder wenn eine Farbe an keiner Variable hängt
(dann explizit «ungebunden, #…»).

**Why:** Selina sieht in Figma die Variablennamen, nicht die Hex-Werte. Eine Liste aus
Hex-Werten kann sie nicht nachvollziehen und nicht in Figma wiederfinden. Korrektur vom
8.9.2026 (Polypoint, Radio/Storybook-Vergleich: «Diese sehe ich so in dieser Form nicht in Figma»).

**How to apply:**
- Für Storybook-/CSS-Werte: Hex zuerst gegen den Variablen-Export auflösen und die passende
  Rolle nennen («entspricht `surface-primary-shade600`»); kann keine Rolle zugeordnet werden,
  das sagen.
- Gilt auch in Nachrichtenentwürfen an Dritte (Luca, Denny, Karin).
- Verwandt: [[chat-formatting]] (Findings als Listen), [[message-drafts]].
