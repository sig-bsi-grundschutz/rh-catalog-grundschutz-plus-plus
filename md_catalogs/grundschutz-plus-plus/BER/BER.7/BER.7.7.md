---
x-trestle-set-params:
  ber.7.7-prm1:
    values:
---

# BER.7.7 - \[Schlüsselmanagement\] Kein Transport privater Schlüssel

## Control Statement

Berechtigung KANN den Export privater Schlüssel durch {{ insert: param, ber.7.7-prm1 }} autorisieren.

## Control guidance

Im Allgemeinen ist es sinnvoll, private Schlüssel nur dort zu erzeugen, wo sie auch genutzt werden. Andernfalls könnten sie durch den Export kompromittiert werden. Hiervon sind allerdings zahlreiche Ausnahmen denkbar, z.B. zur Schlüsselerzeugung auf besonders abgesicherten Systemen, zum Transport auf Redundanzsysteme oder zur Datensicherung. Daher ist eine Abwägung sinnvoll, ob der Export zu genehmigen ist.
