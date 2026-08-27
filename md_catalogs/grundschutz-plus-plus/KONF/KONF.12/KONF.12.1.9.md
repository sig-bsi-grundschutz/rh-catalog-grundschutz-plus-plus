# KONF.12.1.9 - \[Kontrollierte Datenverarbeitung\] Journaling

## Control Statement

Konfiguration für Dateiserver SOLLTE Dateisystem-Journaling aktivieren.

## Control guidance

Beim Journaling werden Änderungen an Dateien zunächst in einem speziellen Protokoll (Journal) aufgezeichnet, bevor sie tatsächlich geschrieben werden, um Datenintegrität und Konsistenz sicherzustellen. Auf einem Dateiserver ist dies besonders wichtig, da es das Risiko von Datenverlusten bei plötzlichen Abstürzen oder Stromausfällen minimiert und eine schnelle Wiederherstellung ermöglicht.
