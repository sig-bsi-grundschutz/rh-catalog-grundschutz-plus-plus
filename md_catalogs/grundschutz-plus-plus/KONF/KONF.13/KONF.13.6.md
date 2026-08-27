# KONF.13.6 - \[Senden und Empfangen von Nachrichten\] Publikation der Serversignatur

## Control Statement

Konfiguration für E-Mail SOLLTE die Publikation der Serversignatur im DNS aktivieren.

## Control guidance

Eine Serversignatur, auch bekannt als DKIM (DomainKeys Identified Mail), ist eine kryptografische Signatur, die der E-Mail-Dienst der Institution an jede ausgehende Nachricht anhängt. Sie stellt sicher, dass die E-Mail tatsächlich von der angegebenen Domain gesendet wurde und während der Übertragung nicht manipuliert wurde. Ohne diese Signatur könnte ein Angreifer E-Mails im Namen der Institution versenden (E-Mail-Spoofing), was zu Phishing-Angriffen, dem Diebstahl von Zugangsdaten oder der Verbreitung von Malware führen könnte. Das Aktivieren der Publikation im DNS bedeutet, den öffentlichen Teil dieses kryptografischen Schlüssels im Domain Name System (DNS) der Domain zu veröffentlichen. Empfangende E-Mail-Server können diesen öffentlichen Schlüssel verwenden, um die Signatur der E-Mail zu verifizieren und somit deren Echtheit zu bestätigen. Zur Umsetzung kann die Institution E-Mail-Server-Software so konfigurieren, dass sie DKIM-Signaturen automatisch zu ausgehenden Nachrichten hinzufügt. Dies kann oft durch die Installation und Konfiguration von speziellen DKIM-Filter-Plugins erreicht werden.
