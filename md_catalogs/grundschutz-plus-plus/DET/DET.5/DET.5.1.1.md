---
x-trestle-set-params:
  det.5.1.1-prm1:
    values:
  det.5.1.1-prm2:
    values:
---

# DET.5.1.1 - \[Management von Schwachstellen\] Risikobasierte Priorisierung

## Control Statement

Detektion KANN erkannte Schwachstellen anhand von {{ insert: param, det.5.1.1-prm1 }} innerhalb {{ insert: param, det.5.1.1-prm2 }} überprüfen.

## Control guidance

Bei einer risikobasierten Priorisierung wird nicht nur die Ausnutzbarkeit der Schwachstelle im Allgemeinen, z.B. durch einen CVS-Score, zur Priorisierung herangezogen, sondern die Beurteilung erfolgt durch eine Kombination solcher generellen Informationen mit dem individuellen Risikoprofil der betroffenen Assets. Dies ermöglicht es, Schwachstellen deutlich passgenauer zu beurteilen und die wirklich kritischen Schwachstellen zuerst zu patchen oder mitigieren. Hierzu können CVSS-Score, Informationen aus der Threat Intelligence und aus der Risikobewertung von Geschäftsprozessen kombiniert werden. Hierbei können auch automatisierte Verfahren angewendet werden, z.BMultiplikation von Kennzahlen zur Risikobewertung und von CVSS in Kombination mit Schwellwerten. Ergebnisdokument kann z.B. eine Risikomatrix, oder eine eigene CVE-Bewertungsrubrik sein.
