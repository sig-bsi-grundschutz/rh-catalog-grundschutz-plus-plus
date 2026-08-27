---
x-trestle-set-params:
  det.6.1.1-prm1:
    values:
  det.6.1.1-prm2:
    values:
---

# DET.6.1.1 - \[Vorfallserkennung\] Automatisierte Feststellung

## Control Statement

Detektion SOLLTE kritische Vorfälle anhand von {{ insert: param, det.6.1.1-prm1 }} durch {{ insert: param, det.6.1.1-prm2 }} protokollieren.

## Control guidance

Zur Erfüllung der Anforderung ist es nicht erforderlich, dass alle denkbaren Sicherheitsvorfälle automatisch erkannt werden, sondern nur, dass diejenigen Vorfälle, die in der vorhandenen Infrastruktur automatisch feststellbar sind und mit einem hohen Risiko verbunden sind, automatisch festgestellt werden. Beispiele sind hier ein Virenbefall des zentralen Verzeichnisdienstes, unautorisierte Datenabflüsse oder das Aufbrechen eines Fensters im Sicherheitsbereich. Ressourcen meint hier z.B. Systeme, Zugangskonten, Datenkategorien.
