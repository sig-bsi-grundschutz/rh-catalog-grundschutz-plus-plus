# KONF.12.14 - \[Kontrollierte Datenverarbeitung\] DNS-Falschinformationen

## Control Statement

Konfiguration für DNS-Server SOLLTE DNS-Antworten, die falsche Domain-Informationen liefern, deaktivieren.

## Control guidance

Falsch sind Domain-Informationen, wenn sie nicht der tatsächlichen Erreichbarkeit des Zieles entsprechen, sondern z.B. auf Werbeseiten umleiten. DNS-Server, die falsche Antworten liefern, können zu unerwarteten Fehlern in Anwendungen oder zum DNS-Hijacking führen. Sie sind an unerwarteten Websites, Zertifikatsfehlern oder mit DNS-Prüfsoftware zu erkennen. Gilt sowohl für die Konfiguration des eigenen Servers, als auch für die verwendeten DNS Upstream Server.
