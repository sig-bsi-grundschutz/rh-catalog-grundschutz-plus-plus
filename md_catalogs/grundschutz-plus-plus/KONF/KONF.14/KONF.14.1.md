---
x-trestle-set-params:
  konf.14.1-prm1:
    values:
---

# KONF.14.1 - \[Verteilte Anwendungen\] Verschlüsselung beim Transport

## Control Statement

Konfiguration für Anwendungen SOLLTE Kommunikation beim Transport über Netze nach {{ insert: param, konf.14.1-prm1 }} verschlüsseln.

## Control guidance

Werden Daten unverschlüsselt übertragen, so könnten sie abgehört oder unbemerkt manipuliert werden. Relevant sind hierbei alle von der Anwendung übertragenen Daten, inklusive Authentifizierung an der Benutzerschnittstelle oder API, Abruf von Daten, Server-Server-Replikation oder zur Datensicherung. Das betrifft sowohl Inhalts- als auch Metadaten. Die Umsetzung kann mit Algorithmen zur Transportverschlüsselung wie Transport Layer Security (TLS) oder Ende-zu-Ende-Verschlüsselung erfolgen. Für aktuelle Verschlüsselungsverfahren siehe BSI TR-02102. Die Konfiguration der Verschlüsselung kann sich daran orientieren, wie lange die transportieren Daten, z.B. Transaktionen, vertraulich zu behandeln sind. Eine Herausforderung hierbei sind Anwendungen, die über allgemeine Anbindungen mit anderen Institutionen kommunizieren, z.B. E-Mails oder Anrufe ins öffentliche Telefonnetz. Diese Anwendungen können nur ihren Teil der Verbindungsstrecke verschlüsseln, so dass der Rest der Strecke und damit die Verbindung an sich dennoch unverschlüsselt sein könnte. Überträgt die Anwendung keine schützenswerten Daten über das Netz, so ist die Anforderung entbehrlich.
