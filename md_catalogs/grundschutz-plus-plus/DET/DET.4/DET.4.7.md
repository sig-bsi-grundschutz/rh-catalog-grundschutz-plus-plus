# DET.4.7 - \[Überwachung von Aktivitäten\] Auslaufen von Domains

## Control Statement

Detektion für Webserver KANN das Auslaufen von Domains überwachen.

## Control guidance

Wenn Registrierungsfristen und Verlängerungszeiträume nicht im Blick behalten werden, könnte eine Domain aus Versehen verfallen und damit einhergehend Erreichbarkeits­probleme, Vertrauensverluste oder gar Sicherheits­lücken entstehen. Als Beispiele können Domains dienen, die für Web­auftritte, E‑Mail-Systeme oder API-Endpunkte genutzt werden. Ebenso kann es sich um Subdomains handeln, die für interne Tools, Test­umgebungen oder automatisierte Monitoring­dienste registriert sind. Auch Domains, die nur der Weiterleitung auf Haupt­präsenzen dienen oder die für Zertifikats­ver­waltung (z. B. ACME-Challenges) verwendet werden, können unter diese Überwachung fallen. Jede dieser Anwendungsfälle kann potenziell betroffen sein, wenn die Registrierung unbemerkt abläuft. Hilfreich ist hierfür ein zentrales Inventar aller genutzten Domains in dem Registrierungs­daten (Ablaufdatum, Registrar, Kontakt­email) erfasst werden. Automatisierte Scripts oder Aufgaben­tickets können eingerichtet werden, die in festgelegten Abständen (z. B. 60, 30 und 7 Tage vor Ablauf) eine Benachrichtigung auslösen. Auch Monitoring-Plattformen mit DNS-Plugins können verwendet werden, um Fristen zu prüfen und Erinnerungen zu generieren. Zusätzlich kann eine Prozess­beschreibung definiert werden, in der Verantwortlichkeiten und Eskalations­wege bei nahendem Domain­ablauf festgehalten sind, um schnelle Entscheidungen und Verlängerungen zu ermöglichen.
