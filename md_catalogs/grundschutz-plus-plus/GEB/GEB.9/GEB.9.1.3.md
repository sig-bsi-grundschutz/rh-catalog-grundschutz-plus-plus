---
x-trestle-set-params:
  geb.9.1.3-prm1:
    values:
---

# GEB.9.1.3 - \[Versorgungseinrichtungen\] Redundante Stromversorgung

## Control Statement

Gebäudemanagement für Standorte KANN eine redundante Stromversorgung für {{ insert: param, geb.9.1.3-prm1 }} installieren.

## Control guidance

Wenn die Stromzufuhr ausfällt, könnten geschäftskritische Anwendungen unerwartet ausfallen oder Daten verlorengehen. Die Redundanz der Stromquelle kann z.B. durch einen im System integrierten Akku, durch eine eigenständige unterbrechungsfreie Stromversorgung (USV) oder durch die Anbindung an ein sekundäres Stromnetz gewährleistet werden. Bei Bedarf kann sie auch die Übergangszeit bis zum Anlauf einer längerfristigen Netzersatzanlage überbrücken. Beim Betrieb einer USV ist auf die Einhaltung eines akzeptablen Temperaturbereichs der Batterie zu achten. Bei relevanten Änderungen an den Verbrauchern könnte es vorkommen, dass die USV-Systeme nicht mehr ausreichend dimensioniert sind. Da der Leistungsbedarf von Klimaanlagen oft zu hoch für eine USV ist, empfiehlt es sich zumindest die Steuerung der Anlagen an die unterbrechungsfreie Stromversorgung anzuschließen. Eine regelmäßige Wartung (u.U. nach Vorgabe des Herstellers) der USV und eine Trennung der Leistungselektronik von der Batterie ist empfohlen. Bei sehr hohem Schutzbedarf empfiehlt sich eine redundante Auslegung der USV. Die minimale Stützzeit (Autonomiezeit) ergibt sich als Stützzeit = Wartezeit auf mögliche Wiederkehr der Stromversorung + 2 * Zeit zum Herunterfahren der Komponenten. Bei sehr hohem Schutzbedarf empfiehlt sich eine redundante Auslegung der USV. Die Verkabelungswege sind redundant, wenn die Leitungen über verschiedene Wege geführt sind, sodass z.B. eine versehentliche Trennung nicht beide Leitungen betrifft.
