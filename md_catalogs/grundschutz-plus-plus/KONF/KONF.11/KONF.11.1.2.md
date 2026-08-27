# KONF.11.1.2 - \[Vertrauensbeziehungen\] Authentifizierung von Netzverbindungen - clientseitig

## Control Statement

Konfiguration für Anwendungen SOLLTE die Gegenstelle vor dem Datenaustausch im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement authentifizieren.

## Control guidance

Stellt eine Anwendung Anfragen über das Netz oder nimmt eine Anwendung Anfragen über das Netz entgegen, so gewährleistet eine gegenseitige Authentifizierung der Kommunikationspartner (mutual authentication), dass diese autorisiert ist Anfragen zu stellen oder zu beantworten. Eine gängige Lösung ist die Prüfung von X.509-Zertifikaten beim Verbindungaufbau mit TLS. Für die Umsetzung ist es nicht unbedingt erforderlich, dass sich die Gegenstelle bei jeder Anfrage/Abruf erneut authentifiziert, wenn bei der Authentifizierung eine sichere Verbindung per TLS aufgebaut wird. Mit Anfragen sind alle Zugriffe gemeint, sei es über eine Web-URL oder eigene API. Die Formulierung "im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik Berechtigung (BER) festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist. Für lesende Zugriffe auf unkritische, öffentliche Daten ist die Authentifizierung der lesenden Anwendung entbehrlich.
