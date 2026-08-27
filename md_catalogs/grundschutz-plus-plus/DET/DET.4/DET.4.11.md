# DET.4.11 - \[Überwachung von Aktivitäten\] Anomalien in Netzen und am Perimeter

## Control Statement

Detektion für Netze SOLLTE den Netzwerkverkehr auf Anomalien überwachen.

## Control guidance

Beispiele sind ausgehende Netzverbindungen zu als bösartig bekannten oder gänzlich unbekannten DNS-Domains oder IP-Adressen, Anzeichen für DNS-Tunneling (ungewöhnlich lange Subdomains oder Spitzenwerte für TXT-Mengen), ungewöhnlich hohes Datenvolumen zu Cloud-Speicherlösungen, sowie unautorisierte Portscans oder Brute Force Angriffe auf Fernwartungsschnittstellen wie RDP oder SSH sein. Hierdurch können Verbindungen zu Angreiferservern (C2 Beacons), die Ausbreitung von Angriffen über das Netz, oder Datenabflüsse erkannt werden.
