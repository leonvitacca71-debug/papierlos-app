# PAPIERLOS v0.3 – Testversion

## Installation
Nur `index.html` und `sw.js` im Root des bestehenden GitHub-Pages-Repositories ersetzen. `manifest.webmanifest` und `icon.png` beibehalten. Die Home-Screen-App nicht löschen.

## Neu
- Monatskalender mit Markierungen für offene Termine
- Termine bearbeiten/löschen
- Wiederkehrende Zahlungen (monatlich/jährlich; nächste Fälligkeit entsteht beim Erledigen)
- Termine mit bestehenden Dokumenten verknüpfen
- Smart-Erkennung aus eingefügtem Text, optional textbasierten PDFs über pdf.js-CDN

## Grenzen
Die Smart-Erkennung ist regelbasiert und keine generative KI. Sie kann falsche Beträge/Termine erkennen; Vorschläge müssen geprüft werden. Foto-OCR nur falls die Browser-API `TextDetector` verfügbar ist; sonst Text manuell einfügen. Für echte Cloud-KI ist ein sicherer Server erforderlich. PDFs bleiben lokal gespeichert, aber für das optionale PDF-Textextraktionsmodul wird ein Skript von cdnjs.cloudflare.com geladen; die PDF-Datei selbst wird nicht an einen Server geschickt. Es gibt keine verifizierte Sicherung. Nur Testdaten verwenden.

## Durchgeführte Prüfungen
- JavaScript-Syntax: bestanden
- Automatische Testfälle für Betrag, Datum, Absender, Titel: bestanden
- Browser-End-to-End-Test: nicht möglich, lokale HTTP-URLs werden in dieser Umgebung administrativ blockiert.
