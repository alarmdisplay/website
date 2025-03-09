+++
fragment = "content"
date = "2025-03-09T22:00:00+01:00"
weight = 40

title = "Beta 5"
summary = "Ausnahmen für Probealarme, mehr Dateitypen bei der Textanalyse, Kalenderanzeige u.v.m."
title_align = "left"
+++

Dieses Beta-Release bringt neue Funktionen mit sich.

Die [Dokumentation](https://docs.alarmdisplay.org/) ist entsprechend auf dem neuen Stand, beachtet dort die neuen Upgrade Guides für erforderliche Anpassungen.

Bei Fragen könnt ihr euch gerne im [Forum](https://community.alarmdisplay.org/) melden.

### Zentrale

* Zeitbereiche für geplante Alarmierungen (z.B. Probealarm)
* Örtlichkeit einer Adresse wurde aufgeteilt in Ort und Ortsteil
* Neben PDF werden jetzt auch Bilddateien (TIFF, JPG, PNG, BMP) in überwachten Ordnern verarbeitet
* Schutz gegen erneute Verarbeitung bereits analysierter Dateien
* Objektname kann jetzt extrahiert werden
* Neue Textanalyse-Layouts für die ILS Biberach (Alarmdruck) und ILS Rosenheim (Fax)

Zudem wurden folgende Dinge in der Console geändert:

* Neue Seite für Einstellungen
* Paginierung für Einsätze und Einsatzmittel
* Mehr Hilfetexte

Das Docker-Image basiert jetzt auf Debian Bookworm statt Ubuntu 20.04.

**Für Breaking Changes bitte den neuen [Upgrade Guide](https://docs.alarmdisplay.org/de/Zentrale/Upgrade_Guide.html) beachten.**

### Anzeige

* Neue Komponente: Kalender
* Neue Komponente: Bild von einer URL
* Örtlichkeit einer Adresse wurde aufgeteilt in Ort und Ortsteil

Sichtbare Änderungen an den Displays:
* Wenn der Ortsteil einer Adresse gesetzt ist, wird dieser statt dem Ort angezeigt
* Banner für einen Alarm ohne Detailangaben hat eine andere Farbe bei Probealarm
* Bei einer leeren Bemerkung wird explizit "Keine Bemerkung" ausgegeben
* Objektname wird nun über der Adresse angezeigt
* Adressdetail wird auch ohne Straßenangabe angezeigt

Zudem wurden folgende Dinge in der Console geändert:

* Bekanntmachungen können optional mit einem Start- und Enddatum versehen werden

**Für Breaking Changes bitte den neuen [Upgrade Guide](https://docs.alarmdisplay.org/de/Anzeige/Upgrade_Guide.html) beachten.**
