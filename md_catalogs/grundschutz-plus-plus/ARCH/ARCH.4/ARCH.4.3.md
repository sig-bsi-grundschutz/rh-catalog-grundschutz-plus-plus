# ARCH.4.3 - \[Zugangsbeschränkungen\] Authentifizierung von Routingprotokollen

## Control Statement

Architektur für Netze SOLLTE Änderungen an Routing-Tabellen im Einklang mit den zugehörigen Anforderungen des Identitäts- und Berechtigungsmanagements authentifizieren.

## Control guidance

Hierzu zählt z.B. die Authentifizierung von BGP/OSPF-Sitzungen zur Verhinderung von Route Hijacking, BGP origin validation with RPKI oder OSPF/ISIS/BGP MD5 or TTL+hMAC authentication. Die Formulierung "im Einklang mit den Festlegungen des Identitäts- und Berechtigungsmanagements" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik IDM festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist.
