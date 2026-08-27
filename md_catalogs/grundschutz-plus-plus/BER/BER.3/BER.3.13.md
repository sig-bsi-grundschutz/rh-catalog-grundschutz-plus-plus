---
x-trestle-set-params:
  ber.3.13-prm1:
    values:
---

# BER.3.13 - \[Zugangskonten\] Sperre der Anwendung bei Inaktivität

## Control Statement

Berechtigung für Anwendungen SOLLTE eine Sperre bei Inaktivität nach {{ insert: param, ber.3.13-prm1 }} aktivieren.

## Control guidance

Kann je nach Anmeldeweg durch eine Abmeldung (Automatic Session Locking) direkt an der Anwendung, über Single-Sign-On oder (bei Anmeldung über das Netz) die Trennung der Netzverbindung umgesetzt werden. Eine längere Inaktivität kann z.B. 5-15 Minuten lang sein. Verfügt die Anwendung über keine eigene Authentifizierungsmethode, so ist die Anforderung entbehrlich.
