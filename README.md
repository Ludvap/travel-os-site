# travel-os-site

Veřejný statický web aplikace **Travel OS** (landing page + `/privacy`). Čisté HTML/CSS bez frameworku, bez buildu, bez JS, bez cookies a analytiky.

Samostatný projekt – neobsahuje kód aplikace ani submodul.

## Struktura
- `index.html` – landing page
- `privacy/index.html` – zásady ochrany soukromí (správce Ludvík Peikert; dvě položky [PRÁVNĚ OVĚŘIT])
- `assets/` – CSS, ikona aplikace, písmo Nunito Sans (SIL OFL, viz `assets/OFL.txt`)

## Lokálně
```bash
python -m http.server 8000   # nebo: npx serve .
```

## GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
URL: https://ludvap.github.io/travel-os-site/

Workflow nepoužíváme: deploy z větve je nejjednodušší a nic navíc nevyžaduje.

## Před vydáním aplikace
- doplnit odkazy na Google Play / App Store,
- nechat právně ověřit položky [PRÁVNĚ OVĚŘIT] v `/privacy` (základ pro e-mail pozvaného, předávání mimo EU/EEA),
- případně vlastní doména (soubor `CNAME`).
