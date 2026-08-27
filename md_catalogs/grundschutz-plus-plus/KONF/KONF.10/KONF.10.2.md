---
x-trestle-set-params:
  konf.10.2-prm1:
    values:
---

# KONF.10.2 - \[Konfiguration von Anwendungen\] Kryptographische Verfahren in Anwendungen

## Control Statement

Konfiguration für Anwendungen SOLLTE kryptographische Verfahren nach {{ insert: param, konf.10.2-prm1 }} im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement aktivieren.

## Control guidance

Kryptographie wird für die Authentifizierung, Verschlüsselung und Integritätprüfung in Anwendungen verwendet, z.B. bei der Anmeldung an der Anwendung oder digitalen Signierung von Nachrichten. Die Formulierung "im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik Berechtigung (BER) festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Schlüsselmanagement zu finden ist. Anerkannte kryptographische Verfahren sind in der BSI TR-02102 zu finden.
