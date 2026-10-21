# Snaps by Cindy

Portfoliowebsite voor straatfotografie van Cindy. Statische HTML, geen build-stap.
Alle tekst op de site is in het Nederlands.

## Naam van de site

- De site heet **Snaps by Cindy** (met "by", omdat "snaps" ook Engels is). Gebruik deze schrijfwijze overal: kop, logo, tabbladtitel en footer.
- De rest van de tekst op de site blijft gewoon Nederlands.

## Bestanden

- `index.html`: homepagina (hero, stijlen, recent werk, blog, over mij, footer).
- `portfolio.html`: alle foto's met filters per stijl en een vergrootvenster.
- `fotos.js`: de lijst met alle portfoliofoto's, **nieuwste bovenaan**. Beide pagina's lezen deze lijst.
- `foto/`: de fotobestanden.

## Vaste regel: homepagina toont de 4 nieuwste foto's

"Recent werk" op de homepagina toont altijd automatisch de eerste 4 foto's uit `fotos.js`.
Een nieuwe foto zet je dus **bovenaan** in `fotos.js`. Pas de homepagina niet met de hand aan voor recent werk.

## Nieuwe foto's toevoegen

1. Cindy zet nieuwe foto's in de Google Drive-map **"Claude-Map"**. Haal ze daar op als ze erom vraagt.
   Voeg alleen foto's toe die nog niet in `fotos.js` staan.
2. Maak een webversie: langste zijde maximaal 1600 px, JPEG-kwaliteit ongeveer 84, **zonder EXIF** (vanwege GPS-gegevens).
3. Sla op in `foto/` met een eenvoudige naam zonder spaties, bijvoorbeeld `cafe-sneek.jpg`.
4. Voeg bovenaan in `fotos.js` een regel toe met: `bestand`, `titel` (uit de bestandsnaam, netjes geschreven),
   `stijlen` (een of meer van `straat`, `lange-sluitertijd`, `avond`, `abstract`; bepaal dit door de foto te bekijken),
   `breedte`, `hoogte` en een beschrijvende `alt`-tekst.
5. Commit en push naar `main`.

## Afspraken bijhouden in dit bestand

- Spreken Cindy en Claude een nieuwe werkwijze, voorkeur of vaste regel af, stel dan meteen voor om die hier toe te voegen.
  Na akkoord: werk dit bestand bij, commit en push naar `main`. Alleen wat hier op GitHub staat, blijft bewaard voor een volgende sessie.
- Cindy wil liever te veel dan te weinig vastgelegd hebben. Twijfel je of iets een afspraak is, stel dan voor om het op te nemen.
- Schrijf afspraken in gewone, concrete taal en zet ze onder een passend kopje. Verander of verwijder bestaande afspraken alleen als Cindy dat vraagt.
- Cindy kan dit bestand ook zelf aanpassen. Volg altijd de nieuwste versie.

## Voorbeeldweergave

Er bestaat ook een voorbeeldpagina op claude.ai: https://claude.ai/artifact/QB8dBjgH9gDxF2ESHvRekw
Werk die bij met dezelfde bestanden (`portfolio.html`, `fotos.js` en de nieuwe foto's als bijbestanden).
