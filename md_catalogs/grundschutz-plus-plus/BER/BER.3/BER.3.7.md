# BER.3.7 - \[Zugangskonten\] Single-Sign-On

## Control Statement

Berechtigung für Anwendungen SOLLTE die Anmeldung über einen zentralen Identitätsprovider aktivieren.

## Control guidance

Bei Single Sign-on authentifizieren sich Nutzende bei einem zentralen Identity Provider, der auch die Berechtigungen zur Nutzung der Anwendung prüft. Bei erfolgreicher Authentifizierung und passenden Berechtigungen wird für die Sitzung ein Token ausgestellt, das den Zugang zur Anwendung ermöglicht. Da Nutzende durch Single-Sign-On weniger Anmeldeinformationen benötigen, wird es leichter, sich komplexe Passwörter zu merken oder zentrale gepflegte Schutzmaßnahmen, wie eine Mehr-Faktor-Authentifizierung oder Überwachung von Anmeldeinformationen, auch auf die Anwendung anzuwenden. Zudem erschwert Single-Sign-On auch Phishing-Angriffe, da Anmeldeinformationen nur noch an zentraler Stelle und nicht mehr verstreut in einzelne Anwendungen oder Webseiten abgefragt werden. Andererseits ist bei der Kompromittierung des Single-Sign-On-Logins auch die Authentifizierung an der Anwendung kompromittiert und die Verfügbarkeit der Anwendung hängt auch von der Verfügbarkeit des zentralen Logins ab. Dies kann unter Windows durch Nutzung eines Windows Server Domain Controllers und unter Linux durch Samba mit aktiviertem Heimdal Kerberos Key Distribution Center (KDC) umgesetzt werden.
