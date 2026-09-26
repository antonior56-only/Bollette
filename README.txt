ENERGIA PRO+ — ISTRUZIONI

Apri index.html per l'uso locale. In questo modo le bollette restano nel localStorage del browser; il backup JSONBin richiede una connessione Internet.

CONFIGURAZIONE JSONBIN
1. Crea una Access Key su jsonbin.io con permessi adeguati per creare, leggere e aggiornare i bin.
2. Inserisci la chiave nell'app e seleziona “Salva configurazione”.
3. Lascia Bin ID vuoto e seleziona “Sincronizza ora” per creare un bin privato; l'ID sarà compilato automaticamente. Per le modifiche successive, la sincronizzazione avviene automaticamente.
4. Per passare a un altro dispositivo, pubblica/apri l'app, inserisci la stessa chiave e Bin ID e seleziona “Carica da JSONBin”. Il caricamento sostituisce i dati locali.

La chiave è conservata nel localStorage del browser. Una chiave usata nel frontend può essere letta da chi ha accesso a quel browser: crea una Access Key dedicata con i soli permessi necessari e non usare la Master Key.

INSTALLAZIONE PWA
Pubblica tutti i file di questa cartella su un hosting HTTPS (oppure avvia un server locale su localhost). La PWA non si installa aprendo index.html direttamente come file. Il pulsante “Installa app” appare quando il browser comunica che l'installazione è disponibile e resta nascosto nell'app già installata. Su alcuni browser l'installazione è disponibile dal menu del browser anche senza pulsante.
