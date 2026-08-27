---
x-trestle-set-params:
  konf.12.11-prm1:
    values:
---

# KONF.12.11 - \[Kontrollierte Datenverarbeitung\] Anonyme oder Pseudonyme Kommunikation

## Control Statement

Konfiguration für TK-Anwendungen KANN die Übermittlung {{ insert: param, konf.12.11-prm1 }} zur Gegenstelle aktivieren.

## Control guidance

Wenn eine persönliche Identifikation von Kommunikationspartnern erforderlich ist, ist eine Verschleierung von Erreichbarkeiten sinnvoll. In der klassischen Telefonie kann hierfür die Rufnummerunterdrückung für ausgehende Anrufe (CLIR) oder eine Pseudonymisierung, z.B. durch Übermittlung der 0 statt der Nebenstelle, genutzt werden. Für die Verschleierung der Netzquelle können Proxy-Server oder Anonymisierungsgateways genutzt werden. Für weitere Details siehe "Kompendium für organisationsinterne Telekommunikationssysteme mit erhöhtem Schutzbedarf".
