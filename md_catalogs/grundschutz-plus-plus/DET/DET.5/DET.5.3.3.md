# DET.5.3.3 - \[Management von Schwachstellen\] Historische Analyse

## Control Statement

Detektion KANN Schwachstellen in öffentlich erreichbaren Systemen oder Anwendungen anhand bekannter Anzeichen im Audit Log testen.

## Control guidance

Die historische Analyse von Logdateien ermöglicht es, vergangene Systemaktivitäten systematisch zu untersuchen, um potenzielle Sicherheitsvorfälle zu identifizieren, die zum Zeitpunkt ihres Auftretens unbemerkt blieben. Nach der Entdeckung einer Schwachstelle kann so rückwirkend festgestellt werden, ob und wie diese bereits ausgenutzt wurde. Die Umsetzung kann durch Etablierung eines zentralisierten Log-Managements mit langer Aufbewahrungsdauer, Implementierung automatisierter Such- und Korrelationsalgorithmen zur Erkennung bekannter Angriffsmuster und Anomalien in den Logdaten, sowie durch forensische Analyse der Zeitstempel, Quell-IPs, Benutzeraktivitäten und Zugriffsversuche erfolgen. Bei der Feststellung von Schwachstellen in öffentlich zugänglichen Systemen ist es sinnvoll die Audit-Logs gezielt nach Indikatoren zu durchsuchen, die auf entsprechende Angriffsmuster hindeuten - darunter ungewöhnliche Zugriffszeiten, auffällige Authentifizierungsversuche, verdächtige Datenbankabfragen oder charakteristische Command-Injection-Versuche, wodurch potenzielle Kompromittierungen retrospektiv aufgedeckt und in ihrem vollen Umfang bewertet werden können.
