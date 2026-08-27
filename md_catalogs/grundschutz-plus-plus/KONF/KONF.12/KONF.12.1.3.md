# KONF.12.1.3 - \[Kontrollierte Datenverarbeitung\] Same-Origin-Policy

## Control Statement

Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten Same-Origin-Policy einschränken.

## Control guidance

Die Same-Origin-Policy, oft auch als SOP bekannt, ist ein fundamentaler Sicherheitsmechanismus im Webbrowser, der sicherstellt, dass von einer Quelle (Origin) geladene Skripte oder Dokumente nicht mit Ressourcen einer anderen Quelle interagieren können, wobei eine Quelle durch die Kombination aus Protokoll, Hostname und Port definiert wird. Sinn und Zweck dieser strikten Trennung ist der Schutz vor Datenabfluss und unbefugten Interaktionen zwischen unterschiedlichen Webanwendungen innerhalb derselben Browsersitzung. Ohne diese Isolierung könnte eine schadhafte Webseite beispielsweise vertrauliche Informationen aus einer parallel geöffneten legitimen Anwendung, wie einem Online-Banking-Portal oder internen Firmentool, auslesen und an einen Angreifer senden. Die konsequente Durchsetzung der Same-Origin-Policy durch den Browser kann solche Cross-Site-Scripting-Angriffe (XSS) effektiv unterbinden und somit die Vertraulichkeit und Integrität der vom Nutzer verarbeiteten Daten gewährleisten.
