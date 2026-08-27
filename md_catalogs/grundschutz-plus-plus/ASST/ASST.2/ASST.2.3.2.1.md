---
x-trestle-set-params:
  asst.2.3.2.1-prm1:
    values:
---

# ASST.2.3.2.1 - \[Inventarisierung\] Software Discovery

## Control Statement

Informationen und Assets KANN die Aktualität des Inventars der Anwendungen durch ein automatisiertes Verfahren {{ insert: param, asst.2.3.2.1-prm1 }} überprüfen.

## Control guidance

Die automatische Aktualisierung des Anwendungsinventars (etwa bei Installationen, Konfigurationsänderungen und Deinstallationen) dient in erster Linie der vollständigen Transparenz über die IT-Landschaft. Ein aktuelles Anwendungsinventar kann als Grundlage für Compliance-Nachweise, Lizenzmanagement und Schwachstellenanalysen dienen. Die Automatisierung dieses Prozesses verringert dabei den manuellen Verwaltungsaufwand und erhöht die Datenqualität, da menschliche Fehler oder Versäumnisse bei der Dokumentation vermieden werden können. Konkrete Anwendungsfälle können die automatische Erfassung einer neu installierten ERP-Software im Inventar, die Dokumentation einer Konfigurationsänderung an einer Firewall-Anwendung oder die Entfernung einer nicht mehr genutzten Datenbanksoftware aus dem Inventar sein. Auch Updates von Anwendungen, Änderungen an Zugriffsberechtigungen oder Konfigurationsanpassungen aufgrund neuer Sicherheitsanforderungen können als relevante Ereignisse für eine Inventaraktualisierung betrachtet werden. Für die Umsetzung können Software Asset Management (SAM) Tools eingesetzt werden, die über Agenten oder regelmäßige Netzwerk-Scans Änderungen erkennen. Eine Alternative kann die Integration von Deployment- und Konfigurationsmanagement-Systemen mit der CMDB (Configuration Management Database) sein, wodurch jede Änderung automatisch im zentralen Inventar gespiegelt wird. Die Implementierung von Event-Triggern in der IT-Infrastruktur kann ebenfalls dazu beitragen, dass bei definierten Ereignissen eine sofortige Inventaraktualisierung ausgelöst wird. Einen hohen Mehrwert für alle Sicherheitsbereiche kann es haben, Inventardaten aus verschiedenen Quellen automatisiert miteinander abzugleichen, z.B. aus Verzeichnisdiensten, AMDB, EDR und CMDB. Eine regelmäßige Validierung der Prozesse durch Stichprobenkontrollen kann dabei helfen, die Vollständigkeit und Genauigkeit der automatisierten Inventarisierung zu gewährleisten.
