# VYTA APP

Pagina di prenotazione pranzi salutari con consegna in azienda: menu del giorno dopo, ricerca e filtri, carrello e modulo di consegna.

È un unico file statico (`index.html`), senza dipendenze da installare.

## Come modificare il menu
Apri `index.html` e cerca `MENU`, `SLOTS` e `CUTOFF` all'inizio dello script: lì ci sono piatti, prezzi, fasce di consegna e orario limite.

## Pubblicare con GitHub Pages
Settings → Pages → Branch `main` / cartella `/ (root)` → Save.

## Da collegare
L'invio reale degli ordini non è implementato: cerca il commento `invio reale dell'ordine` in `index.html`.
