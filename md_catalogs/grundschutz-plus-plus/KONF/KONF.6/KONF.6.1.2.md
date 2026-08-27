---
x-trestle-set-params:
  konf.6.1.2-prm1:
    values:
---

# KONF.6.1.2 - \[Rollen und Berechtigungen\] Isolierung von Anwendungen

## Control Statement

Konfiguration für IT-Systeme KANN die Isolierung von {{ insert: param, konf.6.1.2-prm1 }} aktivieren.

## Control guidance

Die Isolation von Anwendungen (auch Application Sandboxing oder Application Confinement genannt) kann die Auswirkungen von Fehlfunktionen oder einer Kompromittierung auf andere Anwendungen und Systemressourcen begrenzen. Hierzu werden Zugriffe einer Anwendung auf beispielsweise Prozesse, Dateisystembereiche, Netzwerkressourcen oder Geräte auf die für ihren Betrieb vorgesehenen Ressourcen und Schnittstellen beschränkt. „Bestimmte Anwendungen“ bezeichnet die Anwendungen, für die aufgrund ihres Einsatzzwecks oder der damit verbundenen Risiken eine isolierte Ausführung vorgesehen ist. Die Isolation kann mit unterschiedlichen technischen Mechanismen umgesetzt werden. Hierzu zählen beispielsweise Betriebssystemfunktionen zur Zugriffsbeschränkung wie SELinux- oder AppArmor-Profile, containerbasierte Isolation oder die Ausführung in virtuellen Maschinen. Die verschiedenen Verfahren bieten unterschiedliche Isolationsstärken. Container teilen sich typischerweise den Kernel des Hostsystems, während virtuelle Maschinen zusätzlich über ein eigenes Gastbetriebssystem und einen eigenen Kernel gegenüber dem Hostsystem abgegrenzt sind.
