---
x-trestle-set-params:
  not.4.14-prm1:
    values:
---

# NOT.4.14 - \[Datensicherung\] Offline-Kopie

## Control Statement

Notfallplanung für Daten SOLLTE eine Offline-Kopie {{ insert: param, not.4.14-prm1 }} ausführen.

## Control guidance

Eine Offline-Kopie ist eine Datensicherung, die physisch oder logisch von produktiven Systemen und dem laufenden Netzwerk getrennt ist („offline backup“ oder „air-gapped backup“). „Regelmäßig“ bedeutet, dass die Institution in Abhängigkeit von Verfügbarkeit und Kritikalität ihrer Daten feste Intervalle definiert, beispielsweise täglich, wöchentlich oder monatlich. Der Sinn und Zweck dieser Vorgabe liegt darin, sicherzustellen, dass im Falle von Schadsoftwarebefall oder gezielten Angriffen keine gleichzeitige Kompromittierung aller Sicherungskopien stattfinden kann; ein Angriff könnte sonst auch Backups verschlüsseln oder löschen. Eine Offline-Kopie kann dagegen die Wiederherstellung kritischer Systeme nach einem Ransomware-Angriff oder auch nach einem physischen Ausfall, etwa durch Stromschaden oder Brand, unterstützen. Eine Institution kann dies umsetzen, indem sie (1) Kopien in Papierform oder auf wechselbaren Medien wie externen Festplatten, RDX-Kassetten oder Bändern erstellt, die nach dem Backup-Vorgang vom Netzwerk getrennt und geschützt aufbewahrt werden, (2) Cloud-Backups so konfiguriert, dass sie durch Write-Once-Read-Many-(WORM)-Speicher geschützt und logisch von aktiven Systemen isoliert sind, oder (3) eine Rotation von Datenträgern einführt, bei der Kopien an einem separaten, physischen Standort verwahrt werden.
