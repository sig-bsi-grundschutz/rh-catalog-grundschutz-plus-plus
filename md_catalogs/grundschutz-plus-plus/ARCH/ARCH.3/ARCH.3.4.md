---
x-trestle-set-params:
  arch.3.4-prm1:
    values:
---

# ARCH.3.4 - \[Wireless LAN\] Verschlüsselte Netzanbindung

## Control Statement

Architektur für WLANs SOLLTE die Netzanbindung {{ insert: param, arch.3.4-prm1 }} verschlüsseln.

## Control guidance

Ohne eine sichere Verschlüsselung könnte ein Angreifer durch „Sniffing“ sensible Inhalte wie Passwörter, E-Mails oder Geschäftsdaten abfangen oder sogar schadhaften Datenverkehr in die Kommunikation einschleusen. Ebenso könnte ein schwacher oder veralteter Standard wie WEP einem Angreifer ermöglichen, das WLAN-Passwort innerhalb weniger Minuten zu knacken und damit vollständigen Netzzugang zu erlangen. Eine zeitgemäße und wirksame Verschlüsselung kann dagegen die Vertraulichkeit und Integrität der Kommunikation sicherstellen und bietet Schutz vor Angriffen wie „Man-in-the-Middle“-Manipulationen oder unerwünschtem Zugriff über „Rogue Clients“. Netzanbindung bedeutet hier, dass nicht nur die über das Netz transportierten Daten verschlüsselt werden, sondern auch die Kommunikation selbst, z.B. die Adressen kommunizierender Geräte. Anerkannten Standards meint z.B. WPA3-Enterprise mit 802.1X und EAP-TLS. Für Details siehe IEEE 80211, WPA3.
