ENERGIA PRO+ — ISTRUZIONI

Apri index.html per l'uso locale. In questo modo le bollette restano nel localStorage del browser; il backup JSONBin richiede una connessione Internet.

CONFIGURAZIONE JSONBIN
1. Crea una Access Key su jsonbin.io con permessi adeguati per creare, leggere e aggiornare i bin.
2. Inserisci la chiave nell'app e seleziona “Salva configurazione”.
3. Sul primo dispositivo lascia Bin ID vuoto, salva la configurazione e seleziona “Sincronizza ora” per creare un bin privato. L'ID viene mostrato e salvato automaticamente.
4. Sugli altri dispositivi apri l'app, inserisci la stessa Access Key e il Bin ID creato al punto 3 e salva la configurazione. L'app caricherà automaticamente i dati condivisi all'apertura; puoi anche aggiornarli con “Carica da JSONBin”.
5. Dopo aver configurato la chiave e il Bin ID, ogni aggiunta, modifica o eliminazione aggiorna automaticamente il bin. Le credenziali vanno inserite una volta in ogni browser/dispositivo. Per vedere su un dispositivo le modifiche inviate da un altro, ricarica i dati con “Carica da JSONBin” o riapri l'app.

La chiave è conservata nel localStorage del browser. Una chiave usata nel frontend può essere letta da chi ha accesso a quel browser: crea una Access Key dedicata con i soli permessi necessari e non usare la Master Key.

INSTALLAZIONE PWA
Pubblica tutti i file di questa cartella su un hosting HTTPS (oppure avvia un server locale su localhost). La PWA non si installa aprendo index.html direttamente come file. Il pulsante di installazione avvia il prompt quando il browser lo supporta; altrimenti mostra le istruzioni per installare dal menu del browser. Il pulsante resta nascosto nell'app già installata.

AGGIORNAMENTI
Quando viene pubblicata una nuova versione, l'app mostra “È disponibile una nuova versione di Energia PRO+”. Seleziona “Aggiorna app” per attivarla e ricaricare la pagina. Il controllo avviene all'apertura dell'app e quando si torna alla scheda.
