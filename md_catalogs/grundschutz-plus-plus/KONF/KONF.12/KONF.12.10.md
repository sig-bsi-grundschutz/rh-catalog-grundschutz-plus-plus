# KONF.12.10 - \[Kontrollierte Datenverarbeitung\] Cookie-Attribute

## Control Statement

Konfiguration für Webanwendungen SOLLTE Cookie-Attribute aktivieren.

## Control guidance

"Secure" erzwingt die verschlüsselte HTTPS-Übertragung, wodurch Man-in-the-middle-Angriffe verhindert werden. "SameSite" sorgt dafür, dass Cookies nur zurückgesendet werden, wenn die Anfrage von der ursprünglichen Seite stammt. Hierdurch werden Cross-Site-Request-Forgery-Angriffe erschwert. "HttpOnly" verbietet es Client-seitigen Skripten auf das Cookie zuzugreifen, wodurch Cross-Site Scripting (XSS) erschwert wird.
