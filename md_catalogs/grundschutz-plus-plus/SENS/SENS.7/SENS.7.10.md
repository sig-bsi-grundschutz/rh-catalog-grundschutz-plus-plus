# SENS.7.10 - \[Umgang mit spezifischen Zielobjekten\] Trennen nicht benötigter Anschlüsse

## Control Statement

Sensibilisierung für Nutzende von Virtualisierungslösungen SOLLTE zum Trennen nicht benötigter Verbindungen zwischen Host und virtuellem Gast sensibilisieren.

## Control guidance

Werden unnötige Verbindungen zwischen Host und Gast nicht getrennt, könnte dies zu unautorisiertem Zugriff auf Daten oder Systeme führen, etwa wenn eine Malware aus dem Gast Zugriff auf Host-Ressourcen erhält oder wenn sensible Dateien versehentlich zwischen beiden Umgebungen ausgetauscht werden. Durch eine saubere Trennung kann das Risiko seitlicher Bewegungen innerhalb der IT-Infrastruktur verringert werden und die Integrität einzelner Arbeitsumgebungen kann erhalten bleiben. Dies betrifft z.B. angeschlossene Geräte und Schnittstellen wie Drucker, USB-Sticks oder auch die Netzanbindung. Auch einfache Checklisten für IT-Personal und Nutzende können helfen, das Bewusstsein zu stärken, dass Komfortfunktionen wie „Drag & Drop“ zwischen Host und Gast zwar praktisch erscheinen, aber potenziell eine unnötige Angriffsfläche eröffnen können.
