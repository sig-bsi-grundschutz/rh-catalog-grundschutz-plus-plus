# ARCH.2.2.3 - \[Netzdesign\] Segmentierung von Servern und Clients

## Control Statement

Architektur für Netze SOLLTE Verbindungen zwischen Hostsystemen und Clients einschränken.

## Control guidance

Die Anforderung gilt auch, wenn die IT-Systeme nur noch als VMs oder Container existieren. Die Segmentierung kann hier in die virtuelle Netzwerk‑Ebene verlagert werden, sodass die Segmentierung weder vom Hypervisor noch von den Workloads umgangen wird. Die Anforderung kann auch physisch durch dedizierte Infrastruktur für VDI/Client‑VMs umgesetzt werden. Um die klare Trennung sicherzustellen, wird empfohlen kein Bridging zwischen Port‑Groups sowie auf dem virtuellen Switch keinen promiscuous Mode zu verwenden.
