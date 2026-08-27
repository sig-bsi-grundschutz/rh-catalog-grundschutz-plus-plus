# KONF.6.6.1 - \[Rollen und Berechtigungen\] Mandantenfähigkeit

## Control Statement

Konfiguration für Anwendungen SOLLTE wenn die Anwendung mehrere Mandaten bedient, für jeden Mandanten eine eigene Berechtigungskonfiguration aktivieren.

## Control guidance

Der Ausdruck "mehrere Mandanten" (im Englischen auch multi-tenancy genannt) bezieht sich auf eine Softwarearchitektur, bei der eine einzige Instanz einer Anwendung gleichzeitig die Bedürfnisse mehrerer, voneinander unabhängiger Kundengruppen (Mandanten) bedient. Eine eigene Berechtigungskonfiguration bedeutet, dass jeder Mandant eine separate, von den anderen getrennte Sammlung von Zugriffsregeln und -rechten erhält. Dies dient dem Schutz vor Datenlecks, da ein Angreifer, der sich unrechtmäßig Zugang zu einem Mandanten verschafft, dadurch nicht automatisch die Berechtigungen für andere Mandanten übernimmt. Eine separate Konfiguration kann verhindern, dass ein Fehlverhalten oder eine Fehlkonfiguration bei einem Mandanten die Sicherheit aller anderen beeinträchtigt. Technische Möglichkeiten hierfür sind die Verwendung von mandantenspezifischen Datenbank-Schemata oder die logische Trennung von Daten innerhalb einer gemeinsamen Datenbank durch Mandanten-IDs. Darüber hinaus kann die Institution sicherstellen, dass die Authentifizierung und Autorisierung für jeden Mandanten streng getrennt sind, zum Beispiel durch die Nutzung unterschiedlicher API-Schlüssel oder Single-Sign-On-Konfigurationen pro Mandant.
