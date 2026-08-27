# DEV.2.5 - \[Softwareentwicklung - Security by Design\] Einschränkung des Zugriffs auf Zugangsdaten

## Control Statement

Entwicklung für Anwendungen SOLLTE den lesenden und schreibenden Zugriff auf Zugangsdaten einschränken.

## Control guidance

Von der Anwendung verwendete Zugangsdaten können z.B. API-Schlüssel oder Datenbankanmeldeinformationen sein. Statt diese im Quellcode zu hinterlegen ist es besser, sie in Umgebungsvariablen oder sogenannten Vaults zu speichern. Hierbei hilft es auch, solche Daten mit .gitignore-Regeln aus der Versionskontrolle auszuschließen.
