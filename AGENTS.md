# Convenzioni di sviluppo

- Ogni nuova richiesta si sviluppa in un branch **temporaneo** e si propone tramite pull request verso `master`; non esistono branch permanenti per singole richieste.
- Dopo test e verifica, effettuare il merge della PR e rimuovere il branch sorgente. Se annullata, chiudere la PR senza merge e cancellare il branch quando non più necessario.
- Lasciare `README.md` breve e descrittivo. Inserire **tutte** le note di versione e le modifiche in `CHANGELOG.md`, mantenendo lo storico. Documentazione tecnica altrove.
- Non modificare branch protetti e non pubblicare segreti. Se esiste un branch `production`, promuovere separatamente i soli file necessari con una PR dedicata, senza merge indiscriminati.
- Configurare nelle impostazioni GitHub **Automatically delete head branches** per la rimozione automatica dei branch dopo il merge.
