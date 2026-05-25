# Tkáč – Slovenská Weaver hra

Slovenská verzia hry Weaver Wordle.

## Ako hrať
- Dostaneš štartovacie a cieľové slovo (obe 4 písmená)
- Každým krokom zmeň presne 1 písmeno
- Každé slovo musí byť platné slovenské slovo
- Cieľom je dostať sa na cieľové slovo s čo najmenej krokmi

## Nasadenie na Render.com

1. **Nahraj na GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Tkáč – Slovenská Weaver hra"
   git remote add origin https://github.com/tvoj-username/tkac-wordle.git
   git push -u origin main
   ```

2. **Na Render.com:**
   - Prihlás sa na [render.com](https://render.com)
   - Klikni **New → Static Site**
   - Vyber GitHub repozitár
   - Nastav:
     - **Build Command:** (nechaj prázdne)
     - **Publish directory:** `.`
   - Klikni **Create Static Site**

3. **Hotovo!** Render ti dá URL ako `tkac-wordle.onrender.com`

## Súbory
- `index.html` – celá hra (HTML + CSS + JS v jednom súbore)
- `render.yaml` – konfigurácia pre Render
- `words.js` – zásobný zoznam slov (referenčný, nie používaný priamo)
