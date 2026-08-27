---
x-trestle-set-params:
  not.4.16-prm1:
    values:
---

# NOT.4.16 - \[Datensicherung\] Test der Datensicherung

## Control Statement

Notfallplanung für Daten SOLLTE den Erfolg der Datensicherung {{ insert: param, not.4.16-prm1 }} überprüfen.

## Control guidance

Die Überprüfung der Vollständigkeit kann durch Statistiken des Datenumfangs plus Stichproben der Daten durchgeführt werden. Ein Integritätstest prüft, ob die gesicherten Daten ohne Änderungen im Vergleich zum Original vorliegen. Hierzu können je nach Daten auch Berechtigungen und Metadaten gehören, wenn diese für die Rücksicherung erforderlich sind (z.B. Wiederherstellung eines Laufwerks mit Ordnern die verschiedene Zugriffsberechtigungen haben).
