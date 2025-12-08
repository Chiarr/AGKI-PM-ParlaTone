23.11.2025 - ChatGPT
Ziel der LLM-Nutzung: Basis-Blog erstellen, Struktur der Webseite und Texte.
Verwendete Prompts: „Hallo :) Ich brauche deine Hilfe beim Erstellen eines Forschungsblogs (im Rahmen eines Uni-Projektes). Ich werde dir mein Projektkonzept als PDF geben und die Aufgabenstellung. Ein GitHub-Projekt habe ich bereits erstellt und ich arbeite am liebsten mit Python in VSCode und mit Github Desktop. Kannst du mir bitte helfen? :)“
Tools/Funktionen: Dokumentenverarbeitung, Texterstellung, Code Writing.
Pros: Code und Texte überraschend gut und hilfreich. Spart viel Zeit.
Cons: Alles sehr geglättet und einheitlich. Insgesamt ein bisschen langweilig.


01.12.2025 - ChatGPT  
Ziel der LLM-Nutzung: Vertiefenden Fokus „Datenaufbereitung: Herausforderungen und Lösungsansätze“ ausformulieren (für den Blog) + optionale HTML-Version.  
Verwendete Prompts:  
- „Danke! Kannst du bitte noch den vertieften Fokus: 'Datenaufbereitung: Herausforderungen und Lösungsansätze' erstellen?“  
Tools/Funktionen: Texterstellung (wissenschaftlicher Stil), Strukturierung in Unterkapitel, HTML-Generierung für `<section id="fokus">`.  
Pros:  
- Klarere Struktur der Datenaufbereitung (Herausforderungen + Lösungsansätze).  
- Sehr hilfreich, um den methodischen Teil präziser zu formulieren, ohne im Text zu „verloren zu gehen“.  
- HTML-Version spart Zeit beim Übertragen in `index.html`.  
Cons:  
- LLM hat tendenziell eher Standardformulierungen, ich musste nachträglich manche Stellen kürzen und an meinen Schreibstil anpassen.  
- Gefahr, dass der Text fertiger wirkt, er tatsächlich ist, bzw. tiefergehend als die Datenaufbereitung tatsächlich schon ist.

Offene Fragen:  
- Wie kann ich im Blog sichtbar machen, welche Aussagen schon gut abgesichert sind und welche eher Arbeitsannahmen sind?  

---

07.12.2025 - ChatGPT  
Ziel der LLM-Nutzung: Einarbeiten des Kurs-Feedbacks in die bestehende `index.html` + Ergänzung um LLM-Hinweis, Glossar (Hover-Tooltips) und Quellen; anschließend CSS-Redesign in beige/grün.  
Verwendete Prompts:  
- „Danke! Wir haben Feedback bekommen, kannst du mir bitte helfen es in die bestehende index.html einzuarbeiten? Und kannst du da bitte auch ein Glossar für Fachbegriffe einfügen?“  
- „Danke! Kannst du bitte das css not ein bisschen anpassen, dass es ein bisschen bunter und hübscher aussieht. Leichte beige und grün Töne, bitte :)“  

Tools/Funktionen: HTML-Strukturierung, Einbau von Hinweistext zu LLM („Expert in the Loop“), Erstellung eines Glossars mit `data-definition`-Tooltips, CSS-Design (Farbschema, Typografie, Schatten, Responsiveness).  
Pros:  
- Sehr konkrete, direkt einbaubare HTML- und CSS-Snippets → wenig Copy-Paste-Overhead.  
- Glossar-Implementierung mit Hover-Tooltips ist didaktisch schön und erfüllt die Forderung nach klaren Begriffserklärungen.  
- Neues Farbkonzept (Beige/Grün) wirkt deutlich „weniger Slop“ und professioneller.  
Cons:  
- LLM neigt dazu, sehr viel HTML/CSS auf einmal zu liefern – ich musste genau prüfen, was wirklich nötig ist, damit es nicht überladen wird.  
- Stil ist immer noch relativ generisch; es besteht die Gefahr, dass andere Projekte ähnlich aussehen, wenn sie dieselben Prompts nutzen.  

Offene Fragen:  
- Sollte ich das Glossar im Blog eher kurz halten und die ausführlicheren Definitionen in `GLOSSAR.md` auslagern?  
- Wie kann ich im Code selbst markieren, an welchen Stellen LLM-Code eingebunden wurde (Kommentare o. ä.)?  

---