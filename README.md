# Charakterbogen PWA v8 – Speicherfix

Gefundener Fehler in v7:
`loadState()` war implementiert, wurde beim Start aber nicht aufgerufen.
Dadurch begann jeder App-Start wieder mit dem Default-Spielstand.

v8:
- lädt IndexedDB vor dem ersten Rendern
- fällt bei Bedarf auf localStorage-Backup zurück
- synchronisiert beide Speicher nach erfolgreichem Start
- speichert beim Hintergrundwechsel/Schließen
- korrigiert Import und Reset
- enthält einen kleinen Speichertest
- aktualisiert den Service Worker aktiv
- Cache-Version v8

Auf GitHub ersetzen:
- index.html
- manifest.webmanifest
- sw.js

PNG-Artworks bleiben unverändert.
