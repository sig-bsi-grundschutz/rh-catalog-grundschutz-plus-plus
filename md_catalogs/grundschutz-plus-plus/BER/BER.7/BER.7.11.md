# BER.7.11 - \[Schlüsselmanagement\] Integrität

## Control Statement

Berechtigung SOLLTE die Verifikation der Integrität geheimer Schlüssel vor jeder Nutzung verankern.

## Control guidance

Wird die Integrität von Schlüsseln vor der Verwendung nicht geprüft, so könnte er unbemerkt durch einen Angreifer ausgetauscht werden, wodurch der Angreifer den vermeintlich verschlüsselten Austausch mitlesen. Daher ist ein Integritätsschutz (z.B. eine bekannte Checksumme oder Fingerabdruck) von abgelegten Schlüsseln sinnvoll. Dies kann z.B. durch den Abgleich von Prüfsummen geschehen, welche auf einem anderen IT-System gespeichert sind. Für die Implementierung genügt es, wenn die eingesetzten IT-Produkte bereits so entwickelt oder beschafft worden sind, dass sie die Prüfung automatisiert durchführen.
