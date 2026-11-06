# PAPIERLOS – Web-App Version 0.1

## Was funktioniert
- Startseite mit Aufgaben, Zahlungen und Fristen
- Dokumentenliste mit Kategorien und Suche
- Kalenderansicht mit Monatsnavigation und Fälligkeiten
- Neue Dokument-Metadaten, Zahlungen und Fristen anlegen
- Aufgaben erledigen / zurücksetzen, Dokumenteinträge löschen
- Speicherung lokal im Browser (localStorage), ohne Konto
- PWA-Manifest, Offline-Cache und iPhone-Home-Screen-Icon

## Einschränkungen
- Keine echten PDF- oder Foto-Uploads; Dokumente sind derzeit nur Datensätze.
- Keine OCR, KI, Push-Benachrichtigungen oder Cloud-Synchronisation.
- Kein App-Store-Build; keine native SwiftUI-Ausführung.
- Demo-Daten sind als Beispiele gekennzeichnet.
- Browserdaten können verloren gehen. Keine sensiblen Unterlagen verwenden.
- Noch nicht auf einem realen iPhone getestet.

## Kostenlos auf dem iPhone bereitstellen
1. ZIP entpacken.
2. Alle Dateien aus dem Ordner `PAPIERLOS-WebApp` in ein neues öffentliches GitHub-Repository hochladen (keine echten persönlichen Dokumente).
3. In GitHub unter Settings > Pages die Veröffentlichung aus dem Branch `main`, Ordner `/ (root)` aktivieren.
4. Die HTTPS-URL auf dem iPhone in Safari öffnen.
5. Teilen > Zum Home-Bildschirm > Hinzufügen.

Alternative: Dateien über einen statischen HTTPS-Host wie Netlify Drop bereitstellen. HTTPS ist für die PWA erforderlich.

## Prüfschritte
1. App starten und Start/Dokumente/Kalender wechseln.
2. Über + ein Dokument hinzufügen und in Dokumente suchen.
3. Über + eine Zahlung mit Fälligkeit hinzufügen.
4. Zahlung als erledigt markieren.
5. Safari bzw. die App schließen, neu öffnen, Einträge prüfen.
6. Flugmodus aktivieren und App erneut starten, um Offline-Cache zu prüfen.

Hinweis: Für echte App-Store-Veröffentlichung ist später ein separater nativer Build nötig.
