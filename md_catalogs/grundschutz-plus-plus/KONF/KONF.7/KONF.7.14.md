# KONF.7.14 - \[Schutz vor Schadcode\] Code-Signierung im Betriebssystemkern

## Control Statement

Konfiguration für IT-Systeme SOLLTE die Signaturprüfung für nachladbaren Code im Kernelmodus aktivieren.

## Control guidance

Nachladbarer Code im Kernelmodus verfügt typischerweise über weitreichende Berechtigungen und kann bei einer Kompromittierung erhebliche Auswirkungen auf das gesamte IT-System haben. Eine Signaturprüfung kann dazu beitragen, das Laden von nicht oder nicht vertrauenswürdig signiertem Code im Kernelmodus zu verhindern. Beispiele sind die erzwungene Signaturprüfung von Kernelmodulen unter Linux oder die Signaturprüfung von Kernelmodus-Treibern unter Windows. Die Schutzwirkung der Signaturprüfung hängt von den verwendeten Vertrauensankern ab. Hierbei kann insbesondere berücksichtigt werden, welche Signaturschlüssel beziehungsweise Herausgeber als vertrauenswürdig eingestuft werden. Eine gültige Signatur allein erlaubt keine Aussage über die Sicherheit oder Qualität des signierten Codes.
