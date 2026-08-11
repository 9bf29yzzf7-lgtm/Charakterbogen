# Charakterbogen – Life RPG

Diese Dateien bilden eine kleine installierbare PWA.

## GitHub Pages einrichten

1. Lade alle Dateien in die oberste Ebene deines Repositorys hoch.
2. Öffne in GitHub: Settings → Pages.
3. Unter "Build and deployment" wähle "Deploy from a branch".
4. Branch: `main`, Ordner: `/(root)`, dann speichern.
5. Öffne die veröffentlichte GitHub-Pages-Adresse in Safari.
6. Auf dem iPhone: Teilen → Zum Home-Bildschirm.

Die Charakterdaten werden im Browser per localStorage gespeichert und nicht ins Repository geschrieben.

## Dateien

- `index.html` – die App
- `manifest.webmanifest` – PWA-Metadaten
- `sw.js` – Offline-Cache
- `icon-192.png`, `icon-512.png` – App-Icons

Hinweis: Vor größeren Änderungen am Gerät am besten den Spielstand in der App exportieren.
