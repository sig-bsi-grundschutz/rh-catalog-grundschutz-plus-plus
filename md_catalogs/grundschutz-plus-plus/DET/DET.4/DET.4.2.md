---
x-trestle-set-params:
  det.4.2-prm1:
    values:
---

# DET.4.2 - \[Überwachung von Aktivitäten\] Automatische Angriffserkennung

## Control Statement

Detektion für IT-Systeme SOLLTE diese auf Anzeichen für Angriffe durch {{ insert: param, det.4.2-prm1 }} überwachen.

## Control guidance

Wenn professionelle Tätergruppen Zugriff auf Systeme und Daten erhalten, nutzen sie diese zunehmend schneller für ihre Zwecke aus, z.B. um Daten abfließen zu lassen oder Ransomware zu verteilen. Zur Umsetzung können sowohl netz- als auch hostbasierte Erkennungssysteme (NIDS und HIDS) verwendet werden. Für die Detektion bei IT-Systemen ohne Installationsmöglichkeit wie Appliances, IoT-Geräte oder OT-Systeme kann ein kombinierter Ansatz aus Netzwerk- und Loganalyse sinnvoll sein. Angriffe können signaturbasiert, sowie durch Verhaltensanalyse und Anomalien erkannt werden. Die Anforderung kann auch mit bereits vorhandenen oder im System integrierten Angriffserkennungsmechanismen erfüllt werden. Zweckmäßig ist es Schwellwerte und Kategorien (Info, Warnung, Alarm) so festzulegen, dass Probleme frühzeitig erkannt werden können, aber beim Betriebspersonal keine Alarmmüdigkeit (alert fatigue) aufkommt. Hierzu ist es hilfreich die Ergebnisse regelmäßig auszuwerten und wenn nötig Korrekturmaßnahmen zu ergreifen.
