# ARCH.5.1.6 - \[Perimeterschutz\] Blockieren direkter Management-Verbindungen

## Control Statement

Architektur für Externe Netzanschlüsse SOLLTE Verbindungen zu Management-Schnittstellen blockieren.

## Control guidance

Zum Internet offene Management-Schnittstellen werden von Angreifern durch Scans leicht gefunden und sind häufig Ziel von Angriffen. Deshalb ist es sinnvoll, alle eingehenden Verbindungen zu Management-Schnittstellen aus externen Netzen zu blockieren, einschließlich der Verwaltung von VPN- und Firewallsystemen selbst. Wenn eine Administration dieser Systeme aus der Ferne erforderlich ist, so kann dieser Zugriff stattdessen über ein VPN in das interne Netz hergestellt werden, wobei auch hiermit ein erhöhten Risiko für Angriffe einhergeht.
