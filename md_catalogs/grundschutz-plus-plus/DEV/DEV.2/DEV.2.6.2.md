# DEV.2.6.2 - \[Softwareentwicklung - Security by Design\] Ausgabekodierung

## Control Statement

Entwicklung für Anwendungen SOLLTE eine Ausgabekodierung ausführen.

## Control guidance

Ausgabekodierung (Output Encoding) ist wichtig, da sie spezielle Zeichen neutralisiert und so Angriffe wie Cross-Site Scripting (XSS) oder HTML-Injektionen verhindert, die ansonsten Schadcode ausführen könnten. Empfehlenswert ist kontextabhängiges Encoding und Escaping, basierend auf standardisierten Frameworks wie OWASP ESAPI.
