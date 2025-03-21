+++
fragment = "content"
weight = 55
title = "Projektfortschritt: Anzeige"
+++

### Umgesetzt
- Ruhemodus mit verschiedenen Komponenten
  - Datum / Uhrzeit
  - Unwetterkarten des DWD
  - Ank&uuml;ndigungen
  - Alarmhinweis, solange auf Daten gewartet wird
  - Bild aus URL
  - Termine aus ics-Feed
- Layoutsystem zur Platzierung von Komponenten
- Alarmansicht
  - Titel, Stichwort, Ortsangabe, Freitext der Leitstelle, verstrichene Zeit
  - Karte vom Zielort oder Knopf zur Übernahme der Koordinaten in Navigations-App
  - Automatische R&uuml;ckkehr in den Ruhemodus nach einstellbarer Zeit
- Unterstützung von Geräten zur Anzeige, die nicht dauerhaft verbunden sein können (z. B. Tablets)
- Verwaltungsoberfl&auml;che zur Konfiguration der Displays und Verwaltung der Inhalte
- Benutzeraccounts und API-Keys
- REST-API inkl. Authentifizierung

### Demnächst
- Wetterdaten des DWD (via [Bright Sky](https://brightsky.dev/))
- E-Mail-Versand f&uuml;r Nutzerverwaltung und bei Problemen

### F&uuml;r die Zukunft
- Ruhemodus
  - Unwetterwarnungen auf Gemeindeebene in Textform
  - Hochwasserpegel
  - Fahrzeugstatus
- Alarmansicht
  - Anzeige von Hydranten bei Brandeins&auml;tzen
  - Alarmierte Fahrzeuge/Einheiten
  - Anzeige von mehreren Einsätzen
