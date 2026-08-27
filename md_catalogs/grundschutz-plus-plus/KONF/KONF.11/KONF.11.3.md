---
x-trestle-set-params:
  konf.11.3-prm1:
    values:
---

# KONF.11.3 - \[Vertrauensbeziehungen\] Veröffentlichung von Domain-Infomationen

## Control Statement

Konfiguration für DNS-Server SOLLTE die Veröffentlichung von Domain-Infomationen anhand von {{ insert: param, konf.11.3-prm1 }} einschränken.

## Control guidance

Angreifer nutzen häufig DNS um das Netz zu erkunden (DNS-Reconnaissance). Veröffentlichen Sie Domain-Informationen nur, wenn diese zu einem Dienst gehören, der zur externen Nutzung gedacht ist. Nur intern benötigte DNS-Einträge dagegen bleiben intern. Kriterien können z.B. Domains oder Subdomain sein (intern.domain.com vs www.domain.com).
