# KONF.13.10 - \[Senden und Empfangen von Nachrichten\] Authentifizierung der Server-Zertifikate über DNS

## Control Statement

Konfiguration für E-Mail SOLLTE die Authentifizierung der Server-Zertifikate über das DNS aktivieren.

## Control guidance

Die Authentifizierung der Server-Zertifikate über das DNS (Domain Name System) kann die Sicherheit der E-Mail-Kommunikation erheblich steigern. Dabei werden Zertifikatsinformationen in DNS-Einträgen genutzt, um die Echtheit der TLS/SSL-Zertifikate eines E-Mail-Servers zu überprüfen und sicherzustellen, dass man tatsächlich mit dem beabsichtigten Kommunikationspartner spricht. Techniken wie DANE (DNS-based Authentication of Named Entities) oder CAA (Certificate Authority Authorization) nutzen spezifische DNS-Resource Records (wie TLSA oder CAA Records), um entweder die verwendeten Zertifikate oder die autorisierten Zertifizierungsstellen im DNS zu hinterlegen. Dies kann verhindern, dass ein Angreifer eine gefälschte Identität vortäuschen oder eine Man-in-the-Middle-Attacke durchführen könnte, indem er ein nicht autorisiertes oder kompromittiertes Zertifikat präsentiert. Ohne diese zusätzliche Überprüfung könnte ein Angreifer beispielsweise den E-Mail-Verkehr der Institution abfangen und mitlesen, während er sich als der legitime Server ausgibt. Die Aktivierung dieser DNS-basierten Überprüfung kann also die Vertraulichkeit und Integrität der übertragenen E-Mails schützen. Zur Umsetzung werden Informationen über eigene Serverzertifikate im DNS hinterlegt und die Prüfung eingehender E-Mails auf hinterlegte Einträge der sendenden Servers aktiviert.
