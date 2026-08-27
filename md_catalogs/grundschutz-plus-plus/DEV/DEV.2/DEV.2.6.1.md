# DEV.2.6.1 - \[Softwareentwicklung - Security by Design\] Eingabevalidierung

## Control Statement

Entwicklung für Anwendungen SOLLTE Eingabedaten auf eingeschleuste Befehle testen.

## Control guidance

Bei der Eingabevalidierung (Input Validation) wird getestet, ob die Eingabedaten eingeschleuste Befehle enthalten, z.B. SQL-Injection, Kommandozeilenbefehle oder Prompt Injection bei generativer KI. Welche Eingaben betroffen sein könnten, kann durch eine Taint Analyse herausgefunden werden. Alternativ können auch alle Eingabedaten validiert werden (Server Side Validation).
