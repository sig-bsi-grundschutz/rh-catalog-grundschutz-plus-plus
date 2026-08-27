# KONF.14.2 - \[Verteilte Anwendungen\] Source Port Randomisierung

## Control Statement

Konfiguration für DNS-Server SOLLTE Source Port Randomisierung aktivieren.

## Control guidance

Die mehrfache Verwendung gleicher Source Ports erleichtert Angreifern das Erraten gültiger Antworten, z. B. bei DNS-Spoofing oder Cache-Poisoning-Angriffen. Sourceport-Randomisierung (IETFC RFC 5452) erhöht die Anzahl möglicher Kombinationen und erschwert derartige Angriffe.
