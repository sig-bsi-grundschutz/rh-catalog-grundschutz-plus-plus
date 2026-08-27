---
x-trestle-set-params:
  test.3.2-prm1:
    values:
---

# TEST.3.2 - \[Tests\] Testabdeckung

## Control Statement

Änderungen und Tests SOLLTE die Testabdeckung {{ insert: param, test.3.2-prm1 }} überprüfen.

## Control guidance

Ein ungenügendes Testverfahren könnte beispielsweise dazu führen, dass Schwachstellen in kritischen Anwendungen unentdeckt bleiben, was wiederum zu Datenverlust, unbefugtem Zugriff oder Systemausfällen führen könnte. Ein Beispiel hierfür ist der Fall einer industriellen Steuerungsanlage, bei der eine nicht ausreichend getestete Firmware-Aktualisierung zu einem Sicherheitsversagen und anschließendem Produktionsausfall führt. Der Begriff "Testabdeckung" (engl. "test coverage") bezeichnet hierbei den Umfang, in dem Komponenten, Funktionen und Schnittstellen eines Systems durch strukturierte Tests überprüft werden. Zur Umsetzung kann eine Institution verschiedene Maßnahmen implementieren: Für Software kann ein Code-Coverage-Monitoring etabliert werden, während für Hardware systematische Testmatrizen entwickelt werden können, die alle relevanten Betriebsparameter und Umgebungsbedingungen abdecken. Test-Dashboards können sowohl Software- als auch Hardware-Metriken visualisieren und in Entwicklungs- bzw. Implementierungsprozesse integriert werden. Für Hardware können FMEA-Analysen (Failure Mode and Effects Analysis) die kritischen zu testenden Komponenten identifizieren, während Software durch automatisierte CI/CD-Tests abgesichert werden kann. Bei der Implementierung empfiehlt es sich, einen risikobasierten Ansatz zu verfolgen, bei dem zuerst sicherheitskritische Komponenten umfassend getestet werden. Zudem kann eine systematische Dokumentation aller Testfälle und -ergebnisse, sowohl für Hardware- als auch für Software-Komponenten, die Nachvollziehbarkeit und kontinuierliche Verbesserung der Testabdeckung unterstützen. Zudem kann eine Kombination aus verschiedenen Testebenen (z.B. Stichproben, automatisierte und manuelle Verfahren, Unit-, Integrations- und Systemtests) eine umfassendere Abdeckung gewährleisten.
