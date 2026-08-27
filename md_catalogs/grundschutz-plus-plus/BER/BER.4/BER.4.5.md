# BER.4.5 - \[Berechtigungsmanagement\] Systemfunktionen ohne Authentifizierung

## Control Statement

Berechtigung für IT-Systeme SOLLTE Funktionen, auf die ohne vorherige Authentifizierung zugegriffen werden kann, dokumentieren.

## Control guidance

Funktionen ohne Authentifizierung sind alle Zugriffsmöglichkeiten auf Schnittstellen oder Daten des Systems, für die keine Authentifizierung erforderlich ist. Hierzu gehören z. B. Sprachassistenten, offene Webserver-Ports oder das Einblenden von Inhalten aus Apps auf dem Sperrbildschirm, wodurch persönliche Nachrichten oder Logintoken für Unbefugte zugänglich sein könnten. Solche Funktionen sind häufige Einfallstore für Angriffe auf das System oder für Datenleaks. Daher ist es sinnvoll eine Übersicht dieser Funktionen zu führen, selbst wenn die Funktionen benötigt werden.
