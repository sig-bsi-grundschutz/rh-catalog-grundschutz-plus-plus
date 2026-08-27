---
x-trestle-set-params:
  konf.11.4-prm1:
    values:
---

# KONF.11.4 - \[Vertrauensbeziehungen\] Erraten von Zugriffslinks

## Control Statement

Konfiguration für Webanwendungen SOLLTE das Durchprobieren von Zugriffslinks durch {{ insert: param, konf.11.4-prm1 }} blockieren.

## Control guidance

Ermöglichen Links den Zugriff auf vertrauliche Daten ohne Authentifizierung, so könnten Angreifer versuchen diese zu finden, z.B. mit Durchprobieren von Meeting-Links oder Ressourcen-URLs. Mögliche Maßnahmen sind Nicht-Sequentielle IDs mit hoher Entropie, Rate Limiting von Anfragen oder CAPTCHA. Hierbei bietet sich eine Kombination von Maßnahmen an, die Anzahl erwarteter Zugriffe, Verfügbarkeits- und Usability-Kriterien ebenso beachtet wie das Risikoprofil der Anwendung. Bietet die Webanwendung keinerlei Zugriff auf schützenswerte Informationen ohne Authentifizierung, so ist die Anforderung entbehrlich.
