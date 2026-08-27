# ARCH.2.3 - \[Netzdesign\] Mikrosegmentierung

## Control Statement

Architektur für IT-Systeme KANN Verbindungen zu allen anderen IT-Systemen einschränken.

## Control guidance

Mikrosegmentierung ist die Unterteilung des Netzes in möglichst kleine Segmente (z.B. pro IT-System oder Server-Anwendung). Für jedes dieser Segmente wird die erlaubte Kommunikation definiert und gefiltert. Mikrosegmentierung sorgt dafür, dass z.B. zwei medizinische Geräte mit gleicher Rolle zwar ins gleiche VLAN dürfen, aber nicht direkt miteinander kommunizieren dürfen. Die Umsetzung kann mit dynamischen VLANs, softwaredefinierten Netzwerken (SDN) oder Netzwerk-Firewalls auf Host-Ebene erfolgen. Die Mikrosegmentierung begrenzt Angriffe, die sich lateral ausbreiten.
