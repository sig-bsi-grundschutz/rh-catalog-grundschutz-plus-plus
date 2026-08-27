# ARCH.5.1.8 - \[Perimeterschutz\] Inspektion verschlüsselter Verbindungen

## Control Statement

Architektur für Externe Netzanschlüsse SOLLTE den Inhalt unverschlüsselter und verschlüsselter Verbindungen basierend auf der Art des Inhalts einschränken.

## Control guidance

Verschlüsselte Verbindungen wie VoIP über TLS oder HTTPS-Anfragen können über Sicherheitsproxies oder die Inspektion auf den Endstellen der Verbindungen inspiziert werden. Ein Proxy bzw. Proxy-Server ist ein Vermittler im Netz, der zwischen dem Client und einer Netzressource, wie einer Webseite, fungiert. Er dient als Brücke zwischen dem Client und dem Server, wobei Anfragen und Antworten stellvertretend abgewickelt werden. Proxys können Datenverkehr filtern, blockieren, oder auch speichern, um die Netzwerkleistung zu optimieren. Systeme zur Filterung von Webinhalten gehören zu den häufigsten Arten von Proxyservern, die zur Vermittlung des Internetzugangs eingesetzt werden. Diese Server können TCP-Sitzungen protokollieren und die Zugriffskontrolle durch Blockieren bestimmter URLs, IP-Adressen oder Domänennamen erzwingen. Institutionen können Web-Proxys mit benutzerdefinierten Erlaubnis- und Sperrlisten konfigurieren, um den Zugriff auf der Grundlage von Richtlinien zu regeln. Es ist jedoch zu beachten, dass Proxyserver die Nutzung virtueller privater Netzwerke (VPN) beeinträchtigen und je nach Implementierung Risiken wie Man-in-the-Middle-Angriffe (MitM) mit sich bringen können. Beispiel-Implementierungen sind Squid, Nginx, Privoxy.
