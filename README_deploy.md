# Publicare pe GitHub Pages — `dental-market-ro`

URL final: **https://vladtm75.github.io/dental-market-ro/**

## Fișiere de urcat (exact aceste 2, în rădăcina repo-ului)
- `index.html`  (dashboard-ul mobil, cu Open Graph deja setat absolut)
- `Dental_Market_Mobile_OG.png`  (imaginea de preview 1200×630)

> Important: păstrează numele `Dental_Market_Mobile_OG.png` neschimbat — e referit în og:image.

## Pași (≈2 minute)

1. Intră pe https://github.com/new
   - **Repository name:** `dental-market-ro`
   - Vizibilitate: **Public** (necesar pentru GitHub Pages gratuit)
   - Apasă **Create repository**.

2. În repo-ul nou: **Add file → Upload files**.
   - Trage ambele fișiere (`index.html` și `Dental_Market_Mobile_OG.png`).
   - **Commit changes**.

3. Activează Pages: **Settings → Pages**
   - **Source:** Deploy from a branch
   - **Branch:** `main` / folder `/ (root)` → **Save**.

4. Așteaptă ~1 minut. Pagina va fi live la:
   **https://vladtm75.github.io/dental-market-ro/**

## Verificare preview WhatsApp
- WhatsApp/Telegram pun în cache prima previzualizare. Dacă vrei să forțezi reîmprospătarea după modificări, testează întâi pe:
  - Facebook Sharing Debugger: https://developers.facebook.com/tools/debug/ (lipești URL-ul → „Scrape Again")
  - apoi trimite linkul pe WhatsApp.

## Dacă vrei alt nume de repo
URL-urile Open Graph din `index.html` sunt setate pentru `dental-market-ro`. Dacă schimbi numele repo-ului, anunță-mă să reactualizez cele 3 referințe `og:url` / `og:image` / `twitter:image`.
