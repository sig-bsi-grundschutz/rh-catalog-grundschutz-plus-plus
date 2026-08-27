---
x-trestle-set-params:
  det.5.3.1-prm1:
    values:
---

# DET.5.3.1 - \[Management von Schwachstellen\] Autorisierung kritischer Scans

## Control Statement

Detektion SOLLTE kritische Scans durch {{ insert: param, det.5.3.1-prm1 }} autorisieren.

## Control guidance

Schwachstellenscans könnten aufgrund ihres Umfangs oder der breiten Abdeckung ihrer Aktivitäten selbst Fehlerzustände provozieren oder Schwachstellen auslösen. Wenn Scans besondere Berechtigungen benötigen - z.B. lokale Administrationsrechte oder Zugriff auf ein abgeschottetes Netz sensibler, betriebskritischer Systeme, so kann eine Autorisierung solcher Scans, vor der eine Abwägung der damit verbundenen Risiken vorgenommen wird, angezeigt sein.
