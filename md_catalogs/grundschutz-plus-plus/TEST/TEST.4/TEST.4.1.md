# TEST.4.1 - \[Freigabe\] Autorisierung von Änderungen

## Control Statement

Änderungen und Tests SOLLTE kritische Änderungen anhand von Kriterien einschließlich der Sicherheitsanforderungen autorisieren.

## Control guidance

Änderungen gelten als kritisch, wenn sie breite Auswirkungen auf Geschäftsprozesse haben, beispielsweise die Aktivierung der Zwei-Faktor-Authentifizierung am zentralen Verzeichnisdienst. Die Kritikalität ergibt sich zudem aus Art und Umfang der Änderung, etwa bei umfangreichen Migrationen oder sicherheitsrelevanten Fehlerbehebungen. Kritische Änderungen betreffen häufig die Bereitstellung für eine große Zahl interner oder externer Nutzender oder Eingriffe in hochverfügbare Systeme. Zu den maßgeblichen Kriterien für die Freigabe zählen das fehlerfreie Durchlaufen definierter Tests, eine ausreichende Nutzerakzeptanz in einem Beta-Test und das erfolgreiche Bestehen von Penetrationstests. Zweckmäßig ist eine mehrstufige Autorisierung, in der Änderungen anhand der prognostizierten Auswirkungen den Kategorien niedrig, mittel oder hoch zugeordnet und mit abgestuften Genehmigungsanforderungen verknüpft werden. Während bei geringfügigen Änderungen an unkritischen Systemen eine konzentrierte Prüfung grundlegender Sicherheitsanforderungen wie Authentifizierung, Verschlüsselung und Härtung ausreichen kann, erfordern umfangreiche Vorhaben mit hohem Risikoprofil in der Regel automatisierte Prüfmechanismen, ergänzt durch Checklisten für manuelle Tätigkeiten, um die Auswirkungen verlässlich beherrschbar zu halten.
