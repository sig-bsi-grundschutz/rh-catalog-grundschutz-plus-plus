---
x-trestle-set-params:
  not.4.16.1-prm1:
    values:
---

# NOT.4.16.1 - \[Datensicherung\] Test der Wiederherstellung

## Control Statement

Notfallplanung für Daten SOLLTE die Wiederherstellung mindestens anhand von repräsentativen Stichproben {{ insert: param, not.4.16.1-prm1 }} überprüfen.

## Control guidance

Unter „Erfolg der Datensicherung“ ist hier die Vollständigkeit („completeness“) und Integrität („integrity“) der erstellten Backups zu verstehen. Eine fehlerhafte oder unvollständige Sicherung könnte unbemerkt bleiben, wenn nicht aktiv geprüft wird, während eine gezielte Validierung die Sicherheit bietet, dass sich die Daten bei Bedarf in unveränderter Form vorfinden lassen. Damit kann ein gravierender Datenverlust, etwa durch korrupte Sicherungsdateien oder abgebrochene Backup-Jobs, rechtzeitig erkannt und behoben werden. Die Anforderung zielt darauf ab, Risiken durch Scheinsicherheit zu reduzieren – etwa wenn Backup-Prozesse zwar automatisiert laufen, aber unbemerkt leere, fehlerhafte oder inkonsistente Datenbestände erzeugen könnten. Durch eine regelmäßige Überprüfung kann die Institution sicherstellen, dass die gesicherten Daten tatsächlich verwendbar bleiben, und damit das Risiko von Ausfallzeiten oder irreversiblen Informationsverlusten verringern. Konkret umgesetzt werden kann dies z. B., indem (1) Backup-Logs automatisch auf Fehlermeldungen oder Warnungen geprüft werden, (2) Prüfsummenverfahren wie Hashes (z. B. SHA-256) zur Integritätskontrolle eingesetzt werden und (3) stichprobenartige Vergleiche zwischen gesicherten und Originaldateien durchgeführt werden. Die Stichprobe kann sich dabei entweder auf die Wiederherstellung selber (= Wiederherstellung nur einiger Daten) als auch auf den deren Überprüfung (= Öffnen nur einiger Daten) beziehen. Stichproben sind repräsentativ, wenn die Zusammensetzung der Stichprobe von Test zu Test geändert wird und die Wahrscheinlichkeit der Stichprobenauswahl auch der Bedeutung der Daten entspricht. Zweckmäßig ist es dazu, bei der Stichprobenauswahl den Schutzbedarf der Daten zu berücksichtigen: Für besonders wichtige Systeme wie Verzeichnisdienste und für den Geschäftsbetrieb unerlässliche Daten ist eine häufigere Überprüfung erforderlich als für Daten und Systeme, auf die im Notfall auch verzichtet werden kann. Die Anforderung ist auch erfüllt, wenn statt einer Stichprobe eine vollständige Wiederherstellung vorgenommen und geprüft wird. Die Anforderung ist auch dann erfüllt, wenn die Überprüfung durch aktive Verwendung der Daten nach einer Wiederherstellung erfolgt (z.B. durch Inbetriebnahme neuer Server-Container, die aus einer versionierten Datensicherung automatisch angelegt werden).
