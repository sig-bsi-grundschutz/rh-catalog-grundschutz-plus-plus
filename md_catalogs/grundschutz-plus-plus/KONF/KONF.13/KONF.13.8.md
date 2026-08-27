---
x-trestle-set-params:
  konf.13.8-prm1:
    values:
---

# KONF.13.8 - \[Senden und Empfangen von Nachrichten\] DMARC-Reports

## Control Statement

Konfiguration für E-Mail KANN DMARC-Reports {{ insert: param, konf.13.8-prm1 }} überprüfen.

## Control guidance

Mit DMARC kann der Empfänger dem Sender automatische Berichte über den DMARC-Status empfangener E-Mails bereitstellen. Diese Berichte liefern Hinweise auf fehlgeschlagene Authentifizierungsprüfungen, Fehlkonfigurationen oder Missbrauchsversuche. Eine automatisierte Auswertung unterstützt dabei, Zustellprobleme frühzeitig zu erkennen und geeignete Korrekturmaßnahmen abzuleiten.
