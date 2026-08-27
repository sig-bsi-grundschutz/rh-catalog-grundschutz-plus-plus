---
x-trestle-set-params:
  det.3.6-prm1:
    values:
  det.3.6-prm2:
    values:
---

# DET.3.6 - \[Protokollierung\] Unbestreitbarkeit

## Control Statement

Detektion für Daten KANN Nachweise für den Zusammenhang {{ insert: param, det.3.6-prm1 }} mit {{ insert: param, det.3.6-prm2 }} dokumentieren.

## Control guidance

Für Handlungen, die eine besondere Bedeutung für die rechtliche Compliance oder die korrekte Verarbeitung von Daten in kritischen Geschäftsprozessen haben, kann es sinnvoll sein, eine zweifelsfreie Zuordnung des Ereignisses zu einer Person zu gewährleisten. Beispiele können das Senden von Nachrichten als Geschäftsleitung, die Überweisung hoher Beträge auf Konten im Ausland oder der Zugang einer Nachricht mit großer rechtlicher Bedeutung sein. Für einen zweifelsfreien Nachweis reicht die einfache Zuordnung zu einem Zugangskonto oft nicht aus, da das Konto auch von anderen missbraucht worden sein könnte. Zum Nachweis können verschiedene Maßnahmen eingesetzt werden: Digitale Signaturen auf Basis asymmetrischer Kryptographie können die Urheberschaft von Dokumenten verifizieren, während Zeitstempel von vertrauenswürdigen Zeitservern die chronologische Integrität sicherstellen. Eine dezentrale Speicherung der Logs auf verschiedenen Systemen erschwert Manipulationsversuche; ergänzend erhöht die Implementierung einer Blockchain-Technologie mit verketteten Hashwerten die Fälschungssicherheit erheblich. Hardwarebasierte Sicherheitsmodule (HSMs) können kryptografische Schlüssel vor unbefugtem Zugriff schützen.
