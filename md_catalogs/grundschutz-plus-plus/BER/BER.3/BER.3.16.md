# BER.3.16 - \[Zugangskonten\] Keine Gruppenkonten

## Control Statement

Berechtigung SOLLTE Gruppenkonten im Regelbetrieb untersagen.

## Control guidance

Ein Gruppenkonto (englisch shared account) bezeichnet hier ein Zugangskonto, das von mehreren natürlichen Personen gemeinsam genutzt wird und daher keiner einzelnen natürlichen Person eindeutig zugeordnet werden kann. Vom Regelbetrieb erfasst ist die gewöhnliche, wiederkehrende Nutzung im Tagesgeschäft, nicht jedoch ein eng begrenzter Ausnahmefall mit gesonderter Begründung und Absicherung, sowie nachvollziehbarer Zuordnung der Nutzung zu einer konkreten Person. Der Ausschluss von Gruppenkonten hat das Ziel die Nachvollziehbarkeit von Zugriffen und Änderungen zu verbessern und eine eindeutige Verantwortlichkeit für die Nutzung von Berechtigungen sicherzustellen. Die Verwendung von Gruppenkonten im Regelbetrieb könnten hingegen die Aufklärung von Sicherheitsvorfällen erschweren, die missbräuchliche Nutzung von Zugriffsrechten begünstigen oder nach dem Ausscheiden einzelner Nutzer unbemerkte Zugriffsmöglichkeiten bestehen lassen. Für technisch unvermeidbare Sonderfälle können stattdessen speziell gekennzeichneter Funktions- oder Dienstkonten (service accounts) verwendet werden. Im Unterschied zu Gruppenkonten sind Service Accounts nicht zur gemeinsamen interaktiven Nutzung durch mehrere Mitarbeiter gedacht. Sie können beispielsweise einen Datenbankdienst mit einer Anwendung verbinden, automatisierte Datensicherungen durchführen oder den Datenaustausch zwischen zwei Systemen ermöglichen. Um klar von Gruppenkonten abgegrenzt zu sein benötigt ein Dienstkonto eine klar nachvollziehbare Zweckbindung, die Sperrung interaktiver Anmeldungen, sowie eine regelmäßige Erneuerung von Authentisierungsmerkmalen.
