---
x-trestle-set-params:
  konf.12.1-prm1:
    values:
---

# KONF.12.1 - \[Kontrollierte Datenverarbeitung\] Eingabevalidierung

## Control Statement

Konfiguration für Anwendungen SOLLTE die Validierung von Eingabedaten durch {{ insert: param, konf.12.1-prm1 }} aktivieren.

## Control guidance

Eingabevalidierung (engl. input validation) ist die technische und logische Überprüfung von Daten, die von Nutzenden, Schnittstellen oder externen Quellen an eine Anwendung übergeben werden. Ziel ist es, sicherzustellen, dass nur erwartete, syntaktisch und semantisch korrekte Eingaben verarbeitet werden – beispielsweise Zahlen in einem numerischen Feld, zulässige Dateiformate bei Uploads oder inhaltlich beschränkte Steuerzeichen in Formularen. Fehlende oder unzureichende Eingabevalidierung könnte es Angreifenden ermöglichen, schadhaften Code einzuschleusen (injection attacks wie SQL Injection oder Command Injection), Geschäftslogik zu manipulieren oder Systeme über Ressourcenmissbrauch lahmzulegen. Eine saubere Validierung kann dagegen die Angriffsfläche deutlich reduzieren und die Verlässlichkeit der Anwendung erhöhen. Dabei hängt die Ausgestaltung stark vom Einsatzzweck ab: Während etwa bei einer Textverarbeitung größere Freiheiten gewährt werden können, erfordern sensible Szenarien wie SQL-Injection bei Datenbankanfragen, die Abwehr von prompt injection bei Large Language Models (LLM) oder die Verarbeitung von Zahlungsdaten sehr strikte Prüfungen. Je nach Anwendung und Risikoprofil können Plausibilitätsprüfungen, die Beschränkung der Eingabedaten auf vordefinierte Werte, Verifikationen der Daten bei einer dritten Stelle (z.B. eines Zahlungsmittels beim Zahlungsanbieter), Regular Expression Entry Patterns, oder Data Escaping als Maßnahmen sinnvoll sein.
