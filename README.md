# Charakterbogen PWA v4

Diese Version verwendet PNG-Artworks statt SVGs.

Lege diese Dateien direkt neben `index.html` ab:

- `dragon.png`
- `str.png`
- `dex.png`
- `con.png`
- `int.png`
- `wis.png`
- `cha.png`

Die Bilddateien sind absichtlich **nicht** in dieser ZIP enthalten.

Neu gegenüber v3:
- alle Artwork-Referenzen auf `.png` umgestellt
- PNGs werden sauber per `object-fit: contain` skaliert
- Offline-Cache lädt nur die Kern-App vorab
- Artworks werden beim ersten Abruf automatisch gecacht

Hinweis: Das CON-Artwork muss noch als `con.png` vorhanden sein, bevor es angezeigt werden kann.
