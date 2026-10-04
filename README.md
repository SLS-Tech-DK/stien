# Stien 🚲

Crowdsourcet hul-anmeldelsesplatform for cyklister i København. *Cyklister hjælper cyklister.*

Stien lader cyklister anmelde farlige huller i cykelstien med foto og alvorsgrad. Andre bekræfter fundene, og de samlede anmeldelser kan sendes videre til kommunen for at fremskynde udbedring. Projektet startede efter gentagne nærved-styrt på Tagensvej og blev til et rigtigt produkt.

**Live:** https://stien.netlify.app

## Features
- Anonym anmeldelse med foto og alvorsgrad (let / moderat / alvorlig)
- Bekræftelse fra andre cyklister (validering af anmeldelser)
- Interaktivt kort (Leaflet) + listevisning
- Geolokation til automatisk placering
- CSV / GeoJSON-eksport til kommunal sagsbehandling
- Admin-dashboard
- Valgfrit telefonnummer, hashet lokalt mod spam
- Onboarding-tutorial for nye brugere

## Tech
- Single-file frontend: HTML + CSS + vanilla JavaScript
- Kort: Leaflet
- Data: `localStorage` i staging-mode, med valgfri Supabase REST-backend (anon-key sættes i `CONFIG`)
- Hosting: Netlify (static), Supabase free tier

## Kør lokalt
Åbn `index.html` i en browser. Uden Supabase-config kører appen i staging-mode med data gemt lokalt i browseren.

## Om
Bygget af [SLS Tech](https://github.com/SLS-Tech-DK) — solo tech-studie, København. Dette repo er en showcase-udgave; ingen nøgler eller persondata.
