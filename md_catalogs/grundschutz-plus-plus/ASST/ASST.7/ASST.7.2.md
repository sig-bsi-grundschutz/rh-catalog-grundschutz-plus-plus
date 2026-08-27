---
x-trestle-set-params:
  asst.7.2-prm1:
    values:
---

# ASST.7.2 - \[Löschen und Vernichten\] Aufbewahrungs- und Löschfristen

## Control Statement

Informationen und Assets für Daten SOLLTE die Aufbewahrung für {{ insert: param, asst.7.2-prm1 }} verankern.

## Control guidance

Klar festgelegte und in Prozessen verankerte Löschfristen helfen Sicherheits- und Compliancerisiken zu minimieren, indem Informationen entsorgt werden, wenn sie nicht mehr benötigt werden. Dies gilt sowohl für Originaldaten als auch für Kopien und archivierte Aufzeichnungen, einschließlich Protokolldateien. Hier besteht ein enger Bezug zu Compliance-Verpflichtungen, sowohl zur Aufbewahrung (z.B. für Nachweispflichten aus dem Steuerrecht) als auch zur Löschung (z.B. aus dem Datenschutzrecht). Die Auswahl der Methode zum Löschen hängt von der Vertraulichkeit der Daten, verwendeten Anwendungen oder Speichermedien und ggf. bestehenden Compliance-Verpflichtungen ab. Eine Herausforderung stellt dabei der Umgang mit Datenkopien in Datensicherungen dar. Da das nachträgliche Herausfiltern bestimmter Daten aus Datensicherungen häufig sehr aufwändig ist, ist es empfehlenswert die Versionierung der Datensicherungen so zu gestalten, dass die Daten zum Ablauf der Löschfrist ohnehin mit neueren Datensicherungen überschrieben wurden oder ältere Kopien der Datensicherung insgesamt gelöscht sind. Für kurzlebige Daten bietet es sich an diese nicht in eine einzige zentrale Datensicherung aufzunehmen, sondern je nach Schutzbedarf an Integrität und Verfügbarkeit dieser Daten gar keine oder eine Datensicherung für kurzlebige Daten, z.B. Diagnosedaten mit Personenbezug, vorzuhalten.
