Tagwerk - Standalone-Build (statische Dateien)

Inhalt: index.html, manifest.webmanifest, sw.js, icon-180/192/512.png
Hosting: Diese Dateien einfach von einem Webserver ausliefern, in einem eigenen Unterordner (z. B. /tagwerk/) oder unter einer eigenen Subdomain/einem eigenen Port. Es gibt kein Backend und keine Build-Schritte.
Wichtig: Fuer "Zum Home-Bildschirm" auf dem iPhone und fuer den Service Worker muss die Seite ueber HTTPS laufen (localhost geht ohne).

Daten: liegen nur im Browser (localStorage, Schluessel "tagwerk-v1") des jeweiligen Geraets und der jeweiligen Adresse. Backup/Wiederherstellen: in der App unter Ziele -> Daten. Ein Wechsel der Adresse (anderer Host/Port) = leere App, dann Backup einspielen.
Nicht enthalten in dieser Version: die Claude-Funktionen (Woche per Sprache planen, Einrichten per Sprache, Konto-Speicherung). Sie funktionieren nur als Claude-Artefakt.
