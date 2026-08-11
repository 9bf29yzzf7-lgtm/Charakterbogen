# Charakterbogen PWA v5

Diese ZIP enthält nur den App-Code, keine Artworks.

## Erwartete PNG-Dateien im selben Verzeichnis wie index.html

- dragon.png
- str.png
- dex.png
- con.png
- int.png
- wis.png
- cha.png

Achte exakt auf Kleinschreibung.

## Was v5 behebt

- alle Bildreferenzen verwenden PNG
- `?v=5` erzwingt neue Bildabrufe statt alter Safari-/PWA-Caches
- neuer Service-Worker-Cache `charakterbogen-v5`
- Navigation und App-Code werden online bevorzugt aktualisiert
- Bilder werden beim ersten Laden lokal gecacht
- fehlende Bilder zeigen kein blaues Safari-Fragezeichen mehr
- detaillierte Tusche-PNGs werden sauber mit `object-fit: contain` skaliert
- vorhandene Charakterdaten bleiben im bisherigen `lifeRpgSheetV2`-Speicher erhalten

## Update auf GitHub

Ersetze nur:
- index.html
- manifest.webmanifest
- sw.js

Die sieben PNG-Artworks bleiben separat im Repository.
