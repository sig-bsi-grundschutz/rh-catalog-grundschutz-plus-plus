---
x-trestle-set-params:
  arch.6.1-prm1:
    values:
---

# ARCH.6.1 - \[Vertraulichkeit und Integrität im Weitverkehrsnetz\] Kontrollierte Verbindungsführung

## Control Statement

Architektur für Externe Netzanschlüsse KANN eine {{ insert: param, arch.6.1-prm1 }} kontrollierte Verbindungsführung für Weitverkehrsverbindungen aktivieren.

## Control guidance

Unter einer physisch kontrollierten Verbindungsführung kann in diesem Kontext die Verwendung dedizierter Leitungswege (Dark Fiber), sowie Hardware-Komponenten wie Router, Firewalls oder Trennstellen verstanden werden, die den Zugriff auf Leitungen oder Ports unmittelbar begrenzen. Eine logisch kontrollierte Verbindungsführung kann durch softwarebasierte Mechanismen wie VLANs, VPN-Tunnel oder Routing-Regeln erfolgen, die den Datenverkehr unabhängig von der physischen Leitung steuern. Ohne eine kontrollierte Verbindungsführung könnte ein Angreifer über eine ungeschützte oder direkt angebundene Leitung in interne Systeme eindringen und dort Schadsoftware platzieren, Daten manipulieren oder vertrauliche Informationen abziehen. Ebenso könnte durch eine unzureichend kontrollierte Verbindung ein Ausfall der Netzstabilität eintreten, etwa wenn über eine falsch konfigurierte Schnittstelle großflächiger Datenverkehr einbricht und produktive Systeme beeinträchtigt. Eine kontrollierte Architektur kann dagegen Angriffsflächen reduzieren, Datenströme nachvollziehbar machen und die Sicherheit der Informationsflüsse zwischen Institution und externen Partnern oder Netzanbietern erhöhen. Die Umsetzung kann beispielsweise durch klar definierte Übergabepunkte zum externen Netz erfolgen, an denen sämtliche eingehenden und ausgehenden Verbindungen zentral zusammenlaufen und durch Filter- oder Segmentierungsmechanismen geprüft werden.
