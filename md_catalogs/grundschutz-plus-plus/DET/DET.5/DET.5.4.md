---
x-trestle-set-params:
  det.5.4-prm1:
    values:
  det.5.4-prm2:
    values:
---

# DET.5.4 - \[Management von Schwachstellen\] Regelmäßige Penetrationstests

## Control Statement

Detektion für IT-Systeme KANN die tatsächliche Abwehrfähigkeit nach {{ insert: param, det.5.4-prm1 }} {{ insert: param, det.5.4-prm2 }} überprüfen.

## Control guidance

Ein Penetrationstest, oft auch als Pentest bezeichnet, ist eine von Sicherheitsexperten simulierte Cyberattacke, um Schwachstellen und Sicherheitslücken aufzudecken. Ziel ist es, komplexe Schwachstellen in konkreten Informationsumgebungen aufzuspüren, bevor sie von echten Angreifern ausgenutzt werden könnten. Dabei werden verschiedene Methoden und Techniken eingesetzt, die auch von Angreifern verwendet werden könnten, z.B. Informationssammlung, Scan und Ausnutzen von Schwachstellen, seitliches Ausbreiten über das Netz, sowie Versuche, durch Täuschung und Manipulation von Personen an Informationen oder Zugriff zu gelangen. Anerkannte Vorgehensweisen, die für Penetrationstests angewendet werden können, sind z.B. der BSI Praxis-Leitfaden für IS-Penetrationstests, OSSTMM, NIST SP 800-115, PTES (Penetration Testing Execution Standard), OWASP für Webanwendungen oder der Leitfaden für Penetrationstests von Large-Language-Modellen des Expertenkreises KI-Sicherheit. Pentests können von externen Dienstleistern oder internem Personal vorgenommen werden. Entscheidend für ein gutes Ergebnis ist hierbei neben einer standardisierten, strukturierten Vorgehensweise die Qualifikation der ausführenden Personen, da Penetrationstests die Ausforschung komplexer Angriffsmöglickeiten erfordern, die weit über den isolierten Einsatz einzelner Werkzeuge hinausgehen können. Pentesting von Außen enthält sowohl die Suche nach angreifbaren Schwachstellen aus dem Internet, als auch die vorhergehende Recherche, um angreifbare Informationen aufzuspüren (Open Source Intelligence). Zur konsequenten Überprüfung gehört auch, dass deren gefundene Schwachstellen im Rahmen des Schwachstellenmanagements zeitnah behandelt werden. Zweckmäßig ist es daher, gefundene Schwachstellen bestimmten zuständigen Personen oder Rollen zur Behebung zuzuweisen und diese innerhalb der Fristen des Schwachstellenmanagements zu schließen.
