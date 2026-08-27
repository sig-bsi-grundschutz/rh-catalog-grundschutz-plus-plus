---
x-trestle-set-params:
  ber.4.2-prm1:
    values:
---

# BER.4.2 - \[Berechtigungsmanagement\] Autorisierung von Berechtigungen

## Control Statement

Berechtigung SOLLTE die Zuweisung von Berechtigungen durch {{ insert: param, ber.4.2-prm1 }} autorisieren.

## Control guidance

Mit „bestimmte Personen oder Rollen“ sind hier vorab festgelegte, nachvollziehbar benannte Autorisierungsinstanzen gemeint, also etwa disziplinarische Führungskräfte, fachliche Daten- oder Prozessverantwortliche, Systemverantwortliche, Rollen wie Application Owner, Data Owner, Service Owner oder Genehmiger in einem Identity-and-Access-Management-Prozess. Gemeint ist nicht eine beliebige informelle Zustimmung, sondern eine fachlich oder organisatorisch legitimierte Entscheidung darüber, ob eine konkrete Berechtigung zu einer Person, Funktion, Aufgabe oder einem Schutzbedarf passt. Die Vorschrift zielt darauf ab, unkontrollierte, fachlich nicht begründete oder zu weitreichende Berechtigungsvergaben zu vermeiden; ohne eine festgelegte Autorisierungsinstanz könnte ein Zugangskonto Zugriff auf vertrauliche Daten erhalten, eine nicht mehr passende Gruppenmitgliedschaft könnte bestehen bleiben oder ein privilegierter Zugang könnte ohne ausreichende fachliche Prüfung vergeben werden. Eine geregelte Autorisierung kann die Nachvollziehbarkeit von Zugriffsentscheidungen erhöhen, Interessenkonflikte reduzieren und sicherstellen, dass Berechtigungen an Aufgaben, Verantwortlichkeiten und Schutzbedarf ausgerichtet bleiben.
