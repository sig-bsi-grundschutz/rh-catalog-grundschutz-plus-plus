---
x-trestle-set-params:
  konf.10.5-prm1:
    values:
---

# KONF.10.5 - \[Konfiguration von Anwendungen\] Überprüfung der Konfiguration

## Control Statement

Konfiguration für Anwendungen SOLLTE die Übereinstimmung der tatsächlichen Konfiguration mit dem Referenzzustand {{ insert: param, konf.10.5-prm1 }} überprüfen.

## Control guidance

Referenzzustand („baseline configuration“) bezeichnet hier die dokumentierte und freigegebene Konfiguration der Anwendung, also die gewünschte und autorisierte Einstellung von Parametern, Diensten und Komponenten. Die tatsächliche Konfiguration ist die aktuelle technische Umsetzung dieser Einstellungen der Anwendung selbst. Der Abgleich beider Zustände dient vor allem der Vermeidung von Configuration Drift – d.h. dass Anwendungen schleichend von der definierten Grundkonfiguration abweichen. Dies könnte auftreten, wenn Änderungen nicht zentral dokumentiert oder automatisierte Installationen nicht einheitlich umgesetzt werden. Ohne diese Kontrolle könnte es zu unbemerkten Fehlkonfigurationen kommen, die Sicherheitslücken öffnen oder Betriebsstörungen verursachen. Durch regelmäßige Vergleiche kann eine Institution sicherstellen, dass Anwendungen konsistent, vertrauenswürdig und wartbar bleiben. Die Umsetzung kann technisch etwa mit Skripten erfolgen, die automatisiert Konfigurationsparameter auslesen und vergleichen. Auch der Einsatz von „Configuration Management“- oder „Compliance Scanning“-Werkzeugen kann unterstützen, indem sie Differenzen visualisieren und Reports erzeugen. Prozessual kann es hilfreich sein, Prüfintervalle nach Kritikalitätsklassen zu staffeln (z. B. sicherheitskritische Anwendungen wöchentlich, weniger kritische vierteljährlich) und Ergebnisse in Change-Management-Prozesse zurückzuführen.
