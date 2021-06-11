+++
fragment = "content"
date = "2021-06-11T15:30:00+02:00"
weight = 20

title = "Beta 3"
summary = "Neue Alarmquellen und bessere Bedienbarkeit"
title_align = "left"
+++

Nach dem Ende der Förderphase war erst einmal eine Pause und etwas Abstand zum Projekt fällig.
Seit Jahresbeginn kamen ständig neue Funktionen hinzu und bestehende Abläufe wurden verbessert.

Nun war es mal wieder an der Zeit das Ganze in ein Release zu packen.
Die [Dokumentation](https://docs.alarmdisplay.org/) ist entsprechend auf dem neuen Stand.

Wenn ihr bereits eine frühere Version installiert habt, werft besonders einen Blick in den neuen Abschnitt _Konfiguration_ der jeweiligen Komponente.
Eure eigenen Einstellungen müssen jetzt in einer anderen Datei als bisher abgelegt werden, damit in Zukunft die Updates leichter fallen.

Die Komponenten werden nun einheitlich als _Zentrale_ und _Anzeige_ bezeichnet.

Künftige Beta-Versionen sollen wieder in kürzeren Abständen erscheinen.
Für eine einheitliche Nummerierung wurde bei der Zentrale die Beta 2 übersprungen.
Bei Fragen aller Art meldet euch bitte im [Forum](https://community.alarmdisplay.org/).

### Zentrale

* Serielle Schnittstellen können auf Alarmtexte überwacht werden (z. B. von einem DME)
* Neue Textanalyse-Layouts für die ILS Bamberg (Fax) und die ILS Bodensee-Oberschwaben (DME)
* Ein neues Alarmfax kann direkt gedruckt werden
* Allgemeine Verbesserungen bei der Texterkennung
* Die Textanalyse kann jetzt auch WGS84-Koordinaten extrahieren
* Der uploads-Service wurde entfernt
* Alle relevanten Endpunkte unterstützen API-Keys zur Authentifizierung
* Die Datenbank wird zuverlässig verbunden und aktualisiert
* Der Freitext ist nicht mehr in der Länge begrenzt
* Die APIs für Einsätze und Einsatzmittel arbeiten mit verschachtelten Objekten
* Die Pager-API gibt die resultierende Einsatz-ID zurück
* Das Log-Level kann in der Konfiguration festgelegt werden

Zudem wurden folgende Dinge in der Console geändert:

* Allgemeine optische Verbesserungen
* Mehr Feedback auf der Login-Seite
* Neue Oberfläche für Alarmquellen und Weiterverarbeitung
* Übersicht und Editor für Einsätze
* Editor für Einsatzmittel (Selektivrufe / Bezeichner)
* Passwörter von Benutzern können geändert werden
* Automatische Abmeldung bei Ablauf der Sitzung, es erfolgt eine Warnung 15 Minuten zuvor

### Anzeige

* Die API für Einsätze arbeitet mit verschachtelten Objekten
* Alle relevanten Endpunkte unterstützen API-Keys zur Authentifizierung
* Fehler bei der Synchronisation von Einsätzen von der Zentrale behoben
* Die Datenbank wird zuverlässig verbunden und aktualisiert
* Der Freitext ist nicht mehr in der Länge begrenzt
* Das Log-Level kann in der Konfiguration festgelegt werden

Sichtbare Änderungen an den Displays:
* Bei Übungseinsätzen wird das Wort _Übung_ vor den Einsatzgrund gestellt
* Zeilenumbrüche werden nun beim Einsatzort und dem Freitext berücksichtigt
* Der Einsatzort wird zuerst aus den einzelnen Angaben (Straße, Hausnummer) zusammengebaut, _rawText_ ist nur noch die Rückfallebene
* Wenn ein Display die Verbindung zum Server verliert, lädt es nach Wiederherstellung der Verbindung alle zwischenzeitlichen Änderungen nach. Dies ist besonders nützlich, wenn ein Tablet zur Anzeige verwendet wird, das nicht dauerhaft verbunden sein kann.

Zudem wurden folgende Dinge in der Console geändert:

* Allgemeine optische Verbesserungen
* Mehr Feedback auf der Login-Seite
* Passwörter von Benutzern können geändert werden
* Automatische Abmeldung bei Ablauf der Sitzung, es erfolgt eine Warnung 15 Minuten zuvor
* Die Gültigkeit von Ankündigungen wird in der Übersicht angezeigt
