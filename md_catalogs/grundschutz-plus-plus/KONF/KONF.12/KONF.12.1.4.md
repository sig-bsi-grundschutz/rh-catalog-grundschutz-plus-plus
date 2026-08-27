# KONF.12.1.4 - \[Kontrollierte Datenverarbeitung\] Subresource Integrity-Prüfung

## Control Statement

Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten Subresource Integrity-Prüfung einschränken.

## Control guidance

Unter Subresource Integrity (SRI), zu Deutsch etwa „Integrität von Unterressourcen“, versteht man einen Sicherheitsmechanismus von Webbrowsern, der sicherstellt, dass die vom Browser geladenen Ressourcen, wie z.B. JavaScript-Dateien oder CSS-Stylesheets, die von einem Drittanbieter (etwa einem Content Delivery Network, CDN) stammen, nicht unerwünscht manipuliert wurden. Technisch geschieht dies dadurch, dass die Webseite beim Einbinden der Ressource einen kryptografischen Hashwert (oder Digest) der erwarteten Datei als Attribut (z.B. integrity="...") mitsendet. Der Webbrowser kann dann nach dem Herunterladen der Ressource diesen Hashwert neu berechnen und mit dem bereitgestellten Wert vergleichen. Dies ist notwendig, da die Institution zwar die eigene Webseite kontrolliert, aber nicht die Server Dritter, von denen oft Bibliotheken geladen werden. Der Sinn und Zweck dieser Vorschrift liegt darin, die Sicherheit der Endnutzer zu erhöhen und Risiken durch manipulierte externe Inhalte zu minimieren. Ohne diese Prüfung könnte eine kompromittierte Drittanbieter-Ressource bösen Code in die Webseite der Institution einschleusen, was zu Vorfällen wie Datendiebstahl oder der Installation von Malware auf den Geräten der Nutzer führen könnte.
