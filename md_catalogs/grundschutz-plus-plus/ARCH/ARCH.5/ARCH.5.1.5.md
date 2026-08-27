# ARCH.5.1.5 - \[Perimeterschutz\] Deaktivierung von Split Tunneling

## Control Statement

Architektur für Externe Netzanschlüsse SOLLTE Split Tunneling blockieren.

## Control guidance

Um eine durchgehende Kontrolle und Absicherung des Netzverkehrs zu gewährleisten, muss verhindert werden, dass IT-Clients während einer aktiven Verbindung zum internen Netz gleichzeitig ungeschützten Zugriff auf das öffentliche Internet oder andere Netzwerke haben. Dies schließt sogenannte „Split Tunneling“-Konfigurationen aus, bei denen nur ausgewählter Datenverkehr über das VPN geleitet wird, während anderer Datenverkehr (z. B. Webzugriffe) über das lokale Netzwerk oder die Internetverbindung des Clients erfolgt.
