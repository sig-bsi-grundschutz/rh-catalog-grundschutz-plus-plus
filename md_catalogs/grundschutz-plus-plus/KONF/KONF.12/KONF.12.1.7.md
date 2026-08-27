# KONF.12.1.7 - \[Kontrollierte Datenverarbeitung\] Filtern schädlicher Webinhalte

## Control Statement

Konfiguration für Webanwendungen SOLLTE eine Filterung schädlicher Webinhalte aktivieren.

## Control guidance

Anfragen an Webanwendungen könnten dazu führen, dass diese sich anders verhalten als gewollt. Mögliche Folgen sind die unzulässige Preisgabe von Informationen, die Manipulation oder der Verlust von Daten sowie Betriebsstörungen. Typische Auslöser sind SQL Injection oder Cross-Site-Scripting. Solche potenziell schädlich wirkenden Inhalte können durch eine Web Application Firewall oder durch geeignete Eingabevalidierung in der Webanwendung gefiltert werden.
