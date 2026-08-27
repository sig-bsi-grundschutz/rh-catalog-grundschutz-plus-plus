# KONF.13.5 - \[Senden und Empfangen von Nachrichten\] Publikation der Sendeberechtigung

## Control Statement

Konfiguration für E-Mail SOLLTE die Publikation der eigenen Sendeberechtigung im DNS aktivieren.

## Control guidance

Dies wird typischerweise über spezielle DNS-Einträge wie den Sender Policy Framework (SPF) realisiert. Damit kann eine Institution im DNS festlegen, welche Mail-Server berechtigt sind, E-Mails im Namen ihrer Domäne zu versenden. Ein entsprechender DNS-Eintrag, der sogenannte SPF-Record, ermöglicht es empfangenden Mail-Servern, die Absender-Adresse einer eingehenden E-Mail zu überprüfen. Dies kann die Schutzwirkung gegen gängige Risiken wie E-Mail-Spoofing verbessern, bei dem sich ein Angreifer als legitimer Absender ausgibt, um die Empfänger zu täuschen. Ohne eine solche Konfiguration könnte ein Angreifer beispielsweise E-Mails mit gefälschter Absenderadresse verschicken, die scheinbar von der Geschäftsleitung stammen, um einen Nutzer zur Herausgabe von sensiblen Informationen zu verleiten (Phishing). Durch die Aktivierung von SPF kann das Risiko verringert werden, dass solche bösartigen Nachrichten die Postfächer von Nutzern erreichen. Es ist wichtig, den Eintrag sorgfältig zu erstellen, um alle legitimen Absender abzudecken, einschließlich Diensten von Drittanbietern. Ein häufiger Fehler ist, dass nicht alle autorisierten Mail-Server korrekt gelistet sind, was dazu führen könnte, dass legitime E-Mails fälschlicherweise als Spam markiert werden.
