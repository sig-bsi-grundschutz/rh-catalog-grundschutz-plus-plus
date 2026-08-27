---
x-trestle-set-params:
  det.4.11.3-prm1:
    values:
---

# DET.4.11.3 - \[Überwachung von Aktivitäten\] Netzverkehrsfluss

## Control Statement

Detektion für Netze KANN auf kritische Netzverkehrsflüsse anhand von {{ insert: param, det.4.11.3-prm1 }} überwachen.

## Control guidance

Ein Netzverkehrsfluss ist eine Aufzeichnung von Verkehrsdaten einer Netzwerkverbindung (wie Quell-/Ziel-IP, Ports, Protokoll, übertragene Datenmenge und Zeitdauer). Die Aufzeichnung des gesamten Verkehrs (Packet Capture) des vollständigen Inhalts aller Datenpakete ist hierzu nicht erforderlich, sodass die zu untersuchende Datenmenge überschaubar bleibt. Allerdings sind hier Compliance-Anforderungen zur Datenspeicherung relevant. Für datenschutzrechtliche Fragen zu Verkehrsdaten kann der BfDI Leitfaden Speicherung Verkehrsdaten als Grundlage genutzt werden. Beispiele für Kriterien sind die Aufzeichnung an wichtigen Netzgrenzen (DMS-Internet), in kritischen Netzen, zwischen Serversystemen oder bei Leistungsproblemen.
