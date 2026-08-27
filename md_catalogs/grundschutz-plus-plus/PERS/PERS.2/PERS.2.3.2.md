# PERS.2.3.2 - \[Aufgaben, Rollen, Zuständigkeiten\] Rollentrennung - Virtualisierung

## Control Statement

Personal SOLLTE zwischen Administration von virtuellen Systemen und Virtualisierungslösungen eine Rollentrennung verankern.

## Control guidance

Die Administration von virtuellen Systemen bezeichnet im hier relevanten Kontext die operative Verwaltung einzelner virtueller Gastsysteme (VMs, Container, etc.), einschließlich ihrer Bereitstellung, Konfiguration, Wartung und Zugriffskontrolle. Die Virtualisierungslösung hingegen ist hier die übergeordnete Plattform oder Hypervisor-Ebene, welche physische Ressourcen virtualisiert und mehreren virtuellen Gastsystemen bereitstellt. Diese Differenzierung entspricht dem Prinzip der Rollen- bzw. Funktionstrennung (separation of duties bzw. role separation), bei dem Aufgabenbereiche so abgegrenzt werden, dass keine Person gleichzeitig über kritische Systemebenen hinweg vollumfängliche Kontrolle besitzt. Damit wird ein wesentliches Sicherheitsprinzip technischer Infrastruktur auf die Virtualisierungsschichten übertragen. Der Zweck dieser Trennung liegt in der Begrenzung von Fehlerrisiken und der Prävention von Missbrauch – sowohl vorsätzlich als auch unbeabsichtigt. Eine Person, die zugleich die Virtualisierungsebene und virtuelle Systeme verwaltet, könnte durch Fehlkonfiguration, Nachlässigkeit oder Manipulation unbeabsichtigt erhebliche Auswirkungen auf eine Vielzahl von Systemen haben oder deren Nachvollziehbarkeit beeinträchtigen. Eine klare Rollentrennung kann dem vorbeugen, indem sie Kontrollmechanismen stärkt, die Integrität der Umgebung wahrt und Fehler früher erkennen lässt.
