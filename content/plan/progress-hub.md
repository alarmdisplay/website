+++
fragment = "content"
weight = 60
title = "Projektfortschritt: Alarmzentrale"
+++

### Umgesetzt
- Alarmeingang
  - &Uuml;berwachen eines Ordners auf neue Dateien (z. B. PDF nach Faxempfang)
  - Zulieferung durch andere Software per REST-API
- Verarbeitung
  - Extraktion von Informationen aus PDFs durch Texterkennung (OCR)
  - Validieren von Adressen
  - Kombination verschiedener Alarmeing&auml;nge zu einem Einsatz
- Ausgabe
  - Weiterleitung an die Alarmanzeige
- Benutzeraccounts und API-Keys
- REST-API inkl. Authentifizierung

### Geplant
- Verarbeitung
  - Validieren von Koordinaten
- Ausgabe
  - Aufruf einer REST-API
  - Ausdruck von Einsatzdaten und Karten

### F&uuml;r die Zukunft
- E-Mail als Alarmeingang
- E-Mail-Versand bei Alarm oder Problemen
- Anbindung von Messengern / Push-Diensten
- Spezielle API-Endpunkte für gängige Softwareprodukte zur Alarmauswertung
