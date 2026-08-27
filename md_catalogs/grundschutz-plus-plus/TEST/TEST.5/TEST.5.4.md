# TEST.5.4 - \[Bereitstellung\] Persistenz

## Control Statement

Änderungen und Tests SOLLTE die Persistenz nach wesentlichen Änderungen testen.

## Control guidance

Persistenz bedeutet hier, dass eine wesentliche Änderung nach ihrer Einführung dauerhaft wirksam bleibt, also auch nach einem Neustart, einem System-Update oder einem Rückspielen von Konfigurations-Backups nicht unbeabsichtigt verloren geht. Dies könnte beispielsweise dazu führen, dass eine sicherheitsrelevante Konfiguration nach einem Reboot verschwindet oder eine Migration zu einem neuen Anbieter scheitert, weil Daten oder Regeln nicht portabel waren. Eine Institution kann die Anforderung praktisch umsetzen, indem Änderungen nach Abschluss nicht nur funktional, sondern auch über System- und Lebenszyklusereignisse hinweg überprüft werden. Dazu kann es hilfreich sein, Änderungen gezielt mit simulierten Neustarts, Failover-Tests oder dem erneuten Einspielen von Standard-Backups zu validieren. Um den laufenden Betrieb hierdurch nicht zu beeinträchtigen können Systeme oder Anwendungsinstanzen nacheinander oder zu unkritischen Zeiten neu gestartet werden.
