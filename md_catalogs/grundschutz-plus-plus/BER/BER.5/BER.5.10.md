# BER.5.10 - \[Umgang mit Authentisierungsmitteln\] Zugriffsbeschränkung pro IT-System

## Control Statement

Berechtigung für IT-Systeme SOLLTE den lesenden und schreibenden Zugriff auf Authentifizierungsmittel einschränken.

## Control guidance

Lesender Zugriff bezeichnet in diesem Kontext jede Möglichkeit, Authentifizierungsmittel einzusehen, auszulesen, zu exportieren, zu kopieren oder technisch zu verwenden, ohne sie unmittelbar zu verändern; schreibender Zugriff meint jede Möglichkeit, Authentifizierungsmittel anzulegen, zu ändern, zu ersetzen, zu löschen, zu importieren oder deren Vertrauensstatus zu beeinflussen. Authentifizierungsmittel sind hier alle technischen oder organisatorisch verwalteten Mittel, mit denen Identitäten nachgewiesen oder Vertrauensbeziehungen hergestellt werden, etwa Passwörter, private Schlüssel, API-Keys, Token, Zertifikate, Kerberos-Keytabs, SSH-Schlüssel, Recovery-Codes, Hardware-Token-Zuordnungen oder Einträge in Trust Stores. Der Zugriff auf solche Mittel ist besonders sensibel, weil bereits lesender Zugriff in vielen Fällen zur Nachahmung einer Identität oder zur Umgehung vorgesehener Kontrollmechanismen führen könnte, während schreibender Zugriff zusätzlich Manipulationen an Vertrauensketten, Schlüsselmaterial oder Anmeldeverfahren ermöglichen könnte.
