# KONF.1.5 - \[Grundlagen\] Verschlüsselung von Konfigurationsgeheimnissen

## Control Statement

Konfiguration SOLLTE Konfigurationsgeheimnisse verschlüsseln.

## Control guidance

Konfigurationsgeheimnissen sind sensitive, nicht-öffentliche Daten, die von Systemen, Applikationen oder Diensten zur Laufzeit benötigt werden, um auf andere Ressourcen zuzugreifen oder ihre eigene Funktionalität sicherzustellen. Bekannte Beispiele sind Anmeldeinformationen wie Passwörter, Datenbank-Verbindungszeichenfolgen (Connection Strings), API-Schlüssel oder private Schlüssel von Zertifikaten; im Englischen wird hierfür übergreifend der Fachbegriff Secrets verwendet. Der Zweck dieser Vorschrift ist die Sicherstellung der Vertraulichkeit dieser hochsensiblen Informationen. Ungeschützt im Klartext hinterlegt, könnte ein Angreifer bei einem unautorisierten Zugriff auf Konfigurationsdateien, Quellcode-Verzeichnisse oder Backups diese Geheimnisse direkt auslesen und damit weitreichenden Zugriff auf angebundene Systeme oder Daten erlangen.
