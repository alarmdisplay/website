+++
fragment = "content"
weight = 20
title = ""
+++

Um sicherzustellen, dass alles reibungslos funktioniert, muss viel getestet werden.
Dafür suchen wir immer Freiwillige, die bei sich ein Testsystem aufbauen wollen.
In der aktuellen Phase wird es sowohl optisch als auch funktionell noch ein paar ungeschliffene Ecken geben, ein gewisser Wille zum Basteln (im technischen Sinne) könnte erforderlich sein.

**Die erste gemeinsame Beta-Version von Alarmzentrale und Alarmanzeige erscheint am Mittwoch, 26. August 2020.**

Die _Alarmzentrale beta 1_ wird folgende Features haben:

* Überwachung von Ordnern auf neue (Alarmfax-) PDF-Dateien
* Auslesen dieser PDF-Dateien *
* Optionale Validierung von Adressen mittels OpenStreetMap
* API-Endpunkt zum Zuliefern von ausgelösten Selektivrufen
* Kombination von Alarmeingängen zu Einsätzen
* Weiterleitung der Einsätze an die Alarmanzeige

*: Derzeit wird nur das Alarmfax der ILS Augsburg unterstützt, weitere benötigte Formate [bitte melden](https://community.alarmdisplay.org/c/funktionalitaet/alarmzentrale/9)

Die _Alarmanzeige beta 2_ wird folgende Features haben:

* Schneller Onboarding-Prozess von neuen Displays
* Drag-and-drop-Konfiguration von Anzeige-Layouts
* Ruhemodus mit Uhrzeit/Datum, Ankündigungen und DWD-Unwetterkarten
* Alarmanzeige mit Einsatzgrund, Stichwort, Zeit seit dem Alarmeingang, Zieladresse und Freitext der Leitstelle

Beide Komponenten verfügen außerdem über:

* Web-App zur Verwaltung aller Einstellungen im Browser
* Nutzeraccounts (derzeit alle mit der gleichen Berechtigung)
* REST-API und WebSocket-Verbindung für eigene Software
* Authentifizierung mit JWT und statischen API-Keys
