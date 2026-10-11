# Theory-Grounded Questionnaire Generation Guidelines

Ein dokumentiertes Design-Science-Research-Projekt zur Entwicklung wiederverwendbarer Leitlinien für die KI-gestützte Erstellung wissenschaftlich begründeter Fragebogenentwürfe. Demonstriert mit Google NotebookLM am Beispiel **individuelle KI-Readiness von Mitarbeitenden**.

## Forschungsziel
Wie lassen sich theoriegestützte Leitlinien für Large Language Models gestalten und iterativ evaluieren, um die nachvollziehbare Generierung wissenschaftlich begründeter Fragebogenentwürfe zu unterstützen?

## Artefakt und Nutzung
Das eigentliche Artefakt ist **ein Leitlinien-/Prompt-Workflow**, nicht der generierte KI-Readiness-Fragebogen. Die ursprüngliche V3-Leitlinienausgabe steht in `guidelines/v3-notebooklm-original.md`. Für die praktische, themenunabhängige Nutzung gibt es `guidelines/reusable-v3-template.md` (redaktionelle Übertragung; noch nicht separat getestet).

1. Neues Notebook in NotebookLM anlegen.
2. Relevante Forschungsliteratur und einen rechtmäßig nutzbaren Fragebogendatensatz hochladen.
3. Platzhalter in `guidelines/reusable-v3-template.md` ausfüllen und den Prompt ausführen.
4. Quellenangaben **außerhalb des LLM** mit den Originaldokumenten prüfen.
5. Einzelitems unabhängig auf Konstruktpassung und sprachliche Qualität prüfen; überarbeiten, ggf. kognitiv pretesten.
6. Keine Aussagen zu empirischer Validität oder Reliabilität ohne Datenerhebung.

## Repository-Inhalt
- `guidelines/v1-reconstructed.md` – V1 **rekonstruiert**, nicht Originalexport.
- `guidelines/v2-notebooklm-original.md` – unveränderte V2-Ausgabe.
- `guidelines/v3-notebooklm-original.md` – unveränderte V3-Ausgabe.
- `guidelines/v3-final-application-prompt.md` – dokumentierter V3-Anwendungsprompt mit methodischen Präzisierungen.
- `guidelines/reusable-v3-template.md` – allgemeine Nutzungsvorlage (redaktionell erstellt).
- `demonstrations/iteration-{1,2,3}-notebooklm.md` – originale NotebookLM-Fragebogenausgaben.
- `evaluation/evaluation.md` – Iterationen, kritische Sichtung und Grenzen.
- `sources/sources.md` – Materialien und Referenzen.

## Forschungsprozess
Orientierung an Design Science Research (Peffers et al.): Problemidentifikation, Zieldefinition, Design/Entwicklung, Demonstration, Evaluation und Kommunikation. Drei dokumentierte Entwicklungsstufen V1–V3 mit Demonstration im gleichen Anwendungsfall.

## Transparenz und Limitationen
Die NotebookLM-Ausgaben sind als **LLM-generierte Forschungsartefakte** abgelegt. Sie enthalten auch fragliche Konstruktzuordnungen und teils überzogene Selbstevaluationen. Ihre Aufnahme ist **keine wissenschaftliche Billigung**. Ein unabhängiger Expertenreview und eine psychometrische Validierung haben bislang nicht stattgefunden. Die wiederverwendbare Vorlage wurde noch nicht in einem zweiten Themenfeld getestet.

## Veröffentlichungshinweise
Keine urheberrechtlich geschützten Volltexte, Fragebogendatenbanken oder Lehrmaterialien ohne Erlaubnis hochladen. Vor Veröffentlichung Namen, personenbezogene Daten und Projektvorgaben prüfen. Ein GitHub-Repository muss durch die Projektverantwortlichen selbst angelegt und hochgeladen werden.
