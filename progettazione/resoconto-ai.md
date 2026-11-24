Sessione 1 — 4 novembre 2026

Richieste: supporto per organizzare e pubblicare il progetto festival-segnale su GitHub Pages, utilizzando una repository personale e pubblica, separata da altri progetti.

Utilizzo dell'AI: individuazione dei problemi nella struttura della repository e indicazioni per organizzare correttamente i file del sito.

Modifiche: spostamento di index.html, programma.html, style.css e della cartella assets direttamente nella cartella principale della repository.

Problemi e soluzioni: la struttura iniziale, con i file all'interno di una sottocartella, causava un errore 404. È stato suggerito di spostare i file nella root e configurare GitHub Pages sul branch main, nella cartella principale.

Verifica: controllato lo stato della repository e la sincronizzazione con origin/main. Non è stata documentata una verifica completa del sito pubblicato.

Sessione 2 — 11 novembre 2026

Richieste: realizzazione della pagina info.html, mantenendo la struttura e il CSS già utilizzati nel progetto.

Utilizzo dell'AI: supporto nella costruzione del codice HTML e nell'organizzazione dei contenuti della pagina.

Scelte e modifiche: mantenimento della navigazione comune alle altre pagine, utilizzo del foglio di stile condiviso e attenzione alla struttura semantica, con un solo elemento h1 e un titolo appropriato.

Verifica: controllo della struttura HTML e della coerenza con le altre pagine del sito.

Sessione 3 — 16 novembre 2026

Richieste: individuazione di una palette cromatica coerente con le immagini e l'estetica fantasy retro del progetto.

Utilizzo dell'AI: confronto e proposta di colori da utilizzare nella comunicazione visiva del sito.

Scelte e modifiche: valutazione delle combinazioni cromatiche in relazione allo stile grafico di riferimento e alla leggibilità dei contenuti.

Verifica: confronto visivo della palette con le immagini fornite.

Sessione 4 — 17–18 novembre 2026

Richieste: integrazione di un carattere web tramite Google Fonts e ricerca di un font adatto all'estetica del progetto, inizialmente ispirata a Magic: The Gathering.

Utilizzo dell'AI: ricerca di caratteri disponibili su Google Fonts e indicazioni per importarli nelle pagine HTML e applicarli tramite CSS.

Scelte e modifiche: valutazione di diverse soluzioni tipografiche; successivamente è stata adottata una direzione più moderna, con Montserrat per i titoli.

Verifica: controllo del collegamento Google Fonts nell'head delle pagine e dell'applicazione del carattere nel foglio di stile.

Sessione 5 — 18–24 novembre 2026

Richieste: completamento della griglia CSS e delle funzionalità delle pagine del festival; supporto nella gestione dei dati relativi a eventi e sedi.

Utilizzo dell'AI: indicazioni sulle modifiche necessarie al codice HTML e CSS, completamento dei file eventi.json e sedi.json e definizione della documentazione dei dati in dati/SCHEMA.md.

Modifiche: completamento dei record relativi a sei eventi e tre sedi, mantenendo i collegamenti tramite sede_id; predisposizione della struttura responsive della griglia, con una colonna sotto i 600px, due colonne dai 600px e tre colonne dai 1024px.

Scelte: mantenimento delle classi CSS e della struttura grafica già presenti, evitando modifiche non necessarie.

Problemi e soluzioni: attenzione alla coerenza tra gli identificativi delle sedi nei due file JSON e alla corrispondenza tra i dati e gli eventi già presenti nel programma.

Sessione 6 — 25 novembre 2026

Richieste: caricamento dinamico degli eventi tramite fetch, integrazione di una sezione meteo nella pagina info.html e predisposizione di test per verificare il comportamento del sito.

Utilizzo dell'AI: generazione del codice JavaScript per leggere dati/eventi.json e dati/sedi.json, creare dinamicamente le schede degli eventi e gestire eventuali errori; integrazione dell'API Open-Meteo per mostrare temperatura e vento a Torino.

Modifiche: aggiunta degli stati di caricamento, assenza di eventi ed errore; gestione delle sedi non riconosciute tramite il messaggio "Sede da definire"; aggiunta della nota sulla fonte dei dati meteo.

Scelte: utilizzo di Open-Meteo senza chiave API e mantenimento delle classi CSS esistenti per conservare lo stile delle schede.

Problemi e soluzioni: il metodo fetch richiede l'esecuzione del sito tramite un server locale e non l'apertura diretta dei file con file://. È stato individuato Live Preview in VS Code come strumento per avviare l'anteprima, scegliendo External Browser.

Verifica: predisposizione di test per modifiche ai JSON, file mancanti, eventi senza una sede valida, errori dell'API meteo e visualizzazione responsive. I test devono essere completati e documentati dopo l'esecuzione.