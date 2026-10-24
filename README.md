# Sensible Ishockey

Top-down ishockey i retro arkade-stil, med en lodret bane som i Sensible Soccer. Spillet kører i browseren på både mobil og computer. Det hele ligger i én `index.html` uden afhængigheder.

**Aktuel version: Sensible Ishockey 0.6.0**

## Spil som app (fuld skærm)
Åbn spillet via GitHub Pages på mobilen og vælg **Føj til hjemmeskærm**. I Safari ligger den under Del-knappen, i Chrome under menuen ⋮. Så starter spillet i fuld skærm uden browserlinje, med sit eget ikon, og det kan spilles offline. På Android går spillet også i fuld skærm, når en kamp starter, og der er en knap til fuld skærm i hovedmenuen. Du kan spille med telefonen både på højkant og på tværs.

## Styring
- **Mobil:** Træk i venstre side for at skøjte. **SKYD/PASS:** et kort tryk afleverer, hold knappen inde og slip for at skyde. **TJEK:** tackling.
- **Tastatur:** Piletaster eller WASD. Mellemrum eller Z for skud og aflevering, X eller Shift for at tjekke, P eller Escape for pause.
- **2 spillere:** Spiller 1 bruger piletaster, 0 og komma. Spiller 2 bruger WASD, G og H.
- Den spiller, du styrer, har en grøn ring. Modstanderen med pucken har en grå skygge.

## Indstillinger
Sværhedsgrad (Let/Normal/Svær) · Periodelængde (1–3 min) · Icing og offside til eller fra · Lyd.

## Versioner
Navngivning: **Sensible Ishockey 0.x.x**. En større ændring hæver første x, en mindre ændring hæver andet x.

### Sensible Ishockey 0.6.0
- Kan installeres som app med fuld skærm, eget ikon og offline-spil.
- Spillet går i fuld skærm, når en kamp starter på en mobil, der understøtter det.
- Knap til fuld skærm i hovedmenuen og vejledning til at føje spillet til hjemmeskærmen på iPhone.

### Sensible Ishockey 0.5.0
- Balancen er justeret tilbage. Spilleren scorer cirka halvt så ofte som i 0.4.0, og modstanderen scorer cirka 25 % oftere.
- Helt glat is uden riller og sne, så spillerne står tydeligere frem.

### Sensible Ishockey 0.4.0
- Ny balance. Din egen målmand er stærkere, computerens er svagere, og computeren skyder sjældnere og mindre præcist.
- Mere af banen er synlig i højformat, og kontrolstriben i bunden er smallere.

### Sensible Ishockey 0.3.0
- Kan spilles i højformat på mobilen, og banen tilpasser sig skærmen.
- Lettere at score med sigtehjælp mod hjørnerne.
- Pauseknappen er flyttet op i venstre hjørne.

### Sensible Ishockey 0.2.0
- Lodret top-down-bane som i Sensible Soccer.
- Pucken bliver liggende i nettet efter et mål.
- Nemmere afleveringer: de går til medspilleren i den retning du peger, og modtageren griber pucken let.
- Grøn ring om den spiller, du styrer, og grå skygge under modstanderen med pucken.

### Sensible Ishockey 0.1.0
- Første version: 12 hold, AI-modstander, 2 spillere, icing og offside, perioder og overtid.

## Filer
- `index.html`: Spillet til GitHub Pages, med app-installation.
- `game.html`: Det samme spil i artifact-udgaven til Claude.
- `manifest.webmanifest`, `sw.js` og ikonerne: Bruges til app-installation og offline-spil.
