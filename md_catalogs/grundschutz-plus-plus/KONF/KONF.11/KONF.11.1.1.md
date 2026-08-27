# KONF.11.1.1 - \[Vertrauensbeziehungen\] Authentifizierung von geplanten Konversationen

## Control Statement

Konfiguration für TK-Anwendungen SOLLTE den Zugriff auf geplante Konversationen im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement authentifizieren.

## Control guidance

Viele TK-Anwendungen bieten geplante Konversationen, z.B. in virtuellen Meeting-Räumen oder über Telefonkonferenzen, die über eine Rufnummer erreichbar sind. Wird der Zugriff hierauf nicht authentifiziert, so könnten unbemerkt Unberechtigte teilnehmen und Informationen abhören oder auf Meta-Informationen wie Teilnehmer oder Uhrzeiten zugreifen. Der Schutz kann z.B. durch Passwörter/PINs oder über die Anmeldung per Zertifikat oder Single-Sign-On geschehen. Die Formulierung "im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik Berechtigung (BER) festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist.
