# AGKI-PM-ParlaTone 

# Autorin: Chiara Citro

# Info: Forschungsblog und Projektplanung mit LLMs im Rahmen eines Unversitätskurses. 

# GitHub-Link: https://github.com/Chiarr/AGKI-PM-ParlaTone 

# Hinweis: Blog wird mit Hilfe von LLM (ChatGPT) erstellt

## Inhalt des Repositories

- `index.html` – Hauptseite des Forschungsblogs (Projektübersicht, Daten, Methodik, Fokus Datenaufbereitung, Projektplan, Quellen)  
- `styles.css` – zentrales Stylesheet (Layout, Farben, Glossar-Tooltips)  
- `prompts.md` – Prompting-Tagebuch (Dokumentation der LLM-Nutzung, Reflexion „Expert in the Loop“)  
- `GLOSSAR.md` – ausführlicher Begriffskatalog (Arbeitsdefinitionen + offene Fragen)  
- `DATA.md` – Beschreibung der Datenbasis und der geplanten Aufbereitung  
- `METHOD.md` – methodischer Rahmen (Topic Modelling, Tonalität, LLM-Einsatz)

> Hinweis: Originaldaten (z. B. TEI/XML-Protokolle) werden über die Bundestags REST-API: https://dip.bundestag.de/über-dip/hilfe/api#content + Python Wrapper: https://pypi.org/project/BundestagsAPy/ abgerufen. 
ABER: XML Versionen gibt es erst für Protokolle ab 2015. Ob es sinnvoll ist ältere Protokolle in xml umzuwandeln sollte sich zeigen, wenn das Datenausmaß für 2015-2025 klar ist. 
Da ich mir bzgl der Aufarbeitung der Daten noch nicht sicher bin, sind sie vorerst noch nicht im Repo. 
