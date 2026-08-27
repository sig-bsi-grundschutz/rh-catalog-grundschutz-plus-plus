# NOT.4.10 - \[Datensicherung\] Getrennte Aufbewahrung

## Control Statement

Notfallplanung SOLLTE die Datensicherung getrennt von den Originaldaten platzieren.

## Control guidance

Originaldaten (engl. primary data) sind die produktiven oder operativen Daten, die unmittelbar für die laufenden Geschäftsprozesse verwendet werden. Die Anforderung adressiert damit, dass Kopien oder Sicherungen nicht am gleichen Ort wie die produktiven Systeme und deren Speicher verbleiben. Hintergrund ist, dass ein Vorfall wie ein Brand, ein Wasserschaden oder ein gezielter Einbruch gleichzeitig sowohl die produktiven Systeme als auch die dort aufbewahrten Sicherungen betreffen könnte, wodurch eine Wiederherstellung unmöglich wäre. Die physische Trennung kann dagegen die Verfügbarkeit und Wiederanlaufbarkeit der Daten nach einem Schadensereignis sicherstellen. Die Anforderung gilt auch für die Aufbewahrung bei Cloud-Diensten: Eine Aufbewahrung der Datensicherung bei einem Dienstleister, bei dem auch die Originaldaten liegen, erfüllt die Anforderung NICHT. Bei der getrennten Aufbewahrung von Datensicherung sind häufig praktische und sicherheitsrelevante Herausforderungen zu beachten: Ein ausgelagerter Speicherort ist in gleichem Maße schutzbedürftig gegenüber unbefugtem Zugriff wie der Standort der Originaldaten, da sich darauf oft vollständige und aktuelle Kopien sensibler Informationen befinden. Zudem sind längere Wiederanlaufzeiten möglich, wenn der externe Standort nicht unmittelbar erreichbar ist oder wenn logistische Verzögerungen beim Zugriff auf die ausgelagerten Datenträger auftreten. Auch die Gefahr von Inkonsistenzen steigt, wenn Backups zwar ausgelagert, aber nicht regelmäßig synchronisiert oder bei der Überprüfung beachtet werden.
