+++
fragment = "content"
weight = 60
title = "Projektfortschritt: Zentrale"
+++

### Umgesetzt
- Alarmeingang
  - &Uuml;berwachen eines Ordners auf neue PDF-Dateien (z. B. Alarmfax)
  - Ausdruck der gefundenen Datei
  - &Uuml;berwachen einer seriellen Schnittstelle auf Alarmtexte (z. B. von einem DME)
  - Zulieferung durch eigene Software per REST-API (5-Tonfolgen oder ganze Eins&auml;tze)
- Verarbeitung
  - Extraktion von Informationen aus PDFs durch Texterkennung (OCR)
  - Validieren von Adressen (experimentell)
  - Kombination verschiedener Alarmeing&auml;nge zu einem Einsatz
- Ausgabe
  - Weiterleitung an die Anzeige
- Verwaltungsoberfl&auml;che zur Konfiguration
- Benutzeraccounts und API-Keys
- REST-API inkl. Authentifizierung

### Demn&auml;chst
- E-Mail als Alarmeingang
- E-Mail-Versand f&uuml;r Nutzerverwaltung und bei Problemen
- Zeiten f&uuml;r Probealarme

### F&uuml;r die Zukunft
- Ausdruck von Einsatzdaten und Karten
- Spezielle API-Endpunkte für gängige Softwareprodukte zur Alarmauswertung
- Plausibilitätsprüfung von Koordinaten
- Weiterleitung von Einsatzdaten an REST-Endpunkte
