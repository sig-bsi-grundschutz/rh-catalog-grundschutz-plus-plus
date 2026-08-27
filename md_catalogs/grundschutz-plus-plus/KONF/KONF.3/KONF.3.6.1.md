---
x-trestle-set-params:
  konf.3.6.1-prm1:
    values:
---

# KONF.3.6.1 - \[Physischer Schutz\] Automatische Fernlöschung oder -sperre

## Control Statement

Konfiguration für Endgeräte KANN eine automatische Fernlöschung oder -sperre bei Inaktivität nach {{ insert: param, konf.3.6.1-prm1 }} aktivieren.

## Control guidance

Beide Mechanismen können bei längerer Inaktivität ausgelöst werden, also wenn ein Endgerät über einen bestimmten Zeitraum hinweg nicht mehr mit den Systemen der Institution in Kontakt steht oder nicht genutzt wird. Als angemessene Frist für eine solche Inaktivität können z. B. 30 Tage, 60 Tage oder 90 Tage definiert werden, abhängig vom Sicherheitsbedarf und der Einsatzumgebung. Dies kann verhindern, dass ungenutzte Geräte mit sensiblen Daten in Umlauf bleiben oder in falsche Hände geraten. Ein automatisches Entfernen oder Sperren kann hier das Risiko eines Datenabflusses erheblich reduzieren und gleichzeitig eine Kontrolle über den Gerätelebenszyklus sichern. Zur Umsetzung kann die Institution beispielsweise Mobile-Device-Management-Lösungen einsetzen, die nach Ablauf der gewählten Frist automatisiert Fernlöschung oder Fernsperre auslösen. Alternativ kann eine Endpoint-Security-Lösung integriert werden, die periodisch prüft, ob das Gerät eine Verbindung zum Netz herstellt, und bei Überschreiten des Schwellenwerts eine definierte Aktion anstößt. Auch ein Prozess, bei dem Inaktivität zunächst mit einer Warnmeldung angekündigt wird, bevor tatsächlich gesperrt oder gelöscht wird, kann die Benutzerfreundlichkeit erhöhen.
