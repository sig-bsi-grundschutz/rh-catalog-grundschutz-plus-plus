---
x-trestle-set-params:
  arch.9.3-prm1:
    values:
---

# ARCH.9.3 - \[Kapazitätsmanagement\] Automatische Skalierung

## Control Statement

Architektur für Anwendungen KANN eine automatische Skalierung der von der Anwendung verwendeten Computerinstanzen anhand von {{ insert: param, arch.9.3-prm1 }} aktivieren.

## Control guidance

Automatische Skalierung ist die Fähigkeit einer Anwendungsarchitektur, die Anzahl der von einer Anwendung genutzten Serverinstanzen dynamisch und automatisiert zu erhöhen oder zu verringern. Grundlage für diese Anpassungen sind definierte Schwellwerte, die beispielsweise auf Metriken wie CPU-Auslastung, Speichernutzung oder Antwortzeiten beruhen können. Damit wird festgelegt, bei welchen messbaren Bedingungen zusätzliche Server gestartet oder wieder abgeschaltet werden. Typische Werte für Schwellwerte können etwa „80 % durchschnittliche CPU-Auslastung über 5 Minuten“, „weniger als 500 MB freier Arbeitsspeicher“ oder „Antwortzeit über 2 Sekunden bei mehr als 100 gleichzeitigen Anfragen“ sein. Ohne Auto-Scaling könnte es vorkommen, dass Anwendungen unter hoher Last nicht mehr reagieren, Datenverlust entsteht oder ganze Dienste für Nutzer unerreichbar werden. Umgekehrt kann Auto-Scaling helfen, Kosten und Ressourcen zu optimieren, indem ungenutzte Server wieder abgeschaltet werden. Eine sinnvolle Umsetzung kann beispielsweise durch den Einsatz von cloudbasierten Skalierungsgruppen erfolgen, die auf klar definierte Metriken reagieren, oder durch Virtualisierungsplattformen, die zusätzliche Instanzen automatisch bereitstellen. Praktische Tipps sind etwa (1) die Definition realistischer und getesteter Schwellwerte auf Basis historischer Lastprofile, (2) die Einrichtung von Stresstests, um das Verhalten bei Erreichen der Schwellwerte zu validieren, und (3) die Einführung von Alarmierungen, die Administratoren über ungewöhnlich häufiges Hoch- oder Runterskalieren informieren können. So kann die Institution sicherstellen, dass Auto-Scaling verlässlich funktioniert und gleichzeitig eine ökonomische Ressourcennutzung gewährleistet bleibt.
