# DET.3.2 - \[Protokollierung\] Integration von Cloud-Diensten

## Control Statement

Detektion für Cloud-Dienste KANN Ereignisse in der Cloud im Audit Log der Institution protokollieren.

## Control guidance

Daten in Cloud-Diensten könnten von Angreifern über das Internet angegriffen werden, ohne dass Ereignisse im internen Netz hierauf Rückschlüsse geben. Dies könnte zum Beispiel durch Phishing geschehen, wodurch ein OAuth Token für den Cloud-Zugang missbraucht wird. Die Integration der Logs des Cloud-Dienstleisters in die institutionseigene Protokollierung kann hier helfen, z.B. bei Authentifizierung oder Berechtigungsänderungen, sowie bei Zugriff oder Veränderung von Daten. Insbesondere die Integration des Loggings mit einer bedingten Zugriffsrichtlinie kann hier helfen, z.B. indem Zugriffe von ungewöhnlichen IP-Adressen oder Browser Agents auf Angriffe hinweisen können. Die Integration von Cloud-Protokollen in ein internes Logging birgt oft erhebliche Herausforderungen, darunter die Bewältigung des enormen Volumens und der Vielfalt an Datenformaten, was durch selektive Protokollierung, Datennormalisierung und -anreicherung angegangen werden kann. Die Absicherung der Datenpipeline gegen Man-in-the-Middle-Angriffe kann durch die Einhaltung der technischen Anforderungen an die beteiligten IT-Systeme und Anwendungen bewältigt werden, z.B. Verschlüsselung und Authentifizierung. Da Cloud-Anbieter oftzusätzliche Gebühren für den Datentransfer (Egress-Kosten) verlangen bietet es sich an, die Protokolle vor der Übertragung zu filtern, um die Kosten für die Verbesserung der Sicherheit gering zu halten.
