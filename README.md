# travel-os-site

Veřejný statický web aplikace **Travel OS** (landing page + `/privacy`). Čisté HTML/CSS bez frameworku, bez buildu, bez JS, bez cookies a analytiky.

Samostatný projekt – neobsahuje kód aplikace ani submodul.

## Struktura
- `index.html` – landing page
- `privacy/index.html` – zásady ochrany soukromí (dvě pole [DOPLNIT]: správce údajů, právní základ a lhůty)
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
- doplnit v `/privacy` pole [DOPLNIT] (správce údajů, právní základ a lhůty),
- případně vlastní doména (soubor `CNAME`).
