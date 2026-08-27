---
x-trestle-set-params:
  not.4.13-prm1:
    values:
  not.4.13-prm2:
    values:
---

# NOT.4.13 - \[Datensicherung\] Datensouveränität

## Control Statement

Notfallplanung für Outsourcing SOLLTE die Datensicherung von Daten, die bei einem Dienstleister verarbeitet werden, nach {{ insert: param, not.4.13-prm1 }} {{ insert: param, not.4.13-prm2 }} ausführen.

## Control guidance

Dies dient dazu bei einem Ausfall des Dienstleisters die Daten schnell bei einem anderen Dienstleister oder intern weiterverwenden zu können (Interoperabilität in der Exitstrategie). Anerkannt ist hier ein Format, welches auch bei einem anderen Dienstleister verwendet werden kann. Mögliche anerkannte Standards zum Datenaustausch sind z.B. XML, JSON, YAML, CSV, ODF. Eine Sicherungskopie ist unter eigener Hoheit, wenn sie auf Datenträgern im Besitz der Institution aufbewahrt wird, über die dieser Dienstleister keine Kontrolle hat. Relevant sind dabei auch Konfigurationsdateien, Programmcode und Dokumentationen, die zur Verwendung der Daten erforderlich sind.
