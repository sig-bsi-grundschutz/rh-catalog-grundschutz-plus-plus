# DEV.2.3 - \[Softwareentwicklung - Security by Design\] Ausführbarkeit mit minimalen Rechten

## Control Statement

Entwicklung für Anwendungen SOLLTE die fehlerfreie Ausführung mit den geringst möglichen Berechtigungen verankern.

## Control guidance

Die Anwendung ermöglicht die Ausführung mit den geringst möglichen Berechtigungen, wenn sie nur die Berechtigungen benötigt, die für die gerade intendierte Funktionalität erforderlich sind (also z.B. auch ohne Kamerazugriff funktioniert, wenn Nutzende nur vorhandene Bilder betrachten möchten). Sind einzelne Berechtigungen nicht vorhanden, so funktioniert die Anwendung mit entsprechenden Einschränkungen weiterhin (Graceful Degradation).
