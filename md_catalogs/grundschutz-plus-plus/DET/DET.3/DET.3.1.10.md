# DET.3.1.10 - \[Protokollierung\] Nutzungsstatistik

## Control Statement

Detektion für Anwendungen KANN eine Nutzungsstatistik protokollieren.

## Control guidance

Bei der statistischen Protokollierung werden z.B. Anzahl oder Durchschnittswerte gespeichert, nicht jedoch die genaue Herkunft oder der Zeitstempel bestimmter Ereignisse. Nutzungsstatistiken wahren die Privatsphäre der einzelnen Nutzenden, ermöglichen jedoch eine Erkennung von Fehlern oder Anomalien in der Nutzung. Beispiele sind die Anzahl von Anfragen für eine bestimmte Ressource (etwa Webserver-URL oder DNS-Name), Anzahl der Anfragen einer bestimmten Anfrageart, Geräte- oder Anwendungskategorien (etwa pro Browseragent oder Betriebssystemversion), Anzahl bestimmter Antworttypen (z.B. Webserver-Fehlercodes), sowie Zugriffsversuche. Hierdurch können Betriebsprobleme wie Caching Fehler oder DoS-Angriffe erkannt werden.
