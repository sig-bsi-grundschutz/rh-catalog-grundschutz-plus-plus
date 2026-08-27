# KONF.14.1.1 - \[Verteilte Anwendungen\] Obligatorische Verschlüsselung

## Control Statement

Konfiguration für Anwendungen SOLLTE unverschlüsselte und anfällige Verbindungen über Netze deaktivieren.

## Control guidance

Obligatorische Verschlüsselung bedeutet, dass die Anwendung ausschließlich nach dem Stand der Technik verschlüsselt kommuniziert. Unverschlüsselte oder mit bekannten Methoden angreifbare Verbindungsanfragen werden dagegen abgelehnt. Die Verwendung obligatorischer Verschlüsselung im Internet ist aktuell sehr uneinheitlich: Viele E-Mail-Server z.B. verschlüsseln im Auslieferungszustand nur opportunistisch - also nur wenn der Verbindungsaufbau so funktioniert. Das macht Verbindungen anfällig für Downgrade-Angriffe. Diese lassen sich verhindern, indem unverschlüsselte Verbindungen vollständig deaktiviert werden. Andererseits kann es dadurch auch zu Verbindungsproblemen mit Servern kommen, die überhaupt keine Verschlüsselung mit aktuellen Protokollen unterstützen. Für aktuelle Verschlüsselungsverfahren siehe BSI TR-02102.
