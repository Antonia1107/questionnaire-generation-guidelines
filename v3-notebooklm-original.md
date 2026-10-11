# Leitlinienmodell V3 – Allgemeingültiger Standard zur automatisierten, theoriegestützten Fragebogengenerierung

---

## 1. Präambel & Zweck von Leitlinienmodell V3

Das **Leitlinienmodell V3** stellt einen domänen- und themenunabhängigen Qualitätsstandard dar, um wissenschaftliche Fragebögen aus bestehenden empirischen Datensätzen und theoretischen Modellen automatisiert abzuleiten. 

Während V2 den Fokus auf die grobe Abgrenzung von Konstrukten und die Quellentreue legte, schließt **V3** feingliedrige methodische Lücken auf Item-Ebene. Insbesondere adressiert V3 die Gefahr von **semantischen Fehlzuordnungen** (z. B. Verwechslung von Selbstwirksamkeit und Kompetenz, oder Einstellung und Verhalten) sowie **formalen Messfehlern**.

---

## 2. Kernmodule des Leitlinienmodells V3

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                                LEITLINIENMODELL V3                                     │
├────────────────────────────────────────────────────────────────────────────────────────┤
│ Modul 1: Taxonomische & Semantische Konstruktprüfung                                   │
│ • Abgrenzung von Selbsteinschätzung, Kompetenz, Einstellung, Absicht & Verhalten       │
│ • Semantischer 1:1-Abgleich zwischen Item-Aussage und theoretischer Konstruktdefinition│
├────────────────────────────────────────────────────────────────────────────────────────┤
│ Modul 2: Quellenprüfmatrix & Adaptionsprotokoll                                         │
│ • Verpflichtender Beleg von Originalitem, Originalkonstrukt und Zielkonstrukt          │
│ • Lückenlose wissenschaftliche Begründung aller sprachlichen & inhaltlichen Adaptionen │
├────────────────────────────────────────────────────────────────────────────────────────┤
│ Modul 3: Formal-linguistische Item-Qualitätsprüfung                                    │
│ • Ausschluss von Double-Barreled Questions, Mehrdeutigkeiten & normativen Fallstricken │
│ • Prüfung der Polungsrichtung und Vermeidung von Acquiescence Bias                     │
├────────────────────────────────────────────────────────────────────────────────────────┤
│ Modul 4: Item-basiertes Einzel-Evaluations- & Freigabeprotokoll                        │
│ • Prüfung jedes einzelnen Items nach Binär-Kriterien (Pass / Revision / Reject)        │
│ • Verbot pauschaler Qualitätsnoten – Freigabe nur bei 100 % Fehlerfreiheit auf Item-Ebene│
└────────────────────────────────────────────────────────────────────────────────────────┘
```

---

### Modul 1: Taxonomische & Semantische Konstruktprüfung

Jedes Item muss vor seiner vorläufigen Aufnahme einer **taxonomischen Einordnung** und einer **semantischen Kongruenzprüfung** unterzogen werden.

#### A. Verpflichtende Messbereichs-Taxonomie
Jeder Fragebogenindikator muss exakt einer der folgenden fünf epistemischen Kategorien zugeordnet werden:

1. **Selbsteinschätzung (*Self-Assessment / Perceived Trait*)**: Misst die subjektive Wahrnehmung der eigenen Eigenschaft, Mühelosigkeit oder Überzeugung (z. B. *"Ich finde die Bedienung einfach"*).
2. **Tatsächliche Kompetenz (*Actual / Tested Competence*)**: Misst objektiv nachprüfbares Wissen oder deklaratorische Fähigkeiten (z. B. *"Ich kann den Begriff Overfitting korrekterweise erklären"*).  
   *Regel:* Fragen, die mit *"Ich kann..."* oder *"Ich weiß..."* beginnen, sind streng daraufhin zu prüfen, ob sie echtes Können oder nur eine Überzeugung (*Self-Efficacy*) erfassen.
3. **Einstellung & Affekt (*Attitude & Affect*)**: Erfasst Gefühle, Grundhaltungen, Bewertungstendenzen oder Vertrauen gegenüber einem Objekt (z. B. *"Ich empfinde das System als verlässlich"*).
4. **Verhaltensabsicht (*Behavioral Intention*)**: Erfasst die kognitiv formulierte Bereitschaft oder Absicht, in der Zukunft ein bestimmtes Verhalten zu zeigen (z. B. *"Ich beabsichtige, das Tool nächste Woche zu nutzen"*).
5. **Tatsächliches Verhalten (*Actual / Reported Behavior*)**: Misst rückblickend oder aktuell realisiertes Handeln (z. B. *"Ich habe im letzten Monat täglich Berichte mit der KI generiert"*).

#### B. Semantischer 1:1-Match
Es ist eine **logisch-semantische Prüfung** durchzuführen:
\\[\text{Prüffrage: } \text{Bringt die sprachliche Formulierung des Items } \mathbf{exakt} \text{ den Kern der theoretischen Konstruktdefinition zum Ausdruck?}\\]
Wenn das Item eine normative Erwartung (*"Man sollte..."*), eine Affektäußerung (*"Ich fühle..."*) oder eine Handlungsschranke (*"Ich habe Zeit..."*) enthält, darf es **nicht** einem rein kognitiven Fähigkeits- oder Vertrauenskonstrukt zugeordnet werden.

---

### Modul 2: Standardisierte Quellenprüfmatrix & Adaptionsregeln

Zur Sicherstellung der Replikationsfähigkeit und Transparenz ist für jedes Item die folgende **5-spaltige Quellenprüfmatrix** auszufüllen:

| Spalte | Bezeichnung | Inhaltliche Anforderung |
| :--- | :--- | :--- |
| **1** | `Item-ID & Zielkonstrukt` | Eindeutige Kennung sowie das exakte theoretische Zielkonstrukt (eindimensional). |
| **2** | `Originalitem (Wortlaut)` | Exakter Wortlaut des Items aus der Primärquelle in Originalsprache (Deutsch/Englisch). |
| **3** | `Originalkonstrukt & Quelle` | Bezeichnung des Konstrukts in der Ursprungsstudie sowie exakte Quellenangabe. |
| **4** | `Formulierung (V3-Zielitem)` | Deutschsprachige, überarbeitete Itemformulierung. |
| **5** | `Übertragungsart & Begründung` | Deklaration (*Unverändert*, *Übersetzt*, *Adaptiert*, *Neu entwickelt*) mit detaillierter wissenschaftlicher Begründung der Anpassung. |

#### Regeln für Übertragungen:
* **Neu entwickelte Items** müssen als solche gekennzeichnet werden und dürfen **maximal 20 %** des Gesamtinstrumentariums ausmachen.
* **Übersetzungen & Adaptionen** müssen begründen, warum die semantische Valenz des Konstrukts durch den Sprach- oder Kontextwechsel nicht verzerrt wird.

---

### Modul 3: Formal-linguistische Item-Qualitätsprüfung

Jedes Item muss vier strikte Qualitätsfilter passieren:

1. **Ausschluss von *Double-Barreled Questions***:  
   *Fehler:* Koppelung zweier Untersuchungsgegenstände durch „und“, „oder“ sowie mehrgliedrige Prädikate (z. B. *"verstehen und bedienen"*).  
   *Regel:* Jedes Item darf nur **ein** Verb und **ein** direktes Objekt enthalten.
2. **Klarheit & Ambiguitätsfreiheit**:  
   *Fehler:* Verwendung vager Quantifikatoren (z. B. *"oft"*, *"gute Ergebnisse"*) oder mehrdeutiger Fachbegriffe ohne Kontextualisierung.
3. **Prüfung der Polung & *Acquiescence Bias***:  
   *Fehler:* Unreflektierte Umkehrung von Negativ-Items (z. B. von *"unheimlich"* zu *"nicht beängstigend"*), die zu doppelten Verneinungen oder verfälschten Antworthäufigkeiten führt.  
   *Regel:* Negativ gepolte Originalitems sind bevorzugt in ihrer ursprünglichen Richtung zu belassen und bei der Auswertung zu rekodieren, anstatt sie künstlich ins Positiv zu verdrehen.
4. **Vermeidung normativer Verwechselung**:  
   *Fehler:* Umformulierung von Soll-Bestimmungen oder Compliance-Regeln (z. B. *"Sicherheitskontrolle ist nötig"*) zu Indikatoren für persönliches Handeln oder Vertrauen.

---

### Modul 4: Item-basiertes Einzel-Evaluations- & Freigabeprotokoll

Anstelle einer pauschalen Gesamtbewertung führt Leitlinienmodell V3 eine **Item-für-Item-Auditierung** ein.

#### A. Prüfkriterien je Item (Binärprüfung: 1 = Erfüllt, 0 = Nicht erfüllt)
Jedes einzelne Item \\(i\\) wird anhand von 5 harten Kriterien bewertet:

* \\(K_1\\) **Konstruktkongruenz**: Passt die Item-Semantik 1:1 zur theoretischen Definition des Konstrukts?
* \\(K_2\\) **Taxonomische Reinheit**: Ist das Item eindeutig als Selbsteinschätzung, Kompetenz, Einstellung, Absicht oder Verhalten klassifiziert?
* \\(K_3\\) **Quellenechtheit**: Ist das Originalitem nachweisbar oder korrekt als neu entwickelt ausgewiesen?
* \\(K_4\\) **Sprachliche Single-Intentionalität**: Frei von doppelten Fragestellungen, Verschachtelungen und Ambiguitäten?
* \\(K_5\\) **Skalen- & Polungskonsistenz**: Fügt sich das Item nahtlos in die einheitliche 5-stufige Antwortskala ein?

#### B. Entscheidungsregel & Freigabe-Algorithmus

\\[\text{Item-Score } S_i = \sum_{j=1}^{5} K_{j,i}\\]

* **\\(S_i = 5\\) (Pass)**: Item ist ohne Änderungen freigegeben.
* **\\(S_i = 3\\) oder \\(4\\) (Revision)**: Das Item weist methodische Mängel auf und **muss überarbeitet werden**, bevor der Fragebogen zusammengestellt werden kann.
* **\\(S_i \le 2\\) (Reject)**: Das Item ist verworfen und muss durch ein passenderes Ersatzitem ersetzt werden.

> **Verpflichtende Freigabebedingung für den Gesamtfreigabestatus:**  
> Ein Fragebogen erhält die Freigabe erst dann, wenn **100 % aller enthaltenen Items** einen Einzel-Score von \\(S_i = 5\\) erreichen. Pauschale Prozentwerte oder Noten für den Gesamtfragebogen sind unzulässig, solange auch nur ein einziges fehlerhaftes Item enthalten ist.

---

## 3. Unterschiede zwischen V2 und V3 sowie wissenschaftliche Begründung

Die Überarbeitung von V2 zu V3 basiert auf der wissenschaftlichen Aufarbeitung konkreter Fehleinschätzungen bei der Itemformulierung. Die nachfolgende Tabelle dokumentiert die Regeländerungen und deren testtheoretische Begründung:

| Dimension / Aspekt | Leitlinienmodell V2 | Leitlinienmodell V3 | Wissenschaftliche Begründung der Änderung |
| :--- | :--- | :--- | :--- |
| **Prüfebene** | Globale Bewertung des Gesamtfaktorenmodells und pauschale Score-Vergabe. | **Item-basierte Einzelprüfung** mit harten K.o.-Kriterien je Indikator. | Verhindert, dass schlechte oder verfälschte Einzelitems durch eine hohe Gesamtnote kaschiert werden (Messfehlerminimierung). |
| **Taxonomische Differenzierung** | Grobe Unterteilung in Fähigkeiten, Einstellungen und Absichten. | **Fünfstufige Taxonomie**: Selbsteinschätzung vs. Tatsächliche Kompetenz vs. Einstellung vs. Absicht vs. Verhalten. | Vermeidung von Konstrukt-Validitätsbrüchen (z. B. Verwechslung von behauptetem Können und tatsächlicher Performanz). |
| **Konstrukttrennung bei Fähigkeiten & Selbstwirksamkeit** | Akzeptanz von Überzeugungs-Aussagen (*"Ich bin überzeugt, dass ich..."*) als Fähigkeitsindikator. | Strikte Abgrenzung: Überzeugungen = *Self-Efficacy*; deklaratives Wissen / Performanz = *Ability / Competence*. | Bandura (1986): Selbstwirksamkeit ist der Glaube an die eigene Handlungsfähigkeit, nicht die Performanz oder das Wissen selbst. |
| **Behandlung von Erklärbarkeit & Bedienbarkeit** | Zuordnung von Verstehenselementen der Hauptfunktion zu *Explainability*. | *Explainability* misst **Ausschließlich** das kognitive Nachvollziehen von Systemlogik und Output-Validierung. | TAM / Venkatesh et al. (2012): Die Einfachheit der Benutzung (*PEOU*) unterscheidet sich von der Transparenz der Systementscheidung (*Explainability*). |
| **Behandlung von Affekt vs. Kognition** | Zusammenfassung von Vertrauen (*Trust*) und invertierter Beängstigung (*Uncanniness*). | Strikte Trennung von kognitivem Vertrauen (*Trust*) und affektivem Unbehagen (*Uncanny Perception / Anxiety*). | Mayer et al. (1995) & Mori (1970): Vertrauen basiert auf Rationalitätsurteilen (Fähigkeit, Integrität), Unheimlichkeit ist ein primär emotionaler Schutzreflex. |
| **Datenschutz: Vertrauen vs. Kompetenz** | Einordnung von Abwesenheit von Bedenken als reine allgemeine Vertrauensfrage. | Differenzierung zwischen **Datenschutzvertrauen** (Vertrauen in System/Anbieter) und **Datenschutzkompetenz** (Wissen über Datenfluss). | Datensicherheit ist ein Integritätsmerkmal des Systems; das Wissen um sichere Dateneingabe ist eine Nutzerkompetenz. |
| **Verantwortungsvoller Einsatz vs. Normative Regel** | Einordnung von Kontrollforderungen (*Human-in-the-Loop*) als persönliches Verantwortungsverhalten. | Einstufung von Kontrollforderungen als **normative Einstellung / Compliance-Erwartung**, nicht als Indikator persönlicher Readiness. | Fishbein & Ajzen (2010): Die Befürwortung einer Regel (*Norm*) ist nicht identisch mit der eigenen Fähigkeit oder Bereitschaft zur Regeleinhaltung. |

---

## 4. Detaillierte wissenschaftliche Begründung anhand der V2-Schwachstellen

Um die Notwendigkeit der V3-Regeln zu verdeutlichen, werden die konkreten Mängel aus der V2-Evaluation wissenschaftlich analysiert:

### 1. `KIR-03`: Verwechslung von Handlungskompetenz (*Ability*) und Selbstwirksamkeit (*Self-Efficacy*)
* *Formulierung V2:* *"Ich bin überzeugt, dass ich KI-Anwendungen an meinem Arbeitsplatz kompetent bedienen kann."*
* *Fehlanalyse V2:* Das Item wurde dem Konstrukt *Ability* (Handlungskompetenz) zugeordnet.
* *Wissenschaftliche Korrektur in V3:* Die Formulierung *"Ich bin überzeugt, dass..."* misst nicht die tatsächliche Handlungskompetenz (*Ability* nach Mayer et al., 1995), sondern das Zutrauen in die eigene Kompetenz. Dies ist die exakte Definition von **Self-Efficacy** (Bandura, 1986). Ein *Ability*-Item muss direkt das Wissen oder die Beherrschung der Handlung adressieren (z. B. *"Ich beherrsche die Bedienung von..."*).

### 2. `KIR-06`: Unzureichend begründete Zuordnung eines PEOU-Items zu *Explainability*
* *Formulierung V2:* *"Ich verstehe die Hauptfunktionen der von mir genutzten KI-Werkzeuge in ihren Grundzügen."* (Original aus `Datensatz_v1.docx`: Item PEOU 2 *"PowerPilot is easy to understand"*).
* *Fehlanalyse V2:* Das Originalitem entstammt dem Konstrukt *Perceived Ease of Use* (PEOU), wurde aber in V2 zu *Explainability* umdeklariert.
* *Wissenschaftliche Korrektur in V3:* Dass die Hauptfunktion einer Software leicht verständlich ist (*PEOU*), bedeutet nicht, dass der Nutzer versteht, **wie** der KI-Algorithmus zu seinen Ergebnissen gelangt (*Explainability*). V3 verbietet die Umdeutung von PEOU-Originalitems zu *Explainability*, da dies die Diskriminanzvalidität zerstört.

### 3. `KIR-15`: Vermischung von Vertrauen (*Trust*) und emotionalem Unbehagen (*Uncanniness*)
* *Formulierung V2:* *"Ich empfinde den Einsatz von KI-Anwendungen bei meinen Aufgaben als angenehm und nicht beängstigend."* (Original aus `Datensatz_v1.docx`: Item U1 *"unheimlich"* / U3 *"unangenehm"*).
* *Fehlanalyse V2:* Die Negierung von Unheimlichkeit wurde als Indikator für *Trust* eingeordnet.
* *Wissenschaftliche Korrektur in V3:* *Trust* ist eine kognitiv-evaluative Erwartung an die Verlässlichkeit eines Systems (Mayer et al., 1995). *Uncanniness* (Mori, 1970) beschreibt hingegen eine viszerale, affektive Ablehnungsreaktion. Ein Befragter kann einer KI rational vertrauen (*hoher Trust*), sie aber dennoch als unheimlich empfinden (*hohe Uncanniness*). V3 fordert die separate Messung beider Konstrukte.

### 4. `KIR-16` & `KIR-17`: Verwechslung von Datenschutzvertrauen und Datenschutzkompetenz
* *Formulierung V2:* *"Ich habe keine Bedenken, dass vertrauliche Unternehmensdaten... weitergegeben werden."*
* *Fehlanalyse V2:* Das Item wurde als allgemeiner Bestandteil persönlicher KI-Readiness behandelt.
* *Wissenschaftliche Korrektur in V3:* Das Fehlen von Bedenken drückt **Datenschutzvertrauen** in den Anbieter oder das System aus (*Integrity* nach Mayer et al., 1995). Es sagt nichts darüber aus, ob der Befragte über die **Datenschutzkompetenz** verfügt, sensible Daten vor der Eingabe zu anonymisieren. V3 erzwingt die begriffliche Trennung zwischen Vertrauen in die Systemintegrität und eigener Datenschutzkompetenz.

### 5. `KIR-18`: Verwechslung einer normativen Einstellung mit verantwortungsvollem Verhalten
* *Formulierung V2:* *"Ich halte es für erforderlich, KI-generierte Arbeitsergebnisse vor ihrer Verwendung grundsätzlich menschlich zu überprüfen."*
* *Fehlanalyse V2:* Das Item wurde als Maß für persönliches, verantwortungsvolles KI-Verhalten (*Responsible AI Use*) interpretiert.
* *Wissenschaftliche Korrektur in V3:* Die Aussage misst eine **normative Einstellung** bzw. eine Compliance-Forderung (*"Man sollte kontrollieren"*). Sie misst weder das tatsächliche Kontrollverhalten noch die persönliche Bereitschaft, diese Kontrolle selbst gewissenhaft durchzuführen. Nach dem Reasoned Action Approach (Fishbein & Ajzen, 2010) muss zwischen normativer Überzeugung und eigenem Verhalten strikt unterschieden werden.

---

## 5. Standardisiertes Prüf- und Auditprotokoll (Vorlage für nachfolgende Iterationen)

Jeder künftig auf Basis dieses Modellrahmens generierte Fragebogen muss zwingend mit folgendem Protokollmuster auditiert werden:

```markdown
### Standard-Auditprotokoll V3 (Muster)

#### Item-Auditierung
- [ ] Item ID: [z.B. KIR-01]
  - K1 Konstruktkongruenz: [1 = Erfüllt / 0 = Nicht erfüllt]
  - K2 Taxonomische Reinheit: [Kategorie: Selbsteinschätzung / Kompetenz / Einstellung / Absicht / Verhalten]
  - K3 Quellenechtheit: [1 = Nachgewiesen / 0 = Unbelegt]
  - K4 Single-Intentionalität: [1 = Einkriteriell / 0 = Double-Barreled]
  - K5 Skalenkonsistenz: [1 = Konsistent / 0 = Inkonsistent]
  - **Einzel-Score $S_i$:** [Max. 5] ➔ Status: [Pass / Revision / Reject]

#### Gesamt-Freigabestatus
- Anzahle Items gesamt: [N]
- Anzahl Items mit $S_i = 5$: [n]
- **Freigabequote:** [n/N * 100 %]
- **Gesamtergebnis:** [FREIGEGEBEN (nur bei 100 %) / BLOCKIERT]
```

---

*Hinweis:* Das **Leitlinienmodell V3** liegt nun als vollständiges, themenunabhängiges Regelwerk vor. Im nächsten Schritt kann dieses Modell auf konkrete Anwendungsfälle (wie die Überarbeitung des KI-Readiness-Fragebogens) angewendet werden.