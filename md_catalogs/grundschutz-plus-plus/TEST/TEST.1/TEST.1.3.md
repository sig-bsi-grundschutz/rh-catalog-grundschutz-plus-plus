# TEST.1.3 - \[Grundlagen\] Einschränkung von Änderungen

## Control Statement

Änderungen und Tests SOLLTE die Durchführung von Änderungen auf Administrierende einschränken.

## Control guidance

Ziel ist es, zu verhindern, dass unautorisierte Personen Eingriffe in produktive Systeme vornehmen. Ohne diese Einschränkung könnte Schadcode eingeschleust werden, Konfigurationen unbeabsichtigt verändert oder sensible Daten offengelegt werden. Die klare Zuweisung an Administrierende kann gleichzeitig sicherstellen, dass Änderungen nachvollziehbar und fachgerecht durchgeführt werden, wodurch die Stabilität und Verfügbarkeit von Systemen geschützt werden kann. Eine Institution kann die Anforderung beispielsweise durch folgende Maßnahmen umsetzen: (1) Verwendung von Rollenkonzepten, bei denen nur Administrierende Schreibrechte in produktiven Systemen besitzen, während anderen Rollen lediglich Leserechte eingeräumt werden können, (2) Einsatz von Testumgebungen oder Sandbox-Systemen, in denen auch Nicht-Administrierende Änderungen gefahrlos vorbereiten und dokumentieren können, (3) Einführung von Change-Management-Workflows mit Genehmigungsschritten, so dass Administrierende Änderungen erst nach dokumentierter Prüfung umsetzen können, und (4) Einsatz von technischen Kontrollmechanismen wie „Just-in-Time“-Privilegien oder Protokollierung von administrativen Sitzungen, wodurch die Nachvollziehbarkeit und Integrität der Änderungen verbessert werden kann.
