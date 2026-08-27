# ARCH.7.3 - \[Dedizierte Systeme\] Entwicklungs- und Testumgebungen

## Control Statement

Architektur für Virtualisierungslösungen SOLLTE Entwicklungs- und Testumgebungen nicht auf produktiven Hostsystemen platzieren.

## Control guidance

Entwicklungs- und Testumgebungen sind dabei Umgebungen, in denen Software noch nicht ausgereift ist, sondern aktiv entwickelt, angepasst oder erprobt wird. Der Sinn der Vorgabe liegt darin, dass instabile oder absichtlich manipulierbare Testsysteme nicht auf denselben Hostsystemen betrieben werden sollten, auf denen produktive Anwendungen laufen. Andernfalls könnte ein Fehler in experimenteller Software dazu führen, dass der Hypervisor oder das Host-Betriebssystem beeinträchtigt wird und produktive Daten oder Dienste in Mitleidenschaft gezogen werden. Ebenso könnte Schadcode, der in einer Testumgebung eingebracht wird, unerwartet in produktive Netze durchgreifen. Durch die Trennung kann sichergestellt werden, dass ein Ausfall oder eine Kompromittierung in Entwicklungsumgebungen nicht die Stabilität und Vertraulichkeit produktiver Systeme gefährdet. Zur praktischen Umsetzung kann eine Institution Entwicklungs- und Testumgebungen auf dedizierte Virtualisierungshosts auslagern, die physisch oder logisch getrennt von den produktiven Hosts betrieben werden. Zusätzlich kann eine Institution Richtlinien zur Lifecycle-Kennzeichnung von VMs einführen (z. B. „dev“, „test“, „prod“ im Namen oder Tagging), um die klare Trennung auch in größeren Umgebungen praktikabel zu machen.
