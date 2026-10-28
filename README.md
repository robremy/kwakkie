# Kwakkie de Eend (zelfstandige app)

Wat zit erin: index.html (de hele app), manifest.webmanifest, sw.js (werkt offline), icon.svg en icon-192/512.png.

## Waarom hosten?
Microfoon, camera en bewegingssensoren werken alleen op een beveiligde (https) pagina. Een bestand openen vanaf je telefoon werkt dus niet.

## Gratis hosten (kies een)
1. GitHub Pages: maak een nieuwe repository, upload alle bestanden uit deze map, ga naar Settings > Pages en kies de main-branch. Na een minuut staat Kwakkie op https://JOUWNAAM.github.io/REPONAAM/
2. Netlify Drop: sleep deze map naar app.netlify.com/drop. Je krijgt meteen een https-adres.

## Op de telefoon
- Open het adres in Chrome (Android) of Safari (iPhone) en kies Zet op beginscherm.
- Tik op Kwakkie en sta microfoon, camera en beweging toe wanneer erom gevraagd wordt.
- Android Chrome speelt soms een klein pingeluid bij het opnieuw starten van het luisteren. Zet dan Luisteren uit met de knop bovenaan; alles werkt ook met tikken.
- iPhone: spraakherkenning werkt in Safari, maar minder betrouwbaar. Beweging vraagt eenmalig toestemming.
- Het spel Wat zie ik? downloadt eenmalig een herkenmodel (ongeveer 10 MB) en heeft daarom internet nodig.

## Privacy
Camerabeelden blijven op het toestel. Naam en lievelingsdingen staan alleen in de browser. Spraakherkenning in Chrome en Safari stuurt de opname naar Google of Apple; met Luisteren uit gebeurt dat niet.
