+++
fragment = "content"
weight = 55
title = "Projektfortschritt: Alarmanzeige"
+++

### Umgesetzt
- Ruhemodus mit verschiedenen Komponenten
  - Datum / Uhrzeit
  - Unwetterkarten des DWD
  - Ank&uuml;ndigungen
- Layoutsystem zur Platzierung von Komponenten
- Alarmansicht
  - Titel, Stichwort, Ortsangabe, Freitext der Leitstelle, verstrichene Zeit
  - Automatische R&uuml;ckkehr in den Ruhemodus nach vorgegebener Zeit
- Verwaltungsoberfl&auml;che zur Konfiguration der Displays und Verwaltung der Inhalte
- REST-API

### Geplant
- Ruhemodus
  - Termine
- Alarmansicht
  - Karte vom Zielort
  - Anzeige von Hydranten bei Brandeins&auml;tzen
  - Alarmierte Fahrzeuge/Einheiten
- Authentifizierung f&uuml;r REST-API

### F&uuml;r die Zukunft
- Ruhemodus
  - Wetterdaten des DWD (via [Bright Sky](https://brightsky.dev/))
  - Unwetterwarnungen auf Gemeindeebene in Textform
  - Hochwasserpegel
  - Fahrzeugstatus