# 🧭 TopoToets – groep 7 van de Harlekijn

Een topo-quiz met dezelfde kaart-en-antwoordenindeling. Tik op een gekleurd land, een stip voor een stad of eiland, of de lijn van de Po en kies rechts de juiste naam. Met de zoomknoppen kun je de kleine landen en dicht bij elkaar liggende steden beter bekijken.

## Wat leer je?

**Landen:** Zwitserland, Oostenrijk, Italië, Roemenië, Turkije, Irak en Iran

**Steden:** Genève, Bern, Wenen, Milaan, Boekarest, Istanbul, Ankara, Bagdad en Teheran
**Overig / wateren:** Po en Sicilië

## Lokaal starten

Start in deze map een eenvoudige webserver, bijvoorbeeld met `python -m http.server 8000`, en open `http://localhost:8000/`. De quiz heeft geen buildstap of kaart-API-sleutel nodig. Kaartgrenzen en quizlocaties staan lokaal in `basemap.js` en `geography.js`; alleen Leaflet wordt via een CDN geladen.

De land- en riviercontouren zijn afkomstig uit de [publiek-domeindata van Natural Earth](https://www.naturalearthdata.com/about/terms-of-use/) (110m-landen en 50m-rivieren).

## GitHub Pages

Publiceer de branch met deze bestanden via **Settings → Pages → Deploy from a branch → / (root)**.
