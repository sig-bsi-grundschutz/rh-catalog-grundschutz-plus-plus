# ARCH.5.1.9 - \[Perimeterschutz\] Filterung von DNS

## Control Statement

Architektur für Externe Netzanschlüsse SOLLTE unerwünschte Inhalte in DNS-Verbindungen einschränken.

## Control guidance

Unerwünschte Inhalte sind DNS-Anfragen oder -Antworten, die für Geschäftsprozesse unnötige oder sogar schädliche Daten enthalten, z.B. Verbindungen zu bekannten Malware-Domains oder zu Werbe- oder Telemetriediensten. Dies kann entweder nach dem Allowlist- oder Denylist-Ansatz erfolgen. Listen bekannter schädlicher Domains können über Threat Intelligence-Feeds oder spezielle DNS-Lösungen wie Pihole bezogen werden.
