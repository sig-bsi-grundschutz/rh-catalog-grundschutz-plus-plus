# KONF.12.1.1 - \[Kontrollierte Datenverarbeitung\] Zertifikatsprüfung

## Control Statement

Konfiguration für Webbrowser SOLLTE die automatische Validierung des Zertifikates einschließlich der vollständigen Zertifikatskette aktivieren.

## Control guidance

Zertifikatsprüfung (Certificate Validation) ist eine Funktion, bei der ein Browser das digitale Zertifikat einer Webseite vor dem Verbindungsaufbau verifiziert. Dabei wird sichergestellt, dass das Zertifikat von einer vertrauenswürdigen Zertifizierungsstelle (CA - Certificate Authority) ausgestellt, gültig und nicht abgelaufen oder widerrufen ist. Dabei wird die vollständige Zertifikatskette, einschließlich des Root-Zertifikates verifiziert. Ist das Zertifikat ungültig, so wird der Aufruf der Seite blockiert. Die korrekte Implementierung dieses Prozesses kann die Vertraulichkeit und Integrität der übertragenen Daten gewährleisten und schützt vor Man-in-the-Middle-Angriffen, bei denen Angreifer versuchen, den Datenverkehr abzufangen. Zur Umsetzung dieser Anforderung können Institutionen die zentrale Konfiguration von Browsern über Gruppenrichtlinien (Group Policies) oder Mobile Device Management (MDM)-Lösungen vornehmen.
