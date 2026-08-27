---
x-trestle-set-params:
  arch.5.1.10-prm1:
    values:
---

# ARCH.5.1.10 - \[Perimeterschutz\] Webfilterung

## Control Statement

Architektur für Externe Netzanschlüsse SOLLTE den Zugriff auf Webinhalte anhand von {{ insert: param, arch.5.1.10-prm1 }} einschränken.

## Control guidance

Das World Wide Web ist für zahlreiche Geschäftsprozesse essenziell. Andererseits wird das Web von Angreifern auch für die Verbreitung von illegalen Inhalten, Schadprogrammen oder Phishing verwendet. Durch unkontrollierten Webzugriff könnten etwa Schadcode, Phishing oder Datenabfluss in die Institution gelangen. Kriterien meint hier die festgelegten Maßstäbe, nach denen externe Verbindungen zu Webinhalten gefiltert oder eingeschränkt werden. Im Fachjargon spricht man von filtering criteria oder access control policies. Solche Kriterien können beispielsweise Inhaltskategorien (z. B. Glücksspiel, soziale Netzwerke, Streaming), Reputationsbewertungen von Domains (z. B. „malicious“ oder „suspicious“ laut Threat-Intelligence-Feeds), oder technische Eigenschaften (z. B. bekannte IP-Ranges, Länderzugehörigkeit, verwendete Protokolle/Ports, Signaturen) sein. Sinnvoll ist eine Kombination verschiedener Kriterien. Die Anforderung kann über Filterung im Browser, auf Systemen oder an Netzgrenzen umgesetzt werden (z.B. durch Firewalls, Sicherheitsproxies oder VPN-Gateways).
