# KONF.6.1.1 - \[Rollen und Berechtigungen\] Datenkapselung

## Control Statement

Konfiguration für IT-Systeme KANN Datenkapselung aktivieren.

## Control guidance

Bei der Datenkapselung, im Englischen als data encapsulation bekannt, handelt es sich um einen Schutzmechanismus, bei dem Daten logisch vor dem Zugriff des restlichen Systems verborgen werden. Hierdurch wird der direkte Zugriff unterbunden und ausschließlich über definierte, sichere Schnittstellen bereitgestellt. Zweck ist es, die Angriffsfläche auf sensible Daten zu verringern und deren Integrität sowie Vertraulichkeit zu wahren. Ohne eine solche Kapselung könnte beispielsweise eine Schadsoftware auf einem Server direkt auf Konfigurationsdateien oder im Arbeitsspeicher gehaltene Anmeldeinformationen anderer Anwendungen zugreifen und diese manipulieren oder ausleiten. Durch eine wirksame Datenkapselung kann die Institution sicherstellen, dass Zugriffe nur über vorab genehmigte und protokollierte Wege erfolgen, was eine unautorisierte Modifikation oder einen unbemerkten Abfluss von Daten erschwert. Technisch erfolgt dies zum Beispiel durch einen abgeschlossenen Speicherbereich auf einem mobilen Gerät für persönliche Informationen wie Kontakte oder Kalender (PIM-Container). Die Kapselung erfordert eine separate Authentisierung vor dem Zugriff auf die gekapstelten Daten und eine vom Betriebssystem unabhängige Daten- & Transportverschlüsselung innerhalb der Kapselung.
