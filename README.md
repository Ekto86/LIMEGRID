# LIMEGRID 0.11

Familien-Stundenplan als statische Web-App / PWA.

## Bereitstellung über GitHub Pages
1. Repository öffentlich schalten (GitHub Free unterstützt Pages für öffentliche Repositories).
2. Repository → Settings → Pages → Build and deployment → Deploy from a branch.
3. Branch `main`, Verzeichnis `/(root)` auswählen und speichern.
4. Nach Veröffentlichung: https://ekto86.github.io/LIMEGRID/

## Datenschutz und Daten
Personen-, Schul- und Stundenplandaten werden lokal im Browser gespeichert, nicht im GitHub-Repository. Browserdaten können beim Löschen des Website-Speichers oder durch private Sitzungen verloren gehen. Exportiere regelmäßig ein JSON-Backup über die App-Einstellungen.

## Stand
- Hauptdatei: index.html
- Manifest: manifest.webmanifest
- Service Worker: sw.js
- App-Symbol: icon.svg
- Die dauerhafte Speicherung und Installation auf einem echten Android-Gerät sind noch nicht abgenommen.
