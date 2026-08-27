---
x-trestle-set-params:
  bes.5.2-prm1:
    values:
---

# BES.5.2 - \[Auswahl von Produkten und Dienstleistungen - Zusammenarbeit\] Service Level Agreement

## Control Statement

Beschaffungsmanagement für Outsourcing SOLLTE die Einhaltung einer bestimmten Dienstgüte anhand von {{ insert: param, bes.5.2-prm1 }} vereinbaren.

## Control guidance

Dienstgüte (engl. Service Quality oder Service Level) beschreibt das messbare Leistungsniveau, das ein externer Anbieter dauerhaft erbringen soll. Sie wird üblicherweise in Service Level Agreements (SLA) festgelegt und kann Aspekte wie Reaktionszeiten, Verfügbarkeiten, Fehlerraten oder Sicherheitsstandards betreffen. Die Kriterien können z. B. Verfügbarkeit (in %), maximale Wiederherstellungszeiten (Recovery Time Objective, RTO), Datensicherheitsmaßnahmen, Supportzeiten oder Nachweisintervalle für Penetrationstests sein. Der Zweck dieser Vorgabe liegt darin, Risiken unklarer Leistungs- oder Sicherheitsverantwortung zu vermeiden, die im Falle unpräziser oder fehlender Dienstgütezusagen zu Ausfällen, Datenverlusten oder unzureichenden Sicherheitsreaktionen führen könnten. Eine klar definierte und überprüfbare Dienstgüte kann dagegen Transparenz schaffen, die Vergleichbarkeit von Anbietern erleichtern und die Resilienz ausgelagerter Prozesse erhöhen. Dabei sind möglichst objektivierte, quantitative Kriterien deutlich nachvollziehbarer und eindeutiger als einfache Beschreibungen wie "gut". Ein Beipiel ist eine Mindestverfügbarkeit von 99% für einen Server, auf dem hochverfügbare Daten gespeichert werden. Neben einzuhaltenden Mindestkriterien bietet es sich hier auch an optionale Qualitätskriterien festzulegen, bei deren Erfüllung höhere Preise akzeptiert werden, um ein "Race to the bottom" im Wettbewerb der Anbieter um die Institution zu vermeiden, da ein rein preisorientierter Wettlauf auf Kosten der Sicherheit gehen könnte.
