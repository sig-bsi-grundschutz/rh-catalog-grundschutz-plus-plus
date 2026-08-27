---
x-trestle-set-params:
  not.4.3-prm1:
    values:
---

# NOT.4.3 - \[Datensicherung\] Sicherung der Anwendung

## Control Statement

Notfallplanung für Anwendungen SOLLTE deren Datensicherung {{ insert: param, not.4.3-prm1 }} ausführen.

## Control guidance

Hierzu können z.B. sowohl die Daten einer Backend-Datenbank, als auch Konfigurationsdateien oder Sicherheitseinstellungen gehören. Bei einer Verzeichnisdatenbank z.B. sind typischerweise sowohl die eigentlichen Verzeichniseinträge wie Benutzer & Gruppenzugehörigkeiten, als auch Metadaten wie Benutzerattribute, Gruppenrichtlinien und Informationen zur Integration von Drittdiensten erforderlich, um die Verzeichnisdatenbank funktionsfähig wiederherzustellen.
