---
x-trestle-set-params:
  konf.10.5.1-prm1:
    values:
---

# KONF.10.5.1 - \[Konfiguration von Anwendungen\] Automatisierte Überprüfung der Konfiguration

## Control Statement

Konfiguration für Anwendungen KANN die Überprüfung der Konfiguration durch {{ insert: param, konf.10.5.1-prm1 }} aktivieren.

## Control guidance

Die automatische Auditierung der Systemkonfiguration ermöglicht eine kontinuierliche und effiziente Überprüfung, ob IT-Systeme sicher und regelkonform konfiguriert sind. Dabei wird die aktuelle Konfiguration automatisiert mit vordefinierten Soll-Vorgaben (etwa unternehmensinternen Richtlinien oder externen Benchmarks wie denen des Center for Internet Security (CIS)) abgeglichen. Dies ist besonders sinnvoll, da manuelle Prüfungen fehleranfällig, zeitaufwändig und in großen Infrastrukturen kaum durchführbar sind. Automatisierte Audits erhöhen die Transparenz, erkennen Abweichungen frühzeitig und erleichtern die Einhaltung von Compliance-Vorgaben. So wird die Angriffsfläche durch fehlerhafte oder unsichere Einstellungen erheblich reduziert.
