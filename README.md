# Ishockey

Top-down ishockey i retro arkade-stil på en lodret bane. Spillet kører i browseren på både mobil og computer. Det hele ligger i én `index.html` uden afhængigheder.

**Aktuel version: Ishockey 0.9.0**

## Spil som app (fuld skærm)
Åbn spillet via GitHub Pages på mobilen og vælg **Føj til hjemmeskærm**. I Safari ligger den under Del-knappen, i Chrome under menuen ⋮. Så starter spillet i fuld skærm uden browserlinje, med sit eget ikon, og det kan spilles offline. På Android går spillet også i fuld skærm, når en kamp starter, og der er en knap til fuld skærm i hovedmenuen. Du kan spille med telefonen både på højkant og på tværs.

## Turneringer
- **Metal Ligaen · DM-slutspil:** 8 af de 9 danske hold spiller knockout med kvartfinale, semifinale og finale.
- **NHL · Stanley Cup:** 16 af de 32 NHL-hold spiller knockout over fire runder, med Stanley Cup-finalen til sidst.
- Vælg dit hold og spil én kamp ad gangen. De andre kampe i runden bliver afgjort automatisk. Taber du, er du ude.
- Uafgjort afgøres i sudden death-overtid: første mål vinder.
- Turneringen bliver gemt i browseren, så du kan fortsætte senere. Begge turneringer kan køre på samme tid.

I **Kamp** og **2 spillere** vælger du først liga (Metal Ligaen, NHL eller Fantasihold) og derefter holdene.

## Styring
- **Mobil:** Træk i venstre side for at skøjte. **SKYD/PASS:** et kort tryk afleverer, hold knappen inde og slip for at skyde. **TJEK:** tackling.
- **Tastatur:** Piletaster eller WASD. Mellemrum eller Z for skud og aflevering, X eller Shift for at tjekke, P eller Escape for pause.
- **2 spillere på ét tastatur (også Mac):**
  - Spiller 1 (grøn ring): piletaster, **.** skyder/afleverer, **-** tjekker.
  - Spiller 2 (lyseblå ring): WASD, **F** skyder/afleverer, **G** tjekker.
- Den spiller, du styrer, har en grøn ring. Modstanderen med pucken har en grå skygge.

## Indstillinger
Sværhedsgrad (Let/Normal/Svær) · Periodelængde (1–3 min) · Icing og offside (slået fra som standard) · Lyd.

## Versioner
Navngivning: **Ishockey 0.x.x**. En større ændring hæver første x, en mindre ændring hæver andet x.

### Ishockey 0.9.0
- Holdene fra Metal Ligaen og NHL er med, i klubbernes farver.
- To turneringer: DM-slutspil med Metal Ligaen-holdene og Stanley Cup med NHL-holdene.
- Ligavalg i Kamp og 2 spillere. De gamle fantasihold er stadig med.
- Overtid er nu sudden death, og første mål vinder. I turneringer fortsætter overtiden, til der er en vinder.
- Icing og offside er slået fra som standard.

### Ishockey 0.8.0
- Nye taster til 2 spillere på ét tastatur, som også findes på et Mac-tastatur uden numerisk tastatur. Spiller 1: piletaster, . og -. Spiller 2: WASD, F og G.
- Hold-valget viser SP1 og SP2 og tasterne for hver spiller.

### Ishockey 0.7.0
- Spillet hedder nu kun Ishockey: titel, logo, app-navn, versionstekst og reklamebander er rettet.

### Ishockey 0.6.0
- Kan installeres som app med fuld skærm, eget ikon og offline-spil.
- Spillet går i fuld skærm, når en kamp starter på en mobil, der understøtter det.
- Knap til fuld skærm i hovedmenuen og vejledning til at føje spillet til hjemmeskærmen på iPhone.

### Ishockey 0.5.0
- Balancen er justeret tilbage. Spilleren scorer cirka halvt så ofte som i 0.4.0, og modstanderen scorer cirka 25 % oftere.
- Helt glat is uden riller og sne, så spillerne står tydeligere frem.

### Ishockey 0.4.0
- Ny balance. Din egen målmand er stærkere, computerens er svagere, og computeren skyder sjældnere og mindre præcist.
- Mere af banen er synlig i højformat, og kontrolstriben i bunden er smallere.

### Ishockey 0.3.0
- Kan spilles i højformat på mobilen, og banen tilpasser sig skærmen.
- Lettere at score med sigtehjælp mod hjørnerne.
- Pauseknappen er flyttet op i venstre hjørne.

### Ishockey 0.2.0
- Lodret top-down-bane.
- Pucken bliver liggende i nettet efter et mål.
- Nemmere afleveringer: de går til medspilleren i den retning du peger, og modtageren griber pucken let.
- Grøn ring om den spiller, du styrer, og grå skygge under modstanderen med pucken.

### Ishockey 0.1.0
- Første version: 12 hold, AI-modstander, 2 spillere, icing og offside, perioder og overtid.

## Filer
- `index.html`: Spillet til GitHub Pages, med app-installation.
- `game.html`: Det samme spil i artifact-udgaven til Claude.
- `manifest.webmanifest`, `sw.js` og ikonerne: Bruges til app-installation og offline-spil.
