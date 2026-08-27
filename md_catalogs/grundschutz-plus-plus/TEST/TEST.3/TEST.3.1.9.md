# TEST.3.1.9 - \[Tests\] Fuzzing

## Control Statement

Änderungen und Tests KANN die Stabilität gegen Fehlerzustände oder Abstürze bei der Eingabe großer Mengen an Zufallsdaten testen.

## Control guidance

Fuzzing ist eine automatisierte Softwaretestmethode, mit der unerwartete Schwachstellen und Fehler in Anwendungen durch Eingabe zufälliger, unerwarteter oder ungültiger Daten aufgedeckt werden können. Der Hauptzweck besteht darin, Grenzbedingungen zu prüfen und Programmabstürze, Speicherlecks oder sicherheitskritische Fehler wie Buffer Overflows zu identifizieren, bevor Angreifer diese ausnutzen können. Kann durch spezialisierte Tools oder kontinuierliches Fuzzing in der CI/CD-Pipeline umgesetzt werden. Für einen effektiven Einsatz empfiehlt es sich, mit strukturiertem Fuzzing zu beginnen, das auf bekannten Protokollspezifikationen oder Datenformaten basiert, Fuzzing-Tests in die frühen Phasen des Entwicklungszyklus zu integrieren, alle gefundenen Fehler systematisch zu dokumentieren und zu beheben, sowie regelmäßig neue Testfälle auf Basis entdeckter Schwachstellen zu entwickeln, um die Testabdeckung kontinuierlich zu verbessern.
