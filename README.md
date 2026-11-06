# PAPIERLOS Web-App v0.2

## Neu
- Fotoaufnahme über iPhone-Dateiauswahl/Kamera (je nach iOS-Menü)
- PDF-Import aus Dateien
- Foto-Vorschau und PDF öffnen
- Dateien lokal in IndexedDB (bis 15 MB je Datei)
- Bestehende v0.1-Einträge bleiben erhalten (`papierlos_v01` localStorage)
- Service Worker mit neuem Cache `papierlos-v02`

## Installation / Update über GitHub Pages
Im bestehenden Repository `papierlos-app` die Dateien `index.html`, `sw.js`, `manifest.webmanifest`, `icon.png` hochladen und gleichnamige Dateien überschreiben. README kann ebenfalls ersetzt werden. Direkt in `main` committen. Danach die App schließen und neu öffnen; bei alter Ansicht Safari-Seite neu laden.

## Test
1. Bestehende v0.1-Einträge prüfen.
2. Plus → Dokument → Foto aufnehmen oder PDF auswählen → Speichern.
3. Dokumente → Öffnen → Vorschau prüfen.
4. App komplett schließen, neu öffnen und Datei erneut prüfen.
5. Eintrag löschen und prüfen, dass er verschwindet.

## Grenzen
Dies ist eine lokale Test-PWA, **kein** sicherer Dokumententresor. iOS kann Website-Daten unter bestimmten Umständen löschen. Kein Cloud-Backup, keine Verschlüsselung auf App-Ebene, kein OCR/AI, keine Push-Erinnerungen. Keine echten sensiblen Unterlagen verwenden. Funktionalität muss auf echtem iPhone noch getestet werden.
