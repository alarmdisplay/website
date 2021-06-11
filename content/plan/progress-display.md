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
- Layoutsystem zur Platzierung von Komponenten
- Alarmansicht
  - Titel, Stichwort, Ortsangabe, Freitext der Leitstelle, verstrichene Zeit
  - Automatische R&uuml;ckkehr in den Ruhemodus nach vorgegebener Zeit
- Unterstützung von Geräten zur Anzeige, die nicht dauerhaft verbunden sein können (z. B. Tablets)
- Verwaltungsoberfl&auml;che zur Konfiguration der Displays und Verwaltung der Inhalte
- Benutzeraccounts und API-Keys
- REST-API inkl. Authentifizierung

### Demnächst
- Termine im Ruhemodus
- Karte vom Zielort in der Alarmansicht
- E-Mail-Versand f&uuml;r Nutzerverwaltung und bei Problemen

### F&uuml;r die Zukunft
- Ruhemodus
  - Wetterdaten des DWD (via [Bright Sky](https://brightsky.dev/))
  - Unwetterwarnungen auf Gemeindeebene in Textform
  - Hochwasserpegel
  - Fahrzeugstatus
- Alarmansicht
  - Anzeige von Hydranten bei Brandeins&auml;tzen
  - Alarmierte Fahrzeuge/Einheiten
  - Anzeige von mehreren Einsätzen
