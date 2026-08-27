# ARCH.5.1.4 - \[Perimeterschutz\] UDP-basierte Angriffe

## Control Statement

Architektur für Netze SOLLTE bekannte UDP-basierte Angriffsmethoden blockieren.

## Control guidance

UDP-basierte Angriffsmethoden (englisch: known UDP-based attack vectors) sind hierbei Techniken zu verstehen, die das User Datagram Protocol (UDP) ausnutzen. UDP ist das am meisten verwendete Protokoll für die Übertragung von Datenstreams. Aufgrund seiner verbindungslosen Eigenschaft ermöglicht UDP eine sehr schnelle Datenübertragung und wird daher oft für zeitkritische Anwendungen wie Videostreaming, VoIP oder DNS-Anfragen verwendet. Genau diese Eigenschaft macht es jedoch anfällig für Missbrauch, da die Absenderadresse leicht gefälscht werden kann (IP-Spoofing). Beispiele für Angriffe sind Sequence Number Guessing, DHCP Starvation und UDP Hole-Punching Abuse. Die Anforderung kann durch Blockieren solcher Verbindungen oder nur bestimmter Mechanismen umgesetzt werden.
