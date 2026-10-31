# francescozanella.github.io

Pagine pubbliche dell'app Android Banking Dashboard, pubblicate con GitHub Pages. Statiche, senza
segreti e senza raccolta di dati.

| File | Indirizzo | A cosa serve |
|---|---|---|
| `banking/index.html` | `https://francescozanella.github.io/banking/` | ritorno dalla banca: riapre l'app passandole `code` e `state` |
| `banking/privacy.html` | `https://francescozanella.github.io/banking/privacy.html` | informativa privacy |
| `banking/termini.html` | `https://francescozanella.github.io/banking/termini.html` | termini di utilizzo |
| `.well-known/assetlinks.json` | `https://francescozanella.github.io/.well-known/assetlinks.json` | App Link verificato: il ritorno dalla banca apre direttamente l'app firmata |

`.nojekyll` serve perché GitHub pubblichi la cartella `.well-known`.

Gli indirizzi sono registrati nelle applicazioni Enable Banking di chi usa l'app: **non spostare né
rinominare questi file**. Se modifichi lo script di `banking/index.html`, aggiorna l'hash `sha256-…`
nella sua Content-Security-Policy, altrimenti il browser lo blocca.
