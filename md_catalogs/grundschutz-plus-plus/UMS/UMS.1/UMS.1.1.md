---
x-trestle-set-params:
  ums.1.1-prm1:
    values:
---

# UMS.1.1 - \[Umsetzungsstatus\] Ermittlung des Umsetzungsstatus

## Control Statement

Umsetzung MUSS den Umsetzungsstatus der Anforderungen im Anforderungspaket vollständig {{ insert: param, ums.1.1-prm1 }} überprüfen.

## Control guidance

Der Umsetzungsstatus einer Anforderung kann grundsätzlich nur „umgesetzt“ („ja“) oder „nicht umgesetzt“ („nein“) sein. Eine Anforderung gilt nur dann als umgesetzt, wenn sie selbst sowie alle in Abhängigkeit stehenden Anforderungen umgesetzt sind.
