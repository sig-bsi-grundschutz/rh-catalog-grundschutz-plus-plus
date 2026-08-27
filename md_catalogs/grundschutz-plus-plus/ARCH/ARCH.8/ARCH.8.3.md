# ARCH.8.3 - \[Ausfallsicherheit\] Redundante Server

## Control Statement

Architektur für Anwendungen KANN für die Funktionsfähigkeit der Anwendung erforderliche Hostsysteme redundant installieren.

## Control guidance

Redundanz ist gegeben, wenn sowohl das System als auch seine Netzanbindung redundant vorhanden sind. Das System selbst ist nur redundant, wenn auch seine Datenspeicher und Stromversorgung redundant ausgelegt sind. Automatische Umschaltung meint das Failover. Die Anforderung kann durch netzbasierte Load Balancer oder serverseitige automatisch Umschaltung umgesetzt werden (z.B. durch Hello-Pakete).
