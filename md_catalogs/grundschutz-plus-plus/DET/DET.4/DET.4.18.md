---
x-trestle-set-params:
  det.4.18-prm1:
    values:
---

# DET.4.18 - \[Überwachung von Aktivitäten\] Öffentliche Blocklisten

## Control Statement

Detektion für E-Mail KANN öffentliche Blocklisten auf Einträge für eigene E-Mail-Server {{ insert: param, det.4.18-prm1 }} überprüfen.

## Control guidance

Die Überprüfung von E-Mail-Blocklisteneinträgen ist entscheidend, um sicherzustellen, dass Nachrichten zuverlässig zugestellt und nicht als Spam klassifiziert werden. Dazu kann zunächst mit Tools wie MXToolbox oder MultiRBL geprüft werden, ob und auf welchen Listen der Server geführt wird, um anschließend die genauen Ursachen zu ermitteln – häufig spielen kompromittierte Konten, unzureichende Authentifizierungsmethoden oder veraltete E-Mail-Listen eine Rolle. Nach der Identifikation können Admins die grundlegenden Probleme beheben, beispielsweise durch Implementierung von SPF-, DKIM- und DMARC-Protokollen, Bereinigung von E-Mail-Listen oder Beseitigung technischer Schwachstellen, bevor bei den jeweiligen Blocklistenbetreibern ein Antrag auf Entfernung gestellt werden kann, wobei in der Regel Nachweise für die durchgeführten Verbesserungen erforderlich sind; zur langfristigen Prävention kann eine regelmäßige Überwachung der Senderreputation, sowie die Einhaltung bewährter E-Mail-Praktiken beitragen, oder die Nutzung eines seriösen E-Mail-Dienstleisters in Betracht gezogen werden.
