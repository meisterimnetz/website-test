# Website Build Rules – Meister im Netz

## Grundregeln
- Invoke the front-end design skill before writing any front-end code, every session, no exceptions.
- Always build in German unless told otherwise.
- Never push to GitHub unless I explicitly say "push to GitHub" or "commit".
- Always test locally first and show me on localhost before anything goes live.

## Technologie
- Reines HTML + CSS + JavaScript — kein React, kein Next.js, keine Build-Tools.
- Alle Dateien in einem einzigen Ordner pro Webseite, `index.html` als Einstiegspunkt.
- Externe Fonts über Google Fonts CDN. Keine npm-Pakete.

## Design-Qualität
- Professionell und modern — kein "vibe coded AI" Look.
- Animations und Hover-Effekte verwenden.
- Mobile-first und vollständig responsive.
- Klare Hierarchie: Hero → Features → Social Proof → CTA → Footer.

## Screenshot-Workflow
- Nach dem ersten Build: Server starten und 3–4 Screenshots machen (Puppeteer).
- Screenshots in `temp_screenshots/` ablegen, danach löschen wenn ich es sage.
- Screenshot-Vergleich: gebaut vs. Referenz, Unterschiede fixen.
- Bei animierten Elementen: Screenshot-Loop deaktivieren, direkt in Code arbeiten.

## Brand Assets
- Brand-Assets (Logo, Farben, Bilder) liegen in `brand_assets/`.
- Immer zuerst dort nachschauen bevor Farben oder Fonts gewählt werden.

## GitHub & Deploy
- Lokal entwickeln, lokal testen.
- Erst auf explizite Anweisung ("push to GitHub") committen und pushen.
- Commit-Messages auf Englisch, kurz und beschreibend.
- Remote: https://github.com/meisterimnetz/website-test

## Netlify
- Deployment läuft automatisch über Netlify sobald Code auf GitHub ist.
- Nichts manuell deployen.
