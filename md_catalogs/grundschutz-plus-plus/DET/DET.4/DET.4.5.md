# DET.4.5 - \[Überwachung von Aktivitäten\] Unerwünschte Datenabflüsse

## Control Statement

Detektion KANN unerwünschte Datenabflüsse überwachen.

## Control guidance

Unerwünschte Datenabflüsse beziehen sich hier auf jede unautorisierte Übertragung sensibler Informationen aus internen IT-Systemen oder Anwendungen nach außen (engl. data leakage oder data exfiltration). Darunter fallen sowohl absichtliche als auch unbeabsichtigte Transfers, etwa über Endgeräte, Netzwerkkanäle oder Cloud-Schnittstellen, wobei Data Loss Prevention (DLP) als Sammelbegriff für technische und organisatorische Maßnahmen dient, die solche Abflüsse erkennen oder verhindern können. Die Überwachung kann gewährleisten, dass vertrauliche Inhalte nicht unbemerkt der Kontrolle entzogen werden. Herkunft und Ziel solcher Abflüsse können zusätzlich Indikatoren für kompromittierte Zugangskonten oder Fehlkonfigurationen liefern. Der Zweck der Vorschrift liegt darin, potenzielle Datenabflüsse frühzeitig sichtbar zu machen, sodass aufkommende Risiken wie der Verlust von personenbezogenen Datensätzen oder vertraulichen Forschungsunterlagen erkannt werden können; andernfalls könnte ein Angreifer persistente Kommunikationskanäle nutzen, um über längere Zeit unbemerkt Daten abzuziehen. Eine wirksame Überwachung kann dabei Anomalien identifizieren, die auf Missbrauch, Malware-Aktivität oder Fehlbedienungen hindeuten, und kann die Integrität sowie Vertraulichkeit schützenswerter Informationen erhöhen. Mögliche Varianten der Umsetzung können auf datei- und inhaltsbasierter DLP-Analyse, Netzwerk-DLP über definierte inspection points, Monitoring von Cloud-Workloads mittels API-gestützter DLP-Funktionen oder Endpoint-DLP basierend auf Richtlinien für Kopieren, Drucken oder Übertragungen über Wechselmedien beruhen.
