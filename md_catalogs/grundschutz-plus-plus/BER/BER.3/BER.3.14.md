---
x-trestle-set-params:
  ber.3.14-prm1:
    values:
---

# BER.3.14 - \[Zugangskonten\] Kein Recycling von Zugängen

## Control Statement

Berechtigung SOLLTE die Wiederverwendung von Zugangskonten für {{ insert: param, ber.3.14-prm1 }} blockieren.

## Control guidance

Wiederverwendung von Zugangskonten meint hier die erneute Vergabe oder Reaktivierung zuvor bereits verwendeter Zugangskonten für Einzelpersonen, Gruppen, Rollen, Dienste oder Geräte zu anderen Einzelpersonen, Gruppen, Rollen, Diensten oder Geräten (engl. account reuse, account recycling). Der Parameter „einen bestimmten Zeitraum“ beschreibt eine durch die Institution festgelegte Sperr- oder Karenzfrist, innerhalb derer ein deaktiviertes, entzogenes oder nicht mehr zugeordnetes Konto nicht erneut verwendet werden kann; sinnvolle Werte können je nach Schutzbedarf etwa 90 Tage, 180 Tage, ein Jahr oder bei besonders kritischen bzw. privilegierten Konten eine dauerhafte Nichtwiederverwendung sein. Ohne eine solche Sperrfrist könnte eine neue nutzende Person fälschlich Zugriff auf alte Berechtigungen, Protokollzuordnungen, Postfächer, Schlüssel, Tokens oder Anwendungskontexte erhalten, und ein Sicherheitsvorfall könnte später nicht mehr eindeutig einer handelnden Person oder einem technischen Vorgang zugeordnet werden.
