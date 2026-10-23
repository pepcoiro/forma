# Forma

**Forma** è un editor vettoriale utilizzabile direttamente dal browser, pensato per creare e modificare grafiche come locandine e composizioni semplici. L'interfaccia è in italiano e il progetto funziona senza account.

## Funzionalità

- Creazione e modifica di rettangoli, ellissi, triangoli, stelle e linee.
- Inserimento di testo e immagini.
- Disegno di tracciati con lo strumento penna.
- Modifica delle proprietà degli oggetti: posizione, dimensioni, riempimento, contorno e testo.
- Allineamento degli oggetti alla tavola o tra loro.
- Gestione dei livelli, con riordino tramite trascinamento e blocco degli elementi.
- Annullamento e ripristino delle modifiche.
- Zoom della tavola e dimensioni predefinite per formati come A4, A3, Story, quadrato e locandina.
- Importazione di file SVG ed esportazione in SVG o PNG.
- Salvataggio automatico locale nel browser.

## Utilizzo

Apri `index.html` nel browser. Non è necessario installare dipendenze o avviare un backend.

1. Scegli uno strumento dalla barra laterale.
2. Crea forme sulla tavola oppure inserisci testo e immagini.
3. Seleziona un oggetto per modificarne le proprietà nel pannello laterale.
4. Usa i controlli di allineamento e livelli per organizzare la composizione.
5. Esporta il risultato in SVG o PNG.

Il documento viene salvato automaticamente nello spazio locale del browser. L'autosalvataggio non è un archivio cloud: per conservare o trasferire un lavoro, esportalo in un file.

## File del progetto

- `index.html` — struttura dell'interfaccia.
- `style.css` — stile e layout.
- `app.js` — strumenti di disegno, modifica, importazione, esportazione e autosalvataggio.

## Tecnologie

HTML, CSS, JavaScript e SVG nativi. L'applicazione non richiede un framework o un server applicativo; il font Jost viene caricato da Google Fonts quando è disponibile la connessione.

## Limiti

Forma è un editor vettoriale leggero, non un sostituto completo di software professionali come Illustrator o Inkscape. Le funzioni disponibili sono quelle implementate nell'interfaccia del progetto. L'esportazione PNG viene generata nel browser.

## Autore

Giuseppe Coiro — [pepcoiro.github.io/website](https://pepcoiro.github.io/website/)
