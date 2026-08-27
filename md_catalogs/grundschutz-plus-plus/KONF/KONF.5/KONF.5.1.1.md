# KONF.5.1.1 - \[Authentifizierung\] Authentifizierung an der Firmware

## Control Statement

Konfiguration für IT-Systeme SOLLTE den Zugriff auf die Firmware im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement authentifizieren.

## Control guidance

Durch unautorisierte Änderungen an Einstellungen der Firmware (UEFI oder Embedded System) könnten Fehlerzustände entstehen oder Sicherheitsfunktionen wie TPM deaktiviert werden. Dies kann je nach Firmware durch lokale Zugangspasswörter oder zentrale Berechtigung umgesetzt werden. Hierbei sind insbesondere Einstellungen von Sicherheitsfunktionen oder der Netzanbindung relevant. Die Formulierung "im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik Berechtigung (BER) festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist.
