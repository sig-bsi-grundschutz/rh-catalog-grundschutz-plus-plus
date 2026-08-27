# KONF.13.2.2 - \[Senden und Empfangen von Nachrichten\] Verifikation der Serversignatur

## Control Statement

Konfiguration für E-Mail SOLLTE die Serversignatur eingehender E-Mails automatisch authentifizieren.

## Control guidance

Die DKIM-Signatur ist zu unterscheiden von einer PGP-Signatur, die in der Regel nicht automatisch vergeben wird. E-Mails ohne DKIM sind unzureichend authentifiziert, so dass sie leicht für Spoofing oder Phishing missbraucht werden können. Allerdings werden noch immer E-Mails ohne DKIM verschickt, so dass eine Blockierung zu funktionalen Einschränkungen führen könnte. Kompromissmaßnahmen können z.B. die Markierung der E-Mail mit einem Warnhinweis , Allowlisting, Greylisting, Quarantäne oder eine Filterung durch Anomalieerkennung sein. Die Formulierung "im Einklang mit den Festlegungen des Identitäts- und Berechtigungsmanagements" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik IDM festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist.
