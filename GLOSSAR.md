# GLOSSAR – ParlaTONE

Dieses Glossar sammelt zentrale Fachbegriffe, die im Projekt ParlaTONE verwendet werden.
Die Definitionen sind Arbeitsfassungen und können im Projektverlauf präzisiert werden.

---

## Large Language Model (LLM)

**Arbeitsdefinition:**  
Ein Large Language Model ist ein KI-Sprachmodell, das mit Textkorpora
trainiert wurde und in der Lage ist, natürliche Sprache zu verarbeiten und zu generieren.
LLMs können u. a. beim Zusammenfassen, Paraphrasieren, Strukturieren und Kommentieren von Texten
unterstützen.

**Rolle im Projekt:**  
- Unterstützung bei der Textproduktion (z. B. Blogtexte, erste Entwürfe für Dokumentation)  
- Hilfestellung bei der Formulierung von Kategorien und Fragen  
- Reflexionspartner für methodische Entscheidungen  

**Offene Fragen:**  
- Wie kann ich systematisch dokumentieren, an welchen Stellen ein LLM beteiligt war (z. B. in einem eigenen Abschnitt „LLM-Unterstützung“ in jedem Dokument)?  
- Welche Kriterien nutze ich, um LLM-Vorschläge bewusst abzulehnen (z. B. unklare Begründung, Widerspruch zu Fachliteratur)?

---

## Topic Modelling

**Arbeitsdefinition:**  
Topic Modelling ist ein Verfahren des Natural Language Processing (NLP), mit dem aus großen
Textsammlungen automatisch Themen („Topics“) identifiziert werden. Diese Topics entstehen aus
typischen Wortmustern und Kookurrenzen, bilden jedoch keine „Themen“ im streng
geisteswissenschaftlichen Sinn, sondern statistische Cluster.

**Rolle im Projekt:**  
- Identifikation von wiederkehrenden Themen im Bundestagsdiskurs zu §218  
- Grundlage für die Benennung und Interpretation von Diskurssträngen  

**Offene Fragen:**  
- Wie viele Topics sind für den ausgewählten Korpus sinnvoll (Orientierung an Kohärenzmaßen vs. interpretierbarer Anzahl)?  
- Wie kann ich transparent machen, dass Topics interpretierte Konstrukte sind und nicht „objektive Themen“?

---

## Embeddings

**Arbeitsdefinition:**  
Embeddings sind numerische Vektorrepräsentationen von Wörtern, Sätzen oder Dokumenten.  
Texte, die sich inhaltlich ähneln, liegen in diesem Vektorraum näher beieinander als Texte,
die sich stark unterscheiden.

**Rolle im Projekt:**  
- Grundlage für BERTopic (die Redebeiträge werden zunächst in einen semantischen Vektorraum
  eingebettet)  
- Ermöglichen semantische Vergleiche zwischen Reden, ohne nur auf exakte Wortgleichheit
  angewiesen zu sein

**Offene Fragen:**  
- Welches konkrete Embedding-Modell (z. B. deutsches Transformer-Modell) ist für den Korpus zu §218 am geeignetsten (Sprachabdeckung, Trainingsdaten, Lizenz)?  
- Muss ich die Embeddings ggf. nachjustieren (Fine-Tuning) oder reicht ein vortrainiertes Modell?

---

## Tonalität (Tone / Sentiment)

**Arbeitsdefinition:**  
Mit Tonalität ist hier die sprachliche „Stimmung“ eines Redebeitrags gemeint, z. B. ob er
konfrontativ, konsensorientiert, moralisch aufgeladen oder eher technisch-pragmatisch formuliert ist.

**Rolle im Projekt:**  
- Zentrale Dimension der Forschungsfrage: Wie verändert sich der Ton im Diskurs zu §218
  über die Zeit und zwischen Parteien bzw. Geschlechtern?  
- Ergänzung zu inhaltlichen Themenclustern (Topics)

**Offene Fragen:**  
- Welche Tonalitätsdimensionen sind für den Kontext Bundestagsdebatten zu §218 wirklich trennscharf?  
- Reicht eine grobe Einteilung (z. B. „konfrontativ vs. konsensual“), oder ist eine feinere Skala sinnvoll?  
- In welchem Umfang können existierende Sentiment-Modelle für Deutsch sinnvoll genutzt werden, ohne den politischen und normativen Kontext zu verzerren?

---

## TEI/XML (Text Encoding Initiative)

**Arbeitsdefinition:**  
TEI ist ein XML-basierter Standard zur Auszeichnung von Texten (z. B. literarische Werke,
Protokolle, historische Dokumente). Er erlaubt eine feinkörnige Strukturierung von Textbestandteilen
(z. B. Redebeiträge, Sprecher*innen, Kommentare).

**Rolle im Projekt:**  
- Struktur der Plenarprotokolle (Redebeiträge, Zwischenrufe, formale Elemente)  
- Ausgangspunkt für die Datenaufbereitung (Parsing, Extraktion, Normalisierung)

**Offene Fragen:**  
- Welche TEI-Elemente sind für ParlaTONE zwingend relevant (z. B. Sprecher*innen, Abschnitte, Zeitstempel)?  
- Welche Elemente können für die erste Projektphase ignoriert werden, ohne wichtige
  Kontextinformationen zu verlieren?
