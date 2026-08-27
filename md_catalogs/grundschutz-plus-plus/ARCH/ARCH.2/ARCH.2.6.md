---
x-trestle-set-params:
  arch.2.6-prm1:
    values:
---

# ARCH.2.6 - \[Netzdesign\] Topologieüberwachung

## Control Statement

Architektur für Netze SOLLTE die Einhaltung der Netzarchitektur {{ insert: param, arch.2.6-prm1 }} überprüfen.

## Control guidance

Unbeabsichtigte Netzverbindungen können z.B. über falsch gesteckte Kabel, WLAN auf Clients oder Modems im öffentlichen Telefonnetz (PSTN) an einer TK-Anlage entstehen. Die Anforderung kann durch Netzscans, Software zur Topologieüberwachung oder Protokollanalyse umgesetzt werden. Hierbei sind auch virtualisierte Systeme auf VM-Hosts zu berücksichtigen.
