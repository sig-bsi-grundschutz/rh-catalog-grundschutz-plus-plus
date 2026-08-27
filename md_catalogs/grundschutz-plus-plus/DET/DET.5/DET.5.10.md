# DET.5.10 - \[Management von Schwachstellen\] Zeitnahes Patchmanagement

## Control Statement

Detektion SOLLTE ein zeitnahes Patchmanagement verankern.

## Control guidance

Patches (Updates oder Sicherheitsaktualisierungen) sind neue Versionen, die Sicherheitslücken schließen. Je nach Aufbau der betroffenen Assets kann es bei der Aktualisierung auch erforderlich sein, Abhängigkeiten (Bibliotheken, Upstream Software) ebenfalls zu aktualisieren. Dies kann durch automatisierte Installation oder nach einem Test umgesetzt werden. Die Umsetzung kann auch den schrittweisen Rollout von Patches vorsehen, sodass bei Fehlern im Patch nicht alle Systeme gleichzeitig betroffen sind und auch komplexe Fehlerbilder durch Rückmeldungen frühzeitig erkannt werden können. Dies kann zum Beispiel nach dem One-Many-All-Prinzip oder Blue-Green-Deployment erfolgen. Zur Beurteilung der Kritikalität von Patches kann die Krititikalität der mit dem Patch verbundenen Schwachstellen, das Risikoprofil der zu patchenden Assets oder eine Korrelation komplexer Angriffswege herangezogen werden.
