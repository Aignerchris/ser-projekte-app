SER Projekte Web-App – Upload-Anleitung

1. ZIP entpacken.
2. Den kompletten Inhalt in deinen Zielordner auf dem Webspace hochladen.
3. Wichtig: index.html, manifest.json, sw.js und die icon-*.png müssen im selben Hauptordner liegen.
4. Der Unterordner Bilder muss mit hochgeladen werden.
5. Die Website sollte über HTTPS erreichbar sein, sonst funktionieren Offline-Modus und Installation nicht sauber.

Ordnerstruktur:
/
├── index.html
├── manifest.json
├── sw.js
├── icon-120.png
├── icon-152.png
├── icon-167.png
├── icon-180.png
├── icon-192.png
├── icon-512.png
└── Bilder/
    └── HE-Logo.png

iPhone installieren:
- Seite in Safari öffnen
- Teilen
- Zum Home-Bildschirm

Alte Testdaten löschen:
localStorage.removeItem("service_runs_v2");
location.reload();
