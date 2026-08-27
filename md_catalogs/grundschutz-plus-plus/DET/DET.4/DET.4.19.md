---
x-trestle-set-params:
  det.4.19-prm1:
    values:
---

# DET.4.19 - \[Überwachung von Aktivitäten\] Unautorisierte Sendeanlagen

## Control Statement

Detektion für Räume KANN diesen nach unautorisierten Sendeanlagen durch {{ insert: param, det.4.19-prm1 }} überwachen.

## Control guidance

Bleiben unautorisierte Sendeanlagen unbemerkt, so könnten hierüber Abhörversuche stattfinden oder Störungen legitimer Sender und Empfänger auftreten. Bedenklich sind beispielsweise versteckte Wanzen in Büromöbeln, manipulierte Peripheriegeräte mit eingebauten Sendern, ohne Erlaubnis mitgebrachte Access Points, modifizierte Smartphones mit verdeckten Fernzugriffsfunktionen oder getarnte IoT-Geräte mit Netzwerkverbindung, die sensible Informationen abgreifen und nach außen übertragen könnten. Zum Aufspüren können Wireless Intrusion Detection Systems (WIDS) genutzt werden, welche Sendeanagen auffinden und unbekannte Sender melden. Um unautorisierte Sender effektiv zu erkennen sind auch begleitende Maßnahmen sinnvoll: Die Implementierung von Zugangsbeschränkungen und Mitnahmeverboten für nicht geprüfte elektronische Geräte; die Schulung des Personals zur Erkennung verdächtiger Objekte; sowie die Dokumentation aller autorisierten Geräte in einem Inventar, um unbekannte Signalquellen schnell identifizieren zu können.
