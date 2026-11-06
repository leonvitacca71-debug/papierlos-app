# PAPIERLOS v0.2.4 – Speicherreparatur

- IndexedDB-Schreibvorgang gilt erst nach `transaction.oncomplete` als erfolgreich.
- Nach jedem Foto/PDF-Upload wird die gespeicherte Datei erneut gelesen und die Größe überprüft.
- Bestehende Daten und Datenbanknamen bleiben erhalten.
- Service-Worker-Cache-Version erhöht.

## Update
In GitHub `index.html` und `sw.js` im Repository-Hauptverzeichnis ersetzen, committen, GitHub Pages abwarten. Nicht die App oder Website-Daten löschen.

## Test auf dem iPhone
Nur über dasselbe Symbol bzw. denselben Browser testen. Testfoto hochladen, sofort öffnen, App vollständig schließen und erneut öffnen, Foto nochmals öffnen. Safari und Home-Bildschirm-Web-App können getrennte Speicherbereiche haben.

## Sicherheit
Keine vertraulichen Dokumente hochladen. Nur lokaler Prototyp, kein Backup und keine garantierte dauerhafte Aufbewahrung.


## v0.2.5
Dokumente können über „Bearbeiten“ geändert werden (Name, Absender, Kategorie, Datum). Anhänge bleiben in IndexedDB unverändert; bestehende Daten werden nicht migriert oder gelöscht.


## v0.2.7
Mobile Vorschau: getrennte Titel-, Metadaten-, Aktions- und Dateibereiche; PDF-Dateiname und Öffnen-Schaltfläche überlappen nicht mehr. Keine Änderung an gespeicherten Daten oder IndexedDB.
