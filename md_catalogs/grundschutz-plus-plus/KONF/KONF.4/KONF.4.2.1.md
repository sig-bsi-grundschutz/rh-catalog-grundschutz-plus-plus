---
x-trestle-set-params:
  konf.4.2.1-prm1:
    values:
---

# KONF.4.2.1 - \[Vertrauenswürdige Basisdienste\] DNS-Verschlüsselung

## Control Statement

Konfiguration für IT-Systeme SOLLTE DNS-Verbindungen durch {{ insert: param, konf.4.2.1-prm1 }} verschlüsseln.

## Control guidance

DNS-Verschlüsselung, im Englischen oft als DNS over TLS (DoT) oder DNS over HTTPS (DoH) bezeichnet, ist ein Verfahren, bei dem Anfragen zur Namensauflösung im Internet kryptographisch geschützt werden, um deren Vertraulichkeit und Integrität sicherzustellen. Erfolgen diese Anfragen unverschlüsselt, könnte ein Angreifer im Netz die aufgerufenen Webseiten und Dienste eines Nutzers mitlesen und protokollieren. Schlimmer noch, ein Angreifer könnte die Antworten manipulieren, um den Nutzer unbemerkt auf gefälschte Webseiten umzuleiten, beispielsweise für Phishing-Angriffe. Die Aktivierung der DNS-Verschlüsselung kann einem solchen Ausspähen und Manipulieren der Namensauflösung effektiv entgegenwirken und stellt sicher, dass die Kommunikation zwischen dem Client und dem DNS-Server authentisch und nicht einsehbar ist. Nutzt das System kein DNS, so ist die Anforderung entbehrlich.
