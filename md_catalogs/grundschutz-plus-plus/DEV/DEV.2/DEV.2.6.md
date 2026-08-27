# DEV.2.6 - \[Softwareentwicklung - Security by Design\] Widerstandsfähigkeit gegen gängige Angriffsmuster

## Control Statement

Entwicklung für Anwendungen SOLLTE Schutzfunktionen gegen gängige Angriffsmuster installieren.

## Control guidance

Gängige Angriffsmuster sind wiederkehrende Vorgehensweisen von Angreifenden, die in der Praxis häufig auftreten, z. B. SQL-Injection, Cross-Site-Scripting (XSS) oder Pufferüberläufe. Welche Angriffsmuster für die konkrete Anwendung gängig sind, hängt von Funktionalität und Architektur der Anwendung ab, z.B. Prompt Injection bei generativer KI. Die Vorschrift zielt darauf ab, dass Produkte bereits in der Entstehung so gestaltet werden, dass typische Schwachstellen systematisch erschwert werden. Ohne entsprechende Vorkehrungen könnte ein Angreifer etwa durch manipulierte Eingaben vertrauliche Daten auslesen oder unautorisiert Funktionen steuern. Werden Schutzfunktionen frühzeitig eingebaut, kann die Stabilität des Produkts erhöht, die Angriffsfläche reduziert und das Vertrauen der Nutzenden gestärkt werden. Zur Umsetzung können etablierte Programmierpraktiken wie das Verwenden sicherer Standardbibliotheken, das Einschränken von Nutzerrechten im Code oder das Einführen von Fallback-Mechanismen bei fehlerhaften Eingaben verwendet werden. Ergänzend kann die Institution Secure Coding Guidelines nutzen, die häufige Angriffsmuster adressieren und Entwickelnden praxisnahe Hilfen bieten.
