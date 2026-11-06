# PAPIERLOS Release 1.0 – lokale Web-App

## Installation
Die Dateien `index.html`, `sw.js`, `manifest.webmanifest` und `icon.png` in das Stammverzeichnis des bestehenden GitHub-Pages-Repositories hochladen. Die installierte Home-Bildschirm-App nicht löschen. Bestehende Einträge bleiben unter dem bisherigen localStorage-Schlüssel `papierlos_v01` und Anhänge in IndexedDB `papierlos_attachments_v02`.

## Enthalten
Dokumentenarchiv mit Kategorie-Kacheln, Suche, Foto-/PDF-Anhänge, Bearbeiten, Löschen, Zahlungen und Fristen, Wiederholungen, Monatskalender, regelbasierte Texterkennung, PDF-Textauslesung mit pdf.js bei Netzverbindung, JSON-Backup einschließlich Anhängen, Wiederherstellung, ICS-Kalenderexport.

## Grenzen
Kein nativer iOS-Scanner, keine verlässliche Foto-OCR auf iOS Safari, keine Cloud-KI, kein Sync, keine Verschlüsselung, keine garantierten Push-Mitteilungen, keine unabhängige Datenschutz-/Sicherheitsprüfung. Backup ist unverschlüsselt. Vor produktiver Nutzung sind zusätzliche Sicherheits- und Gerätetests erforderlich.
