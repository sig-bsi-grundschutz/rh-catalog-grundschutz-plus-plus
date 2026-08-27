# TEST.3.1.2 - \[Tests\] Verwendung externer Software

## Control Statement

Änderungen und Tests SOLLTE die Einbindung externer Softwareartefakte und -Schnittstellen aus unzuverlässigen oder unbekannten Quellen untersagen.

## Control guidance

Externe Softwareartefakte sind in diesem Kontext nicht von der Institution entwickelte, durch die Änderung in die eigene Infrastruktur eingebundene oder zur Laufzeit nachgeladene Bestandteile wie Bibliotheken, Frameworks, Container-Images, Plug-ins, Packages, Binärdateien, Skripte, Modelle, Templates oder Build-Abhängigkeiten (sog. Third-Party Components, Dependencies). Externe Softwareschnittstellen sind fremde technische Übergabe- und Kommunikationspunkte, über die eine Anwendung Funktionen oder Daten anderer Systeme nutzt, etwa Third-Party APIs, Webhooks, SDK-Schnittstellen, Datenfeeds, Authentifizierungsdienste oder Remote Services. Eine Quelle ist unzuverlässig, wenn zukünftig mit Verstößen gegen die Schutzziele Vertraulichkeit, Verfügbarkeit oder Integrität durch sie zu rechnen ist (d.h. eine Prognose der Vertrauenswürdigkeit). Dies ist insbesondere der Fall, wenn erhebliche Verstöße gegen die Schutzziele durch sie begangen worden sind oder Anzeichen dafür vorliegen, dass bei einer Verwendung mit solchen Verstößen zu rechnen ist. Unbekannte Quellen meint hier Quellen, deren Herkunft, Integrität, Pflegezustand, Verantwortlichkeit, Vertrauenswürdigkeit oder Sicherheitsniveau nicht belastbar nachvollziehbar ist, etwa anonyme Paket-Repositories, private Download-Links, unklare Git-Repositories, veraltete Mirror-Server, nicht verifizierte Container-Registries oder Schnittstellen ohne erkennbare Betreiber-, Sicherheits- und Änderungsinformationen.
