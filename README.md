# Webcam Alpi

Sito statico per GitHub Pages.

1. Crea un repository su GitHub e carica `index.html`, `webcams.json` e questo file.
2. Settings → Pages → Source: branch `main`, cartella `/ (root)`.
3. Il sito sarà su `https://TUOUTENTE.github.io/NOMEREPO/`.

## Aggiungere webcam
- Dal sito: pulsante "Aggiungi webcam" (restano nel tuo browser), poi "Esporta JSON" e sostituisci `webcams.json` nel repository per renderle permanenti.
- A mano: aggiungi un oggetto in `webcams.json` con `name`, `place`, `region`, `province`, `image`, `page`, `source`.

Se `image` è vuoto o non si carica (protezione hotlink), la scheda mostra il link alla pagina originale.
