# OSM Quick Install - Raspberry Pi
```
Dieses Tool ist aktuell in Entwicklung
```
OSM Pi soll im Schnellverfahren eine GIS-Testumgebung auf Basis der OpenStreetMap Datenbank erstellen.

### OSM Pi nutzt diese Module
+ PostgreSql 9.4
+ PostGis
+ osm2pgsql
+ osmctools

#### GIS und Verwaltungsprogramme (optional)
+ QGis (Desktop)
+ pgAdmin3 (Desktop)

### OSM Pi Installation

```Shell
git clone https://github.com/MS-WebDev/osm-pi
chmod +x ./osm-pi/install.sh
./osm-pi/install.sh
```

### ToDo Liste
+ OSM Pi Installer
  * Installation von Abhängigkeiten des OSM Pi Manager
  * und optionaler Programme
+ OSM Pi Manager - rc1
  * soll OSM-Extrakte (via osm2pgsql) importieren können
  * (G)UI 
  * Aufbau einer Multi-Projektstrukur in enger Verbindung zur GIS-Datenbank
  * individuelle Konfiguration ermöglichen

### How do - OSM Pi
+ [Raspberry Pi für OSM optimieren](https://github.com/MS-WebDev/osm-pi/wiki/Raspberry-Pi-f%C3%BCr-OSM-optimieren)
