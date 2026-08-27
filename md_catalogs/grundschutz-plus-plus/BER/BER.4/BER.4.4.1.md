---
x-trestle-set-params:
  ber.4.4.1-prm1:
    values:
---

# BER.4.4.1 - \[Berechtigungsmanagement\] Überprüfung tatsächlicher Berechtigungen

## Control Statement

Berechtigung SOLLTE dokumentierte und tatsächlich vergebene Berechtigungen {{ insert: param, ber.4.4.1-prm1 }} auf Übereinstimmung überprüfen.

## Control guidance

Der Sinn und Zweck der Vorgabe liegt darin, eine unbemerkte Abweichung zwischen Dokumentation und Realität frühzeitig zu erkennen. Ohne diesen Abgleich könnte es vorkommen, dass ehemalige Mitarbeitende weiterhin Zugriff auf interne Systeme behalten oder dass sich im Laufe der Zeit unautorisierte Rechteanhäufungen einschleichen. Durch eine wirksame Überprüfung kann hingegen sichergestellt werden, dass nur aktuelle, geprüfte und erforderliche Zugriffsrechte bestehen bleiben und so die Angriffsfläche der Institution reduziert werden kann. Zur Umsetzung kann die Institution Berechtigungsübersichten automatisiert aus IT-Systemen exportieren und diese mit den in Verzeichnissen oder Rollenmodellen hinterlegten Daten vergleichen, z.B. anhand eines automatisierten Abgleiches mit Personalstammdaten einmal pro Quartal. Diese Anforderung ist auch dann erfüllt, wenn Dokumentation der Berechtigungen und tatsächliche Berechtigung (z.B. ein Verzeichnisdienst) dasselbe sind. Bitte beachten Sie dabei, dass die generelle Anforderung zur Überprüfung vergebener Berechtigungen weiter gefasst ist und z.B. auch den Abgleich zwischen tatsächlich vergebenen Berechtigungen und nicht dokumentieren Erfordernissen (beispielsweise durch die Vorlage bei Vorgesetzten) umfassen kann.
