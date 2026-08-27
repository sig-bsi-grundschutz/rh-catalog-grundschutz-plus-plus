# TEST.3.1.4 - \[Tests\] Testdaten

## Control Statement

Änderungen und Tests SOLLTE die Testfälle abdeckende, aber unkritische Testdaten verankern.

## Control guidance

Testdaten (engl. test data) sind synthetisch erstellte oder abstrahierte Daten, die zur Durchführung von Testfällen genutzt werden. „Unkritisch“ bedeutet hier, dass die Daten keinen schützenswerten Daten wie Geschäftsgeheimnisse oder sicherheitsrelevanten Konfigurationsdetails enthalten. Testfälle (engl. test cases) sind vorab definierte Szenarien oder Abläufe, die das Verhalten einer Anwendung oder eines Systems gezielt prüfen sollen. Der Zweck der Anforderung liegt darin, sicherzustellen, dass Testaktivitäten einerseits realistische Bedingungen nachbilden, andererseits aber keine Risiken durch unbeabsichtigte Preisgabe oder Manipulation produktiver Daten entstehen. Ein Vorfall könnte beispielsweise darin bestehen, dass versehentlich echte Kundendaten in einer Testumgebung landen und durch unzureichende Sicherung Dritten zugänglich werden; durch den Einsatz unkritischer Testdaten kann dieses Risiko vermieden und dennoch die Qualität der Tests gewährleistet werden. Eine Institution kann die Anforderung praktisch umsetzen, indem sie Testdatensätze automatisiert generieren lässt, etwa durch Anonymisierung oder Pseudonymisierung produktiver Daten oder durch die Nutzung von Zufallswerten, die für Testlogik realistisch wirken. Zusätzlich kann es hilfreich sein, Regeln für Entwickler und Tester festzulegen, die dokumentieren, welche Arten von Daten zulässig sind. Auch Tools zur data masking oder synthetic data generation können verwendet werden, um komplexe Datenstrukturen ohne reale Inhalte nachzubilden.
