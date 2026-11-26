# Ausblick nächste Komponenten — Ist-Stand + Schätzung (22.10.2026, intern, nicht an Polypoint)

Grundlage: full.json 22.10. 08:10 (Datei 06:07 UTC), Export `figma-variables-2026-10-22-1330.json`, Skript `multi.py` (Scratch; Logik = audit.py + Strichstärken je Seite + Farb-Overrides verschachtelter Instanzen), Kommentare 22.10.

| Komponente | Befunde | Grob zu tun | Schätzung |
|---|---|---|---|
| Snackbar Doku + Aufräumen | – | Doku Version B (Aktionen Filled, Booleans, Breite folgt Container), 3 Bilder in «Rules» → Instanzen, «Varianten»→«Variants», «white background»; Examples (alte Material-Snackbar) ersetzen; lose Elemente | 2–3 h |
| Autocomplete (large/small) | 8 (Farbe 4, Strichstärke 4) | Bindungen; Kommentare: Overflow-Tooltip für Supporting text (Selina), Farbe umkehren (Luca), Multi-line-Option (Zoltan) → Entscheide; Help-Icon-Overrides; Doku-Bilder prüfen | ½ Tag (+ Multi-line separat) |
| Text area | 36 (alles Abstände) | Abstände binden, Set-Description, Resizer default aus + Scrollbar sm; Kommentare Icon expand_more / Icon-Logik; Doku ohne Behavior/Guidelines | ½ Tag |
| Toolbar (desktop + Items) | 45 (Abstände 19, Strichstärke 2, Farb-Overrides an Icons 24) | Icons auf `.Icon-alternative`-Roles statt Umfärben (Entscheid 10.9. «Icon colors übernehmen»), Abstände, Descriptions; Toolbar mobile hat keine Komponente; Doku ohne Variants | ½–1 Tag |
| Slider (Basic, Range, Indicator, Track) | 284 (Abstände 238, Altvariablen 18, Strich 12, Radius 10, Text 4) | Abstände in Masse binden; Indicator/Track von Alt-/Basisvariablen auf Rollen (evtl. neue Slider-Rollen); Kommentare: min/max als Zahlen, Beschriftung Anfang/Ende (Karin) = Designänderung; Doku hat Lorem ipsum | 1–1,5 Tage |
| Time Picker | 9 (klein) | Bindungen, Shade → Rolle, 3 Set-Descriptions leer, Luca «Farbe gemäss neuer Definition», Help-Icon, Section «Testing» aufräumen | ½ Tag |

Summe ~4–5 Arbeitstage ≈ bei ~2 Tagen/Woche gut 2 Wochen (ohne Abstimmung/Kommentare, +~25 %). Doku-«Bilder» (24–34 Bildfüllungen je Seite) noch nicht einzeln geprüft — können Screenshots oder Bild-Assets sein.
