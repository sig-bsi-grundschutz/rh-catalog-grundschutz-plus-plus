---
x-trestle-set-params:
  det.3.1.11-prm1:
    values:
---

# DET.3.1.11 - \[Protokollierung\] Anwendungsspezifische Ereignisse

## Control Statement

Detektion für Anwendungen KANN {{ insert: param, det.3.1.11-prm1 }} protokollieren.

## Control guidance

Die Festlegung, welche spezifischen Ereignisse protokolliert werden, obliegt der Institution und hängt von der jeweiligen Systemumgebung und dem Schutzbedarf ab. Beispiele sind Änderungen an Zugangskonten im Verzeichnisdienst, Telekommunikationsverbindungen, ein Verstoß gegen eine konfigurierte Policy, unautorisierter Zugriff, API-Aufrufe zwischen verschiedenen Anwendungskomponenten, Transaktionen in einem Finanzsystem oder einer E-Commerce-Anwendung, Konfigurationsänderungen oder ein Absturz der Anwendung. Die Protokollierung dieser Ereignisse kann helfen, die Behandlung durch das Betriebspersonal anzustoßen oder Indizien für Ermittler zu sichern.
