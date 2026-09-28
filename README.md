# Il codice dell’anima – sintesi in 30 slide

Presentazione navigabile (HTML, senza dipendenze) che riassume *Il codice dell’anima. Carattere, vocazione, destino* di James Hillman (Adelphi, 2009). Le parole chiave sono evidenziate in rosso.

## Uso

- Frecce ← → in basso, tasti freccia, PagDown/PagUp, barra spaziatrice o swipe da telefono
- `Home` / `End` per la prima e l’ultima slide
- Tema chiaro/scuro automatico

Apri `index.html` nel browser oppure usa la versione online (vedi sotto).

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository (ad esempio `hillman-codice-anima-slide`) e carica questi file nella radice
2. Vai su **Settings → Pages**
3. In **Build and deployment** scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`
4. Dopo circa un minuto la presentazione sarà su `https://<tuo-utente>.github.io/<nome-repo>/`

Da riga di comando:

```bash
git init
git add .
git commit -m "Prima versione"
git branch -M main
git remote add origin https://github.com/<tuo-utente>/<nome-repo>.git
git push -u origin main
```

## Modificare le slide

I contenuti sono nell’array `D` dentro `index.html`. Ogni slide è `["etichetta", "titolo", ["punto 1", "punto 2", ...]]`. Le parole tra asterischi, come `*daimon*`, vengono rese in rosso.

## Note

Sintesi a scopo di studio, con parole mie; non è affiliata a Hillman né ad Adelphi e non riproduce il testo del libro. Il libro va letto per intero.
