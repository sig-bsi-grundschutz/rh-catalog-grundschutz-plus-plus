# DET.6.2.1 - \[Vorfallserkennung\] Dynamische Sandbox-Analyse

## Control Statement

Detektion KANN verdächtige Dateien in einer isolierten Umgebung mindestens anhand von aufgebauten Netzverbindungen, Systemaufrufen und Dateizugriffen testen.

## Control guidance

Eine dynamische Sandbox Analyse ist die Ausführung des verdächtigen Codes in einer isolierten Umgebung, aus der eine Anwendung nicht durch Ausführung von Systembefehlen ausbrechen kann (Sandbox Detonation). Sie ermöglicht die sichere Untersuchung potenziell schädlicher Dateien in einer isolierten Umgebung, um deren tatsächliches Verhalten zu beobachten. Eine dynamische Analyse kann verschiedene verdächtige Aktivitäten erfassen: Dateisystemoperationen wie das Erstellen, Ändern oder Löschen von Dateien; Registry-Modifikationen, besonders in Autostart-Bereichen; Netzwerkverhalten einschließlich externer Verbindungsversuche und Datenexfiltration; Prozessverhalten wie Injektionstechniken oder unerwartete Kindprozesse; Speichermanipulationen; Persistenzmechanismen wie Dienste oder geplante Aufgaben; Anti-Analyse-Techniken zur Erkennung virtueller Umgebungen; sowie ungewöhnliche API-Aufrufe wie kryptografische Funktionen oder Sicherheitsumgehungen. Die Sandbox kann dabei mit ausreichender Laufzeit, Netzwerksimulation und Snapshot-Funktionen ausgestattet werden, um auch verzögerte oder umgebungsspezifische Schadfunktionen zu erkennen.
