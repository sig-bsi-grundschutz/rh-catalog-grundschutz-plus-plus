---
x-trestle-set-params:
  arch.9.2-prm1:
    values:
---

# ARCH.9.2 - \[Kapazitätsmanagement\] Lastverteilung

## Control Statement

Architektur für Anwendungen KANN eine {{ insert: param, arch.9.2-prm1 }} automatische Lastverteilung aktivieren.

## Control guidance

Netzbasierte Lastverteilung bedeutet hier, dass ein dedizierter Netzwerkdienst – z. B. über Load-Balancer oder Layer-4/Layer-7-Komponenten – den eingehenden Datenverkehr dynamisch auf mehrere Server oder Dienste verteilt. Serverbasierte Lastverteilung bedeutet dagegen, dass die beteiligten Systeme selbst Mechanismen bereitstellen, um Anfragen untereinander weiterzugeben oder zu koordinieren, etwa durch eingebaute Proxy- oder Cluster-Funktionalitäten. Der Zweck einer solchen Verteilung liegt in der Absicherung der Verfügbarkeit: Ein plötzlicher Anstieg von Benutzeranfragen könnte ansonsten einzelne Systeme überlasten und zu Ausfällen führen; ebenso könnte ein Defekt in einem Knoten die Gesamtleistung stark beeinträchtigen. Mit geeigneter Lastverteilung kann die Stabilität der Anwendung verbessert und ein unterbrechungsfreier Betrieb unterstützt werden. Zur Umsetzung kann die Institution netzbasierte Verfahren einsetzen, etwa (1) hardware- oder softwaregestützte Load-Balancer, die eingehende Verbindungen nach konfigurierbaren Regeln verteilen, (2) DNS-basierte Verfahren, bei denen Abfragen gezielt auf unterschiedliche Zielsysteme geleitet werden, oder (3) virtuelle Appliances in virtualisierten oder Cloud-nahen Umgebungen. Serverbasierte Verfahren können etwa durch den Einsatz von Cluster-Software, eingebaute Reverse-Proxy-Funktionen in Webservern oder den Einsatz von Message-Queues realisiert werden. Dabei kann eine Institution darauf achten, dass Monitoring-Funktionen integriert sind, um Engpässe frühzeitig zu erkennen, und dass Konfigurationen für Failover-Szenarien getestet werden. Auch ein gestuftes Testen der Lastverteilung unter realitätsnahen Bedingungen kann helfen, die Wirksamkeit sicherzustellen.
