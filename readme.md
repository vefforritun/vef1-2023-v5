# Vefforritun 1, 2023: Verkefni 5, CSS #3

[Kynning í fyrirlestri](https://youtu.be/R6dVPYmPbnE).

## Markmið

- Útfæra skalanlegann vef.
- Nota grid til að stýra útliti.
- Útfæra kvikun.

## Verkefni 2–6

Í verkefnum 2–6 munum við vinna áfram með sama verkefni og byggja ofan á það:

- [Verkefni 2](https://github.com/vefforritun/vef1-2023-v2) skilgreinir grunn HTML og síður.
- [Verkefni 3](https://github.com/vefforritun/vef1-2023-v3) bætir við grunn viðmóti.
- [Verkefni 4](https://github.com/vefforritun/vef1-2023-v4) setur upp útlit (e. layout).
- [Verkefni 5](https://github.com/vefforritun/vef1-2023-v5) setur upp grind og gerir útlit skalanlegt (e. responsive).
- [Verkefni 6](https://github.com/vefforritun/vef1-2023-v6) setur upp tól til að hjálpa við skipulag og vinnu.

## Verkefnið

Verkefnið er framhald af [verkefni 4](https://github.com/vefforritun/vef1-2023-v2), nýtir það efni sem uppsett er í því, og fylgir þeirri verkefnalýsingu. Leyfilegt er að nota [sýnilausn að verkefni 4](https://github.com/vefforritun/vef1-2023-v4-synilausn), sem gefin verður út föstudaginn 22. september.

Nú skal bæta við ítra útlitið. Allt útlitið skal vera í `./styles.css` og **allar** HTML skrár skulu vísa í það.

## Útlit

Fyrirmyndir að útliti er í `fyrirmynd/` möppu í mismunandi upplausnum. Athugið að fyrirmyndir er uppfærð frá verkefni 4. Skjáskot eru af forsíðu en myndband sýnir allar síður.

Útlit á „takka“ (sem er samt í flestum tilfellum fyrir `<a href>`) hefur verið bætt

**Allt það sem tekið er fram í verkefnum 3 og 4 gildir áfram nema annað komi fram hér**.

### Almennt

Gefið er HTML sem byggt er á sýnilausn 4 og notað í sýnilausn að þessu verkefni, ekki ætti að þurfa að breyta því nokkuð.

Gefið er `styles.css` skjal með grunn að lausn.

Gefið er `grid.css` skjal með „grid overlay“ sem er vísað í í HTML skrám og sést á fyrirmyndum.

### CSS Custom Properties

Nota skal skilgreind CSS custom properties sem gefin eru í `styles.css`, búið er að bæta við skilgreiningum frá verkefni 4.

### Skalanleiki

Þrír brotpunktar eru nú:

- Upp að `500px` breiðum glugga.
- Þaðan og upp að `1000px`.
- Þaðan og upp að hámarksbreidd `1400px`.

Útfærslur á boxum hefur breyst í samræmi við breiðara útlit, í breiðustu útfærslu birtast þrjú í röð, síðan tvö og loks eitt.

### Grind

Útfæra skal grind skv. CSS custom properties og fyrirmyndum.

### Kvikun

Setja skal upp kvikun:

- Þegar síða opnast skal fara úr `opacity: 0` í `opacity: 1`.
- Þegar sveimað er yfir takka skal snúa við litum.

Nota skal CSS custom properties sem eiga við kvikun og hafa forskeytið `--transition-`.

Sjá hvernig kvikun hegðar sér í myndbandi í `./fyrirmynd/v5.mp4`.

### Leturgerðir

Nota skal `Lora` fyrir fyrirsagnir og `Noto Sans Display` fyrir meginmál leturgerðirnar frá Google Fonts. Sækja skal leturgerðirnar og geyma í `fonts/`.

### Takmarkanir

Leyfilegt er að nota allt CSS.

## Netlify

Setja skal upp verkefni á Netlify með því að hlaða upp skrám með „manual deploy“ _eða_ tengja GitHub repo.

## Mat

- 20% – Snyrtilega uppsett og gilt CSS.
- 30% – Skalanleg lausn sett upp skv. forskrift.
- 30% – Grind sett upp skv. forskrift.
- 20% – Kvikun útfærð skv. forskrift.

## Sett fyrir

Verkefni sett fyrir af alvöru í fyrirlestri mánudaginn 25. september 2023.

## Skil

Skila skal í Canvas, seinasta lagi fyrir lok dags mánudaginn 2. október 2023.

Skilaboð skulu innihalda:

- zip skrá með öllum skrám _eða_ hlekkur á almennt (e. public) GitHub.
- slóð á verkefni keyrandi á Netlify sem athugasemd („Add comment“ eða „Bæta við athugasemd“ á skilaskjá í Canvas).

Skila má eins oft og þið viljið þar til skilafrestur rennur út.

## Einkunn

Leyfilegt er að ræða, og vinna saman að verkefni en **skrifið ykkar eigin lausn**. Ef tvær eða fleiri lausnir eru mjög líkar þarf að færa rök fyrir því, annars munu allir hlutaðeigandi hugsanlega fá 0 fyrir verkefnið.

Ef stórt mállíkan (LLM, „gervigreind“, t.d. ChatGTP) er notað til að skrifa part af lausn skal taka það fram. [Sjá nánar á upplýsingasíða um gervigreind hjá HÍ](https://gervigreind.hi.is/).

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.1
