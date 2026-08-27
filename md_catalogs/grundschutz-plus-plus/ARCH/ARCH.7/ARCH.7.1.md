---
x-trestle-set-params:
  arch.7.1-prm1:
    values:
---

# ARCH.7.1 - \[Dedizierte Systeme\] Dedizierte Hostsysteme für Server

## Control Statement

Architektur für Anwendungen SOLLTE Serverdienste ausschließlich auf für die Anwendung dedizierten {{ insert: param, arch.7.1-prm1 }} Hostsystemen platzieren.

## Control guidance

„Serverdienste“ bezeichnen hier die logisch oder physisch abgegrenzten IT-Services (engl. server services), die bestimmte Funktionalitäten einer Anwendung bereitstellen, etwa Datenbankinstanzen, Webserver-Komponenten oder API-Endpunkte. Ein „dediziertes Hostsystem“ (engl. dedicated host system) ist dabei ein physischer oder virtueller Server, der ausschließlich für eine einzelne Anwendung und deren zugehörige Serverdienste betrieben wird, ohne dass darauf weitere fachfremde oder von der Anwendung unabhängige Dienste ausgeführt werden. Mögliche Bereitstellungsformen können virtualisierte Maschinen, Container-fähige Hypervisor-Instanzen, Bare-Metal-Server oder Appliances sein. Diese Abgrenzung dient der klaren Trennung von Verantwortlichkeiten, Konfigurationen und Ressourcen und reduziert die Komplexität innerhalb der Systemlandschaft. Sie schafft eine saubere Zuordnung zwischen Anwendung und ihrer technischen Plattform, was die Nachvollziehbarkeit, Wartbarkeit und Sicherheit der jeweiligen Lösung deutlich erhöht. Ziel ist, dass nicht mehrere Server-Anwendungen auf einem Betriebssystem (oder sogar auf Endgeräten) laufen, um systemische Risiken zu minimieren, die aus Mehrfachnutzung oder unklarer Ressourcenteilung entstehen könnten. Sonst könnte es etwa durch unerwartete Wechselwirkungen zwischen Diensten, fehlerhafte Berechtigungszuweisungen, unbeabsichtigte Seitenkanäle, unkontrollierte Ressourcenkonflikte oder Abhängigkeiten bei Systemupdates zu Betriebsproblemen oder lateralen Bewegungen von Angreifenden kommen. Die Anforderung kann auch durch die Verwendung von virtuellen Maschinen oder Containern realisiert werden.
