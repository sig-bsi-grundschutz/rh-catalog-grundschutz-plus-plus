# BER.5.13 - \[Umgang mit Authentisierungsmitteln\] Identitätsüberprüfung

## Control Statement

Berechtigung SOLLTE vor dem Zurücksetzen von Berechtigungsmitteln eine Identitätsüberprüfung verankern.

## Control guidance

Unter einer Identitätsüberprüfung ist hier die Verifikation zu verstehen, ob die anfragende Person tatsächlich die berechtigte Identität besitzt, für die ein neues Passwort vergeben werden soll; in der Fachsprache wird dies häufig als Identity Verification oder Identity Proofing bezeichnet. Ein Passwort-Reset stellt einen besonders sensiblen Vorgang dar, da hierbei bestehende Authentisierungsmerkmale ersetzt werden und eine erfolgreiche Täuschung einem Unbefugten unmittelbar Zugang zu geschützten Informationen und Diensten verschaffen kann. Eine vorgelagerte Identitätsüberprüfung kann das Risiko verringern, dass sich Angreifer durch Social Engineering, gestohlene Kontaktdaten oder die Ausnutzung unzureichender Supportprozesse Zugang zu Benutzerkonten verschaffen könnten. \n\nDas unberechtigte Zurücksetzen von Zugangsdaten ist eine sehr bekannte Angriffsmethode und erfordert vom Täter nur geringe technische Fähigkeiten. Eine eindeutige Identifizierung des Inhabers des Zugangs kann z.B. anhand eines Personalausweises, durch die persönliche Identifikation bei autorisierten Stellen, die Bestätigung über einen unabhängigen zweiten Kommunikationskanal oder die Nutzung bestehender Mehrfaktor-Authentisierung erfolgen.
