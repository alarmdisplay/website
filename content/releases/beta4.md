+++
fragment = "content"
date = "2022-02-16T23:02:00+02:00"
weight = 40

title = "Beta 4"
summary = "Einsatzkarte, Einstellungen und Zuweisung von Einsatzmitteln"
title_align = "left"
+++

Dieses Beta-Release bringt wieder einige Neuerungen mit und merzt ein paar Fehler aus.

Die [Dokumentation](https://docs.alarmdisplay.org/) ist entsprechend auf dem neuen Stand.
Bei Fragen könnt ihr euch gerne im [Forum](https://community.alarmdisplay.org/) melden.

### Zentrale

* Fehler behoben, bei dem ein zweites Alarmfax für denselben Einsatz die Adresse löschen konnte
* Bekannte OCR-Fehler müssen nicht mehr in der Layout-Config umgangen werden
* In PDF-Dateien eingebettete Texte können direkt ausgelesen werden
* Einsatzmittel zur API der Einsätze hinzugefügt
* Neue API für Einstellungen
* Beim Start wird die Verbindung zur Datenbank nun mehrfach versucht
* Das Log-Level kann beim Betrieb mit Docker per Umgebungsvariable gesetzt werden

Zudem wurden folgende Dinge in der Console geändert:

* Einem Einsatz zugewiesene Einsatzmittel können bearbeitet werden

### Anzeige

* Angabe des Display-Typs: Monitor oder Tablet
* Fehler behoben, bei dem Optionen für neu zum Ruhemodus hinzugefügte Komponenten nicht gespeichert wurden
* Neue API für Einstellungen
* Anzeigedauer von Einsätzen einstellbar
* Beim Start wird die Verbindung zur Datenbank nun mehrfach versucht
* Das Log-Level kann beim Betrieb mit Docker per Umgebungsvariable gesetzt werden

Sichtbare Änderungen an den Displays:
* Ein Alarm ohne Details (z. B. nur 5-Ton-Folge) zeigt weiter den Ruhemodus mit einem konfigurierbaren Hinweis, bis die restlichen Daten eintreffen
* Für Einsätze mit Koordinaten wird eine Karte des Zielorts angezeigt, bei Tablets hingegen ein Knopf zur Übernahme in eine Navigations- oder Karten-App (geo:-Schema)
* Der Einsatzgrund kann verkürzt dargestellt werden (z. B. bei den langen Schlagworten einer bay. ILS)

Zudem wurden folgende Dinge in der Console geändert:

* Auch die letzte/einzige Ansicht eines Displays kann wieder gelöscht werden
* Neue Seite für Einstellungen
