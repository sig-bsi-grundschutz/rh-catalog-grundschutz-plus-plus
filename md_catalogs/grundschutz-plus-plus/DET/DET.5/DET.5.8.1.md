---
x-trestle-set-params:
  det.5.8.1-prm1:
    values:
  det.5.8.1-prm2:
    values:
---

# DET.5.8.1 - \[Management von Schwachstellen\] Auswertung öffentlicher Quellen

## Control Statement

Detektion KANN öffentliche Quellen auf Hinweise zu eigenen Schwachstellen anhand von {{ insert: param, det.5.8.1-prm1 }} {{ insert: param, det.5.8.1-prm2 }} überprüfen.

## Control guidance

Öffentliche Quellen können Hinweise zu aktuellen Schwachstellen geben oder sogar auf die Vorbereitung von Angriffen geben, beispielsweise auf die Nachahmung von Webseiten oder Marken, sowie Typosquatting. Auch Datenleaks wie API-Keys oder falsch konfigurierte Cloud-Systeme können hierüber aufgedeckt werden. Relevante öffentliche Quellen können z.B. Schwachstellendatenbanken, Fachmedien, Security Mailing Listen, Dark Web Foren, Code Repositories, Suchmaschinen oder Soziale Medien sein. Als Kriterien zur Auswahl können verschiedene Suchbegriffe oder Suchmuster herangezogen werden, z.B. Bezeichnungen verwendeter Betriebssysteme oder Komponenten, eigene DNS-Domains, E-Mailadressen, API-Schnittstellen, Markennamen. Die Umsetzung kann durch eigenes Personal oder Threat Intelligence Dienstleister erfolgen.
