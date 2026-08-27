---
x-trestle-set-params:
  konf.12.4-prm1:
    values:
---

# KONF.12.4 - \[Kontrollierte Datenverarbeitung\] Speicherung von Zugangsdaten

## Control Statement

Konfiguration für Webbrowser SOLLTE die Speicherung von Zugangsdaten {{ insert: param, konf.12.4-prm1 }} aktivieren.

## Control guidance

Werden Zugangsdaten gespeichert, so könnten Angreifer diese auslesen und missbrauchen. Daher ist es wichtig, Vertraulichkeit und Integrität sensibler Anmeldedaten zu gewährleisten. Durch die Nutzung einer geprüften Browser‑Extension kann sichergestellt werden, dass Passwörter nur in einem verschlüsselten Vault abgelegt werden, der zentral verwaltet oder versioniert wird. Ein starkes Master‑Passwort kann als Schlüssel dienen, sodass selbst bei Verlust des Geräts oder unautorisiertem Zugriff auf die lokale Datenbank die Daten ohne Kenntnis dieses Passworts nicht lesbar sind. Wird die Funktion komplett deaktiviert, kann das Risiko unkontrollierter Speicherung oder unsicherer Autovervollständigung minimiert werden – der Anwender kann sich stattdessen etwa auf einen externen Manager oder eine Single‑Sign‑On‑Lösung verlassen. Konkret kann dies in der Praxis auf verschiedene Weisen aussehen: So kann eine Institution über Gruppenrichtlinien festlegen, dass nur eine offiziell freigegebene Extension (etwa einer Open‑Source‑Lösung oder eines kommerziellen Anbieters) installiert werden darf. Alternativ lassen sich browserinterne Passwort‑Speicher mit einem Master‑Passwort verschlüsseln – denkbar ist hier sowohl die Nutzung integrierter Funktionen von Browsern mit zuverlässiger Krypto‑Engine als auch externer Tools wie plattformübergreifende Passwort‑Manager, die eine Browser‑Anbindung per Plugin bieten. In Szenarien mit besonders hohen Sicherheitsanforderungen kann die Speicherung ganz deaktiviert werden, etwa indem das entsprechende Feature per Policy abgeschaltet wird und Nutzer gezielt mit einem eigenständigen, von der Institution kontrollierten Tool arbeiten. Für die Umsetzung bietet es sich an, zunächst eine klare Richtlinie zu formulieren, die alle Mitarbeitenden über die zugelassenen Speicherwege informiert und gleichzeitig erklärt, warum unautorisierte Methoden unerwünscht sein können. IT‑Administratoren können über zentrale Management‑Werkzeuge (GPOs, MDM‑Systeme) die Installation autorisierter Extensions automatisieren und unerwünschte Funktionen deaktivieren. Es kann hilfreich sein, standardisierte Vorlagen für sichere Master‑Passwörter zu kommunizieren und regelmäßige Schulungen anzubieten, in denen der Umgang mit dem Passwort‑Manager, das Prüfen der Passwortstärke und das Einspielen von Updates erklärt werden. Schließlich kann eine optionale Passwort‑Auditing‑Funktion im Manager eingesetzt werden, mit der Nutzer Schwachstellen in ihren Passwörtern erkennen und verbessern können – so bleibt die gesamte Passwortlandschaft im Unternehmen übersichtlich und sicher.
