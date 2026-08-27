# BER.5.8 - \[Umgang mit Authentisierungsmitteln\] Mehr-Faktor-Authentisierung am Perimeter

## Control Statement

Berechtigung für Anwendungen von Externe Netzanschlüssen SOLLTE Phishing-resistente Mehr-Faktor-Authentisierung für alle Schnittstellen, auf die von Extern zugegriffen werden könnte, aktivieren.

## Control guidance

Phishing-resistente Mehr-Faktor-Authentisierung bezeichnet Verfahren zur Anmeldung, bei denen mindestens zwei unterschiedliche Faktoren genutzt werden und bei denen die Authentisierung zusätzlich gegen typische Angriffe wie Credential Phishing, Adversary-in-the-Middle-Angriffe oder die Wiederverwendung abgefangener Sitzungsdaten abgesichert ist. Phishing-resistente Verfahren basieren typischerweise auf kryptographischen Nachweisen zwischen Endgerät und Zielsystem und verhindern dadurch, dass einmal abgefragte Zugangsdaten oder Einmalcodes durch täuschend echte Anmeldeseiten weiterverwendet werden können, beispielsweise FIDO2 Passkeys. Hintergrund ist, dass aus externen Netzen wie dem Internet erreichbare Anwendungen (insbesondere die VPN-Einwahl oder Cloud-Anwendungen) ein beliebtes Ziel für Angreifer sind. Klassische Passwörter oder einfache Einmalcodes könnten durch Social Engineering, gefälschte Login-Portale oder Man-in-the-Browser-Angriffe ausgespäht werden.
