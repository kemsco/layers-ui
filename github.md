repo: kemsco/layers-ui
branch: main

## Structure (IMPORTANT)
Le HTML référence des sous-dossiers — garder cette arborescence dans le repo :
- Home.dc.html, Reports.dc.html, TastyCrousty.dc.html
- support.js
- logos/layers-black.png, logos/layers-white.png   ← dans un dossier `logos/` (pas à la racine)
- fonts/proto-mono/ProtoMono-{Regular,Medium,SemiBold}.{woff2,woff}
- textures/grain.png

⚠ Le repo contenait `layers-black.png` / `layers-white.png` à la racine — les remplacer par le dossier `logos/` pour que `src="logos/…"` fonctionne.

## Last sync
date: 2026-08-06T16:10:00Z
note: Export complet des 3 pages + assets (logos, fonts Proto Mono, texture grain) prêt à committer.

### Updated in this project
- TastyCrousty : widget AI Understanding (Global/Site, ⚡ Constat/Amélioration)
- TastyCrousty : Performance Overview (area chart, Daily/Weekly/Monthly)
- TastyCrousty : GEO Matrix (Sujet/Intention/Prompt, colonne Action ⚡, cellules carrées)
- Info-bulles (i) sur les métriques mises en avant

## Screen map
| Screen | Repo file |
| --- | --- |
| Home | Home.dc.html |
| Reports | Reports.dc.html |
| TastyCrousty report | TastyCrousty.dc.html |
| Runtime | support.js |
| Logos | logos/layers-black.png, logos/layers-white.png |
| Fonts | fonts/proto-mono/*.woff2, *.woff |
| Texture | textures/grain.png |
