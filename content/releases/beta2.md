+++
fragment = "content"
date = "2020-08-26T16:12:00+02:00"
weight = 10

title = "Beta 2"
summary = "Die erste gemeinsame Beta-Version von Alarmzentrale und Alarmanzeige"
title_align = "left"
+++

### Neuerungen in der Alarmzentrale

* Überwachung von Ordnern auf neue (Alarmfax-) PDF-Dateien
* Auslesen dieser PDF-Dateien *
* Optionale Validierung von Adressen mittels OpenStreetMap
* API-Endpunkt zum Zuliefern von ausgelösten Selektivrufen
* Kombination von Alarmeingängen zu Einsätzen
* Weiterleitung der Einsätze an die Alarmanzeige

*: Derzeit wird nur das Alarmfax der ILS Augsburg unterstützt, weitere benötigte Formate [bitte melden](https://community.alarmdisplay.org/c/funktionalitaet/alarmzentrale/9)

### Neuerungen in der Alarmanzeige

* Schneller Onboarding-Prozess von neuen Displays
* Drag-and-drop-Konfiguration von Anzeige-Layouts
* Ruhemodus mit Uhrzeit/Datum, Ankündigungen und DWD-Unwetterkarten
* Alarmanzeige mit Einsatzgrund, Stichwort, Zeit seit dem Alarmeingang, Zieladresse und Freitext der Leitstelle

### Neu in beiden Komponenten

* Web-App zur Verwaltung aller Einstellungen im Browser
* Nutzeraccounts (derzeit alle mit der gleichen Berechtigung)
* REST-API und WebSocket-Verbindung für eigene Software
* Authentifizierung mit JWT und statischen API-Keys

## Downloads
* [Alarmzentrale 1.0.0-beta.1](https://github.com/alarmdisplay/hub/releases/download/1.0.0-beta.1/hub-1.0.0-beta.1.tar.gz)
* [Alarmanzeige 1.0.0-beta.2](https://github.com/alarmdisplay/display/releases/download/v1.0.0-beta.2/display-1.0.0-beta.2.tar.gz)
