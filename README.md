# Cabarelli — Static Site (HTML/CSS/JS)

## Struktur
- index.html — Landing / Hero
- drops.html — Produkt-Grid für aktuelle Drops
- archive.html — Filterbares Archiv
- about.html — Philosophie, Codes
- contact.html — Kontakt/Meta
- assets/css/styles.css — Styles
- assets/js/main.js — JS (Burger + Archive-Filter)
- assets/img/* — Platzhalter-Grafiken (SVG)

## Deployment (kostenlos)

### Variante A: GitHub Pages
1. Neues Repo anlegen: cabarelli-site
2. Inhalte dieses Ordners hochladen (alle Dateien).
3. Repo-Einstellungen → Pages → Branch main / Root → Save.
4. Nach ~1 Minute ist die Seite online: https://<dein-user>.github.io/cabarelli-site/

### Variante B: Netlify
1. Auf app.netlify.com einloggen, New site from Git oder Deploy manually.
2. Ordner hochladen → Build Command leer lassen, Publish dir = Root.
3. Fertig. Domain ist direkt verfügbar; später Custom Domain möglich.

### Variante C: Replit
1. Neues Repl → HTML/CSS/JS Template.
2. Dateien aus diesem Ordner hochladen.
3. Run → Public URL kopieren.

## Bearbeitung
- Alles ist Plain HTML/CSS → in jedem Editor änderbar.
- Brand-Farben in :root im CSS.
- Navigation öffnet neue Seiten (target=_self) für schnelle Ladezeiten.

## Tipp für Erweiterungen
- Netlify Forms aktivieren → echtes Kontaktformular ohne Backend.
- SEO-Tags und OG-Bilder in <head> einfügen.
- Optional: CMS (z. B. Netlify CMS oder Contentful) für Drops/Archive.
- Für dynamische Drops → später API oder JSON-System anbinden.

Cabarelli steht für:
Italienischer Schnitt trifft auf Asphalt-Mentalität.
Handwerk trifft auf Block-Energie.
Ein Label, das nicht nur Mode verkauft, sondern ein Lebensgefühl.

© 2025 Cabarelli Collective — Designed with Liebe & Chaos.
