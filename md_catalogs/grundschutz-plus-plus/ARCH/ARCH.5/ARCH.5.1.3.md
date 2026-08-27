# ARCH.5.1.3 - \[Perimeterschutz\] TCP-basierte Angriffe

## Control Statement

Architektur für Netze SOLLTE bekannte TCP-basierte Angriffsmethoden blockieren.

## Control guidance

TCP ist das am meisten verwendete Protokoll für die zuverlässige Datenübertragung. Durch TCP-basierte Angriffe können IT-Systeme gehackt oder Daten unbemerkt ausgeleitet werden. Beispiele sind TCP Session Hijacking (ACK-number guessing), Overlapping-Segment Attacks, TCP Reset (RST) Injection, Xmas-tree Scanning. Die Anforderung kann durch Blockieren solcher Verbindungen oder nur bestimmter Mechanismen umgesetzt werden.
