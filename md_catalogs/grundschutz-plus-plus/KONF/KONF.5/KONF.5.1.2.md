# KONF.5.1.2 - \[Authentifizierung\] Pre-Boot-Authentifizierung

## Control Statement

Konfiguration für Endgeräte KANN den Zugriff vor dem Start des Betriebssystems authentifizieren.

## Control guidance

Diese Authentifizierung vor dem Start, oft als "Pre-Boot Authentication" (PBA) oder "Hardware-based Authentication" bezeichnet, verhindert, dass ein Gerät gestartet wird, bevor sich Nutzende mit Anmeldeinformationen, wie zum Beispiel einem Passwort oder einem biometrischen Merkmal, autorisiert haben. Ohne diese Authentifizierung könnte ein Angreifer versuchen, das Gerät direkt zu booten, die Festplatte zu kopieren oder zu manipulieren, um sensitive Daten zu extrahieren. Eine gängige Methode ist die Verwendung einer Festplattenverschlüsselung (Full Disk Encryption, FDE) mit einer Pre-Boot-Authentifizierung. Eine Institution könnte auch eine Mehr-Faktor-Authentifizierung (MFA) vor dem Start des Betriebssystems einsetzen, beispielsweise indem ein Hardware-Token oder ein biometrischer Scan zusätzlich zum Passwort erforderlich ist, was die Sicherheit weiter erhöht.
