# Entwicklungs- und Evaluationsprotokoll

## Untersuchungsdesign
Design-Science-Research-Artefakt: wiederverwendbare Leitlinien / Prompts zur theoriegestützten Fragebogengenerierung mit einem LLM (hier: NotebookLM). Demonstrationsfall: individuelle KI-Readiness von Mitarbeitenden. Bewertet wird primär die **Nützlichkeit und Qualität des Leitlinienartefakts**, nicht die psychometrische Güte eines validierten Instruments.

## Iterationsverlauf
| Stufe | Demonstration | Beobachtete Probleme | Änderung am Artefakt |
|---|---|---|---|
| V1 | 20 Items, 6 Dimensionen | Konstrukte vermischt, teils pauschale Quellenbezüge, zu weitreichende Gütebehauptungen | V2: Definitionen, Quellenabgleich, Bewertungskriterien |
| V2 | 18 Items, 6 Dimensionen; Modell-Selbstevaluation 19/20 | KIR-03: Selbstwirksamkeit vs. Kompetenz; KIR-06: PEOU vs. Explainability; KIR-15: Unbehagen vs. Vertrauen; KIR-16/17: Datenschutzvertrauen vs. Kompetenz; KIR-18: Norm vs. Verhalten | V3: Einzelitem-Audit, Messbereichstaxonomie, Quellenmatrix |
| V3 | 18 Items, 6 Dimensionen; Modell-Selbstevaluation 18/18 mit 5/5 | KIR-02: Systemverständnis überlappt mit Explainability; KIR-05: Ergebnisprüfung ist nicht gleich Erklärbarkeit; KIR-16: erhebliche Bedeutungsverschiebung bei Quellenadaption; KIR-17/18: selbstberichtetes, nicht beobachtetes Verhalten | Als Limitation dokumentiert; unabhängige Prüfung erforderlich |

## Unabhängige qualitative Sichtung
Die hier dokumentierten Beanstandungen wurden im Rahmen der begleitenden fachlichen Prüfung der Ausgaben formuliert; es wurde **keine unabhängige Expertenstudie**, keine Befragung und keine psychometrische Validierung durchgeführt.

**V2:** Eine vorläufige heuristische Bewertung lautete 12/20 gegenüber 19/20 in der Modell-Selbstevaluation. Diese 12/20 sind **nicht** als reproduzierbar validierter Score zu verstehen; ein vollständig operationalisiertes, unabhängig angewandtes Bewertungsraster liegt nicht vor.

**V3:** Die automatische Vollpunkt-Selbstevaluation ist kein unabhängiger Qualitätsbeleg. Mindestens vier weiterhin diskussionswürdige Items wurden identifiziert (KIR-02, 05, 16, 17/18).

## Methodische Grenzen
- Wiederverwendbarkeit ist durch eine allgemeine Promptvorlage **angelegt**, aber noch nicht in einem zweiten Themenfeld demonstriert.
- Ein Originalitem aus einem anderen Konstrukt ist **kein direkter Validierungsbeleg** für das adaptierte Zielitem.
- Quellenstatus „quellengeprüft“ in NotebookLM-Ausgaben wurde **nicht für sämtliche Zeilen unabhängig verifiziert**.
- Keine Testpersonen, keine Interrater-Reliabilität, keine EFA/CFA, keine Reliabilitäts- oder Validitätskennzahlen.
- Versionsvergleiche beruhen auf unterschiedlichen Promptanweisungen im gleichen Anwendungsfall; Verbesserungen sind daher qualitativ beschrieben, nicht kausal isoliert.

## Nächste sinnvolle Evaluation
1. Zwei unabhängige Beurteilende bewerten Item-Konstrukt-Passung und Quellenbelege mit vorher festgelegtem Raster.
2. Zweiter Transferfall mit anderem Zielkonstrukt; dokumentieren, ob die generische Vorlage ohne strukturelle Änderungen funktioniert.
3. Kognitiver Pretest mit Zielpersonen; erst danach ggf. empirische Pilotierung.
