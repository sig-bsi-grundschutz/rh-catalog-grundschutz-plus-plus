---
x-trestle-set-params:
  arch.6.2-prm1:
    values:
---

# ARCH.6.2 - \[Vertraulichkeit und Integrität im Weitverkehrsnetz\] Verschlüsselung von Weiterverkehrsverbindungen

## Control Statement

Architektur für Externe Netzanschlüsse SOLLTE Verbindungen ins Weitverkehrsnetz nach {{ insert: param, arch.6.2-prm1 }} verschlüsseln.

## Control guidance

Ohne ein etabliertes Verschlüsselungsverfahren könnte sensible Kommunikation im Klartext übertragen werden, was Angreifern ein einfaches Mitlesen ermöglichen könnte – etwa durch Abhören in einem öffentlichen WLAN, durch kompromittierte Router eines Providers oder durch staatliche Massenüberwachung. Auch die unbemerkte Manipulation von Datenpaketen auf dem Weg zwischen Institution und Gegenstelle könnte die Integrität der übermittelten Inhalte gefährden und beispielsweise zu manipulierten Geschäftsdaten oder Schadcode-Einschleusungen führen. Der Einsatz von anerkannten Standards zur Verschlüsselung kann Vertraulichkeit und Integrität wahren, indem die Inhalte für Unbefugte unlesbar bleiben und Kommunikationspartner einander zuverlässig identifizieren können. So kann beispielsweise sichergestellt werden, dass eine entfernte Niederlassung tatsächlich mit der Zentrale verbunden ist und nicht mit einem Angreifer, der den Datenverkehr umleitet. Im Kontext externer Netzanschlüsse bezeichnet „Weitverkehrsnetz“ typischerweise öffentliche Netze wie das Internet oder auch gemietete WAN-Verbindungen über Telekommunikationsanbieter, die institutionsextern betrieben und potenziell unsicher sind. Anerkannte Standards sind z.B. TLS, IPsec oder WireGuard, die regelmäßig überprüft und weit verbreitet eingesetzt werden. Eine Institution kann diese Anforderung durch konkrete Maßnahmen umsetzen, z. B. indem sie Site-to-Site-VPNs zwischen Standorten einrichtet, Remote-Zugriffe von Mitarbeitenden ausschließlich über VPN-Gateways mit Zwei-Faktor-Authentisierung ermöglicht und auch Cloud-Dienste konsequent über gesicherte Verbindungen anbindet.
