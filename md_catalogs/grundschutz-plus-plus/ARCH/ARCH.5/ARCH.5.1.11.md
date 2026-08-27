# ARCH.5.1.11 - \[Perimeterschutz\] P-A-P-Struktur

## Control Statement

Architektur für Externe Netzanschlüsse SOLLTE eine P-A-P-Struktur für eingehende und ausgehende Verbindungen installieren.

## Control guidance

Die P-A-P-Struktur besteht aus 2 Paketfiltern (P) und einem Filter auf Anwendungsebene (A), die durch Hardware getrennt sind und alle Verbindungen auf Anwendungsebene filtern. In Hardware getrennte Systeme sind hier solche, die jeweils über eigene Rechenkomponenten (CPU, RAM, etc.) verfügen und nur über Netzverbindungen zusammenhängen. Dies minimiert die Angriffsfläche für übergreifende Angriffe wie Covert Channel oder Side Channel.
