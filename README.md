# Charakterbogen PWA v7

Neu:
- IndexedDB ist jetzt der Hauptspeicher
- localStorage bleibt als automatische Backup-Kopie
- beim Start wird zuerst IndexedDB geladen, dann das Backup
- Speichern erfolgt bei Änderungen, beim Verlassen der Seite und wenn die App in den Hintergrund geht
- sichtbarer Speicherstatus, z. B. `Spielstand gespeichert · 11:24`
- `Verlauf` wurde in `Journal` umbenannt
- Level-Ups, XP-Buchungen und Mastery-Änderungen bleiben Journal-Einträge
- bestehender localStorage-Spielstand wird automatisch übernommen
- Cache-Version auf v7 erhöht

## Update auf GitHub
Ersetze:
- index.html
- manifest.webmanifest
- sw.js

Die PNG-Artworks bleiben unverändert im Repository.
