# Charakterbogen PWA v10 – Journal-Fix

Fehlerursache:
`history` ist im Browser bereits `window.history`.
Dadurch wurde beim Rendern des Journals nicht das HTML-Element angesprochen.

Fix:
- Journal-DOM-ID ist jetzt `journalEntries`
- `renderHistory()` nutzt explizit `document.getElementById("journalEntries")`
- Cache auf v10 erhöht
- bestehende Daten bleiben erhalten

Auf GitHub ersetzen:
- index.html
- manifest.webmanifest
- sw.js
