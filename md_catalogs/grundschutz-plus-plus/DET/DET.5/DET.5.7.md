---
x-trestle-set-params:
  det.5.7-prm1:
    values:
---

# DET.5.7 - \[Management von Schwachstellen\] Analyse verdeckter Kanäle

## Control Statement

Detektion KANN den Informationsverbund auf verdeckte Kommunikationskanäle {{ insert: param, det.5.7-prm1 }} überprüfen.

## Control guidance

Ein verdeckter Kanal (Covert Channel) ist ein heimlicher Kommunikationskanal, mit dem Angreifer legitime Verbindungen ausnutzen, um verdeckt Daten zu übertragen. Die Analyse verdeckter Kanäle ist insbesondere dann sinnvoll, wenn die Gefahr eines unbefugten Informationsflusses über Sicherheitsdomänen hinweg besteht, beispielsweise bei Anwendungen an externen Netzanschlüssen oder bei IT-Systemen, auf denen Daten mit hoher Sicherheitseinstufung neben anderen Daten verarbeitet werden. Relevant sind dabei sowohl Speicherkanäle (Storage Channel) als auch Zeitkanäle (Timing Channel). Um potenzielle verdeckte Kanäle zu identifizieren bietet es sich an, auf Bedrohungsmodellierungen (Threat Modelling) oder die Sicherheitsarchitektur der betrachteten IT-Produkte zurückzugreifen. Entwickler oder erfahrene Penetrationstester sind am besten in der Lage, potenzielle Schwachstellen in IT-Systemen zu identifizieren, die zu verdeckten Kanälen führen könnten. Einige verdeckte Kanäle können durch darauf spezialisierte Erkennungswerkzeuge (sog. Warden) erkannt werden. Aufgrund der Vielzahl denkbarer verdeckter Kommunikationswege können solche Kanäle jedoch kaum vollständig verhindert werden. Daher ist es zweckmäßig, sich bei der Analyse auf diejenigen potenziellen verdeckte Kanäle zu konzentrieren, die eine bestimmte Bandbreitenschwelle überschreiten. Hierbei bietet sich ein gegenseitiger Abgleich mit existierenden Bedrohungsmodellierungen oder Risikoanalysen an. Auch ergänzende Maßnahmen wie Traffic Normalization können sinnvoll sein - dadurch kann verdeckte Kommunikation zwar nicht erkannt werden, jedoch kann man sie so ausbremsen oder unerkannt eliminieren.
