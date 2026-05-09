# 2EMME Apartments · Manuali Asset

Manuale interattivo online per gli asset degli appartamenti 2EMME Apartments.

Il progetto è pubblicato tramite **GitHub Pages** e contiene una pagina web mobile-first pensata per consultazione rapida da parte di ospiti, housekeeping e gestione operativa.

## Sito online

Quando GitHub Pages è attivo, il sito è disponibile qui:

https://matteomasella-svg.github.io/manualicasa/

## Contenuto

La web app include:

- selezione dell'appartamento
- elenco asset presenti nell'alloggio
- schede uso rapido
- programmi disponibili
- problemi frequenti
- manutenzione ordinaria
- assistenza tecnica
- stima dei consumi energetici con tariffa modificabile €/kWh

## Appartamenti inclusi

- The NoLo Suite - Space & Comfort
- The NoLo Nest - Compact & Smart
- The NoLo Studio - Urban & Sleek
- The NoLo Heritage - Authentic & Charming
- Masotto Terrace View - Bright & Quiet

## Struttura repository

```text
.
├── index.html
├── README.md
└── assets/
    └── logo.jpeg
```

## Pubblicazione con GitHub Pages

Per pubblicare o verificare la pubblicazione:

1. Aprire il repository su GitHub.
2. Andare in **Settings**.
3. Aprire la sezione **Pages**.
4. Impostare:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Salvare.

Dopo il salvataggio, GitHub Pages può richiedere qualche minuto per rendere il sito disponibile.

## Modifica contenuti

Tutti i contenuti principali sono nel file:

```text
index.html
```

Per aggiornare appartamenti, asset, programmi, consumi o contatti assistenza, modificare l'array JavaScript `apartments` presente nel file.

## Logo

Il logo è caricato in:

```text
assets/logo.jpeg
```

Nel file HTML viene richiamato con:

```html
<img class="logo" src="assets/logo.jpeg" alt="2EMME Apartments">
```

## Note operative

- Il sito è statico: non richiede database o backend.
- Funziona su desktop e mobile.
- La stima dei costi energetici è indicativa e dipende dalla tariffa impostata dall'utente.
- I dati tecnici degli asset devono essere verificati periodicamente prima dell'uso operativo.

## Brand

**2EMME Apartments**  
Milano Vacation Rentals
