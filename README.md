# Samen wonen in Goirle — website De Waker

Website voor bewoners van appartementencomplex De Waker in Goirle: nieuws,
activiteiten en praktische informatie. Eén zelfstandig HTML-bestand
(React + Babel via CDN, geen build-stap nodig) — direct te hosten via
GitHub Pages.

## Lokaal bekijken

Open `index.html` gewoon in een browser, of start een lokale server:

```bash
python -m http.server 8000
```

en ga naar `http://localhost:8000`.

## Aanpassen

Alle voorbeeldinhoud (nieuws, activiteiten, contactgegevens, links) staat
overzichtelijk bovenin het `<script>`-gedeelte van `index.html`, met
Nederlandstalige uitleg bij elk onderdeel.

## Publiceren via GitHub Pages

Deze repository is ingesteld om automatisch te publiceren vanaf de
`main`-branch via GitHub Pages (map: `/ (root)`). Elke wijziging die naar
`main` wordt gepusht, verschijnt na enkele minuten live op de Pages-URL.
