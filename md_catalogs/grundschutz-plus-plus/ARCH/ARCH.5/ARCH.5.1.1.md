# ARCH.5.1.1 - \[Perimeterschutz\] Blockieren anfälliger Netzprotokolle

## Control Statement

Architektur für Netze SOLLTE anfällige Netzwerkprotokolle blockieren.

## Control guidance

Anfällig sind Netzprotokolle, wenn sie veraltete oder gar keine Algorithmen zur Verschlüsselung oder Integritätsprüfung verwenden. Hierzu gehören Protokolle wie Telnet, SMB v1, SNMP v1/v2c. Für aktuelle Verschlüsselungsalgorithmen siehe BSI TR 02102.
