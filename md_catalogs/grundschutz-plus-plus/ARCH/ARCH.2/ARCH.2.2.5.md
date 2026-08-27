# ARCH.2.2.5 - \[Netzdesign\] OT-Systeme

## Control Statement

Architektur für Netze SOLLTE Verbindungen zwischen OT-Systemen und anderen IT-Systemen einschränken.

## Control guidance

IT- und OT-Systeme haben typischerweise sehr unterschiedliche Risikoprofile (IT: Schnelllebig, viele Cybersicherheitsmechanismen, OT: Stabilität, weniger Cybersicherheitsmechanismen, beispielsweise industrielle Steuerungssysteme und Gebäudeautomationstechnik). Insbesondere der Zugriff auf OT-Funktionen (z. B. Öffnung zentraler Schließanlage) ist mit erhöhtem Risiko verbunden und könnte auch versehentlich z.B. durch Portscanner ausgelöst werden. Stattdessen ist es empfehlenswert, den Zugriff zu solchen Netzen nur über dafür vorgesehene Quellen zu ermöglichen (z. B. Sprungserver, bestimmte auslösende OT-Systeme).
