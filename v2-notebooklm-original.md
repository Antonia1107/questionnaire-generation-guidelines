# Leitlinienmodell V2 – Überarbeiteter Standard zur automatisierten, theoriegestützten Fragebogengenerierung

---

## 1. Überarbeitungsprozess & Gegenüberstellung (V1 vs. V2)

Die Evaluation der ersten Fragebogeniteration hat gezeigt, dass V1 zwar theoretisch fundierte Konstrukte identifiziert hat, jedoch bei der **Konstrukttrennung**, der **Quellentreue** und der **Grenzziehung der KI-Readiness** methodische Schwächen aufwies. Leitlinienmodell V2 korrigiert diese Mängel systematisch.

| Dimension / Regel | Leitlinienmodell V1 (Status Quo) | Leitlinienmodell V2 (Überarbeitet) | Begründung & Wissenschaftlicher Mehrwert |
| :--- | :--- | :--- | :--- |
| **Konstrukttrennung** | Zusammenfassung verwandter Konstrukte (z. B. *Ability* und *Explainability* in ein Item-Set; *Usefulness* und *Task-Technology Fit* durchmischung). | Strikte Isolierung und eindimensionale Messung aller Subkonstrukte (*Ability*, *Explainability*, *PEOU*, *Self-Efficacy*, *Trust*, *TTF*). | Verhindert Multikollinearität und falsche Ladestrukturen in Faktoranalysen; sichert die Diskriminanzvalidität. |
| **Quellentreue & Item-Identifikation** | Freie Nachformulierung und summarische Quellenzuordnung ohne Überprüfung der tatsächlichen Item-Existenz im Datensatz. | Verpflichtender 1:1-Abgleich mit den Primärquellen (`Datensatz_v1.docx` und Papers). Transparente Angabe von Originaltext, Sprache und Konstrukt. Kennzeichnung ungeprüfter Formulierungen als „Neu entwickelt“. | Eliminierung von Halluzinationen oder fiktiven Validierungen; lückenlose Nachvollziehbarkeit der Items. |
| **Grenzziehung der KI-Readiness** | Vermischung von individuellen Fähigkeiten, Einstellungen, organisatorischen Rahmenbedingungen und Nutzungsabsichten in einem Gesamtwert. | Abgrenzung der *individuellen Disposition* (Fähigkeiten, Einstellungen, verantwortungsvoller Einsatz) von *Kontextfaktoren* (Org. Rahmenbedingungen, Task-Technology Fit) und *Verhaltensfolgen* (Nutzungsabsicht). | Erhöht die Inhaltsvalidität. Organisatorische Unterstützung ist eine Rahmenbedingung (*Facilitating Condition*), keine Eigenschaft der Person. |
| **Validitätsanspruch** | Pauschales Anführen von Theorien erweckte den Eindruck einer bereits nachgewiesenen empirischen Güte. | Strikte Dreiteilung: (1) Theoretische Fundierung, (2) Inhaltliche Plausibilität, (3) Empirische Validierung. Explizites Verbot von Reliabilitätsbehauptungen vor der Pilotierung. | Erfüllung wissenschaftlicher Standards der Testtheorie. Neu skalierte oder übersetzte Items verlieren ihre ursprüngliche empirische Validierung und müssen neu pilotiert werden. |
| **Itemqualität** | Akzeptanz von Kombi-Formulierungen (*Double-Barreled Questions*) und umgepolten Negativ-Items ohne Prüfprotokoll. | Verbot doppelter Fragestellungen; strikt eindimensionale, neutrale Formulierungen; systematische Qualitätsprüfung nach festem Raster. | Reduziert Messfehler und kognitive Überlastung der Befragten. |
| **Systematische Evaluation** | Qualitative Nachbetrachtung ohne quantifizierbare Metriken. | Einführung eines objektiven, kriteriengestützten Evaluationstrasters (Scores 1–5) für Quellenbezug, Theoriekonsistenz, Itemqualität und Anwendbarkeit. | Standardisierte Qualitätsmessung für zukünftige Fragebögen und automatisierte Iterationen. |

---

## 2. Das überarbeitete Leitlinienmodell V2

Das Leitlinienmodell V2 dient als allgemeingültiger, wiederverwendbarer Standard für die theoriegestützte Fragebogenentwicklung im wissenschaftlichen Kontext.

---

### Modul A: Strikte Konstrukttrennung & Definitionen

Um begriffliche Überschneidungen zu vermeiden, werden die theoretischen Konstrukte anhand der Primärliteratur scharf abgegrenzt:

```
                                  ┌────────────────────────────────────────────────────────┐
                                  │            Individuelle KI-Readiness (Person)          │
                                  ├───────────────────────────┬────────────────────────────┤
                                  │   Kognitiv & Fähigkeit    │   Affektiv & Einstellung   │
                                  │  • Ability                │  • Attitude                │
                                  │  • Explainability         │  • Fear / Uncanniness      │
                                  │  • Self-Efficacy          │  • Responsible AI Use      │
                                  └─────────────┬─────────────┴─────────────┬──────────────┘
                                                │                           │
                                                ▼                           ▼
┌──────────────────────────────┐  ┌──────────────────────────────────────────┐  ┌──────────────────────────────┐
│  Kontext & Rahmenbedingungen │  │       Aufgaben-Kontext (Passung)         │  │     Verhaltensentscheidung   │
├──────────────────────────────┤  ├──────────────────────────────────────────┤  ├──────────────────────────────┤
│ • Facilitating Conditions    │─►│ Task-Technology Fit (TTF)                │─►│ Behavioral Intention to Use  │
│ • Perceived Norms / Culture  │  │ (McGrath Task Circumplex x AI Affordance)│  │ (Zielkonstrukt/Folge)        │
└──────────────────────────────┘  └──────────────────────────────────────────┘  └──────────────────────────────┘
```

1. **Ability (Technologische Fähigkeit/Kompetenz)**:  
   *Definition:* Die wahrgenommene oder objektive Fähigkeit einer Person, eine Technologie effektiv zu bedienen und zu nutzen (Teil der Vertrauensdimension nach Mayer et al., 1995).  
   *Abgrenzung:* Unterscheidet sich von *Explainability* (Verstehen des Systems) dadurch, dass es auf die eigene Handlungskompentenz fokussiert.
2. **Explainability (Erklärbarkeit/Transparenz)**:  
   *Definition:* Der Grad, in dem ein Nutzer die internen Mechanismen, Logiken und die Zustandekommen von Ergebnissen eines KI-Systems nachvollziehen und auf Korrektheit prüfen kann.  
   *Abgrenzung:* Betrifft die Eigenschaften des KI-Systems und das Systemverständnis, nicht die allgemeine Handhabungsfreundlichkeit.
3. **Perceived Ease of Use (PEOU / Wahrgenommene Benutzerfreundlichkeit)**:  
   *Definition:* Der Grad, in dem eine Person glaubt, dass die Nutzung eines Systems frei von körperlicher oder geistiger Anstrengung sein wird (TAM/UTAUT2).  
   *Abgrenzung:* Misst den erwarteten Bedienaufwand, unabhängig davon, ob die mathematisch-logische Funktionsweise (*Explainability*) verstanden wird.
4. **Self-Efficacy (Selbstwirksamkeitserwartung)**:  
   *Definition:* Die subjektive Gewissheit einer Person, auch schwierige oder neuartige Aufgaben im Umgang mit der Technologie durch eigene Kompetenz erfolgreich bewältigen zu können (Bandura, 1986).  
   *Abgrenzung:* Misst das Zutrauen in die eigene Lern- und Anpassungsfähigkeit, wohingegen *Ability* den Ist-Zustand vorhandener Fähigkeiten beschreibt.
5. **Trust (Vertrauen in die Technologie)**:  
   *Definition:* Die Bereitschaft eines Nutzers, sich gegenüber den Handlungen des KI-Systems vulnerabel zu zeigen, basierend auf der Erwartung, dass das System fähig (*Ability*), wohlwollend (*Benevolence*) und integerr/datenschutzkonform (*Integrity*) agiert.  
   *Abgrenzung:* Vertrauen ist eine affektiv-kognitive Haltung/Einstellung gegenüber dem System, keine Fähigkeit des Nutzers.
6. **Task-Technology Fit (TTF / Aufgaben-Technologie-Passung)**:  
   *Definition:* Der Grad, in dem die Funktionalitäten einer Technologie exakt zu den Anforderungen einer spezifischen Aufgabe (z. B. nach McGrath’s Task Circumplex: Planung, Kreativität, Urteil) passen.  
   *Abgrenzung:* Beschreibt ein relationales Konstrukt zwischen Aufgabe und Werkzeug, nicht eine Eigenschaft der Person.

---

### Modul B: Systematische Abgrenzung der KI-Readiness

Die **Individuelle KI-Readiness** beschreibt die persönliche Bereitschaft und Befähigung einer Einzelperson, KI-Technologien sinnvoll, kompetent und ethisch verantwortungsvoll in das eigene Handeln zu integrieren.

#### 1. Zur individuellen KI-Readiness gehörende Dimensionen:
*   **Kognitive Bereitschaft & Kompetenz**: Vorhandenes Wissen, *Self-Efficacy* und die Fähigkeit zur kritischen Ergebnisbewertung (*Explainability Assessment*).
*   **Affektive Bereitschaft & Einstellung**: Offenheit gegenüber technologischer Veränderung, Abwesenheit irrationaler Ängste (*Uncanniness/Fear*).
*   **Verantwortungsvoller KI-Einsatz (Responsible Use & Accountability)**: Bewusstsein für Datenschutz, Urheberrecht, Halluzinationen und ethische Risiken bei der Arbeitsausführung.

#### 2. Auszuschließende bzw. separat zu modellierende Dimensionen:
*   **Organisatorische Rahmenbedingungen (*Facilitating Conditions / Org Support*)**: IT-Infrastruktur, Schulungsangebote oder Vorgaben der Geschäftsführung sind **Kontextfaktoren der Organisation**, nicht der Person.
*   **Nutzungsabsicht (*Behavioral Intention*)**: Die Absicht, KI zu nutzen, ist das **Ergebnis/Zielkonstrukt**, das durch die KI-Readiness erklärt werden soll.
*   **Aufgaben-Passung (*Task-Technology Fit*)**: Ein schlechter Fit liegt an der Aufgabenstellung oder der Software, nicht an mangelnder Readiness der Person.

---

### Modul C: Rules of Engagement – Quellentreue & Itemgenerierung

Jedes Item muss nach folgendem Protokoll dokumentiert und hergeleitet werden:

1. **Strikte Quellenvalidierung**: Das zugrunde liegende Originalitem muss wörtlich in den Quellen (`Datensatz_v1.docx` oder den Literaturangaben der Papers) existieren.
2. **Standardisierte Protokollierung**:
   *   `Item-ID`: Eindeutiger Identifikator.
   *   `Zielkonstrukt`: Exakt ein theoretisches Konstrukt (keine Kombi-Konstrukte).
   *   `Formulierung (Deutsch)`: Neutrales, klares Zielitem.
   *   `Primärquelle`: Genaue Angabe der Quelle [z. B. Paper 4 / Datensatz_v1 Q4].
   *   `Originalitem & Originalkonstrukt`: Exakter Wortlaut und Konstruktbezeichnung der Quelle.
   *   `Übertragungsart`:
       *   *Unverändert* (1:1 übernommen)
       *   *Übersetzt* (Sprachübertragung ohne inhaltliche Änderung)
       *   *Adaptiert* (Inhaltliche Kontextanpassung, z. B. ChatGPT \\(\rightarrow\\) Allgemeine KI)
       *   *Neu entwickelt* (Falls kein Originalitem existiert – **offen zu deklarieren!**)
   *   `Begründung der Adaption`: Fachliche Relevanz der Modifikation.
3. **Qualitätsregeln für Item-Formulierungen**:
   *   **Keine Doppelmodellierungen (*Double-Barreled Items*)**: Verbot von Verknüpfungen wie „...ist leicht verständlich *und* nützlich“.
   *   **Eindimensionalität**: Jedes Item misst exakt einen Sachverhalt.
   *   **Polarität**: Vermeidung doppelter Verneinungen.

---

### Modul D: Differenziertes Validitäts- & Reliabilitätsverständnis

Das Leitlinienmodell V2 unterscheidet strikt zwischen drei Stufen der wissenschaftlichen Absicherung:

```
┌────────────────────────────────────────────────────────────────────────┐
│ Stufe 1: Theoretische Fundierung (Theory-Grounded)                    │
│ Deduktive Herleitung von Konstrukten aus Literatur & Modellen         │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│ Stufe 2: Inhaltliche Plausibilität & Inhaltsvalidität (Content-Valid)  │
│ Expertensichtung, kognitive Pre-Tests (Think-Aloud Protocols)          │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │ (Erst nach empirischer Datenerhebung!)
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│ Stufe 3: Empirische Validierung & Reliabilität (Empirically Validated)  │
│ Faktorenanalysen (EFA/CFA), Cronbachs Alpha, CR, AVE, HTMT-Kriterium   │
└────────────────────────────────────────────────────────────────────────┘
```

*   **Regel zur Gütebehauptung**: Für neu generierte, adaptierte oder übersetzte Items darf **keine empirische Validität oder Reliabilität** behauptet werden. Die Veröffentlichung eines Fragebogens ohne Datenerhebung stellt lediglich ein *theoretisch fundiertes Erhebungsinstrument (Hypothese)* dar.

---

## 3. Evaluationsschema für zukünftige Fragebögen

Um generierte Fragebögen objektiv zu bewerten, wird folgendes metrisches Bewertungsschema etabliert. Jeder Fragebogen muss in vier Hauptkategorien auditiert werden (Bewertung von 1 = ungenügend bis 5 = exzellent):

```
                                 GESAMT-EVALUATIONSSCORE
                                        (Max. 20 Pkt.)
                                              │
         ┌──────────────────┬─────────────────┴──────────────────┬──────────────────┐
         ▼                  ▼                                    ▼                  ▼
┌──────────────────┐┌──────────────────┐              ┌──────────────────┐┌──────────────────┐
│ 1. Quellentreue  ││ 2. Theorie-      │              │ 3. Itemqualität  ││ 4. Anwendbarkeit │
│    & Nachweis    ││    konsistenz    │              │    & Methodik    ││    & Kontext     │
│    (Max. 5 Pkt.) ││    (Max. 5 Pkt.) │              │    (Max. 5 Pkt.) ││    (Max. 5 Pkt.) │
└──────────────────┘└──────────────────┘              └──────────────────┘└──────────────────┘
```

### Audit-Raster

#### 1. Quellentreue & Nachweisbarkeit (Source Traceability)
*   **5 Punkte**: Jedes Item ist lückenlos auf ein nachweisbares Originalitem aus den Quellen zurückführbar. Abweichungen/Adaptionen sind vollständig begründet.
*   **3 Punkte**: Quellen vorhanden, aber teilweise ungenaue Zuordnung oder fehlende Vergleiche zum Originalwortlaut.
*   **1 Punkt**: Fiktive Quellen oder Erfindung nicht existierender Originalitems.

#### 2. Theoretische Konsistenz & Konstrukttrennung (Construct Purity)
*   **5 Punkte**: Strikte Eindimensionalität aller Skalen. Keine Durchmischung von *Ability*, *Explainability*, *PEOU*, *Self-Efficacy* oder *TTF*.
*   **3 Punkte**: Leichte begriffliche Überschneidungen zwischen benachbarten Konstrukten.
*   **1 Punkt**: Schwere Konstruktkonfusion (z. B. Verschmelzung von Nutzungsabsicht und Fähigkeit).

#### 3. Itemqualität & Sprachliche Präzision (Item Quality)
*   **5 Punkte**: Keine doppelten Fragestellungen (*Double-Barreled*), durchgängig neutrale, verständliche Formulierungen, einheitliche Antwortskalen.
*   **3 Punkte**: Vereinsamte unklare Begriffe oder vereinzelt mehrdeutige Satzstrukturen.
*   **1 Punkt**: Suggestivfragen, verschachtelte Satzkonstruktionen oder uneinheitliche Antwortskalen.

#### 4. Anwendbarkeit & Kontextuelle Eignung (Methodological Rigor)
*   **5 Punkte**: Klare Abgrenzung von individueller Disposition, Org-Kontext und Verhaltenskonsequenzen. Zielgruppengerechte Tonalität. Strikte Trennung von theoretischer Fundierung und empirischer Validierung.
*   **3 Punkte**: Konzeptionelle Unschärfen bei der Zielgruppenansprache oder unklare Grenzziehung der KI-Readiness.
*   **1 Punkt**: Behauptung empirischer Validität ohne vorliegende Daten; ungeeignetes Antwortformat.

---

### Anwendungstests / Scoring-Formel

\\[\text{Qualitäts-Score (\%)} = \left( \frac{\sum \text{Erreichte Punkte in Kat. 1--4}}{20} \right) \times 100\\]

*   **\\(\ge 90\%\\) (Exzellent)**: Freigabe für Pre-Test und Pilotierung.
*   **\\(70--89\%\\) (Überarbeitungsbedürftig)**: Nachbesserung bei Konstrukttrennung oder Quellenbelegen erforderlich.
*   **\\(< 70\%\\) (Mangelhaft)**: Ablehnung; Neugenerierung nach Leitlinienmodell V2 erforderlich.

---

Dieses Leitlinienmodell V2 steht nun als **systematische, universell einsetzbare Methodik** bereit, um in künftigen Iterationen theoriegestützte Fragebögen für beliebige wissenschaftliche Fragestellungen zu entwickeln.