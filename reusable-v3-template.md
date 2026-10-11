# Wiederverwendbare Prompt-Vorlage (aus V3 abgeleitet)

**Status:** Redaktionell aufbereitete, themenunabhängige Nutzungsvorlage; **nicht** separat mit NotebookLM getestet. Sie ergänzt, ersetzt aber nicht die originale V3-Ausgabe.

## Parameter vor dem Start ausfüllen
- Untersuchungsgegenstand / Zielkonstrukt: `[THEMA]`
- Zielgruppe und Kontext: `[ZIELGRUPPE / KONTEXT]`
- Sprache: `[SPRACHE]`
- Umfang: `[ITEMZAHL]`
- Antwortformate: `[SKALA(N)]`
- Verfügbare Literatur / Itemdatenbank: `[QUELLENLISTE]`
- Abgrenzungen: `[NICHT ZU MESSENDE KONSTRUKTE]`

## Arbeitsauftrag
Entwickle anhand **ausschließlich** der bereitgestellten Quellen einen wissenschaftlich begründeten Fragebogen zu `[THEMA]` für `[ZIELGRUPPE / KONTEXT]`.

1. Definiere das Zielkonstrukt und benachbarte, auszuschließende Konstrukte. Kennzeichne konzeptionelle Entscheidungen als solche.
2. Extrahiere Konstrukte und **wortgetreue** Items samt Quelle, Fundstelle und ursprünglicher Konstruktzuordnung. Ist ein Originalitem nicht nachweisbar, notiere „nicht nachgewiesen“; erfinde keines.
3. Leite Zielitems ab. Unterscheide unveränderte Übernahme, Übersetzung, Adaption und Neuentwicklung. Begründe jeden Konstruktwechsel und jede wesentliche Inhaltsänderung.
4. Unterscheide Selbstauskunft, objektiv getestete Kompetenz, Einstellung, Absicht und selbstberichtetes bzw. beobachtetes Verhalten. Eine Selbstauskunft ist kein objektiver Leistungstest.
5. Prüfe jedes Item einzeln auf Konstruktpassung, Messbereich, Quellenechtheit, inhaltliche Eindimensionalität und Antwortformat/Polung. Dokumentiere **Pass / Revision / Reject** mit Begründung und überarbeiteter Fassung.
6. Gib Fragebogen, Quellenmatrix, Auditmatrix, ungelöste Probleme und Hinweise zur erforderlichen externen und empirischen Prüfung aus.
7. Stelle niemals fest, dass ein Fragebogen validiert, reliabel oder „100 % fehlerfrei“ sei, nur weil ein Sprachmodell ihn selbst positiv bewertet hat.

**Ausgabe:** Konstruktübersicht, `[ITEMZAHL]` Items in `[SPRACHE]`, Antwortskalen, Quellen- und Adaptionsmatrix, Einzelitem-Audit, Grenzen und nächste Prüfschritte.
