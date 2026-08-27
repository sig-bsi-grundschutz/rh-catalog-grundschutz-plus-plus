---
x-trestle-set-params:
  ber.4.4-prm1:
    values:
---

# BER.4.4 - \[Berechtigungsmanagement\] Überprüfung von Berechtigungen

## Control Statement

Berechtigung SOLLTE vergebene Berechtigungen {{ insert: param, ber.4.4-prm1 }} auf Erforderlichkeit überprüfen.

## Control guidance

Erforderlichkeit bedeutet in diesem Kontext, dass eine vergebene Berechtigung nur dann als gerechtfertigt gilt, wenn sie für die aktuelle Aufgabenwahrnehmung, Rolle oder Funktion einer Person tatsächlich benötigt wird. Dabei kann zwischen fachlicher Notwendigkeit (z. B. Zugriff auf eine bestimmte Anwendung, um Kernaufgaben erfüllen zu können) und zeitlicher Relevanz (z. B. Projektzugriff, der nur für die Dauer des Projekts sinnvoll ist) unterschieden werden. Als mögliche Werte für den Parameter regelmäßig bieten sich an: (1) quartalsweise, (2) halbjährlich, (3) jährlich – je nach Kritikalität der Systeme und Sensibilität der Daten. Die regelmäßige Überprüfung der Erforderlichkeit kann verhindern, dass sich unbemerkt überhöhte Rechte („Privilege Creep“) ansammeln, die Angreifern im Falle einer Kompromittierung zusätzlichen Spielraum eröffnen könnten. Ohne solche Kontrollen könnte ein ehemaliger Projektmitarbeiter weiterhin Zugang zu sensiblen Daten haben oder ein interner Angreifer auf nicht benötigte Administrationsrechte stoßen. Umgekehrt kann die Überprüfung sicherstellen, dass Berechtigungen stets am aktuellen Aufgabenprofil ausgerichtet bleiben und so Schaden durch Missbrauch oder Fehlhandlungen eingedämmt werden kann. Zur Umsetzung kann eine Institution rollenbasierte Zugriffskonzepte einsetzen, die regelmäßig mit den Ist-Berechtigungen der Nutzer abgeglichen werden („Access Reviews“). Dies kann durch automatisierte Reports aus Verzeichnisdiensten, Datenbanken oder Fachanwendungen erfolgen, die Verantwortlichen zur Bestätigung oder Korrektur vorgelegt werden. Hilfreich kann auch ein Vier-Augen-Prinzip sein, bei dem Vorgesetzte die Notwendigkeit von Berechtigungen bestätigen. Darüber hinaus kann es nützlich sein, temporäre Projekt- oder Sonderrechte mit Ablaufdatum zu vergeben, sodass diese automatisch entzogen werden, wenn sie nicht mehr bestätigt werden.
