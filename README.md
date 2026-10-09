# Progress Lab – mobilní webová aplikace (PWA)

## Publikování zdarma přes GitHub Pages
1. Na github.com si založ účet (pokud jej nemáš) a vytvoř nový **veřejný** repozitář například `progress-lab`.
2. Nahraj **obsah této složky** (index.html, app.js, style.css, sw.js, manifest.webmanifest a oba PNG soubory) do kořene repozitáře.
3. Otevři **Settings → Pages → Build and deployment → Deploy from a branch**, zvol `main` a `/ (root)`, ulož.
4. Po nasazení otevři adresu `https://TVUJ-UCET.github.io/progress-lab/` (nahraď TVUJ-UCET svým uživatelským jménem).
5. Na iPhonu otevři stránku v Safari → Sdílet → Přidat na plochu.

## Důležité
- Veškeré tréninky a plán jsou ukládány do `localStorage` daného prohlížeče. Při vymazání dat prohlížeče se mohou ztratit. Pravidelně používej **Export** a zálohu ulož mimo telefon.
- Aplikace funguje offline po prvním úspěšném načtení na HTTPS.
- Neobsahuje server, účty, synchronizaci ani platby. GitHub Pages je veřejný hosting statických stránek, nikoli prodejní platforma.
- Odhad 1RM je orientační, nikoli lékařské ani tréninkové doporučení.
- Před komerčním zveřejněním ověř aktuální podmínky hostingu a právní podmínky podnikání nezletilých.

## Lokální test
Spusť v této složce `python -m http.server 8000` a otevři `http://localhost:8000` na počítači. Instalace PWA na iPhone vyžaduje HTTPS hosting.
