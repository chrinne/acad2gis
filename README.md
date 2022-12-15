# Handreichung für die Migration von CAD-Projekten zu SpatiaLite

Handreichung mit Erfahrungen zum Transfer von CAD-Projekten in AutoCAD zu GIS Projekten. Ausgangspunkt sind Dateien von archäologischen Ausgrabungen (2D, 3D), das Ziel ist SpatiaLite. 

Work in progess.

Kiel Universioty GitLab repo push mirrored to the public github repo.

## Einleitung

CAD-Software dient der 3D-Konstruktion, es ist meist eine hoch komplexe, professionelle und kostspielige Software. Der Einsatz in der Archäologie geht wesentlich auf den Einsatz von Tachymetern auf archäologischen Ausgrabungen seit den 1980er Jahren zurück. Damit liegen in vielen Denkmalämtern seit 40 Jahren akkumuliert Plandokumentationen in diesem digitalen Format vor. Der Mehrwert digitaler Format gegenüber den ggf. vorhandenen Papierplänen ist unstrittig. 

Es muss demnach auf archäologischer Seite Kompetenz und *know how* im Umgang mit CAD-Daten und der Migration in alternative Format vorgehalten werden. Diese Handreichung ist ein Aufschlag, er kann und muss erweitert werden.

Ausgangspunkte sind zwei unterschiedliche Projekte:

 1. Eine 1997 digitalisierte Papierdokumentation zur Ausgrabung des **Kollektivgraben Odagsen** (1980-1984). Entsprechend der Vorlage liegen sehr viele 2D Dateien mit ergänzenden Informationen vor.
 
 2. Eine 1988 und 1990 durchgeführte und auf Papier dokumentierte Flächengrabung einer Siedlung, die 2021 in eine einzige Datei mit AutoCAD anhand der eingebundenen Zeichnungen (xref) digitalisiert wurde. Hierbei wurden Layernamen und Blöcke mit Attribut sehr konsequent genutzt. 

 3. Eine tachymetrisch direkt digital in AutoCAD dokumentierte Flächenausgrabung. Die Daten liegen als 3D- und 2D-Objekte mit einigen typischen Fehlern vor. Der Fokus liegt auf der Behebung dieser Fehler im Zuge der Aufbereitung für das GIS.
 
Ziel ist in jedem Fall eine SpatiaLite Datenbank. Diese bietet die Möglichkeiten einer Datenbank ohne den Einsatz eines Servers und dem damit notwendigen Aufwand bei Service, Update und Sicherheit. 

## License
CC-BY-SA 4.0
