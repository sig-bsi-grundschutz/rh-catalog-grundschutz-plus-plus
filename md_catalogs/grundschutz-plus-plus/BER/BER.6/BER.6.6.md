---
x-trestle-set-params:
  ber.6.6-prm1:
    values:
---

# BER.6.6 - \[Passwortgebrauch\] Monitoring von Zugangsdaten

## Control Statement

Berechtigung SOLLTE Zugangsdaten auf Kompromittierung durch {{ insert: param, ber.6.6-prm1 }} überwachen.

## Control guidance

Eine Kompromittierung meint hier, dass Zugangsdaten wie Benutzername und Passwort (englisch: credentials) von Unbefugten eingesehen, abgefangen oder manipuliert wurden, sodass ein Missbrauch für unautorisierte Zugriffe möglich wird. Dies könnte etwa durch Leaks in Datenbanken, durch Phishing-Angriffe oder durch das Abfangen unverschlüsselter Übertragungen entstehen. Ein automatisierter Mechanismus bezeichnet hierbei eine technische Lösung, die ohne manuelles Zutun kontinuierlich prüft, ob bekannte Indikatoren einer Kompromittierung vorliegen (englisch: credential monitoring system). Geeignete Mechanismen können etwa Credential-Leak-Monitoring-Dienste, Data Breach Checker oder Darknet-Scanning-Tools sein. Der Zweck dieser Vorgabe liegt darin, dass ein frühzeitiges Erkennen von kompromittierten Zugangsdaten helfen kann, unautorisierte Logins und den Missbrauch sensibler Systeme zu verhindern; ohne eine solche Überwachung könnte ein Angreifer über lange Zeit unentdeckt mit gestohlenen Daten arbeiten und kritische Schäden verursachen. Ergeben sich hierbei Anzeichen auf eine Kompromittierung oder einen Leak der Zugangsdaten, so kann als Reaktion ein Wechsel der Zugangsdaten über einen nicht kompromittierten Kommunikationskanal veranlasst oder schlicht das betroffene Zugangskonto gesperrt werden.
