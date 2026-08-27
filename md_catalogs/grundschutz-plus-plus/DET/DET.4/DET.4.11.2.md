# DET.4.11.2 - \[Überwachung von Aktivitäten\] Netzwerk-Honeypots

## Control Statement

Detektion für Netze KANN Netzwerk-Honeypots installieren.

## Control guidance

Honeypots sind Systeme, die das Verhalten eines Betriebsservers simulieren, um bei netzbasierten Angriffen Informationen über den Angriff zu erhalten. Geeignet sind z.B. vermeintliche Rechnungsbearbeitungssysteme oder Datenbank-Server. Alarmierungsereignisse können hier z.B. Login-Versuche oder unerwartete API-Abfragen sein. Allerdings kann es hierbei zu falsch-positiv Vorfallsmeldungen kommen, insbesondere wenn die Honeypots dort platziert werden, wo sie für legitime Nutzende leicht zugänglich sind, oder wenn legitime Netzwerkscans bereits eine Alarmierung auslösen. Daher ist es sinnvoll, die konkreten Einsatzgegebenheiten in einer Risikoanalyse zu betrachten und den möglichen Detektionsmehrwert mit den potenziellen Risiken solcher falsch-positiv Meldungen abzuwägen.
