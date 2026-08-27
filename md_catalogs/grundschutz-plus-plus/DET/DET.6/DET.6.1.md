---
x-trestle-set-params:
  det.6.1-prm1:
    values:
---

# DET.6.1 - \[Vorfallserkennung\] Beurteilung von Ereignissen

## Control Statement

Detektion SOLLTE ein Verfahren zur Beurteilung von sicherheitsrelevanten Ereignissen anhand von {{ insert: param, det.6.1-prm1 }} verankern.

## Control guidance

Aus einer größeren Menge von sicherheitsrelevanten Ereignissen kann durch Filterung und Korrelation eine kleinere Menge sicherheitskritischer Ereignisse destilliert werden. Dies bedeutet, dass aus allen möglichen Sicherheitsereignissen (wie Zugriffsversuche, Systemänderungen, Netzwerkverkehr) besonders auf die potenziell gefährlicheren oder wichtigeren Ereignisse geachtet wird. Für die Definition eines sicherheitskritischen Ereignisses, siehe Glossar (Namensräume des Grundschutz++). Die Filterung erfolgt sinnvollerweise automatisiert, z.B. durch SIEM, EDR. Die Überwachung kann anhand von bestimmten Begriffen (z.B. "login from unknown device", "blocked malware", "permission changed") oder durch Anomalieerkennung erfolgen. Aufgrund der Vielzahl an möglichen Ereignissen sind detaillierte Kriterien nur schwer festzulegen. Die Kriterien können sich daher auch an einem überschaubaren Schema, etwa einer Abschätzung der Auswirkungen auf die Geschäftsprozesse und gesetzlichen Meldepflichten, orientieren. Sobald ein solches kritisches Ereignis erkannt wird, erfolgt eine Bewertung durch definierte Personen oder Rollen. Diese entscheiden, ob das Ereignis tatsächlich als Sicherheitsvorfall eingestuft werden kann.
