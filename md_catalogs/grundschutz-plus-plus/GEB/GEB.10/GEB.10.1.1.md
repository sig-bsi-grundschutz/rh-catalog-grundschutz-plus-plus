---
x-trestle-set-params:
  geb.10.1.1-prm1:
    values:
---

# GEB.10.1.1 - \[Schutz vor Elementarschäden\] Luftstrom-Analyse

## Control Statement

Gebäudemanagement für Serverräume KANN den Klimatisierungsbedarf anhand einer Luftstrom-Analyse {{ insert: param, geb.10.1.1-prm1 }} überprüfen.

## Control guidance

Luftstromanalyse ist die systematische Bewertung von Luftbewegungsmustern zur Optimierung der Kühleffizienz und zur Vermeidung von Geräteausfällen. Dabei wird untersucht, wie die kalte Luft in der Einrichtung verteilt wird, es werden potenzielle Hotspots oder Bereiche mit Stagnation identifiziert, und es wird ein ordnungsgemäßer Wärmeaustausch durch die Überwachung der Einlass- und Auslasstemperaturen in den Serverracks sichergestellt. Zu den möglichen Methoden gehören CFD-Modelle (Computational Fluid Dynamics) zur Simulation von Luftströmungsmustern vor der Implementierung, der Einsatz von Temperatur- und Luftströmungssensoren an strategischen Stellen, Rauchtests zur visuellen Verfolgung der Luftbewegungspfade und Druckdifferenzmessungen zur Überprüfung der Integrität des Containments. Ein gut ausgeführtes Luftstrommanagement steht außerdem in direktem Zusammenhang mit geringeren Kühlkosten (oft 20-30 % Einsparungen), einer längeren Lebensdauer der Geräte und einer höheren Rechendichte pro Quadratmeter. Zu den bewährten Lösungen zur besseren Zirkulation gehören die Eingrenzung von Warm- und Kaltgängen, um eine Vermischung der Luftströme zu verhindern, die Aufrechterhaltung optimaler Rack-Einlasstemperaturen, die Sicherstellung einer angemessenen Perforation der Bodenfliesen in Doppelbodenumgebungen, die Optimierung der Serverplatzierung, um einen Bypass-Luftstrom zu vermeiden, und die Durchführung regelmäßiger Wärmebilduntersuchungen, um sich entwickelnde Probleme zu erkennen. Besonderer Aufmerksamkeit bedarf das Kabelmanagement, da eine ungeordnete Verkabelung den Luftstrom um bis zu 60 % behindern kann; ebenso ist es sinnvoll Abdeckplatten aller ungenutzten Rack-Räume abzudichten, um eine innere Zirkulation heißer Luft zu verhindern.
