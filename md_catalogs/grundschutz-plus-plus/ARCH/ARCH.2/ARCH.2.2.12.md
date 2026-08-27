# ARCH.2.2.12 - \[Netzdesign\] Sprungserver

## Control Statement

Architektur KANN Sprungserver installieren.

## Control guidance

Ein Sprungserver (englisch „jump server“ oder „jump host“) ist ein speziell abgesicherter Server, der als einzig vorgesehener Einstiegspunkt in ein Verwaltungsnetz oder zu administrierten Systemen dient. Alle administrativen Sitzungen laufen über diesen zentralen Knotenpunkt, wodurch die Angriffsfläche reduziert und die Nachvollziehbarkeit erhöht wird. Ohne Sprungserver könnte ein Angreifer beispielsweise über kompromittierte Administrator-Notebooks unbemerkt direkt auf zentrale Systeme zugreifen und dort Manipulationen durchführen. Ein Sprungserver kann hingegen alle Management-Zugriffe zentral kanalisieren, sodass verdächtige Aktivitäten leichter erkannt und im Nachhinein nachvollzogen werden können. Praktische Umsetzungen können sein: (1) der Einsatz eines dedizierten, gehärteten Servers mit restriktiven Firewall-Regeln, (2) die Nutzung von Mehrfaktor-Authentisierung und zentralem Benutzer-Management auf dem Sprungserver, (3) eine verpflichtende Session-Aufzeichnung oder Protokollierung sämtlicher Administrationsvorgänge.
