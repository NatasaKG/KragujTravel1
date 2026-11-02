# Kraguj Travel — sajt

Statičan sajt (HTML + slike), spreman za GitHub Pages.

## Objavljivanje na GitHub Pages
1. Napravi novi repozitorijum na GitHub-u (npr. `kraguj-travel`).
2. Ubaci **sadržaj** ovog foldera u koren repozitorijuma (`index.html` mora biti u korenu, ne u podfolderu).
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
4. Posle 1–2 minuta sajt je na `https://natasakg.github.io/KragujTravel/`.

## Pre nego što sajt postane pravi
- Zameni `https://natasakg.github.io/KragujTravel` pravom adresom u `index.html`, `utisci.html`, `robots.txt` i `sitemap.xml`.
- U `index.html` i `utisci.html` promeni `noindex, nofollow` u `index, follow`.
- Za sopstveni domen: dodaj fajl `CNAME` sa nazivom domena i podesi DNS kod registra.

## Stranice
- `index.html` — početna
- `utisci.html` — utisci putnika (link „Vidi utiske" sa početne; nazad preko logotipa i dugmeta „Nazad na početnu")
- `404.html` — stranica za nepostojeće adrese
