# ARCH.5.1 - \[Perimeterschutz\] Einschränkung und Inspektion von Verbindungen

## Control Statement

Architektur für Netze SOLLTE Verbindungen zwischen IT-Systemen einschränken.

## Control guidance

Über Netverbindungen können unbeabsichtigte Verbindungen aufgebaut werden oder netzbasierte Angriffe über das Internet gegen die Institution erfolgen. Unerwünschter Datenverkehr nach außen können z.B. private IP-Adressen (RFC 1918 leakage), Multicasting, TCP/UDP Ports für veraltete, angreifbare Protokolle oder ICMP-Verkehr sein. Die Beschränkung der Verbindung zwischen IT-Systemen kann sowohl durch zustandsbehaftete Paketfilter, als auch mit Application Layer Gateways umgesetzt werden. Empfehlenswert ist eine Kombination aus Allowlisting, IP-Reputationslisten, Deep Packet Inspection und Durchsatzratenbegrenzung. Hierbei können Verbindungen auch nach Kategorien autorisiert werden (z.B. anhand von IP-Subnetzen oder Voraussetzungen wie per Zertifikat authentifzierten IT-Systemen). Damit dabei keine unnötigen Verbindungen zugelassen werden, ist es wichtig, die Kategorisierung möglich genau zu wählen (z.B. möglichst einzelne Subnetze statt des ganzen Netzes oder nur bestimmte Ports oder Anwendungen zuzulassen).
