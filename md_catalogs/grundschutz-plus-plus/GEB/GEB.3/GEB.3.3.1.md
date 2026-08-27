---
x-trestle-set-params:
  geb.3.3.1-prm1:
    values:
---

# GEB.3.3.1 - \[Physischer Zutritt\] Zugangskontrollanlage

## Control Statement

Gebäudemanagement für Standorte KANN Zutritte durch {{ insert: param, geb.3.3.1-prm1 }} im Einklang mit den Festlegungen des Identitäts- und Berechtigungsmanagements authentifizieren.

## Control guidance

Der Einsatz einer automatischen Zugangskontrollanlage zur Authentifizierung von Personen dient primär dem Schutz von sensiblen Bereichen, vertraulichen Informationen und kritischer Infrastruktur. Durch diese Maßnahme kann sichergestellt werden, dass nur autorisierte Personen Zutritt zu geschützten Bereichen erhalten, wodurch das Risiko von Industriespionage, Datendiebstahl oder Sabotage erheblich reduziert werden kann. Ohne eine solche Kontrolle könnte es beispielsweise zu unbefugtem Zutritt durch Fremde kommen, die sich als Mitarbeiter ausgeben, oder zu einem "Tailgating"-Vorfall, bei dem Unbefugte autorisierten Personen unbemerkt folgen und sich so Zugang verschaffen. Bei der Implementierung einer automatischen Zugangskontrollanlage kann eine mehrfaktorielle Authentifizierung in Betracht gezogen werden, die auf einer Kombination aus Besitz (z.B. Chipkarte, Token), Wissen (PIN-Code, Passwort) und/oder biometrischen Merkmalen (Fingerabdruck, Gesichtserkennung) basiert. Die Zugangsrechte können granular nach Personengruppen, Zeitfenstern und Bereichen differenziert werden, was die Sicherheit weiter erhöht. Für eine effektive Umsetzung kann die regelmäßige Überprüfung der Protokolle der Zugangskontrollanlage auf ungewöhnliche Aktivitäten hilfreich sein, ebenso wie regelmäßige Sensibilisierungsmaßnahmen für Mitarbeiter bezüglich der korrekten Nutzung der Anlage und der Vermeidung von Sicherheitslücken wie dem gemeinsamen Nutzen von Zugangsmitteln. Die Formulierung "im Einklang mit den Festlegungen des Identitäts- und Berechtigungsmanagements" bedeutet, dass die Authentifizierung so erfolgt, wie in der Praktik IDM festgelegt. Hierzu gehört insbesondere die Verwendung aktueller kryptographischer Verfahren, wie sie im Thema Kryptographie zu finden ist.
