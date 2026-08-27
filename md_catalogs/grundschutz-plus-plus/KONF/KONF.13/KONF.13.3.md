# KONF.13.3 - \[Senden und Empfangen von Nachrichten\] Kryptographische Signatur des Mailservers

## Control Statement

Konfiguration für E-Mail SOLLTE die Kryptographische Signatur des Mailservers aktivieren.

## Control guidance

Die kryptographischen Signatur des Mailservers ist ein digitaler Stempel des versendenden Mailservers selbst, mit dem die Authentizität des sendenden Mailservers belegt wird. Ein bekannter technischer Standard hierfür ist DomainKeys Identified Mail (DKIM). Diese Signatur wird durch den absendenden Mailserver (oder einen vorgeschalteten Dienst) unter Verwendung eines privaten kryptographischen Schlüssels erzeugt. Der Empfänger kann die Signatur mit einem öffentlich zugänglichen Schlüssel, der typischerweise im Domain Name System (DNS) der sendenden Domain hinterlegt ist, verifizieren. Diese Schutzmaßnahme kann die Glaubwürdigkeit der E-Mails erhöhen und trägt zur Prävention von Risiken bei, wie dem Spoofing des Absenders: Ein Angreifer könnte ohne eine solche Signatur die Identität der Institution vortäuschen, was zu Phishing-Vorfällen führen könnte.
