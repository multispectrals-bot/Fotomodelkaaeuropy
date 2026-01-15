# Fotomodelkaaeuropy
Modeling
# fotomodelkaaeuropy

Testovacia jednopage stránka pre projekt **Fotomodelka a Európy**.

## Obsah repozitára
- `index.html` — kompletná testovacia stránka (kontakt, portfólio, galéria, simulátor platobnej brány).
- `casting1.jpg` … `casting6.jpg` — (voliteľné) fotografie z kastingu, nahraďte vlastnými súbormi.

## Ako nasadiť (GitHub Pages)
1. Vytvorte nové public repo (napr. `fotomodelkaaeuropy`) na GitHub.
2. Nahrajte `index.html` a prípadné obrázky do koreňa repozitára.
3. V repozitári choďte do **Settings → Pages**, vyberte branch `main` a root `/`, kliknite **Save**.
4. Po niekoľkých minútach bude stránka dostupná na `https://<github-username>.github.io/<repo-name>`.

## Lokálne testovanie
- Stačí otvoriť `index.html` dvojklikom, alebo spustiť jednoduchý lokálny server:
  - Python 3: `python -m http.server 8000` → otvorte `http://localhost:8000`.

## Zmena dĺžky alarmu
- V `index.html` nájdite premennú `ALARM_DURATION_MS` a nastavte ju v milisekundách (napr. `30000` = 30 s).

## Bezpečnostné upozornenia
- Simulátor platobnej brány je **len lokálna vizualizácia**. **Nevkladajte skutočné platobné údaje.**
- Simulátor neodosiela údaje a obsahuje ochrany (vymazanie polí, blokovanie fetch/XHR).
- Pri reálnom spracovaní zdravotných alebo platobných údajov použite overené služby a zabezpečené riešenia (Stripe, PayPal, atď.).

## Úpravy
- Nahraďte `casting1.jpg` … `casting6.jpg` vlastnými fotografiami v rovnakom priečinku ako `index.html`.
- Ak chcete, môžem upraviť README tak, aby obsahoval priamo vašu finálnu URL (potrebujem vaše GitHub používateľské meno a názov repozitára).
