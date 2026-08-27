---
x-trestle-set-params:
  det.5.6-prm1:
    values:
---

# DET.5.6 - \[Management von Schwachstellen\] Threat Hunting

## Control Statement

Detektion KANN den Informationsverbund durch Sicherheitsexperten auf Anzeichen für Angriffe {{ insert: param, det.5.6-prm1 }} überprüfen.

## Control guidance

Threat Hunting bezeichnet eine proaktive Suche nach Anzeichen für Sicherheitsvorfälle durch Analyseexperten, da fortschrittliche Angriffe durch automatisierte Systeme zur Angriffserkennung häufig nicht detektiert werden können. Im Unterschied zum Penetrationstest steht dabei nicht das Aufsuchen von Schwachstellen, sondern das Finden bereits erfolgreicher Angriffe oder Bedrohungen in den eigenen Systemen und Anwendungen im Vordergrund. In einem ersten Schritt werden Hypothesen, wo und wie sich Angreifer in Infrastrukturen eingeschlichen haben könnten, aufgestellt. Dabei kann man sich etwa auf den Kontext des Informationsverbunden und existierende Bedrohungsmodellierungen stützen. Anschließend werden einschlägige Zielobjekte ausgewählt und auf Anzeichen für verdächtige Aktivitäten untersucht, etwa IT-Systeme, die direkt aus dem Internet erreichbar sind, Jumphosts oder zentrale Hostsysteme. Die Ergebnisse der Überprüfung fließen dann in die regelmäßige Auswahl und Verbesserung von Schutzmaßnahmen mit ein.
