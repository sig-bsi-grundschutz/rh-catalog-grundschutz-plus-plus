---
x-trestle-set-params:
  not.4.4-prm1:
    values:
---

# NOT.4.4 - \[Datensicherung\] Automatische Datensicherung

## Control Statement

Notfallplanung für Daten SOLLTE die Datensicherung durch {{ insert: param, not.4.4-prm1 }} ausführen.

## Control guidance

Ein automatisierter Mechanismus (engl. automated mechanism) ist hier ein technisches Verfahren, das ohne manuelles Zutun in festgelegten Intervallen oder bei bestimmten Ereignissen Sicherungskopien von Daten erstellt und dokumentiert. Er kann z. B. über Skripte, Backup-Software oder systemeigene Dienste umgesetzt werden, die regelmäßig und zuverlässig ausgeführt werden. Der Zweck solcher Mechanismen liegt darin, menschliche Fehlerquellen und Auslassungen zu vermeiden, denn eine manuelle Sicherung könnte in Stresssituationen übersehen werden oder unvollständig sein. Die Vorgabe kann so verhindern, dass im Falle von Schadsoftwarebefall oder Hardwareausfall kritische Daten unwiederbringlich verloren gehen, und sie kann eine schnelle Wiederherstellung der Arbeitsfähigkeit nach einem Vorfall ermöglichen. Ohne Automatisierung könnte eine Institution etwa nach einem Ransomware-Angriff feststellen, dass keine aktuelle Sicherung vorliegt. Die Anforderung ist auch dann erfüllt, wenn zusätzlich manuelle Datensicherungen durchgeführt werden.
