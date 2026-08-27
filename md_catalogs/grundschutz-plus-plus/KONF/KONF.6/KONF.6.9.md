# KONF.6.9 - \[Rollen und Berechtigungen\] Zugriff auf Code

## Control Statement

Konfiguration für Webserver SOLLTE den Zugriff auf Quelldateien einschränken.

## Control guidance

Quelldateien sind in diesem Zusammenhang alle Dateien, die zur Funktionsweise einer Webanwendung benötigt werden, deren Auslieferung an den Browser von Nutzenden aber nicht erforderlich ist. Dazu gehören Programmier- oder Skriptcode, Konfigurationsdateien, Datenbankverbindungen und sensible Daten wie APIs oder Anmeldeinformationen. Das Verhindern des direkten Zugriffs auf diese Dateien dient der Prävention von Informationslecks und der Minderung des Risikos unautorisierter Offenlegung. Eine nicht restriktive Konfiguration könnte beispielsweise die Offenlegung von Code-Teilen, die Logik der Anwendung oder sogar hartkodierten Passwörtern ermöglichen, was zu einer weitreichenden Kompromittierung des Systems führen könnte. Die Umsetzung kann durch platzieren dieser Dateien außerhalb des WWW-Wurzelverzeichnisses erfolgen. Weiterhin kann der Zugriff auf bestimmte Dateitypen wie .php, .ini, .env oder .sql mittels Webserver-Regeln (z.B. in .htaccess für Apache oder location-Blöcke in Nginx) explizit verweigert werden, wodurch auch versehentlich im öffentlichen Verzeichnis abgelegte Quelldateien geschützt sind. Bei der Wahl eines Content-Management-Systems oder Frameworks kann eine sichere Standardkonfiguration die Umsetzung erleichtern. Zusätzlich können serverseitige Skripte so konfiguriert werden, dass sie nur aus vordefinierten, sicheren Verzeichnissen ausgeführt werden dürfen, was als Secure Execution Path bekannt ist.
