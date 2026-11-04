# Portfolio Noah Kocherhans

Enthalten: `index.html` (die Website, 1:1 wie in der Vorschau), `images/` (Hero- und Porträtfoto), `projects.json` (die Projekte), `admin/` (CMS-Oberfläche).

## 1. Nur online stellen (ohne CMS)
Ordner auf netlify.com/drop ziehen oder per FTP zu einem Hosting (z. B. Hostpoint, Infomaniak) hochladen. Fertig.

## 2. Projekte ändern
Projekte stehen in `projects.json` (Titel, Kategorie, Bild, Link). Ein Bild legst du in `images/projects/` ab und trägst den Pfad ein, z. B. `/images/projects/video1.jpg`. Ohne Bild erscheint der Platzhalter.

## 3. CMS (Decap CMS unter /admin)
1. Ordner in ein GitHub-Repository hochladen.
2. Repo bei Netlify oder Cloudflare Pages verbinden (Seite wird bei jeder Änderung neu veröffentlicht).
3. In `admin/config.yml` die Zeile `repo:` auf dein Repository ändern.
4. GitHub-Login für Decap einrichten, siehe Anleitung auf decapcms.org (GitHub-Backend).
5. Danach unter `deinedomain.ch/admin` einloggen und Projekte im Browser bearbeiten.

## Noch zu ersetzen
Hero-Video (aktuell Standbild), Adobe-Icons (aktuell nachgebaute Kacheln), echte Projekte.
