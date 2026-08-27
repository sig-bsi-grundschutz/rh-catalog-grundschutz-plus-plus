# ARCH.2.1 - \[Netzdesign\] Netzsegmente

## Control Statement

Architektur für Netze SOLLTE eine Unterteilung des internen Netzes in Netzsegmente unter Berücksichtigung der Anforderungen der Institution und des Schutzbedarfes verankern.

## Control guidance

Die Aufteilung in Netzsegmente (auch Netzdomänen oder Subnetze genannt) ermöglicht es, verschiedene Zonen mit unterschiedlichen Schutzanforderungen – z. B. Büro-IT, Produktionsnetz, Managementnetz – getrennt zu betrachten und gezielt zu schützen. Relevant sind dabei (falls vorhanden) auch WLANs/SSIDs, IoT-Geräte wie vernetzte Kühlschränke, Hausleittechnik, operative Technologien, Industrielle Steuerungssysteme oder Netze zum Zugriff auf Speichersysteme (Storage Area Network, SAN). Die Anforderung gilt auch, wenn die Systeme nur noch als VMs oder Container existieren. Die Segmentierung kann hier in die virtuelle Netzwerk‑Ebene verlagert werden, sodass die Segmentierung weder vom Hypervisor noch von den Workloads umgangen wird. Die Einteilung in Segmente kann anhand einer Klassifizierung von Netzen erfolgen (z.B. nach Schutzbedarf der dort verarbeiteten Daten oder nach Risikoklassen angeschlossener Systeme) erfolgen. Beispiele hierfür sind Internet-Domäne, Endgeräte-Domäne, Domäne für zentrale Serverdienste, Domäne für Systeme hoher Vertraulichkeit. Alternativ können auch organisatorische Domänen verwendet werden, z. B. Personalwesen, Marketing, Finanzverwaltung, Innere Verwaltung. Die Filterkriterien können sich nach den Sicherheitsanforderungen der jeweiligen Netze im Einzelnen oder nach einer vorgenommenen Klassifikation der Netze richten. Hierzu gehören insbesondere die Anforderungen zur Authentifizierung und Autorisierung von Assets.
