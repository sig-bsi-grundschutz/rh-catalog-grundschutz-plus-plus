# KONF.6.2 - \[Rollen und Berechtigungen\] Gemeinsam genutzte Verzeichnisse

## Control Statement

Konfiguration für Dateiserver SOLLTE die Zugriffsrechte gemeinsam verwendeter Verzeichnisse einschränken.

## Control guidance

Relevant sind hierbei sowohl speziell eingerichtete Verzeichnisse für die gemeinsame Bearbeitung von Dateien als auch Verzeichnisse, die vom System für gemeinsame Dateien verwendet werden, z.B. /tmp. Unter Linux kann das Sticky-Bit verwendet werden, um den Zugriff auf die Dateien in diesem Verzeichnis einzuschränken, so dass nur noch der Eigentümer einer Datei (oder der Eigentümer des Verzeichnisses) diese Datei löschen oder umbenennen darf.
