# KONF.14.3 - \[Verteilte Anwendungen\] Iterative Beantwortung

## Control Statement

Konfiguration für DNS-Server SOLLTE die iterative Beantwortung von DNS-Anfragen aus dem Internet aktivieren.

## Control guidance

Bei iterativen Anfragen kommt die Antwort direkt vom autoritativen Server, statt auf zwischengespeicherte Antworten anderer DNS-Resolver zu vertrauen. Dies reduziert die Angriffsfläche für Cache Poisoning und erschwert DNS-Tunneling zur Datenexfiltration oder Command-and-Control-Kommunikation.
