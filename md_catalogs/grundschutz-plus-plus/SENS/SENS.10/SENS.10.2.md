# SENS.10.2 - \[Administration\] Umgang mit privilegierten Berechtigungen

## Control Statement

Sensibilisierung für Administrierende SOLLTE zum Umgang mit privilegierten Berechtigungen sensibilisieren.

## Control guidance

Privilegierte Berechtigungen (auch „administrative Rechte“, „Root-Berechtigungen“ oder „elevated privileges“ genannt) ermöglichen weitreichende Systemeingriffe und können bei unsachgemäßer Verwendung schwerwiegende Sicherheitsvorfälle verursachen. Beispielsweise könnte ein Administrator mit Root-Zugriff versehentlich kritische Systemdateien löschen, sensible Daten einsehen, oder Angreifer könnten solche Zugangsdaten abgreifen und mit diesen durch Lateral Movement ungehindert im Netzwerk agieren. Dies wird besonders deutlich an realen Vorfällen, bei denen Administratoren durch Social Engineering zum Einsatz ihrer Berechtigungen manipuliert wurden oder durch mangelndes Bewusstsein für Sicherheitsimplikationen ihrer Handlungen Schwachstellen selbst geschaffen haben. Stattdessen ist es sinnvoll, solche Berechtigungen nur dann zu verwenden, wenn sie für die aktuelle Aktion erforderlich sind, z.B. durch sudo. Zudem ist es bei diesen Zugangsdaten besonders wichtig, dass sie nicht ungeschützt abgelegt werden. Das betrifft auch Zugangsdaten, die in Skripten oder Anwendungen hinterlegt werden um diese auszuführen: Werden diese beim Aufruf von Kommandozeilenbefehlen oder in Skripten mitgespeichert, könnten sie in Protokollen oder im Prozessspeicher sichtbar sein und missbraucht werden. Sinnvoll ist stattdessen die Verwendung von Passwort-Managern, Umgebungsvariablen oder speziellen Secrets-Management-Lösungen. Dazu gehört auch die regelmäßige Rotation solcher Zugangsdaten bei Dienstekonten (Service Accounts).
