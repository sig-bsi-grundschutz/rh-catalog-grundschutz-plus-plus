---
x-trestle-set-params:
  ber.3.12-prm1:
    values:
---

# BER.3.12 - \[Zugangskonten\] Systemsperre bei Inaktivität

## Control Statement

Berechtigung für IT-Systeme SOLLTE eine Sperre bei Inaktivität nach {{ insert: param, ber.3.12-prm1 }} aktivieren.

## Control guidance

Kann durch eine Bildschirmsperre oder Abmeldung (Automatic Session Locking) umgesetzt werden. Eine längere Inaktivität kann z.B. 5-15 Minuten lang sein. Verwendet das System keine eigene Authentifizierung, so ist auch diese Anforderung entbehrlich.
