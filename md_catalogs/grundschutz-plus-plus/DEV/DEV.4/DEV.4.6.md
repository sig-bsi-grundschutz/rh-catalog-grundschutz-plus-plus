# DEV.4.6 - \[Softwareentwicklung - Code\] Compileroptionen

## Control Statement

Entwicklung für Anwendungen SOLLTE Compileroptionen für Sicherheitsfunktionen vor dem Release aktivieren.

## Control guidance

Compileroptionen wie Stack Canaries, PIE, PIE, CFI können automatisch Schutzmechanismen in Programme einbauen. Bewährte Praxis ist es, diese Compileroptionen zu aktivieren, sofern es keine entgegenstehenden besonderen Gründe gibt, darauf im Einzelfall zu verzichten. Werden interpretierte Programmiersprachen verwendet, so ist die Anforderung analog auf die Interpreter-Optionen anzuwenden.
