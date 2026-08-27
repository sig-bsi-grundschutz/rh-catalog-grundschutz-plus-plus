---
x-trestle-set-params:
  ber.3.11-prm1:
    values:
---

# BER.3.11 - \[Zugangskonten\] Anmeldeversuchsgrenze an der Anwendung

## Control Statement

Berechtigung für Anwendungen SOLLTE weitere Anmeldeversuche nach Erreichen von {{ insert: param, ber.3.11-prm1 }} fehlgeschlagenen Versuchen vorübergehend blockieren.

## Control guidance

Häufen sich Anmeldeversuche, so könnte ein Angreifer Zugangsdaten durchprobieren. Durch eine Anmeldeversuchsgrenze wird der Zugriff durch das massenhafte Durchprobieren von Zugangsdaten (Credential Stuffing) verhindert. Dies kann z.B. durch die Begrenzung der Anmeldeversuche pro Client oder pro IP erfolgen. Dies betrifft sowohl die Anmeldung an der Benutzeroberfläche als auch über das Netz. Relevant sind hierbei sowohl primäre als auch ggf. vorhandene sekundäre Zugänge (z.B. Sicherheitsfragen, Passwort zurücksetzen). Für die Wahl des Schwellwertes ist die Anzahl der betroffenen Zugangskonten, die Passwortlänge und der Schutzbedarf der Anwendung von Bedeutung. Je nach Risikoprofil der Anwendung sind verschiedene Lösungen denkbar, z.B. die Verwendung von CAPTCHAS bei Erreichen der Anmeldeversuchsgrenze oder indem der Zeitraum einer Blockierung nach jedem fehlgeschlagenen Anmeldeversuch erhöht wird. Erfordert die Anwendung keine Zugangsdaten, so ist auch diese Anforderung entbehrlich.
