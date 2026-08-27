# DEV.4.7 - \[Softwareentwicklung - Code\] Deterministischer Binärcode

## Control Statement

Entwicklung für Anwendungen KANN eine reproduzierbare Vorgehensweise zur Erstellung eines bestimmten Binärcodes aus dem Quellcode dokumentieren.

## Control guidance

Ein bestimmter Binärcode meint hier eine reproduzierbare Anwendung (Reproducible builds). Das bedeutet, dass jeder, der denselben Quellcode und dieselbe Build-Umgebung verwendet, bitweise identische Binärdateien erstellt, was die Integrität der Software gegen Manipulationen oder Malware sichert. Dies geschieht durch die genaue Beschreibung der Build-Umgebung und die Vermeidung von zufälligen Faktoren wie Zeitstempeln, die sich auf die erzeugten Artefakte auswirken könnten.
