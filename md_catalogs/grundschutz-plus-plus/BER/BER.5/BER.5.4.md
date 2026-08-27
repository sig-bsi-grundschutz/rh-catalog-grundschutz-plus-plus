---
x-trestle-set-params:
  ber.5.4-prm1:
    values:
---

# BER.5.4 - \[Umgang mit Authentisierungsmitteln\] Nur etablierte Kryptographie

## Control Statement

Berechtigung SOLLTE bei kryptografischen Authentifizierungsmitteln die ausschließliche Verwendung etablierter kryptografischer Algorithmen nach {{ insert: param, ber.5.4-prm1 }} verankern.

## Control guidance

Kryptografische Authentifizierungsmittel sind Authentisierungsnachweise, deren Sicherheit wesentlich auf kryptografischen Verfahren beruht, etwa Passwort-Hashing, Zertifikate, Schlüsselpaare, Smartcards, Hardware-Token, Passkeys/FIDO2-Authentifikatoren, signaturbasierte API-Zugänge oder SSH-Schlüssel (engl. cryptographic authenticators). Etablierte kryptografische Algorithmen sind mathematisch fundierte Verschlüsselungsverfahren und Protokolle, die in der aktuellen Praxis nicht mit vertretbarem Aufwand gebrochen werden können, beispielsweise für Signaturen, Message Authentication Codes, Hashfunktionen, Schlüsselableitung oder authentisierte Verschlüsselung. Sie basieren auf mathematisch schwer lösbaren Problemen, bieten Resistenz gegen bekannte kryptanalytische Angriffe, unterstützen ausreichend große Schlüssellängen und wurden von Experten gründlich geprüft und analysiert. Aktuelle etablierte Algorithmen sind in BSI TR-02102 zu finden. Für weitere Details zur Implementierung siehe Detailspezifikation kryptografischer Abläufe und Mechanismen des BSI.
