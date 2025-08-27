# Phrasal Verbs Flashcards (Preloaded Dataset)

Questa mini applicazione web consente di studiare **phrasal verbs** tramite
flashcards e il metodo Leitner. È precaricata con 130 verbi frasali: i
100 verbi più comuni (estratti dal PDF fornito) e 30 verbi extra
aggiuntivi. Tutte le carte vengono salvate nel `localStorage` del
navigatore, quindi il progresso viene mantenuto tra le sessioni.

## Funzionalità principali

* **Ricerca** e filtro per fonte (PDF, Extra, Manual) e per scatola
  (1‑5).
* **Flip** delle flashcard: clicca su una carta per visualizzarne
  definizione, esempio e, se presente, l’assonanza. Con i pulsanti
  `<` e `>` puoi spostarla nella scatola precedente o successiva.
* **Aggiunta manuale** di nuove carte tramite un modulo dedicato.
* **Importazione/esportazione** in formato JSON per salvare o
  ripristinare l’intero set di carte.
* **Ricarica** del dataset originale da `pv_preloaded.json` e
  aggiunta dei 30 verbi extra con un clic.

## Come usarla

1. Apri `index.html` in un browser moderno (Chrome, Firefox). Se non
   ci sono dati salvati, l’app caricherà automaticamente i 130 verbi
   da `pv_preloaded.json`.
2. Utilizza la barra di ricerca e i menu a tendina per filtrare.
3. Clicca su una carta per capovolgerla. Usa i pulsanti per spostarla
   nelle diverse scatole.
4. Aggiungi nuove carte compilando il modulo e premi “Aggiungi”.
5. Premi **Esporta JSON** per scaricare il tuo progresso come file;
   **Importa JSON** per ricaricare un file esportato in precedenza.

## Deploy su Vercel o CodeSandbox

Per pubblicare l’app online:

1. Clona o scarica questa cartella.
2. Carica tutto il contenuto su un servizio di hosting statico come
   [Vercel](https://vercel.com) o [Netlify](https://netlify.com).
3. Assicurati che `index.html` e `pv_preloaded.json` siano nella root
   del progetto, poiché l’app li richiede per funzionare.

L’app non richiede compilazione né dipendenze: è sufficiente un
semplice hosting statico.