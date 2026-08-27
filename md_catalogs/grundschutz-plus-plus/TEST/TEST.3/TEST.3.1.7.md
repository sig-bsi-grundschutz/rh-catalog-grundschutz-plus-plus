# TEST.3.1.7 - \[Tests\] Chaos Engineering

## Control Statement

Änderungen und Tests KANN die Resilienz bei Simulation verschiedenartiger Störungen testen.

## Control guidance

Chaos Engineering kann helfen, die Zuverlässigkeit von Systemen oder Anwendungen zu erhöhen, indem es die Resilienz, also die Fähigkeit bei störenden Einflüssen den Betrieb fortzusetzen oder wiederherzustellen, durch simulierte Ausfälle oder Störungen testet. Dabei ist jedoch zu beachten, dass dabei keine geschäftskritischen, im Betrieb befindlichen Dienste gestört werden. Daher ist der Ansatz nur nach einer Analyse und Abwägung der Risiken sinnvoll. Zweckmäßig ist es dabei, geschäftskritische Systeme und Anwendungen mit hohen Auswirkungen zu priorisieren, häufige Ausfallmodi zu testen, kritische Abhängigkeiten unter Stress zu setzen, vergangene Vorfälle nachzubilden und Systemannahmen durch methodische Prozesse zu hinterfragen. Hierzu kann eine Karte der Abhängigkeiten verwendet werden oder eine Analyse kritischer Pfade. Wertvolle Experimente können Netzwerkbeeinträchtigungen, Dienstausfälle, Abhängigkeitsunterbrechungen, Ressourcenerschöpfung, Multiregionsausfälle und Zeitsynchronisationsprobleme umfassen. Geschäftskritische Dienste können dabei z.B. durch eine Begrenzung auf bestimmte Systeme, oder Durchführung solcher Tests nur außerhalb der Betriebszeiten geschützt werden.
