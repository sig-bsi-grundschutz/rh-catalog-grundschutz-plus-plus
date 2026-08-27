# ARCH.2.2.7 - \[Netzdesign\] Management-Netz

## Control Statement

Architektur für Netze SOLLTE ein oder mehrere Management-Netze installieren.

## Control guidance

Ein Management-Netz ist ein physisch oder durch Netzfilter separiertes Netzsegment, das dediziert für die Überwachung, Verwaltung und Wartung von IT-Systemen bestimmt ist. Es ist von anderen Produktions- und Datennetzen getrennt, um den Zugriff auf kritische Verwaltungsfunktionen zu schützen und die Verfügbarkeit dieser Zugänge auch bei Problemen im restlichen Netz zu sichern. Dies gilt auch für virtualisierte Systeme. Im Kontext der Containerisierung empfiehlt es sich, administrative Zugänge auf Applikations-Container immer über die Container-Runtime erfolgen zu lassen.
