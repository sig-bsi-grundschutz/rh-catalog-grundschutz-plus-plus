---
x-trestle-set-params:
  geb.10.1.2-prm1:
    values:
---

# GEB.10.1.2 - \[Schutz vor Elementarschäden\] Klimamessung

## Control Statement

Gebäudemanagement für Serverräume SOLLTE Lufttemperatur und Luftfeuchtigkeit anhand von {{ insert: param, geb.10.1.2-prm1 }} überwachen.

## Control guidance

IT-Infrastruktur benötigt typischerweise eine Umwelttemperatur von nicht viel mehr als 25°C und eine Luftfeuchtigkeit von nicht über 60%. Bei höheren Werten altern Komponenten schneller und das Risiko von Ausfällen durch Abwärme oder Spannungsüberschläge steigt. Ermitteln Sie Grenzwerte anhand der Herstellerangaben der im Raum eingesetzten Komponenten. Die Überwachung kann mit klimatechnischen Sensoren in den Geräten selbst oder im Raum realisiert werden. Eine saisonale Anpassung der Lüftungsanlagen kann erforderlich sein, insbesondere in Einrichtungen, die mit Eco-Modus arbeiten.
