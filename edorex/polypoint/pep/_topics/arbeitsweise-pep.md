---
name: Selinas Arbeitsweise im PEP-Mandat
description: Selinas persönliche Regeln im PEP-Mandat - Priorität, Benennung entscheidet sie, Wert sichtbar machen, Doku-Texte nur im Chat, Mandat bis Dezember.
---

# Arbeitsweise PEP (Selina)

Aus dem PEP-Index ausgelagert am 2026-11-26 (Index-Health M009), Wortlaut unverändert.

## Arbeitsweise

- **Priorität:** zuerst fertig machen, was in der letzten Session nicht ganz fertig wurde (jüngster Close-Eintrag), **danach** die Prio-Liste (Prio-Seite in Figma).
- **🏷️ BENENNUNG VON VARIABLEN/TOKENS = SELINAS ENTSCHEID (Selina 22.10.2026):** Namensfragen (z. B. Umbenennung einer Variablen-Familie wie `outline-<status>-variant-dark`) gehören in Selinas Verantwortung, sie entscheidet sie selbst. **Nicht als Webex-Frage ans Team vorschlagen.** Die Regel «erst kommunizieren, dann umbauen» gilt für neues Verhalten und neue Definitionen, die das Team betreffen, nicht für Benennungen im Design-System. Bei Namensfragen: Optionen + Meinung an Selina, sie entscheidet. Zitat: «Solche Fragen kann ich in Webex nicht wirklich stellen. So wie ich das sehe ist das meine Verantwortung und ich entscheide das.»
- **💎 WERT SICHTBAR MACHEN (Selina 27.10.2026):** Selina ist im Mandat (bis Dezember) und muss ihren Beitrag zeigen können. In Entwürfen ihre Arbeit nie als «Ausarbeiten» fremder Entwürfe formulieren (kein «ich verdrahte dann noch …»), sondern als das, was sie ist: Prüfung und Definition von «Ready» nach DS-Standard. Befunde an Komponenten anderer sachlich benennen, ohne Personen blosszustellen (Carla nie angreifen). **Ownership respektieren:** Wer eine Komponente begonnen hat (z. B. Luca: Rating_v2, Name im Section-Titel), setzt die Befunde selbst um; Selina prüft und gibt frei, sie übernimmt nicht («Ich will ihm da nichts wegnehmen»). **Ausnahme/Update 17.11.2026: Rating_v2 stellt Selina selbst fertig** (Prio-Seite: «v1 Rating (Luca & Selina)», Luca hat keine Zeit) — Zuständigkeit immer an der Prio-Seite nachlesen; Meldungen dazu als Stand formulieren, **Luca keinen Auftrag geben**.
- **DOC-WORKFLOW RULE (Selina 2026-07-25): doc texts are delivered in CHAT ONLY — never written as md files.** Selina inserts docs into Figma immediately; extra files on her machine are unwanted. Only exception: if she explicitly defers insertion to a later day, park the text in a topic file (chat is session-bound). Status/decisions still go to ai-collab cells as usual — just not doc full texts.
- **Mandat Selina endet im DEZEMBER 2026** → sie macht dann einen Recap, was offen ist. Alles, was «für später» zurückgestellt wird, in [_topics/dezember-recap-offen.md](_topics/dezember-recap-offen.md) eintragen; ab Mitte November aktiv daran erinnern.

## Ergänzung (war doppelt zu work-style/figma-orte-per-name)

- **COMMUNICATION RULE (Selina 2026-08-18): NEVER hand Selina bare Figma node IDs — they are not searchable in Figma.** Always give either a **clickable deep link** or the **exact component/page name** (ideally both). Link pattern: `https://www.figma.com/design/ivVuByHDDqZe9QjPIuuuMC/00-PDX--Polypoint-Design-Experience--?node-id=<NODE>` with the node id written with a **dash** instead of the colon (`71534:15520` → `71534-15520`). Node IDs may still be used internally for tool calls and may accompany a link as a suffix, but never stand alone in an answer or a list Selina has to act on.
