# William Dions kurdiska bok

Gratis statisk PWA med 10 helger, 200 ordplatser (169 unika ord), meningar, flashcards, matchningsspel, skrivtest, föräldrabedömda muntliga test och lokalt sparade framsteg.

## Publicera gratis på GitHub Pages
1. Skapa ett gratis GitHub-konto (om du inte redan har ett).
2. Skapa ett nytt **public** repository, t.ex. `william-kurmanji`.
3. Ladda upp **innehållet i den här mappen** till repositoryts rot (index.html, app.js, style.css, data.json, sw.js, manifest.webmanifest). `build_data.py` behövs inte för publicering.
4. Öppna **Settings → Pages → Build and deployment → Deploy from a branch**.
5. Välj `main` och `/ (root)` och spara. Vänta tills GitHub visar en publicerad adress.
6. Öppna adressen i mobil/surfplatta/dator. Via webbläsarens meny kan du välja "Lägg till på hemskärmen" där det stöds.

## Viktigt
- Alla framsteg sparas **endast i den aktuella webbläsaren** (localStorage). De synkas inte mellan enheter. Använd Exportera/Importera för att flytta en säkerhetskopia.
- Rensa inte webbläsardata utan att exportera först.
- Skrivtest använder exakt stavning (skiljetecken och stora bokstäver ignoreras).
- Muntliga test bedöms av en förälder. Inga ljudfiler eller inspelningar ingår.
- Kurmanji-innehållet kommer från ett tidigare kursutkast och behöver språkgranskas av en kurmanjitalande vuxen, särskilt vissa substantiv och verbformer.
- Publicera inte personliga uppgifter i GitHub-repot. Appen innehåller endast förnamn i titel och välkomsttext.
- GitHub Pages är publik hosting: alla som känner till adressen kan se kursinnehållet, men inte Williams lokalt lagrade resultat.

## Testa lokalt
I mappen: `python -m http.server 8000`, besök sedan `http://localhost:8000`.
