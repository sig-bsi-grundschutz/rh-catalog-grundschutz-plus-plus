---
x-trestle-set-params:
  konf.9.2-prm1:
    values:
---

# KONF.9.2 - \[Verfügbarkeit von Ressourcen\] Begrenzung der Rechenleistung

## Control Statement

Konfiguration für Hostsysteme KANN die zur Verfügung stehende Rechenleistung anhand von {{ insert: param, konf.9.2-prm1 }} einschränken.

## Control guidance

Dies kann durch eine Beschränkung der Anzahl verwendeter Rechenkerne, der Rechenleistung pro Rechenkern oder durch eine indirekte Beschränkung (z.B. eine begrenzte Menge an Anfragen oder Eingabetoken in Anwendungen) umgesetzt werden.
