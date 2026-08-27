---
x-trestle-set-params:
  det.4.12.1-prm1:
    values:
---

# DET.4.12.1 - \[Überwachung von Aktivitäten\] Auslastung des Netzes

## Control Statement

Detektion für Netze SOLLTE die Auslastung des Netzes anhand von {{ insert: param, det.4.12.1-prm1 }} überwachen.

## Control guidance

Die Überwachung der Netzauslastung ermöglicht eine schnelle Reaktion bei Verfügbarkeitsproblemen. Wichtige Indikatoren sind Auslastung der verfügbaren Bandbreite, Netzlatenz und Packverluste. Unerwartet hoher Datenverkehr kann auch ein Indiz für einen unautorisierten Zugriff auf große Datenmengen sein. Zur Umsetzung ist es zweckmäßig zunächst Normwerte zu ermitteln (Baselining).
