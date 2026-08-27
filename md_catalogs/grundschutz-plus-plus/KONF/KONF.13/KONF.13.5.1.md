# KONF.13.5.1 - \[Senden und Empfangen von Nachrichten\] Strenge Senderpolicy

## Control Statement

Konfiguration für E-Mail SOLLTE eine strenge Senderpolicy aktivieren.

## Control guidance

Ein strenger Senderpolicy-Eintrag, auch "hard fail" (-all) genannt, weist empfangende Mailserver an, E-Mails, die von nicht autorisierten Servern stammen, zurückzuweisen oder als Spam zu markieren. Dies kann das Risiko von Phishing-Angriffen erheblich reduzieren, bei denen Angreifer versuchen, sich als vertrauenswürdige Institutionen auszugeben. Eine solche Konfiguration kann auch Spoofing verhindern, bei dem die Absenderadresse gefälscht wird, was dazu führen könnte, dass Kunden oder Mitarbeiter betrügerischen Anweisungen folgen, die scheinbar von der Institution selbst stammen. Zur Umsetzung einer strengen Senderpolicy kann die Institution sicherstellen, dass sie einen SPF-Eintrag in ihren DNS-Einstellungen hinterlegt. Dieser Eintrag sollte alle autorisierten Server explizit auflisten und mit dem "-all" Mechanismus enden, um eine strikte Ablehnung nicht konformer E-Mails zu signalisieren.
