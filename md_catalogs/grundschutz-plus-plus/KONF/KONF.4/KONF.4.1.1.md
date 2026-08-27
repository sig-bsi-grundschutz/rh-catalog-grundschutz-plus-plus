# KONF.4.1.1 - \[Vertrauenswürdige Basisdienste\] Weiterleitung von Anmeldeinformationen

## Control Statement

Konfiguration für IT-Systeme SOLLTE die Weiterleitung mehrfach verwendbarer Anmeldeinformationen deaktivieren.

## Control guidance

„Weiterleitung mehrfach verwendbarer Anmeldeinformationen“ (auch als Credential Forwarding oder Credential Delegation bezeichnet) meint Mechanismen, bei denen Anmeldeinformationen oder daraus abgeleitete Authentisierungsinformationen an ein weiteres System übertragen oder diesem zur weiteren Authentisierung zur Verfügung gestellt werden. Dadurch können auf dem Zielsystem Informationen oder Authentisierungsfähigkeiten verfügbar werden, die bei einer Kompromittierung für weitere Zugriffe missbraucht werden könnten. Die Einschränkung der Weiterleitung kann das Risiko reduzieren, dass Angreifende nach der Kompromittierung eines Systems Anmeldeinformationen oder daraus abgeleitete Authentisierungsinformationen für laterale Bewegungen verwenden. Insbesondere bei privilegierten Zugangskonten kann dadurch vermieden werden, dass wiederverwendbare Anmeldeinformationen auf weniger vertrauenswürdigen Systemen verfügbar werden. Für Remotezugriffe können Verfahren eingesetzt werden, bei denen die Anmeldeinformationen nicht an das Zielsystem übertragen werden. Beispiele unter Windows sind Remote Credential Guard oder Restricted Admin für Remotedesktopverbindungen. Bei SSH-Verbindungen kann auf die Weiterleitung des lokalen SSH-Authentisierungsagenten verzichtet werden. Wird Agent Forwarding nicht benötigt, kann dessen Verwendung client- und serverseitig eingeschränkt werden.
