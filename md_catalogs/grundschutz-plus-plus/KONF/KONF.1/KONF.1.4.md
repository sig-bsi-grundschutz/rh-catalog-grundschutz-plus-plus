# KONF.1.4 - \[Grundlagen\] Einschränkung des Zugriffs auf Dokumentation

## Control Statement

Konfiguration SOLLTE den Zugriff auf dokumentierte Konfigurationen einschränken.

## Control guidance

„Dokumentierte Konfigurationen“ sind hierbei festgehaltene Einstellungen von IT-Systemen, Anwendungen, Netzwerken oder Sicherheitskomponenten, die in schriftlicher oder elektronischer Form vorliegen und den Sollzustand einer IT-Umgebung definieren. Der Zweck der Vorschrift liegt darin, die Integrität und Vertraulichkeit solcher Konfigurationsinformationen zu schützen. Ein unkontrollierter Zugriff könnte beispielsweise dazu führen, dass ein Unbefugter Passworteinstellungen oder Firewall-Regeln manipuliert. Aus der Konfiguration von IT-Systemen könnte ein Angreifer zudem wichtige Informationen zu möglichen Schwachstellen ablesen (z.B. bei technisch notwendiger Verwendung schwacher Verschlüsselungsalgorithmen oder unsicherer Authentisierungsprotokolle wie NTLM). Ein strikter Zugriffsschutz (z.B. durch restriktive Berechtigungen oder Verschlüsselung) verhindert den unberechtigten Zugriff zu diesen sensiblen Informationen. Praktisch hilfreich kann auch sein, Konfigurationen verschlüsselt abzulegen und bei elektronischen Repositories sogenannte „Branch Protection“-Mechanismen einzusetzen, sodass Änderungen nur über geprüfte Freigabeprozesse übernommen werden können. Auf Papier vorliegende Konfigurationen kann die Institution in verschlossenen Schränken oder Archiven mit eingeschränktem Personenkreis verwahren.
