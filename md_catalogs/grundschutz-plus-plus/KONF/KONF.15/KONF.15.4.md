# KONF.15.4 - \[Ressourcenauslastung\] Überbuchung von virtualisierten Ressourcen

## Control Statement

Konfiguration für Virtualisierungslösungen KANN die Überbuchung von virtualisierten Ressourcen deaktivieren.

## Control guidance

Die Überbuchung (engl. overcommitment) beschreibt in Virtualisierungslösungen die Zuweisung von mehr virtuellen Ressourcen – etwa CPU-Kernen, Arbeitsspeicher oder Speicherplatz – an virtuelle Instanzen, als physisch tatsächlich vorhanden sind. Dies kann kurzfristig zu einer höheren Auslastung und Dichte von virtuellen Instanzen führen, birgt jedoch das Risiko, dass die zugrunde liegende Hardware unter Last nicht mehr alle angefragten Ressourcen bereitstellen kann. Der Zweck der Anforderung liegt darin, die Stabilität, Verfügbarkeit und Vorhersehbarkeit der virtualisierten Umgebung sicherzustellen. Ohne diese Begrenzung könnte es unter hoher Auslastung zu Leistungseinbrüchen, Systemabstürzen oder inkonsistenten Speicherzuständen kommen, während eine restriktive Konfiguration die Zuverlässigkeit und die Berechenbarkeit der Performance einer virtuellen Infrastruktur deutlich verbessern kann. Eine Institution kann die Umsetzung dieser Vorgabe durch verschiedene Maßnahmen erreichen: (1) In der Hypervisor-Konfiguration kann die Vergabe virtueller CPUs und Arbeitsspeicher exakt auf die physisch vorhandenen Ressourcen begrenzt werden. (2) Es kann sinnvoll sein, Profile oder Templates für virtuelle Maschinen zu nutzen, die konservative Standardwerte vorgeben, sodass die Gefahr unbeabsichtigter Überbuchung reduziert wird.
