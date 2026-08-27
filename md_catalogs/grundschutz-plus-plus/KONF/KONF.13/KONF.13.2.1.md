# KONF.13.2.1 - \[Senden und Empfangen von Nachrichten\] Verifikation der Sendeberechtigung

## Control Statement

Konfiguration für E-Mail SOLLTE eine automatische Verifikation der Sendeberechtigung aktivieren.

## Control guidance

Mit dem Sender Policy Framework (SPF) kann geprüft werden, ob der Sender zum Versand von E-Mails für diese Mailadresse berechtigt war. E-Mails ohne SPF-Header sind unzureichend authentifiziert, so dass sie leicht für Spoofing oder Phishing missbraucht werden können. Allerdings werden noch immer E-Mails ohne SPF verschickt, so dass eine Blockierung zu funktionalen Einschränkungen führen könnte. Kompromissmaßnahmen können z.B. die Markierung der E-Mail mit einem Warnhinweis , Allowlisting, Greylisting, Quarantäne oder eine Filterung durch Anomalieerkennung sein.
