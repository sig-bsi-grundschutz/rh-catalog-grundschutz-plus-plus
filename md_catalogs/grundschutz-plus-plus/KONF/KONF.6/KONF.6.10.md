# KONF.6.10 - \[Rollen und Berechtigungen\] Auflistung von Verzeichnisinhalten

## Control Statement

Konfiguration für Webserver SOLLTE die Auflistung von Verzeichnisinhalten einschränken.

## Control guidance

Über das Auflisten von Verzeichnisinhalten erhalten Angreifer Einblick in die interne Struktur des Systems und potenziell sensibler Daten. Zur Umsetzung kann in der Konfiguration des Webservers (z.B. Apache, Nginx) die Directory-Listing-Funktion deaktiviert werden. Alternativ kann über Dateien wie .htaccess der Zugriff auf die notwendigen Verzeichnisse eingeschränkt werden.
