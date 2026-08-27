# KONF.12.1.5 - \[Kontrollierte Datenverarbeitung\] HTTP Strict Transport Security (HSTS)

## Control Statement

Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten HTTP Strict Transport Security (HSTS) Richtlinie einschränken.

## Control guidance

Die HTTP Strict Transport Security (HSTS) ist ein Web-Sicherheitsmechanismus – definiert in IETF RFC 6797 – der Webbrowser zwingt, eine ausschließlich verschlüsselte Verbindung (HTTPS) mit einem Webserver zu nutzen, selbst wenn der Nutzer oder eine Anwendung versucht, über das unsichere HTTP zuzugreifen. Konkret beinhaltet die HSTS-Richtlinie (oder Policy) einen speziellen HTTP-Antwort-Header, den der Webserver an den Browser sendet, der die Dauer (max-age) festlegt, für die der Browser die Verbindung nur über HTTPS herstellen soll. Die restriktive Konfiguration von Webbrowsern in Bezug auf diese Richtlinie kann die Schutzwirkung erhöhen, da so das Risiko eines Man-in-the-Middle (MITM)-Angriffs, bei dem ein Angreifer eine unverschlüsselte Verbindung abfangen oder den Nutzer auf eine unsichere Seite umleiten könnte, deutlich reduziert wird. Eine solche Konfiguration kann die Institution vor dem ungewollten Downgrade-Angriff (Downgrade Attack) schützen, bei dem die Verbindung von HTTPS auf das unsichere HTTP erzwungen wird.
