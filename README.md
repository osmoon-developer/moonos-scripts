MoonOS Scripts 

In questa repository ci sono gli script nativi usati su MoonOS v1.2 Aurora per gestire, aggiornare e ottimizzare il sistema direttamente dal terminale.
Elenco degli script

    moon-upgrade: Gestisce gli aggiornamenti di sistema in sicurezza sincronizzando i pacchetti dai mirror di Arch Linux.

    moonos-boost: Svuota la cache, ottimizza la gestione della ZRAM e spinge la CPU al massimo delle prestazioni per dare una sferzata di velocità al PC.

    moonos-control: Un pannello di controllo testuale che permette di regolare al volo le impostazioni grafiche e le configurazioni principali.

    moonos-report: Genera un report rapido sullo stato dell'hardware, sull'uso della memoria RAM e sui consumi generali del sistema.

Come installarli manualmente

Se vuoi testare o inserire questi script su un'installazione di Arch Linux, basta copiare i file dentro la cartella dei binari di sistema e dare i permessi di esecuzione.

Istruzioni da terminale:

    Spostati nella cartella dove hai scaricato gli script.

    Copia i file nella directory di sistema:
    sudo cp moon-upgrade moonos-boost moonos-control moonos-report /usr/bin/

    Dai i permessi di esecuzione agli script:
    sudo chmod +x /usr/bin/moon-upgrade /usr/bin/moonos-boost /usr/bin/moonos-control /usr/bin/moonos-report
