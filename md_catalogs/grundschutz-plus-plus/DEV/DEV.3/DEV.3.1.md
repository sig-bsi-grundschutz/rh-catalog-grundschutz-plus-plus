# DEV.3.1 - \[Softwareentwicklung - Härtung\] Replay-Angriffe

## Control Statement

Entwicklung für Anwendungen SOLLTE Replay-Angriffe blockieren.

## Control guidance

Wenn die Anwendung Anfragen von anderen Anwendungen oder IT-Systemen entgegennimmt (z.B. per API), dann besteht die Gefahr, dass Angreifer eine vorherige Anfrage erneut verwenden um unbefugt Zugang zu erhalten. Maßnahmen können sein: (1) Identifikatoren, die nur einmal gültig sind (Nonce, Sequenznummern), (2) kryptographische Mechanismen wie MAC und Digitale Signaturen, Challenge-Response-Authentifizierung, OTP.
