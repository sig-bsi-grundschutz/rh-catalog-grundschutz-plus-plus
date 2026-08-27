# KONF.6.8 - \[Rollen und Berechtigungen\] Berechtigungen des Webserver-Prozesses

## Control Statement

Konfiguration für Webserver SOLLTE die Berechtigungen des Webserver-Prozesses einschränken.

## Control guidance

Wird der laufende Prozess über das Web kompromittiert, so verhindert eine Einschränkung der Rechte eine weitere Ausbreitung des Angriffs. Relevant sind dabei Zugriffsrechte für Dateisystem und Systemfunktionen. Zweckmäßig ist es hierzu, die Berechtigungen so einzuschränken, dass der Serverdienst a) keinen Zugriff auf Dateien außerhalb des WWW-Wurzelverzeichnisses hat, b) Schreibzugriffe innerhalb des WWW‑Wurzelverzeichnisses nur in explizit autorisierten Unter­verzeichnissen hat, c) keine Programme oder Shell‑Befehle außerhalb der vorgesehenen Interpreter ausführen kann, d) keine privilegierten Berechtigungen besitzt. Unterverzeichnisse die Schreibrechte benötigen könnten sind etwa /uploads, /cache, /tmp.
