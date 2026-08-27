---
x-trestle-set-params:
  konf.15.1-prm1:
    values:
  konf.15.1-prm2:
    values:
---

# KONF.15.1 - \[Ressourcenauslastung\] Begrenzung des Speicherplatzes

## Control Statement

Konfiguration für Anwendungen von Hostsystemen KANN in der Anwendung zur Verfügung stehenden Speicherplatz pro {{ insert: param, konf.15.1-prm1 }} anhand von {{ insert: param, konf.15.1-prm2 }} einschränken.

## Control guidance

Dies ist besonders in Multi-Tenant-Architekturen relevant, wie sie häufig bei Cloud-Diensten oder SaaS-Anwendungen (Software as a Service) zum Einsatz kommen. Ein solcher maximaler Schwellwert (engl. threshold) könnte beispielsweise 5 GB oder 10 GB betragen und stellt die Obergrenze für den Speicherplatz dar, der einem einzelnen Konto oder Mandanten zugewiesen wird. Die Beschränkung des verfügbaren Speicherplatzes kann verhindern, dass ein einzelnes Konto oder ein Mandant die gesamten Ressourcen des Hostsystems belegt und so die Leistung für andere Nutzer negativ beeinflusst, was zu einer Denial-of-Service-Situation (DoS) führen könnte. Bei der Umsetzung ist es sinnvoll auch ein Benachrichtigungssystem zu etablieren, das Nutzer oder Administratoren informiert, wenn ein Schwellenwert kurz vor der Überschreitung steht. Zudem können automatisierte Prozesse zur Datenbereinigung (data lifecycle management) in Betracht gezogen werden, die ältere oder nicht mehr benötigte Dateien in solchen Fällen archivieren oder löschen, um den Speicherplatz effizient zu nutzen. Die Institution kann auch verschiedene Schwellenwerte für unterschiedliche Kontotypen oder Mandanten festlegen, basierend auf deren spezifischen Bedürfnissen.
