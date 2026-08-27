# ARCH.2.2.6 - \[Netzdesign\] Demilitarisierte Zone

## Control Statement

Architektur für Netze SOLLTE eine demilitarisierte Zone installieren.

## Control guidance

Unter einer Demilitarisierten Zone versteht man in diesem Kontext ein logisch oder physisch getrenntes Teilnetz, in dem Systeme mit exponierten Diensten – wie Webserver, Mail-Gateways oder VPN-Endpunkte – betrieben werden. Systeme der Institution, die sowohl aus dem öffentlichen Netz als auch aus dem internen Netz erreichbar sind, werden in einer demilitarisierten Zone (DMZ) so betrieben, dass (1) der Netzverkehr zwischen dem System und dem öffentlichen Netz gefiltert wird und (2) der Netzverkehr zwischen dem System und anderen internen Netzen gefiltert wird. Eine DMZ kann sowohl durch dedizierte Hardware-Firewalls als auch durch virtuelle Netzwerksegmente umgesetzt werden. Ohne eine solche Trennung könnte ein kompromittierter Webserver direkt als Sprungbrett ins interne Netz dienen oder Schadsoftware könnte sich ungehindert auf sensible Systeme ausbreiten. Mit einer DMZ kann eine Institution hingegen erreichen, dass kompromittierte Systeme isoliert bleiben und sicherheitskritische interne Netze weiterhin geschützt sind.
