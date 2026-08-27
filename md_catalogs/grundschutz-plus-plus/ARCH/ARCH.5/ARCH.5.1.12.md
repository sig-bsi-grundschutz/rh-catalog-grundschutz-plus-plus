# ARCH.5.1.12 - \[Perimeterschutz\] Software-definierte Verbindungen

## Control Statement

Architektur für Netze KANN Verbindungen zwischen IT-Systemen anhand dynamischer Kriterien einschränken.

## Control guidance

Software-definierte Verbindungen sind logisch kontrollierte Netzwerkpfade, deren Zugriffsbedingungen nicht statisch hinterlegt, sondern anhand aktueller Merkmale bewertet werden; dynamische Kriterien meint dabei festgelegte Filterregeln, deren Werte situativ ermittelt werden, etwa über „context attributes“ oder „dynamic policies“. Solche Merkmale können als contextual signals wie momentane Auslastung, Gerätezustand („device posture“) oder zeitliche Rahmenbedingungen interpretiert werden, während die zugrunde liegenden Regeln unverändert bleiben und nur ihre Bewertung variiert. Dies kann helfen, laterale Bewegungen einzudämmen und kann gleichzeitig unerwartete Zugriffe in veränderten Betriebszuständen abblocken; ein Angriff, der unentdeckt Systeme durchqueren könnte, oder ein kompromittierter Client, der außerhalb definierter Parameter agiert, könnte dadurch abgewehrt werden. Praktisch kann dies über segmentierende „Software-Defined Networking“-Mechanismen, kontextabhängige Firewall-Policies oder adaptive Access-Control-Engines erfolgen. Eine angemessene Absicherung ist hier zu verstehen als ein Bündel verlässlicher Signale, die den Zustand eines Endpunkts oder Dienstes authentisch widerspiegeln. Als Varianten kommen etwa kontextabhängige SDN-Flows, regelbasierte Mikrosegmentierung über Identity-Tags oder der Einsatz von Policy-Engines infrage, die ihre Entscheidungen anhand dynamisch erfasster Werte wie Geräteintegrität, Standort oder Risikobewertung fällen.
