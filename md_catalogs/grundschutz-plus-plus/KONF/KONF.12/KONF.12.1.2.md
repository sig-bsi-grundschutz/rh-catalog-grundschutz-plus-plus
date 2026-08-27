# KONF.12.1.2 - \[Kontrollierte Datenverarbeitung\] Content Security Policy (CSP)

## Control Statement

Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten Content Security Policy einschränken.

## Control guidance

Eine Content Security Policy (CSP) ist ein Sicherheitsmechanismus, der es einer Webseite erlaubt, dem Webbrowser mitzuteilen, von welchen Quellen er aktive Inhalte wie Skripte oder auch passive Inhalte wie Bilder laden darf. Durch diesen als Whitelist funktionierenden Ansatz kann die Institution die Angriffsfläche ihrer Webanwendungen erheblich reduzieren. Ohne eine wirksame CSP könnten Angreifer durch Cross-Site-Scripting-Angriffe (XSS) bösartige Skripte in eine Webseite einschleusen, die dann im Browser des Nutzers ausgeführt werden und beispielsweise sensible Daten auslesen oder Aktionen im Namen des Opfers durchführen könnten. Die Aktivierung einer CSP blockiert die Ausführung von nicht vertrauenswürdigen Skripten und das Laden unerwünschter Ressourcen und schützt somit die Integrität und Vertraulichkeit der Web-Sitzung.
