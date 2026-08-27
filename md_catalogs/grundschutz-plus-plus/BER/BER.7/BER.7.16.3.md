# BER.7.16.3 - \[Schlüsselmanagement\] Erneuerung

## Control Statement

Berechtigung SOLLTE den Schlüssel anhand der Vorgaben für die Schlüsselbeglaubigung bei Erneuerung einer Beglaubigung testen.

## Control guidance

Die Erneuerung einer Beglaubigung beschreibt den Vorgang, bei dem ein ablaufendes oder gefährdetes Zertifikat durch ein neues ersetzt wird, wobei die Vertrauenskette erhalten bleibt. Dazu wird geprüft, ob die Vorgaben für die Erneuerung der Beglaubigung erfüllt sind. Das Testen des Schlüssels im Rahmen der Erneuerung dient dazu, die fortgesetzte Vertrauenswürdigkeit und Funktionsfähigkeit des Schlüssels sicherzustellen, etwa durch Verifikation der Signatur, Abgleich der Fingerprints oder Validierung gegen Sperrlisten. Der Zweck dieser Anforderung liegt in der Sicherstellung, dass bei der Erneuerung eines Zertifikats keine kompromittierten, fehlerhaften oder unautorisierten Schlüssel weiterverwendet werden. Wird die Schlüsselprüfung unterlassen, könnte ein Angreifer manipulierte oder gefälschte Schlüssel einschleusen, was zu unbemerktem Datenabgriff, Identitätsmissbrauch oder Integritätsverlust führen könnte. Eine wirksame Prüfung kann dagegen sicherstellen, dass nur überprüfte und gültige Schlüssel erneut beglaubigt werden, wodurch das Vertrauensniveau der gesamten kryptographischen Infrastruktur stabil bleibt. Sinnvolle Umsetzungsvarianten können z. B. die Nutzung automatisierter Schlüsselvalidierungen in Public-Key-Infrastrukturen (PKI), der Einsatz von Hardware-Sicherheitsmodulen (HSM) für die Signaturprüfung oder der Abgleich über Transparenzregister wie Certificate Transparency Logs sein.
