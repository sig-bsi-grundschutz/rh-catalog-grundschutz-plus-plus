# STM.2.1.4.1 - \[Anforderungspaket\] Vererbung von Zielobjektkategorien

## Control Statement

Strukturmodellierung MUSS die in der Hierarchie übergeordneten Zielobjektkategorien ebenfalls dem jeweiligen Asset die in der Zielobjekthierarchie übergeordnet sind zuweisen.

## Control guidance

Hier werden die zuvor zugeordneten Zielobjektkategorien um diejenigen Kategorien erweitert, die in der Zielobjekthierarchie übergeordnet sind. Anforderungen werden einmalig für die passende Zielobjektkategorie definiert und dann auf alle nachgeordneten Kategorien vererbt. Eine automatisierte Verarbeitung der Vererbungshierarchie kann den Umsetzungsaufwand erheblich reduzieren, ohne dass Themen außen vor bleiben. Die Vererbung erfolgt entlang der Zielobjekthierarchie, indem für jede zugeordnete Zielobjektkategorie alle Elternknoten bis zur Wurzel einbezogen werden. Die Vererbung ist deterministisch, da die Zielobjekthierarchie fest definiert ist. Eine Automatisierung der Vererbung ist möglich und wird empfohlen, wenn die Hierarchie maschinenlesbar vorliegt.
