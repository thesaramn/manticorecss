# ManticoreCSS

**ManticoreCSS** è un piccolo framework CSS per l’impaginazione a griglie, ispirato alle tabelle HTML dei primi anni 2000 ma costruito con CSS Grid moderno e responsive.

## 📦 Contenuto

- `manticore.css` – Il framework con tutte le griglie pronte all’uso

## 🧱 Come funziona

Ogni griglia è basata su 12 colonne e si costruisce usando classi come `.grid-66`, `.grid-48`, `.grid-3333` ecc., insieme alle colonne `.col-1`, `.col-2`, ecc.

Tutte le griglie sono responsive: sotto i 768px le colonne si impilano verticalmente in automatico.

## 🚀 Come usarlo

1. Scarica `manticore.css`
2. Includilo nella tua pagina HTML:
   ```html
   <link rel="stylesheet" href="manticore.css">
   ```
3. Usa le griglie nel tuo layout:
   ```html
   <div class="grid-66">
     <div class="col-1">Colonna sinistra</div>
     <div class="col-2">Colonna destra</div>
   </div>
   ```

👉 Per la documentazione completa visita il sito ufficiale: **[https://manticorecss.vercel.app](https://manticorecss.vercel.app)**

## 📄 Licenza

MIT – puoi usarlo liberamente per progetti personali e commerciali.
