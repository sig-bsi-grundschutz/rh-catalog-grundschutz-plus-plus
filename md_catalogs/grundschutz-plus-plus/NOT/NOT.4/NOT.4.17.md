---
x-trestle-set-params:
  not.4.17-prm1:
    values:
---

# NOT.4.17 - \[Datensicherung\] Anwendungstest

## Control Statement

Notfallplanung für Anwendungen KANN deren Funktionsfähigkeit nach Wiederherstellung {{ insert: param, not.4.17-prm1 }} überprüfen.

## Control guidance

Diese Anforderung zielt darauf ab, die Disaster-Recovery-Fähigkeiten einer Anwendung insgesamt zu gewährleisten. Durch regelmäßige Tests der Wiederherstellung aus Backups wird sichergestellt, dass im Ernstfall (Systemausfall, Datenverlust, Cyberangriff) eine funktionierende Wiederherstellung möglich ist. Dabei wird nicht nur die bloße Wiederherstellung getestet, sondern auch die Funktionalität der wiederhergestellten Anwendung verifiziert – inklusive Datenintegrität und korrekte Übernahme der Konfiguration.
