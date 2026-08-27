# KONF.10.1.1 - \[Konfiguration von Anwendungen\] Versionierung der Anwendungskonfiguration

## Control Statement

Konfiguration für Anwendungen SOLLTE eine Versionierung vorheriger Konfigurationen verankern.

## Control guidance

Die Versionierung bezeichnet hier die strukturierte Nachvollziehbarkeit von Änderungen an Konfigurationen, also das Speichern, Dokumentieren und bei Bedarf Wiederherstellen älterer Zustände einer Anwendung. Sie unterscheidet sich von einem einfachen Backup dadurch, dass nicht nur eine Kopie vorliegt, sondern explizit eine fortlaufende Historie mit Vergleichen, Rücksetzpunkten (rollback points) und optional Kommentaren geführt wird. Der Zweck liegt darin, dass eine ungewollte oder fehlerhafte Anpassung an einer Anwendungskonfiguration im Betrieb schnell erkannt und – wenn erforderlich – präzise auf einen definierten, funktionsfähigen Zustand zurückgesetzt werden kann. Ohne diese Rückgriffsmöglichkeit könnte ein Konfigurationsfehler den gesamten Dienst außer Betrieb setzen, während eine Versionierung die Verfügbarkeit und Nachvollziehbarkeit stärken kann. Zur Umsetzung kann eine Institution technische Verfahren einsetzen, die eine automatische Ablage und Historisierung von Konfigurationsdateien unterstützen, beispielsweise durch (1) den Einsatz verteilter Versionskontrollsysteme wie Git oder Subversion (SVN) für textbasierte Konfigurationsdateien, (2) integrierte Konfigurationsarchivierung in gängigen Deployment- oder Container-Tools, oder (3) systemseitige Snapshot-Mechanismen, die gezielt für Konfigurationsverzeichnisse genutzt werden.
