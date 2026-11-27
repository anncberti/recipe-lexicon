# Mama T's, receptsajt

Receptsajt byggd med HTML och CSS under Lexicons frontendutbildning.

## Sidor

* Startsida (`home.html`) med hero där rubriken ligger ovanpå bilden, kategorier och receptkort
* Receptsida för pannkakor (`index.html`)
* Dela recept (`form.html`), ett formulär med validering i HTML och CSS

## Fokus utifrån undervisningen

* Designsystem enligt CUBE CSS: composition, utility, block och exception
* Tokens för färg (`hsl()` och `light-dark()`), typsnitt, avstånd och hörnradie
* Mörkt läge med en omkopplare som bara använder CSS (`:has()` och `color-scheme`)
* Grid för sidlayout med namngivna ytor, `repeat(auto-fit, minmax(...))` för kort och galleri, flex för meny och kategorier
* Hero där bild och text delar samma gridcell, i stället för `position: absolute`
* `:has()` för avbockade ingredienser, obligatoriska fält och feltexter
* `:user-invalid` och `:user-valid` i formuläret
* Semantisk HTML, skip link, `aria-current="page"`, tydlig fokusmarkering och färger valda med WCAG AA-kontrast som mål

## Köra sajten

Öppna `index.html` i en webbläsare. Typsnittet Montserrat hämtas från Google Fonts och några bilder från [picsum.photos](https://picsum.photos/).
