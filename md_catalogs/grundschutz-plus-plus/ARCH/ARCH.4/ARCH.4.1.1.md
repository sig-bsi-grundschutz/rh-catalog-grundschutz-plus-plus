---
x-trestle-set-params:
  arch.4.1.1-prm1:
    values:
---

# ARCH.4.1.1 - \[Zugangsbeschränkungen\] Dynamische Netzzugangskontrolle

## Control Statement

Architektur für Interne Netzsegmente SOLLTE den Zugriff von IT-Systemen auf das Netzsegment anhand {{ insert: param, arch.4.1.1-prm1 }} im Einklang mit den zugehörigen Anforderungen des Identitäts- und Berechtigungsmanagements authentifizieren.

## Control guidance

Bei der dynamischen Netzzugangskontrolle (Posturing oder Dynamic NAC) wird vor dem Netzzugang auch der Zustand des IT-Systems geprüft, z.B. der aktuelle Patchlevel des Systems oder von Erkennungssignaturen. Hierzu gehört auch die softwaredefinierte Netzzugangskontrolle, die dynamisch auf Aktivitäten des Systems oder aktuelle Threat Intelligence reagieren kann. Empfehlenswert ist es hierbei, die Konfiguration der Systeme automatisiert vorzunehmen, z.B. über eine automatische Supplicant-Konfiguration beim Rollout und die Zuweisung von Zertifikaten über Enrollment-Dienste. Die Formulierung "im Einklang mit den Festlegungen des Identitäts- und Berechtigungsmanagements" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik IDM festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist.
