---
x-trestle-set-params:
  arch.2.2-prm1:
    values:
---

# ARCH.2.2 - \[Netzdesign\] Einschränkung von Verbindungen zwischen Segmenten

## Control Statement

Architektur für Netze SOLLTE Verbindungen zwischen Netzsegmenten anhand von {{ insert: param, arch.2.2-prm1 }} einschränken.

## Control guidance

Dient dem Ziel, die Angriffsfläche innerhalb interner und externer Netze zu reduzieren und die Ausbreitung potenzieller Schadsoftware oder unberechtigter Zugriffe einzudämmen. Ohne solche Begrenzungen könnte ein einzelner kompromittierter Bereich direkten Zugriff auf weitere sensible Segmente erhalten und dadurch Geschäftsprozesse massiv beeinträchtigen. Beispielsweise benötigt ein Endgerät Verbindungen zu internen Servern und Druckern, während Gäste lediglich auf den Internetanschluss Zugriff benötigen. Im Blick auf weitreichende Sicherheitsvorfälle ist hier insbesondere die Trennung interner Netzsegmente vom Internet zu beachten. Diese Regeln können auf Kriterien wie Gerätetyp (z. B. Laptop, IoT-Gerät), Benutzerrolle (z. B. Administrator, Gast), physischem Anschlussort oder Uhrzeit basieren. Eine klare Trennung von Benutzergruppen über VLANs oder dynamische ACLs erhöht die Sicherheit und Transparenz. Für die Einführung in eine bestehende Umgebung kann ein gestuftes Vorgehen gewählt werden: (1) Zunächst wird ein Überwachungsmodus ("Audit-Only") aktiviert, der protokolliert, welche Zugriffe durch eine strengere Richtlinie verweigert würden, ohne sie tatsächlich zu blockieren. (2) Anschließend werden diese Protokolle analysiert, um legitime, für den Geschäftsbetrieb notwendige Zugriffe zu identifizieren und diese gezielt in die jeweiligen Rollen und Berechtigungsgruppen aufzunehmen. (3) Erst wenn keine legitimen Zugriffe mehr in den Protokollen als "verweigert" auftauchen, wird die Richtlinie scharf geschaltet und blockiert aktiv alle nicht explizit erlaubten Zugriffe.
