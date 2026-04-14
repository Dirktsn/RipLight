# RipLight PWA

Warm reading light for bedtime. Geen app store nodig — werkt als PWA rechtstreeks vanuit de browser.

## Bestanden

```
reading-light/
├── index.html
├── manifest.json
├── sw.js
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Hosten op GitHub Pages

1. Maak een nieuw repository aan op GitHub, bv. `riplight`
2. Upload alle bestanden (inclusief de `icons/` map)
3. Ga naar **Settings → Pages → Source**: kies `main` branch, root `/`
4. Na een minuutje is de app live op `https://jouwusername.github.io/riplight/`

## Installeren als PWA

**Android (Chrome):**  
Open de URL → tik de drie puntjes → "Toevoegen aan startscherm"

**iPhone (Safari):**  
Open de URL in Safari → tik het deel-icoontje → "Zet op beginscherm"

## Functies

- Volledig scherm (geen browser UI zichtbaar)
- Helderheid en warmte instelbaar
- Tik op het scherm om bediening te tonen/verbergen
- Screen wake lock (scherm blijft aan)
- Volledig offline beschikbaar na eerste bezoek
