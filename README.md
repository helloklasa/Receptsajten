# Receptsajten

Övningsprojekt enligt Figma-länken i [kursrepot för Test och kartläggning](https://github.com/Lexicon-Utbildning-Front-end-2026-2027/test-och-kartlaggning) och instruktioner i [detta repo](https://github.com/Lexicon-Utbildning-Front-end-2026-2027/vecka-1/tree/main).

En enkel, responsiv receptsida för pannkakor byggd med semantisk HTML och modern CSS.

## Innehåll

- Semantisk HTML (`article`, `header`, `section`, rubriknivåer, listor, `figure` etc.)
- Responsiv layout
- Tillgänglighet enligt WCAG (alt-texter, kontrast, `lang`-attribut)

## Checklista för åtgärder - Vecka 1

- [**x**] Hårdkodade storlekar på bilder så att inget "layout shift" upplevs
- [**x**] delade upp innehållet i varsin `section` med **aria-labelledby** (och `id` på varje h2, ex. `ingredients-heading`). _Ingredienser_, _Så här gör du_ och _Serveringsförslag_ är tre separata delar med egna rubriker. Kopplingen ger varje sektion ett tillgängligt namn så att skärmläsare kan lista och hoppa mellan dem.
- [**x**] Checkbox för ingredienser. Varje checkbox ligger inuti en `label` som kopplar samman text och ruta utan att behöva använda `for` och `id`. Detta gör hela raden klickbar.
- [**x**] `role="list"` på ingrediens-listan då vissa skärmläsare (Safari/VoiceOver) kan strunta i att läsa elementet som en lista.
- [**x**] `figure` och `figcaption` för serveringsbilder. Bildtext som tillför information utöver bildernas egna `alt`-texter.
