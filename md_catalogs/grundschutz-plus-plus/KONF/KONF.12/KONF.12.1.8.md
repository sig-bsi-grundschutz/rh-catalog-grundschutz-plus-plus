# KONF.12.1.8 - \[Kontrollierte Datenverarbeitung\] Duplikate im Verzeichnisbaum

## Control Statement

Konfiguration für Verzeichnisdienste SOLLTE Duplikate im Verzeichnisbaum blockieren.

## Control guidance

Da jedes Zugangskonto nur einmal benötigt wird können Duplikate von Attributen wie Name oder Organisationseinheit nur als Fehler oder Angriff vorkommen. In OpenLDAP kann dies beispielsweise durch Overlays realisiert werden. Dies gilt ausschließlich für Daten von Nutzenden.
