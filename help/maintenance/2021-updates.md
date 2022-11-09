---
title: Aggiornamenti di manutenzione di Workfront per il 2021
description: Cronologia degli aggiornamenti di manutenzione del 2021 per [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
source-git-commit: 65b26c28f83d32aa44e23ca5820bb9a8d8267935
workflow-type: ht
source-wordcount: '10019'
ht-degree: 100%

---

# Aggiornamenti di manutenzione di [!DNL Workfront] per il 2021

Nel 2021 sono stati effettuati gli aggiornamenti di manutenzione seguenti:

## Aggiornamenti di dicembre 2021

+++**Aggiornamento di manutenzione del 23 dicembre 2021**

**Le nuove attività sono impostate su un vincolo attività predefinito non corretto**

_Attività_

Quando un utente crea una nuova attività tramite il pulsante “[!UICONTROL Nuova attività]” e l’opzione [!UICONTROL Nuovi valori predefiniti attività - Data di inizio] è impostata su “[!UICONTROL Oggi]”, il parametro relativo al vincolo attività è configurato su “[!UICONTROL Più presto possibile]” e non su “[!UICONTROL Iniziare non prima di]”. Ciò può verificarsi anche quando si utilizzano i modelli di progetto.

**L’apertura di un programma nella sezione [!UICONTROL Gruppi] comporta la visualizzazione di una pagina vuota**

_Configura_

Quando un utente visualizza i gruppi nella sezione [!UICONTROL Configurazione] e tenta di aprire, modificare o copiare un programma, l’operazione ha esito negativo e viene visualizzata una pagina vuota.

**Le modifiche non vengono visualizzate quando si riordina il pannello di navigazione a sinistra**

_Navigazione_

Quando un utente trascina un elemento nel tentativo di riordinare il pannello di navigazione a sinistra, al momento del rilascio l’elemento torna nella posizione precedente. Quando l’utente aggiorna la pagina, il pannello a sinistra mostra il nuovo ordine.

**Il collegamento per inviare un documento richiesto conduce a una pagina vuota.**

_Documenti_

Quando un utente riceve una richiesta di invio di un documento e fa clic sul collegamento all’oggetto in cui è stato richiesto il documento, il collegamento conduce a una pagina vuota. Ciò può verificarsi quando si fa clic su un collegamento all’interno di un’e-mail o una notifica in-app.

**[!UICONTROL Il Bilanciatore dei carichi di lavoro] mostra 0 ore assegnate**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente visualizza il [!UICONTROL Bilanciatore dei carichi di lavoro] e l’impostazione “[!UICONTROL Mostra date previste]” è abilitata, tutte le date future visualizzano 0 ore assegnate.

**Le bozze scompaiono a intermittenza dalle cartelle**

_[!DNL Workfront Proof]_

Quando un utente effettua l’accesso a [!DNL Workfront Proof] e visualizza una cartella, questa appare vuota. Se l’utente ricontrolla in un secondo momento, le bozze sono visibili.

+++

+++**Aggiornamento di manutenzione del 16 dicembre 2021**

**Facendo clic su un annuncio nell’elenco delle notifiche viene visualizzata una pagina vuota**

_Notifiche_

Quando un utente apre l’elenco delle notifiche tramite l’icona [!UICONTROL Notifiche] e fa clic su un annuncio, viene visualizzata una pagina vuota.

**Il pannello di riepilogo mostra il messaggio “[!UICONTROL Nessuna selezione]” quando l’attività è selezionata**

_Attività_

Quando un utente apre il riepilogo di un documento nella sezione [!UICONTROL Documenti] di un progetto, seleziona un’attività dal relativo elenco e tenta di visualizzarne il riepilogo, l’operazione ha esito negativo e viene visualizzato il messaggio seguente:

[!UICONTROL Nessuna selezione. Selezionare un documento nell&#39;elenco per visualizzare i dettagli.]

Il messaggio fa riferimento ai documenti anche se l’utente si trova nell’elenco delle attività.

**[!UICONTROL Lavoro non assegnato] non si carica**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente crea un filtro all’interno del [!UICONTROL Bilanciatore dei carichi di lavoro] utilizzando il campo [!UICONTROL Assegnazione:ID ruolo], la sezione [!UICONTROL Lavoro non assegnato] non si carica.

**Quando si allega un modello tramite l’opzione “[!UICONTROL Personalizza e allega]” i valori dei campi personalizzati si cancellano**

_Progetti_

Se un utente allega un modello a un progetto utilizzando l’opzione “[!UICONTROL Personalizza e allega]” e al progetto è già associato un modulo personalizzato, i valori dei campi personalizzati non vengono riportati e devono essere immessi manualmente. Ciò si verifica anche quando il modello include lo stesso modulo personalizzato.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 10 dicembre 2021**

**[!UICONTROL Errore] durante l’associazione di un modello a un progetto esistente**

_Progetti_

Quando un utente tenta di allegare un modello a un progetto esistente, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

+++

+++**Aggiornamento di manutenzione del 9 dicembre 2021**


**Il pannello di navigazione a sinistra compresso si espande al caricamento della pagina**

_Navigazione_

Quando un utente imposta la visualizzazione compressa del pannello di navigazione a sinistra e successivamente aggiorna la pagina, il pannello di navigazione si espande nella pagina ricaricata. Il pannello di navigazione sinistro si espande anche quando l’utente apre una pagina in una nuova scheda.

**[!UICONTROL Il Bilanciatore dei carichi di lavoro] mostra 0 ore assegnate**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente visualizza il [!UICONTROL Bilanciatore dei carichi di lavoro] e l’impostazione “[!UICONTROL Mostra date previste]” è abilitata, tutte le date future visualizzano 0 ore assegnate.

+++

+++**Aggiornamento di manutenzione dell’8 dicembre 2021**

**L’approvazione si ripristina dopo aver effettuato un aggiornamento**

_Approvazioni_

Se un utente prende una decisione su un’approvazione utilizzando l’intestazione dell’oggetto e immediatamente dopo aggiorna l’oggetto, le icone di approvazione vengono nuovamente visualizzate nell’intestazione e la decisione di approvazione non viene salvata.

**[!UICONTROL Impossibile eseguire la modifica in linea di un’assegnazione in un report]**

_Report_

Quando un utente tenta di eseguire una modifica in linea di un’assegnazione in un report, il valore del campo non cambia e la modifica non viene salvata.


+++

+++**Aggiornamento di manutenzione del 2 dicembre 2021**

**Aggiunta di una barra durante la digitazione manuale dell’URL**

_Richieste_

Quando un utente compila una richiesta e inizia a digitare manualmente un URL, viene aggiunta una barra vicino alla parte iniziale dell’URL. L’utente non può eliminare la barra.

**Non è possibile rimuovere le sezioni personalizzate dal pannello di navigazione a sinistra**

_Navigazione_

Quando un utente tenta di rimuovere una sezione personalizzata dal pannello di navigazione a sinistra facendo clic sulla X accanto alla sezione, l’operazione ha esito negativo.

**Lavoro non assegnato non si carica**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente crea un filtro all’interno del [!UICONTROL Bilanciatore dei carichi di lavoro] utilizzando il campo [!UICONTROL Assegnazione:ID ruolo], la sezione [!UICONTROL Lavoro non assegnato] non si carica.

**Impossibile caricare le pagine in determinati browser**

_[!DNL Workfront]_

Quando un utente lavora in [!DNL Workfront], le pagine non si caricano e l’utente visualizza il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

Questo problema è stato segnalato in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Questo errore si verifica in modo casuale e può influenzare qualsiasi area di [!DNL Workfront].

+++


## Aggiornamenti di novembre 2021

+++**Aggiornamento di manutenzione del 18 novembre 2021**

**[!DNL Workfront]per [!DNL Jira]: errore “[!UICONTROL clientID o clientSecret non valido]” al momento dell’accesso**

_Integrazioni di Workfront_

Gli utenti sono stati disconnessi dall’integrazione [!DNL Jira] per Workfront. Quando un utente tenta di accedere all’integrazione [!DNL Workfront for Jira], l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL clientID o clientSecret non valido]”

**Il modulo personalizzato allegato alla richiesta non si aggiorna durante la selezione di un nuovo Argomento coda**

_Richieste_

Quando un utente crea una richiesta, seleziona un Argomento coda che allega automaticamente un modulo personalizzato alla richiesta e successivamente seleziona un Argomento coda diverso, il modulo personalizzato del primo Argomento coda rimane allegato alla richiesta.

**Le icone non vengono visualizzate correttamente**

_[!DNL Workfront]_

Le immagini delle icone non vengono visualizzate correttamente. Questo problema è stato segnalato in molte sezioni di [!UICONTROL Workfront].

**Le attività non vengono esportate in formato PDF quando si seleziona l’opzione “Altre dimensioni’.**

_Attività_

Quando un utente tenta di esportare un elenco di attività in formato PDF utilizzando l’opzione “[!UICONTROL Altre dimensioni]”, può selezionare una dimensione e fare clic su [!UICONTROL Esporta], ma l’elenco non viene esportato. Non viene visualizzato alcun messaggio di errore o indicazione che comunichi la mancata esportazione.

**L’indicatore dell’immagine non viene visualizzato nelle notifiche e-mail**

_Notifiche_

Quando un utente aggiunge un’immagine a un aggiornamento, il destinatario dell’aggiornamento riceve una notifica e-mail. Tale notifica non include un indicatore della presenza di un’immagine nell’aggiornamento.

**Impossibile caricare le pagine in determinati browser**

_[!DNL Workfront]_

Quando un utente lavora in [!DNL Workfront], le pagine non si caricano e l’utente visualizza il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

Questo problema è stato segnalato in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Questo errore si verifica in modo casuale e può influenzare qualsiasi area di Workfront.

+++

+++**Aggiornamento di manutenzione dell’11 novembre 2021**

**Problema con le integrazioni dei documenti: visualizzazione di una pagina vuota nel popup di caricamento del documento da[!DNL Google Drive*]*

_Documenti_

Quando un utente tenta di aggiungere un nuovo documento a [!DNL Workfront] da [!DNL Google Drive] tramite [!UICONTROL Aggiungi nuovo] > [!UICONTROL Da [!DNL Google Drive]], la schermata popup di caricamento rimane vuota.

**Impossibile utilizzare più di un filtro nel Bilanciatore dei carichi di lavoro**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di utilizzare più di un filtro nel [!UICONTROL Bilanciatore dei carichi di lavoro], riscontra i problemi seguenti:

* Se seleziona due filtri, viene applicato solo il filtro inferiore.
* Se seleziona più di due filtri, non viene visualizzato alcun risultato.

**Non è presente alcuna intestazione del documento “[!UICONTROL Cartelle di progetto]” nell’area relativa ai documenti del progetto**

_Progetti_

Quando un utente si trova all’interno di un progetto e visualizza i relativi documenti, l’intestazione “[!UICONTROL Cartelle di progetto]” non è visibile nel menu di navigazione a sinistra. La freccia a discesa è ancora presente e l’utente può selezionare una cartella.

**Le colonne sulla bacheca Kanban sono troppo grandi e non è possibile regolarle**

_Agile_

Quando un utente visualizza una bacheca Kanban contenente più colonne e queste colonne sono troppo larghe, l’utente deve scorrere per visualizzarle oppure deve spostare le schede nelle colonne più a destra. La larghezza delle colonne non è regolabile, pertanto l’utente non può rimpicciolirle in modo da visualizzarle contemporaneamente sullo schermo.

**È stata migliorata l’interfaccia per la creazione di un nuovo team**

_Team_

La creazione di team è ora più intuitiva grazie ai nuovi suggerimenti visivi. Quando selezioni l’icona [!UICONTROL Cambia team] su una pagina del team, il collegamento [!UICONTROL Crea nuovo team] presenta un’icona per indicare “[!UICONTROL nuovo]” e appare separato dal resto dell’elenco, in modo da distinguerlo rispetto a un nome del team. Questa interfaccia è la stessa per i team Agile e non Agile.

+++

+++**Aggiornamento di manutenzione del 4 novembre 2021**

**Le nuove attività sono impostate su un vincolo attività predefinito non corretto**

_Attività_

Quando un utente crea una nuova attività tramite il pulsante “[!UICONTROL Nuova attività]” e l’opzione Nuovi valori predefiniti attività - Data di inizio è impostata su “[!UICONTROL Oggi]”, il parametro relativo al vincolo attività è configurato su “[!UICONTROL Più presto possibile]” e non su “[!UICONTROL Iniziare non prima di]”.

**I campi non vengono visualizzati nelle schede delle bacheche delle storie di Agile**

_Agile_

Quando un utente visualizza una bacheca delle storie di Agile, le relative schede mostrano solo i campi [!UICONTROL Descrizione] e [!UICONTROL Stato]. Tutti gli altri campi, compresi quelli personalizzati, non vengono visualizzati.

**Le schede tornano alla colonna originale prima di passare alla nuova colonna**

_Agile_

L’utente può visualizzare una scheda durante il suo trascinamento in una nuova colonna della bacheca delle storie. Quando rilascia la scheda nella nuova colonna, tuttavia, questa appare brevemente nella colonna originale prima di essere visualizzata nella nuova colonna.

**Valori non disponibili per il campo personalizzato nel filtro**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di creare un filtro utilizzando un campo personalizzato, il valore del campo personalizzato non viene visualizzato e non può essere inserito nel filtro.

**Impossibile caricare le pagine nel [!DNL Firefox] browser**

_[!DNL Workfront]_

Quando un utente lavora in [!DNL Workfront] utilizzando un browser [!DNL Firefox], le pagine non si caricano e si visualizza il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

Questo errore si verifica in modo casuale e può influenzare qualsiasi area di [!DNL Workfront].

**Errore relativo alla data durante la creazione di un progetto a partire da un modello.**

_Modelli_

Quando un utente crea un progetto a partire da un modello, imposta la modalità di pianificazione su [!UICONTROL Data di inizio] e seleziona un vincolo attività, l’operazione ha esito negativo e viene visualizzato un messaggio di errore in base al vincolo attività.

La finestra di dialogo **[!UICONTROL Esporta diagramma di Gantt] non risponde**

_Diagramma di Gantt_

Quando un utente nella nuova esperienza di [!DNL Workfront] tenta di esportare il [!UICONTROL Diagramma di Gantt] selezionando l’opzione “[!UICONTROL Quello che vedo]”, l’esportazione del [!UICONTROL Diagramma di Gantt] ha esito negativo e la finestra di dialogo non risponde. L’utente non è in grado di chiudere o uscire dalla finestra di dialogo.

**Le icone non vengono visualizzate correttamente**

_[!DNL Workfront]_

Le immagini delle icone non vengono visualizzate correttamente. Questo problema è stato segnalato in alcune situazioni, tra cui:

* Immagini per mansioni o gruppi di lavoro durante la condivisione di un oggetto
* Icone a sinistra e a destra nei report calendario
* Icone di ordinamento nelle colonne dei report

**Sono state aggiunte delle caselle di controllo alle richieste nella sezione [!UICONTROL Inviato] dell’area [!UICONTROL Richieste]**

_Richieste_

Sono state aggiunte delle caselle di controllo a sinistra dei nomi delle richieste nell’elenco [!UICONTROL Inviato] dell’area [!UICONTROL Richieste]. In questo modo è più facile selezionare una richiesta e visualizzare le informazioni aggiuntive.

**I filtri del Bilanciatore dei carichi di lavoro supportano ora i trimestri personalizzati**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

I filtri del [!UICONTROL Bilanciatore dei carichi di lavoro] ora supportano i trimestri personalizzati.

**È stato aggiornato l’operatore di filtro per il campo Durata nei filtri del Bilanciatore dei carichi di lavoro**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Sono stati aggiornati gli operatori di filtro quando si filtrano le aree del [!UICONTROL Bilanciatore dei carichi di lavoro] in base alla [!UICONTROL Durata].

+++


## Aggiornamenti di ottobre 2021

+++**Aggiornamento di manutenzione del 28 ottobre 2021**

**[!UICONTROL Home] e [!UICONTROL Il mio lavoro] restituiscono una pagina vuota**

_[!UICONTROL Home] / [!UICONTROL Il mio lavoro]_

L’utente visualizza una pagina vuota quando passa a [!UICONTROL Home] o Il mio lavoro.

**Impossibile visualizzare o modificare i dettagli del [!UICONTROL Gruppo di argomenti]**

_Richieste_

Quando un utente tenta di visualizzare o modificare i dettagli di un Gruppo di argomenti, la pagina visualizzata appare vuota ad eccezione di “[!UICONTROL Dettagli gruppo di argomenti]” presente nell’intestazione

**I pulsanti di scelta vuoti obbligatori vengono compilati automaticamente**

_Richieste_

Quando un utente invia una richiesta con un campo pulsante di scelta obbligatorio senza tuttavia scegliere un valore per tale campo, all’invio della richiesta viene selezionato automaticamente il primo valore.

+++

+++**Aggiornamento di manutenzione del 21 ottobre 2021**

**Impossibile aggiungere un filtro nel [!UICONTROL Bilanciatore dei carichi di lavoro]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di aggiungere un filtro nel [!UICONTROL Bilanciatore dei carichi di lavoro], si apre il pannello [!UICONTROL Aggiungi filtro] ma non viene visualizzato alcun contenuto al suo interno, rendendo impossibile l’aggiunta di un filtro.

**La bacheca Scrum di Agile non visualizza le storie**

_Agile_

Quando un utente tenta di visualizzare la bacheca Scrum nell’iterazione di un team, visualizza una pagina vuota.

**La bacheca delle storie Scrum è vuota quando si utilizzano i filtri**

_Agile_

Quando un utente tenta di visualizzare uno storyboard Scrum con qualsiasi filtro diverso da “[!UICONTROL Tutto il team]” viene mostrata una schermata vuota. L’utente non è in grado di tornare al filtro “[!UICONTROL Tutto il team]”.

**Gli elenchi sono visibili solo su una piccola area dello schermo**

_Elenchi_

Quando un utente tenta di visualizzare un elenco tramite un browser [!DNL Safari] su un [!DNL Mac] con [!DNL Big Sur OS], l’elenco appare solo su una piccola area dello schermo. L’utente può scorrere l’elenco, ma l’area potrebbe essere così piccola da renderne la lettura difficile o impossibile.

**I pulsanti di scelta vuoti obbligatori vengono compilati automaticamente**

_Richieste_

Quando un utente invia una richiesta con un campo pulsante di scelta obbligatorio senza tuttavia scegliere un valore per tale campo, all’invio della richiesta viene selezionato automaticamente il primo valore.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 21 ottobre 2021**

**[!UICONTROL Home] e [!UICONTROL Il mio lavoro] restituiscono una pagina vuota**

_[!UICONTROL Home] / [!UICONTROL Il mio lavoro]_

L’utente visualizza una pagina vuota quando passa a [!UICONTROL Home] o [!UICONTROL Il mio lavoro].

+++

+++**Aggiornamento di manutenzione del 20 ottobre 2021**

**[!UICONTROL Il Bilanciatore dei carichi di lavoro] è impostato come opzione di pianificazione predefinita**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente utilizza il [!UICONTROL Modulo di pianificazione] impostato come opzione predefinita, nota che il [!UICONTROL Bilanciatore dei carichi di lavoro] è stato impostato come predefinito.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 19 ottobre 2021**

**Impossibile assegnare una richiesta durante la sua creazione**

_Richieste_

Quando un utente crea una richiesta all’interno della nuova esperienza [!DNL Workfront] e tenta di assegnare un utente digitandone il nome nel campo [!UICONTROL Assegnazioni], il campo non visualizza l’elenco a discesa e l’utente non può selezionare il nome dell’assegnatario.

**La bacheca delle storie Scrum è vuota quando si utilizzano i filtri**

_Agile_

Quando un utente tenta di visualizzare uno storyboard Scrum con qualsiasi filtro diverso da “[!UICONTROL Tutto il team]” viene mostrata una schermata vuota. L’utente non è in grado di tornare al filtro “[!UICONTROL Tutto il team]”.

+++

+++**Aggiornamento di manutenzione del 14 ottobre 2021**

**I modelli condivisi a livello di sistema non sono visibili**

_Modelli_

Quando un utente crea un progetto e tenta di utilizzare un modello condiviso a livello di sistema, non riesce a visualizzarlo nell’elenco dei modelli disponibili e quindi non può utilizzarlo.

**Errore durante la creazione di progetti a partire da modelli**

_Modelli_

Quando un utente tenta di creare un progetto a partire da un modello che include un modulo personalizzato con una sezione visibile solo agli amministratori, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Categoria con valore/i di chiave primaria “xxxxxxxxxxxxxxxx” non trovata]”

**Sono stati aggiornati i collegamenti per copiare e spostare le attività**

_Attività_

I collegamenti per copiare e spostare le attività sono stati aggiornati con “[!UICONTROL Copia in]” e “[!UICONTROL Sposta in]” nella pagina e nell’elenco delle attività.

**Rimuovere il limite alla ricerca di mansioni quando si esegue l’override delle tariffe di fatturazione per un progetto**

Ruoli

NOTA: questo aggiornamento è attualmente disponibile nell’ambiente di anteprima e sarà pronto per la produzione con la versione 22.1. Per ulteriori informazioni, vedi “Panoramica della versione 22.1”.

L’override delle tariffe di fatturazione per le mansioni all’interno di un progetto effettua ora la ricerca tra tutti i ruoli nel sistema.

In precedenza, [!DNL Workfront] effettuava la ricerca di ruoli in ordine alfabetico tra i primi 2.000.

+++

+++**Aggiornamento di manutenzione del 7 ottobre 2021**

**[!UICONTROL Le notifiche in-app non sono più visibili nel] centro notifiche**

_Notifiche_

Alcune notifiche non sono più disponibili quando l’utente accede al centro notifiche. In alcuni casi, la notifica potrebbe scomparire prima che l’utente possa visualizzarla.

**Gli annunci non sono visibili nella pagina [!UICONTROL Tutti gli annunci]**

_Notifiche_

Quando un utente apre la pagina [!UICONTROL Tutti gli annunci] dalla sezione [!UICONTROL Notifiche] non sono visibili annunci nelle seguenti aree:

* [!UICONTROL Posta in arrivo]
* [!UICONTROL Preferiti]
* [!UICONTROL Bozze]
* [!UICONTROL Eliminato]

**Errore durante l’assegnazione di un lavoro nel [!UICONTROL Bilanciatore dei carichi di lavoro]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di effettuare un’assegnazione dal [!UICONTROL Bilanciatore dei carichi di lavoro], l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

+++


## Aggiornamenti di settembre 2021

+++**Aggiornamento di manutenzione del 30 settembre 2021**

**Errore durante l’accesso o l’uscita rapida dalla pagina [!UICONTROL Home]**

_Home_

Quando un utente accede o esce rapidamente dalla [!UICONTROL Home], la pagina non si carica e l’utente visualizza il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

Questo problema può verificarsi anche quando si accede alla [!UICONTROL Home] tramite un pin.

+++

+++**Aggiornamento di manutenzione del 23 settembre 2021**

**[!UICONTROL Accesso negato] durante la visualizzazione dei ticket inviati a[!DNL Workfront]**

_problemi_

Quando un utente tenta di visualizzare un ticket dopo averlo inviato a [!DNL Workfront] riceve il messaggio di errore seguente:

“[!UICONTROL Accesso negato: ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

**Il pannello di riepilogo Caso di business mostra valori errati**

_Progetti_

I valori visualizzati durante l’accesso di un utente al pannello di riepilogo [!UICONTROL Caso di business] non corrispondono a quelli presenti nelle singole sezioni di [!UICONTROL Caso di business].

**Le intestazioni di colonna non sono allineate con le colonne negli elenchi**

_Configura_

Quando un utente si trova nella sezione [!UICONTROL Configurazione] e visualizza un elenco, ad esempio [!UICONTROL Moduli personalizzati] o [!UICONTROL Livelli di accesso], le intestazioni di colonna per tale elenco non sono allineate con le colonne dell’elenco.

**Gli utenti che non dispongono delle autorizzazioni di condivisione appropriate possono allegare i moduli personalizzati agli oggetti**

_Moduli personalizzati_

Tutti gli utenti possono allegare un modulo personalizzato a un oggetto se tale modulo è impostato per essere visibile a livello di sistema all’interno della nuova esperienza [!DNL Adobe Workfront]. Gli utenti, tuttavia, dovrebbero solo essere in grado di visualizzare il modulo personalizzato e non di allegarlo a un oggetto, a meno che non sia stato condiviso specificatamente con loro.

+++

+++**Aggiornamento di manutenzione del 16 settembre 2021**

**Impossibile modificare i gruppi**

_Gruppi_

Quando un utente tenta di modificare o eliminare un gruppo, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Riproviamo. Gruppo con valore/i di chiave primaria “ID gruppo” non trovato]”.

**[!UICONTROL Ottimizzatore portfolio] non visualizza i progetti**

_Portfolio_

Quando un utente tenta di visualizzare i progetti in [!UICONTROL Ottimizzatore portfolio] non viene visualizzato alcun elenco, rendendo impossibile l’interazione con i progetti.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 10 settembre 2021**

**Data e ora sono contrassegnate in formato UTC durante la modifica in linea**

_Elenchi_

Quando un utente esegue la modifica in linea di una data o di un orario (in un elenco di oggetti), la data e l’ora sono contrassegnate in formato UTC. La data e l’ora non sono impostate in formato UTC in [!DNL Workfront]. Il problema riguarda solo la visualizzazione di questi parametri, non i dati effettivi.

**Il colore del testo non viene visualizzato correttamente durante l’applicazione della formattazione condizionale**

_Report_

Quando un utente visualizza un report con una formattazione condizionale che modifica il colore del testo, quest’ultimo rimane inalterato.

+++

+++**Aggiornamento di manutenzione del 9 settembre 2021**

**I dettagli dei problemi non vengono visualizzati nella sezione Problemi**

_Home_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente seleziona un problema da [!UICONTROL Elenco lavori], l’anteprima nel pannello a destra mostra alcuni campi senza valori immessi. Tuttavia, se l’utente passa al problema e visualizza la scheda [!UICONTROL Dettagli problema], in questi campi sono presenti i valori immessi.

**Gli utenti devono disporre delle autorizzazioni Contribute per visualizzare la sezione [!UICONTROL Approvazioni] nella nuova esperienza Workfront**

_Approvazioni_

Gli utenti devono disporre delle autorizzazioni [!UICONTROL Contribute] relative a un determinato oggetto per visualizzare la sezione [!UICONTROL Approvazioni] nella nuova esperienza [!DNL Workfront]. Dovrebbero essere necessarie soltanto le autorizzazioni [!UICONTROL Visualizzazione] per visualizzare la scheda [!UICONTROL Approvazioni] quando è in corso un processo di approvazione sull’oggetto.

**[!UICONTROL Errore] durante l’utilizzo dei filtri**

_Elenchi_

Quando un utente tenta di utilizzare uno dei filtri seguenti:

* [!UICONTROL Tutti i progetti]
* [!UICONTROL Progetti ai quali collaboro]
* [!UICONTROL Le Mie Attività Correnti]

l’elenco diventa vuoto e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Riproviamo.]”

**[!UICONTROL La sezione Attività] rimane vuota durante la modifica in linea**

_Modelli_

Quando un utente tenta effettuare la modifica in linea delle attività all’interno di un modello utilizzando una visualizzazione che include il campo “[!UICONTROL Assegna a: Nome]” e l’assegnazione contiene un utente, la sezione [!UICONTROL Attività] è vuota e l’utente non è in grado di modificare le attività del modello.

**Impossibile esportare [!UICONTROL Ottimizzatore portfolio]**

_Portfolio_

Quando un utente tenta di esportare [!UICONTROL Ottimizzatore portfolio] facendo clic su una delle opzioni di esportazione, l’operazione in [!UICONTROL Ottimizzatore portfolio] ha esito negativo.

**Non vengono inviate notifiche relative alle risposte**

_Notifiche_

Quando un utente risponde a un aggiornamento in [!DNL Workfront], gli altri utenti del thread di commenti non ricevono le relative notifiche.

**Le modifiche ai dati personalizzati causano ritardi**

_Campi personalizzati_

Quando un utente modifica i dati personalizzati, influenzando così gli altri dati visualizzati, le modifiche si caricano lentamente.

**L’icona “[!UICONTROL Comprimi o espandi tutto]” non viene visualizzata in caso di raggruppamento**

_Reporting_

L’icona “[!UICONTROL Comprimi o espandi tutto]” non viene visualizzata nell’intestazione di un elenco o di un report quando si applicano i raggruppamenti a tali elementi.

**[!UICONTROL Seleziona] e [!UICONTROL Annulla] non sono visibili durante la modifica delle allocazioni di un’attività**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di modificare l’allocazione di un’attività e l’intervallo di tempo di tale attività si estende fino o oltre il bordo della pagina visibile, i pulsanti [!UICONTROL Seleziona] e [!UICONTROL Annulla] non sono visibili, di conseguenza l’utente non può salvare o annullare le modifiche di allocazione.

**L’aggiunta di un campo personalizzato alla [!UICONTROL Home] causa la perdita di dati nel campo**

_[!UICONTROL Home]_

Quando un campo personalizzato viene aggiunto alla pagina [!UICONTROL Home], gli altri campi vengono visualizzati in modo errato a causa della perdita di dati al loro interno.

**Impossibile visualizzare gli elementi collegati quando si accede come altro utente**

_Integrazioni_

Quando un amministratore tenta di visualizzare gli elementi collegati effettuando l’accesso come altro utente da un provider esterno, non è in grado di aprire le cartelle collegate e visualizzare gli elementi al loro interno.

+++

+++**Aggiornamento di manutenzione del 2 settembre 2021**

**Impossibile fissare il dashboard personalizzato**

_Dashboard_

Quando un utente tenta di fissare un dashboard personalizzato, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore durante l’operazione di fissaggio. Contatta [!DNL Workfront] per risolvere il problema]”.

**[!DNL Workfront Proof]: il riepilogo di stampa è vuoto**

[!DNL Workfront Proof]

Quando un utente apre il riepilogo di stampa per stampare una bozza, l’intestazione viene visualizzata correttamente ma il riepilogo è vuoto.

+++


## Aggiornamenti di agosto 2021

+++**Aggiornamento di manutenzione del 26 agosto 2021**

**In [!DNL Safari] è presente uno sfondo grigio scuro nel testo delle intestazioni di colonna**

_Elenchi_

Nel browser [!DNL Safari] è presente uno sfondo grigio scuro sulle intestazioni di colonna, in modo da evidenziare il testo. Questo problema non si verifica con altri browser supportati.

**Errore imprevisto durante la configurazione delle attività predecessore**

_Attività_

Quando un utente tenta di impostare un’attività predecessore utilizzando la modifica in linea, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore inatteso]”

+++

+++**Aggiornamento di manutenzione del 19 agosto 2021**

**Filtri salvati mancanti dopo aver selezionato un filtro che non mostra problemi**

_Elenchi_

I filtri salvati non sono presenti in un elenco di problemi dopo aver selezionato un filtro che non mostra risultati.

**I dettagli dei problemi non vengono visualizzati nella sezione Problemi**

_[!UICONTROL Riepilogo Home]_

In [!DNL Adobe Workfront Classic], quando un utente seleziona un problema da [!UICONTROL Elenco lavori], l’anteprima nel pannello a destra mostra alcuni campi senza valori immessi. Tuttavia, se l’utente passa al problema e visualizza la scheda [!UICONTROL Dettagli problema], in questi campi sono presenti i valori immessi.

+++

+++**Aggiornamento di manutenzione del 12 agosto 2021**

**Impossibile personalizzare la visualizzazione agile di un progetto**

_Agile_

Quando un utente tenta di personalizzare una visualizzazione agile già esistente in un progetto, la finestra si chiude e l’utente non è in grado di modificare la vista.

**Il nome non si aggiorna nelle nuove versioni di un documento**

_Documenti_

Quando un utente carica una nuova versione di un documento, il nome del documento non viene aggiornato in modo da corrispondere al nome della versione più recente.

**L’icona del predecessore non diventa verde dopo aver completato l’attività.**

_Attività_

Quando un’attività presenta un predecessore completo, la corrispondente icona nell’attività dipendente non diventa verde.

Tutti gli utenti possono allegare un modulo personalizzato a un oggetto se tale modulo è impostato per essere visibile a livello di sistema all’interno della nuova esperienza [!DNL Adobe Workfront]. Gli utenti, tuttavia, dovrebbero solo essere in grado di visualizzare il modulo personalizzato e non di allegarlo a un oggetto, a meno che non sia stato condiviso specificatamente con loro.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 6 agosto 2021**

**Impossibile selezionare i calendari nelle impostazioni del calendario di [!DNL Outloo]**

_Home_

All’interno della nuova esperienza [!DNL Workfront], quando un utente visualizza il proprio calendario di [!DNL Outlook] dalla Home e apre le impostazioni, le caselle di controllo destinate alla selezione dei calendari non sono presenti. Se l’utente fa clic sul punto in cui dovrebbe trovarsi la casella di controllo, il calendario risponde come se la casella di controllo fosse presente.

**Impossibile autorizzare nuovamente la connessione a [!UICONTROL Webdam]** o verificarla

_[!DNL Workfront Fusion]_

Gli utenti [!DNL Adobe Workfront Fusion] con scenari di connessione a [!UICONTROL Webdam] devono essere consapevoli del fatto che tali connessioni a [!UICONTROL Webdam] richiedono una nuova autenticazione manuale ogni 14 giorni. L’API [!UICONTROL Webdam] attualmente non supporta la riautorizzazione automatica.

+++

+++**Aggiornamento di manutenzione del 5 agosto 2021**

**Impossibile interagire con un documento nel [!UICONTROL pannello Riepilogo] o nel menu [!UICONTROL Altro]**

_Documenti_

Nella nuova esperienza di [!DNL Workfront], quando un utente visualizza un documento e tenta di effettuare una selezione nel [!UICONTROL pannello Riepilogo] o nel menu [!UICONTROL Altro], il documento viene deselezionato e il [!UICONTROL pannello Riepilogo] o il menu [!UICONTROL Altro] non viene visualizzato.

**[!UICONTROL Il pulsante Nuova richiesta] non viene visualizzato**

_Richieste_

Nella nuova esperienza di [!DNL Adobe Workfront], quando un utente accede alla pagina [!UICONTROL Richieste], il pulsante [!UICONTROL Nuova richiesta] non viene visualizzato e l’utente non è in grado di inviare una richiesta.

**Gli utenti che non dispongono delle autorizzazioni di condivisione appropriate possono allegare i moduli personalizzati agli oggetti**

_Moduli personalizzati_

Tutti gli utenti possono allegare un modulo personalizzato a un oggetto se tale modulo è impostato per essere visibile a livello di sistema all’interno della nuova esperienza [!DNL Adobe Workfront]. Gli utenti, tuttavia, dovrebbero solo essere in grado di visualizzare il modulo personalizzato e non di allegarlo a un oggetto, a meno che non sia stato condiviso specificatamente con loro.

**Impossibile modificare le impostazioni della bozza quando si crea una nuova bozza**

_[!DNL Workfront Proof]_

Quando un utente crea una nuova bozza e tenta di modificare le impostazioni, queste tornano a un’impostazione precedente.

**[!UICONTROL La bacheca delle storie] non si carica correttamente**

_Agile_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente passa a una [!UICONTROL Storyboard], il caricamento della bacheca può richiedere fino a 10 secondi. Il ritardo è dovuto al fatto che il sistema carica tutte le schede, mentre dovrebbe caricarne solo 50 alla volta.

+++


## Aggiornamenti di luglio 2021

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 29 luglio 2021**

**Impossibile caricare una nuova bozza o una nuova versione della bozza**

_[!DNL Workfront Proof]_

Quando un utente tenta di caricare una nuova bozza o una nuova versione della bozza nell’esperienza [!DNL Workfront] classica, la nuova pagina non viene visualizzata, rendendo impossibile caricare la bozza o la versione.

+++

+++**Aggiornamento di manutenzione del 29 luglio 2021**

Le pagine **[!UICONTROL Attività bozza] e [!UICONTROL Impostazioni visualizzatore bozza] sono sempre disponibili**

_[!DNL Workfront Proof]_

Le pagine [!UICONTROL Attività bozza] e [!UICONTROL Impostazioni visualizzatore bozza] sono sempre visibili, anche se l’utente non è autorizzato ad accedere per aggiornare tali pagine.

In precedenza, quando un utente con un profilo di autorizzazione di bozza personalizzato passava a un documento, le pagine [!UICONTROL Attività bozza] e [!UICONTROL Impostazioni visualizzatore bozza] a sinistra non erano sempre visibili.

**Messaggio di errore durante l’utilizzo dell’opzione [!UICONTROL Percentuale] per [!UICONTROL Ore allocate]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente seleziona l’opzione [!UICONTROL Percentuale] per [!UICONTROL Ore allocate] ed è presente un lavoro elencato nella sezione [!UICONTROL Lavoro non assegnato], viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

+++

+++**Aggiornamento di manutenzione del 22 luglio 2021**

**I nomi delle nuove versioni delle bozze risultano tagliati**

_[!DNL Workfront Proof]_

Quando un utente in [!DNL Adobe Workfront Classic] carica una nuova versione di una bozza con un punto nel nome del file, la parte finale del nome viene tagliata.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 19 luglio 2021**

**Errore durante l’accesso a progetti, schede orario, attività o programmi**

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente tenta di accedere a progetti, schede orario, attività o programmi, visualizza il messaggio di errore “[!UICONTROL Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

+++

+++**Aggiornamento di manutenzione del 15 luglio 2021**

**La priorità predefinita per le nuove richieste non è corretta**

_Richieste_

Quando utente crea una richiesta nella nuova esperienza [!DNL Adobe Workfront], la priorità assegnata a tale richiesta non corrisponde a quella impostata in [!UICONTROL Preferenze progetto] e non è possibile modificarla prima di inviare la richiesta.

**[!UICONTROL Vai alla bozza] non reindirizza al commento**

_Notifiche e-mail_

Quando un utente riceve una notifica e-mail relativa a un commento della bozza e fa clic su [!UICONTROL Vai alla bozza], il collegamento non funziona o l’utente viene reindirizzato verso un commento errato.

**I valori dei campi con formato Rich Text non vengono trasferiti dopo la conversione di un problema in un’attività**

_Moduli personalizzati_

Quando un utente converte un problema in un’attività e tale problema contiene un modulo personalizzato allegato con un valore inserito in un campo di testo con formato Rich Text, tale valore non viene trasferito dopo la conversione.

**I valori dei campi personalizzati si modificano dopo la selezione**

_[!DNL Workfront Proof]_

Quando un utente crea una nuova bozza nella nuova esperienza [!DNL Adobe Workfront] e immette un valore in alcuni campi personalizzati della bozza, il valore di alcuni campi precedenti viene ripristinato al valore predefinito e non a quello inserito dall’utente.

**[!UICONTROL Il campo di completamento automatico Assegna a] non funziona**

_[!UICONTROL Home]_

In [!DNL Adobe Workfront Classic], quando un utente crea un progetto, un’attività o una richiesta dalla sezione [!UICONTROL Home], il campo di completamento automatico [!UICONTROL Assegna a] non si popola con i nomi utente.

**Arrotondamento errato delle ore**

_Schede orario_

Nella nuova esperienza di [!DNL Adobe Workfront], quando un utente passa a [!UICONTROL Schede orario] > [!UICONTROL Tutte le schede orario], i numeri delle ore totali per alcune schede orario vengono arrotondati a una cifra decimale invece che a incrementi di 0,25 ma le ore totali vengono visualizzate correttamente nelle singole schede. Ad esempio, nell’area Tutte le schede orario, una scheda mostra un totale di 44,8 ore tuttavia quando si apre il totale ammonta a 44,75 ore.

**Impossibile delegare le approvazioni**

_[!UICONTROL Home]_

In [!DNL Adobe Workfront Classic], quando un utente fa clic su [!UICONTROL Tutte le schede orario] nell’area [!UICONTROL Home] e inizia a digitare il nome dell’utente a cui delegare l’approvazione, nell’elenco di [!UICONTROL completamento automatico] non viene visualizzato alcun risultato, rendendo impossibile selezionare un utente.

**[!UICONTROL La vista Grafico di Gantt] non è disponibile per i report attività**

_Report_

NOTA: questo problema riguarda anche i report del progetto.

Quando un utente apre un report attività nella nuova esperienza [!DNL Adobe Workfront], l’opzione per selezionare una vista [!UICONTROL Grafico di Gantt] non è presente nella barra degli strumenti del report. Se la vista [!UICONTROL Grafico di Gantt] è selezionata come impostazione predefinita nel report, viene invece visualizzato un formato elenco.

**Facendo clic su [!UICONTROL Ulteriori informazioni] in un report non si caricano i vari elementi**

_Dashboard_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente visualizza un report su un dashboard e fa clic sul pulsante [!UICONTROL Ulteriori informazioni], non succede nulla e l’utente non è in grado di visualizzare tutti gli elementi del report.

+++

+++**[!DNL Adobe Workfront Fusion]- Aggiornamento di manutenzione del 1° luglio 2021**

**La copia dei moduli non funziona**

_[!DNL Adobe Workfront Fusion]_

Quando un utente seleziona più moduli e tenta di copiarli e incollarli, l’operazione ha esito negativo.

+++

+++**Aggiornamento di manutenzione del 1° luglio 2021**

**I colori impostati per le schede non vengono rispettati**

_Kanban_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente imposta colori specifici per le schede nelle impostazioni del team, tali colori non si riflettono sulle schede Kanban.

**Impossibile incollare il testo nel campo del messaggio personalizzato**

_[!DNL Workfront Proof]_

Quando un utente crea una nuova bozza nel [!UICONTROL visualizzatore bozze web] e tenta di incollare un testo da un’e-mail che si trova nel campo [!UICONTROL Messaggio] della sezione [!UICONTROL Notifica e-mail], non riesce a incollare il testo. Questo comportamento si verifica apparentemente solo quando il testo ha una formattazione di paragrafo ed è presente un’interruzione di paragrafo.

**Le richieste vengono inviate con i campi obbligatori vuoti**

_Richieste_

Quando un utente effettua una richiesta e la invia, le informazioni presenti nei campi obbligatori non vengono inviate con la richiesta.

**[!UICONTROL Il pulsante Nuova richiesta] non viene visualizzato**

_Richieste_

Nella nuova esperienza di [!DNL Adobe Workfront], quando un utente accede alla pagina [!UICONTROL Richieste], il pulsante [!UICONTROL Nuova richiesta] non viene visualizzato e l’utente non può inviare una richiesta.

**Errore durante l’espansione di un modulo personalizzato**

_Progetti_

All’interno della nuova esperienza [!DNL Adobe Workfront], quando un utente tenta di espandere un modulo personalizzato allegato a un progetto, l’operazione ha esito negativo e viene visualizzato il messaggio di errore “[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova ad aggiornare la pagina del browser.]”. L’aggiornamento della pagina non risolve il problema.

**[!DNL Adobe Workfront]viene ora visualizzato nelle e-mail del centro annunci**

E-mail

Con l’introduzione del marchio [!DNL Adobe Workfront] in tutta l’applicazione, sono stati apportati i seguenti aggiornamenti alle e-mail del centro annunci:

* L’icona con il leone di [!DNL Adobe Workfront] è stata aggiunta all’area del contenuto principale.
* Il logo di [!DNL Adobe Workfront] è stato aggiunto al piè di pagina.

In futuro questo marchio verrà visualizzato su altri tipi di e-mail di Workfront.

+++


## Aggiornamenti di giugno 2021

+++**Aggiornamento di manutenzione del 24 giugno 2021**

**Impossibile modificare un team**

_Agile_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente fa clic su [!UICONTROL Modifica] per aprire la pagina [!DNL Edit] team per un team Agile, inizialmente la pagina si carica ma successivamente le impostazioni scompaiono e la pagina appare vuota.

**Dati rimossi dalla richiesta inviata**

_Richieste_

Nella nuova esperienza [!DNL Adobe Workfront], i valori precedentemente immessi in una richiesta non vengono più visualizzati dopo il suo invio, sia per quanto riguarda i campi personalizzati che i campi obbligatori.

**Le colonne non vengono visualizzate**

_Kanban_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente aggiunge una colonna [!UICONTROL Campi aggiuntivi] personalizzata su una bacheca Kanban, tutte le intestazioni di colonna non vengono più visualizzate sulla bacheca.

+++

+++**[!DNL Adobe Workfront Fusion]- Aggiornamento di manutenzione del 23 giugno 2021**

**Il collegamento interrotto è stato rimosso nelle e-mail di notifica**

_[!DNL Adobe Workfront Fusion]_

Il collegamento alle impostazioni di notifica è stato rimosso dalle e-mail di notifica di [!DNL Adobe Workfront Fusion].
Per informazioni sulla modifica delle impostazioni di notifica, vedi la sezione Organizzazioni e team di [!DNL Adobe Workfront Fusion].

+++

+++**Aggiornamento di manutenzione del 17 giugno 2021**

**[!UICONTROL La vista Grafico di Gantt] non è disponibile per i report attività**

_Report_

Quando un utente apre un report attività nella nuova esperienza [!DNL Adobe Workfront], l’opzione per selezionare una vista [!UICONTROL Grafico di Gantt] non è presente nella barra degli strumenti del report. Se la vista [!UICONTROL Grafico di Gantt] è selezionata come impostazione predefinita nel report, viene invece visualizzato un formato elenco.

**L’errore relativo al limite di caratteri non viene visualizzato durante l’invio di richieste**

_Richieste_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente tenta di inviare una richiesta e supera il limite di caratteri per un campo, l’operazione ha esito negativo ma non viene visualizzato alcun messaggio di errore. In [!DNL Adobe Workfront Classic], l’utente visualizza l’avviso “[!UICONTROL [number] caratteri superati” e quando tenta di inviare la richiesta riceve il messaggio di errore “Controllare i seguenti elementi: non immettere più di 2.000 caratteri. Hai inserito [number] caratteri.]”

+++

+++**Aggiornamento di manutenzione del 10 giugno 2021**

**Le attività modello riordinate non vengono spostate**

_Modelli_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente trascina un’attività modello in una nuova posizione all’interno di un elenco, il numero delle attività modello viene aggiornato ma non riordinato.

**Attività secondarie non selezionate con le attività padre**

_Modelli_

Quando un utente seleziona un’attività padre in un progetto creato da un modello, le attività secondarie non vengono selezionate automaticamente.

**La modifica in linea delle milestone in un elenco attività mostra tutte le milestone**

_Progetti_

Nella nuova esperienza di [!DNL Adobe Workfront], quando a un progetto è stato aggiunto un percorso milestone e un utente effettua una modifica in linea della colonna [!UICONTROL Milestone: Nome] nell’elenco attività, il menu a discesa mostra tutti i percorsi milestone e non soltanto quelli associati al progetto.

+++

+++**Aggiornamento di manutenzione del 3 giugno 2021**

**Il prompt provoca la visualizzazione errata della pagina**

_Report_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente esegue un report con un prompt, le colonne del report si spostano rapidamente da sinistra a destra.

**Alcune frasi della pagina [!UICONTROL Nuova bozza] non sono tradotte correttamente**

_[!DNL Workfront Proof]_

In [!DNL Workfront Proof], quando un utente passa alla pagina di creazione [!UICONTROL Nuova bozza] in una lingua diversa dall’inglese, alcune frasi rimangono in lingua inglese.

**Le etichette Disattivato ed Eliminato sono state aggiunte agli utenti di [!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Le etichette utente Disattivato] ed [!UICONTROL Eliminato] sono state aggiunte alle seguenti aree in [!DNL Workfront] Proof:

* Pagina [!UICONTROL Dettagli bozza]
* [!UICONTROL Viste bozza]
* [!UICONTROL Visualizzatore di bozze]
* [!UICONTROL Flussi di lavoro bozza]
* Pagina [!UICONTROL Stampa commenti]
* Pagina [!UICONTROL Utente]

+++


## Aggiornamenti di maggio 2021

+++**Aggiornamento di manutenzione del 27 maggio 2021**

**[!UICONTROL Conferma data] viene visualizzato automaticamente per gli aggiornamenti**

_Attività_

Nella nuova esperienza di [!DNL Adobe Workfront], quando un utente inserisce un aggiornamento in un’attività, il calendario [!UICONTROL Conferma data] viene visualizzato automaticamente, senza selezione del campo [!UICONTROL Conferma data] da parte dell’utente.

**[!UICONTROL Il menu Altro] non è presente in filtri, viste e raggruppamenti**

_Elenchi_

Nella nuova esperienza [!DNL Adobe Workfront], quando un utente visualizza i filtri, le viste o i raggruppamenti di un elenco, l’icona del menu [!UICONTROL Altro] non è presente, rendendo impossibile la condivisione o, in caso di accesso, la rimozione di questi elementi.

**Quando si copia e si incolla un [!UICONTROL Numero di riferimento] in un progetto viene aggiunta la parola “[!UICONTROL Questo]”**

_Progetti_

Nella nuova esperienza [!DNL Workfront], quando un utente passa a un progetto, copia il [!UICONTROL Numero di riferimento] dalla sezione [!UICONTROL Panoramica] e lo incolla, alla fine di tale numero viene aggiunta la parola “[!UICONTROL Questo]”.

**[!UICONTROL Le e-mail di Riepilogo giornaliero] vengono inviate anche quando la funzionalità è disabilitata**

_Notifiche e-mail_

Alcuni utenti ricevono le notifiche e-mail di [!UICONTROL Riepilogo giornaliero] anche se tale funzionalità non è stata abilitata nelle impostazioni utente.

**Errore L’oggetto non esiste più**

_Oggetti_

Nella nuova esperienza [!DNL Workfront], quando un utente tenta di aprire alcuni oggetti, visualizza il messaggio di errore “[!UICONTROL L’oggetto non esiste più. È possibile che l’indirizzo web sia stato digitato in modo errato. Controllare l’indirizzo e digitarlo di nuovo.]”. Il collegamento all’oggetto viene ancora visualizzato in elenchi, recenti, preferiti, risultati della ricerca e altro ancora, ma non è possibile accedervi e non viene visualizzato nel cestino con gli oggetti eliminati.



+++

+++**Aggiornamento di manutenzione del 20 maggio 2021**

**Opzioni di bozza mancanti**

_Bozze_

Quando un utente carica un’altra versione di una bozza in [!DNL Workfront], i collegamenti [!UICONTROL Apri bozza] e [!UICONTROL Flusso di lavoro bozza] non sono presenti, rendendo il file più simile a un documento che a una bozza. Quando mancano questi collegamenti, viene visualizzata anche l’etichetta [!UICONTROL In sospeso] e gli altri utenti non sono in grado di generare la bozza mentre si trova nello stato [!UICONTROL In sospeso].

**Gli utenti non ricevono i report pianificati per la consegna**

_Report_

Talvolta gli utenti non ricevono i report pianificati per la consegna.

**Impossibile rimuovere l’accesso per il modello di layout**

_Dashboard_

Quando un utente accede alle opzioni [!UICONTROL Condivisione] di un dashboard per rimuovere l’accesso a un modello di layout, accanto a tale modello non viene visualizzata alcuna icona [!UICONTROL Elimina], di conseguenza l’utente non è in grado di rimuovere l’accesso.

+++

+++**[!DNL Workfront Fusion]- Aggiornamento di manutenzione del 17 maggio 2021**

**Il dashboard Organizzazione ora visualizza correttamente il numero di scenari attivi**

_[!DNL Workfront Fusion]_

Il dashboard [!UICONTROL Organizzazione] mostrava in precedenza un campo vuoto anziché il numero di scenari utilizzati.

**La vista esplorazione dell’archivio dati ora mostra le etichette delle colonne**

_[!DNL Workfront Fusion]_

Le strutture di dati che utilizzavano le etichette di colonna mostravano in precedenza il nome della colonna nella vista [!UICONTROL esplorazione dell’archivio dati].  Ora viene visualizzata l’etichetta della colonna.  Se non viene identificata alcuna etichetta per la colonna, viene visualizzato il nome.

**L’errore relativo all’inizializzazione dello scenario non influisce più sui dati del webhook**

_[!DNL Workfront Fusion]_

In precedenza, la generazione di un errore durante l’inizializzazione di uno scenario avviato da un webhook, inclusi quelli che utilizzano eventi in tempo reale per l’attivazione, poteva comportare la perdita dell’accesso ai dati del webhook.  Ora, se si verifica un errore durante l’inizializzazione dello scenario, ad esempio l’impossibilità di verificare una connessione, i dati del webhook vengono mantenuti nella coda del webhook e si tenta automaticamente una nuova esecuzione.  Dopo tre tentativi falliti, lo scenario viene disattivato ma le informazioni rimangono nella coda.

**I record nelle code webhook vengono ora elaborati in batch più piccoli**

_[!DNL Workfront Fusion]_

In precedenza, se un utente attivava uno scenario inattivo a cui era associata una coda del webhook con molti record, [!DNL Workfront Fusion] tentava di elaborare l’intera coda in una singola esecuzione (con più cicli).  A seconda della quantità di record elaborati, talvolta ciò comportava il superamento del tempo massimo, ossia 40 minuti, per l’elaborazione della singola esecuzione.  Ora, quando si attiva uno scenario inattivo a cui è associata una coda del webhook con più record, Workfront Fusion elaborerà fino al numero massimo di record identificati in una singola esecuzione (in genere 2 record per esecuzione).

**Gli archivi dati ora visualizzano correttamente i valori pari a “0”**

_[!DNL Workfront Fusion]_

In precedenza, i valori dell’archivio dati pari a 0 venivano visualizzati come vuoti. &lt;...>

+++

+++**Aggiornamento di manutenzione del 13 maggio 2021**

**Il calendario a discesa viene visualizzato dietro l’intestazione [!UICONTROL Lavoro non assegnato]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente passa al [!UICONTROL Bilanciatore dei carichi di lavoro] in [!DNL Workfront Classic], la parte superiore del selettore data è nascosta dietro l’intestazione [!UICONTROL Lavoro non assegnato], impedendo all’utente di passare ad altri mesi.

**Impossibile incollare il testo nel campo del messaggio personalizzato**

_[!DNL Workfront Proof]_

Nota: apparentemente questo problema riguarda soltanto il browser web [!DNL Google Chrome] al momento.

Quando un utente crea una nuova bozza in [!DNL Workfront Proof] e tenta di incollare un testo da un’e-mail che si trova nel campo [!UICONTROL Messaggio] della sezione [!UICONTROL Notifica e-mail], non riesce a incollare il testo.

**Il generatore mostra campi non supportati**

_Moduli personalizzati_

Quando un utente genera un modulo personalizzato e tenta di creare un campo calcolato utilizzando un campo dinamico, ad esempio [!UICONTROL N. rischi aperti], la casella di calcolo viene evidenziata in rosso, non consentendo il salvataggio delle modifiche. I campi dinamici non devono essere visualizzati nel selettore per i campi calcolati.

**Impossibile caricare l’anteprima delle attività in [!UICONTROL Elenco lavori]**

_Home_

Nella nuova esperienza di [!DNL Workfront], quando un utente viene assegnato a un modello di layout che include campi personalizzati nell’area [!UICONTROL Home], la pagina non risponde e se l’utente seleziona un’attività dalla sezione [!UICONTROL Elenco lavori] la pagina non si carica.

**Gli oggetti nell’[!UICONTROL Elenco lavori] non vengono caricati nell’area [!UICONTROL Home]**

_[!UICONTROL Home]_

Quando un utente fa clic su un oggetto nella sezione [!UICONTROL Elenco lavori] dell’area Home, l’intestazione dell’oggetto viene visualizzata nel pannello di destra, ma i relativi dettagli non vengono mostrati. Alla fine l’utente visualizza un messaggio di tipo “[!UICONTROL Le pagine non rispondono]”.

**Problemi relativi ai campi in formato Rich text in[!DNL Microsoft Outlook]**

_Integrazioni di Workfront_

Quando un utente aggiorna un campo in formato Rich text con [!DNL Workfront for Outlook], non è in grado di eseguire le operazioni seguenti:

* Utilizzare il tasto Backspace
* Copiare il testo
* Incollare il testo
* Inviare una richiesta quando tutti i campi sono compilati

+++

+++**Aggiornamento di manutenzione del 6 maggio 2021**

**[!UICONTROL Il campo Valuta] non funziona come previsto**

_Elenchi_

Quando un utente tenta di modificare in linea il campo Valuta in un elenco, non può salvare le modifiche a causa dei problemi seguenti:

* Gli elenchi Attività e Problemi non consentono l’immissione di simboli di valuta
* Gli elenchi non consentono l’immissione di abbreviazioni di valuta quando si utilizza una lingua diversa dall’inglese
* Gli elenchi Attività secondaria e problemi consentono solo l’abbreviazione di valuta USD, indipendentemente dalla valuta impostata nel progetto

**Il nome non viene aggiornato per corrispondere al nuovo nome della bozza**

_Documenti_

Quando un utente crea una nuova versione di una bozza e aggiorna il nome della bozza, l’oggetto documento in [!DNL Workfront] mantiene il nome originale invece di corrispondere al nuovo nome della bozza.

**[!UICONTROL I pulsanti Caso di business] non funzionano quando si allegano moduli personalizzati**

_Progetti_

Nella nuova esperienza [!DNL Workfront], quando si crea un progetto a partire da un modello a cui è allegato un modulo personalizzato, gli utenti non sono in grado di inviare, rifiutare o approvare un caso di business.

**Visualizzazione delle bozze archiviate in elenchi e report**

_Bozze_

Quando un utente visualizza il proprio elenco di lavoro in [!UICONTROL Home] o [!UICONTROL Il mio lavoro], nella pagina vengono visualizzate le bozze che sono già state archiviate. Le bozze archiviate vengono visualizzate anche nei report e nei dashboard.

**I progetti creati da un modello presentano impostazioni di accesso errate**

_Progetti_

Quando un utente crea un progetto da un modello, le impostazioni di accesso del modello non vengono trasferite nel nuovo progetto creato.

**Gli oggetti nell’[!UICONTROL Elenco lavori] non vengono caricati nell’area [!UICONTROL Home]**

_[!UICONTROL Home]_

Quando un utente fa clic su un oggetto nella sezione [!UICONTROL Elenco lavori] dell’area Home, l’intestazione dell’oggetto viene visualizzata nel pannello di destra, ma i relativi dettagli non vengono mostrati. Alla fine l’utente visualizza un messaggio di tipo “[!UICONTROL Le pagine non rispondono]”.

+++


## Aggiornamenti di aprile 2021

+++**Aggiornamento di manutenzione del 29 aprile 2021**

L’integrazione di **[!DNL SharePoint] esegue l’autenticazione utilizzando le credenziali di un’integrazione separata**

_Integrazioni di Workfront_

Quando un utente dispone di più integrazioni di [!DNL SharePoint], un’autenticazione di [!DNL SharePoint] tenta di accedere utilizzando le credenziali di un’altra integrazione di [!DNL SharePoint].

**Impossibile caricare o esportare file dai [!DNL Adobe] prodotti**

_Integrazioni di Workfront_

Quando un utente tenta di caricare o esportare i file utilizzando l’integrazione di [!DNL Workfront for Adobe Creative Cloud], visualizza il messaggio di errore “[!UICONTROL Impossibile leggere la proprietà “stages” di undefined]” e l’operazione ha esito negativo.

**I file non sono visibili in [!DNL Internet Explorer]**

_Documenti_

Quando un utente con un browser [!DNL Internet Explorer] passa alla sezione [!UICONTROL Documenti] di un oggetto, la schermata [!UICONTROL Documenti] è vuota e non mostra i file. Alcuni utenti sono in grado di visualizzare solo determinati documenti, ma il numero di file visualizzati non corrisponde a quello riportato accanto alla sezione [!UICONTROL Documenti].

+++

+++**Aggiornamento di manutenzione del 22 aprile 2021**

**Attività aggiunte nell’ordine errato**

_Modelli_

Quando un utente aggiunge un’attività a un modello, l’attività non riceve il numero previsto e viene aggiunta in una posizione errata.

**Le bozze vengono ora combinate in un’unica e-mail**

_Bozze_

[!DNL Workfront] ora invia un’e-mail per le bozze combinate anziché inviare un’e-mail per ogni file incluso.
+++

+++**[!DNL Workfront Fusion]- Aggiornamento di manutenzione del 15 aprile 2021**

**Errore “[!UICONTROL Scenario rifiutato]” durante l’esecuzione di uno scenario**

_[!DNL Workfront Fusion]_

Quando un utente tenta di eseguire uno scenario, l’operazione ha esito negativo e l’utente riceve il messaggio “[!UICONTROL Scenario rifiutato]”.

+++

+++**Aggiornamento di manutenzione del 15 aprile 2021**

**[!UICONTROL Il Bilanciatore dei carichi di lavoro] visualizza un numero errato di ore pianificate**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente visualizza le ore pianificate per un’attività nel [!UICONTROL Bilanciatore dei carichi di lavoro], il valore mostrato non corrisponde alle ore pianificate assegnate all’attività.

**La barra di navigazione superiore non è visibile in [!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Quando un utente passa a una pagina diversa da Dashboard in [!DNL Workfront Proof], la barra di navigazione superiore scompare. L’utente non è in grado di accedere alle funzionalità della barra di navigazione, ad esempio alle impostazioni dell’account o al profilo.

**Miglioramento dei moduli personalizzati**

_Moduli personalizzati nel mio gruppo_

Per una migliore esperienza durante la compilazione di un modulo personalizzato, la visualizzazione delle etichette nei campi personalizzati lunghi è stata perfezionata. Quando lo spazio orizzontale è sufficiente per visualizzarle interamente, queste etichette non vengono più troncate.

+++

+++**Aggiornamento di manutenzione dell’8 aprile 2021**

**Impossibile creare bozze nell’integrazione di [!DNL Adobe Creative Cloud]**

_Integrazioni di Workfront_

Quando un utente tenta di creare una bozza direttamente da [!DNL Adobe Creative Cloud], la bozza non viene generata.

+++

+++**Aggiornamento di manutenzione del 1° aprile 2021**

**Problemi durante la visualizzazione del pannello di riepilogo in [!DNL Chrome]**

_[!UICONTROL Riepilogo]_

Quando un utente apre il pannello [!UICONTROL Riepilogo] tramite il browser [!DNL Chrome], l’interfaccia utente del pannello di riepilogo non si comporta come previsto. L’utente non è in grado di scorrere la pagina, le icone potrebbero scomparire e il contenuto potrebbe sovrapporsi ad altri elementi.

**[!UICONTROL Nella sezione Team] di [!UICONTROL Configurazione] non vengono mostrati tutti i team**

_[!UICONTROL Configura]_

L’amministratore è in grado di visualizzare solo i team che ha creato personalmente quando accede alla pagina [!UICONTROL Team] di [!UICONTROL Configurazione]. I team creati da altri amministratori non sono visibili.

**Impossibile aggiungere aggiornamenti a un progetto che si trova nello stato [!UICONTROL In attesa di approvazione]**

_Progetti_

Quando un utente tenta di aggiungere un aggiornamento a un progetto che si trova nello stato [!UICONTROL In attesa di approvazione] e tale utente non è designato all’approvazione del progetto, l’aggiornamento non viene aggiunto e l’utente visualizza l’avviso seguente:

Impossibile modificare un progetto con lo stato “[!DNL Pending Approval]”. È possibile modificare il progetto cambiando lo stato.

+++


## Aggiornamenti di marzo 2021

+++**Aggiornamento di manutenzione del 26 marzo 2021**

**I pulsanti in un caso di business vengono visualizzati in modo errato**

_Progetti_

Quando un utente visualizza un caso di business e la finestra è in modalità a schermo intero, i pulsanti [!UICONTROL Salva] e [!UICONTROL Annulla] vengono visualizzati al centro dello schermo, sovrapponendosi ad altri elementi del caso di business.

**Impossibile modificare l’ordinamento di un report**

_Report_

Quando un utente tenta di modificare l’ordinamento di un report nella nuova esperienza [!DNL Workfront], l’ordinamento non cambia rispetto a quello selezionato al momento della creazione del report.

**La Condivisione è disabilitata per le nuove bozze**

_[!DNL Workfront Proof]_

Quando un utente crea una bozza con l’opzione [!UICONTROL Condivisione pubblica] abilitata, al momento della sua generazione la condivisione si disabilita. Gli altri utenti non possono visualizzare il pulsante [!UICONTROL Condividi] o condividere la bozza.

**Errore “[!UICONTROL Impossibile generare la bozza]” durante la creazione di una bozza**

_[!DNL Workfront Proof]_

Quando un utente tenta di creare una bozza, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Impossibile generare la bozza -- Errore interno]”

+++

+++**[!DNL Workfront Fusion]- Aggiornamento di manutenzione del 25 marzo 2021**

**Raccolta o campo di riferimento ridondante rimosso dal pannello di mappatura**

_[!DNL Workfront Fusion]2.0_

Quando un utente utilizza un termine dell’API [!DNL Workfront] per selezionare una raccolta o un campo di riferimento da includere nell’output di un modulo [!DNL Workfront], l’output mostra tale campo con due punti, ad esempio, [!UICONTROL proprietario:nome], e anche negli attributi (nome è un campo sotto proprietario). Il campo contrassegnato con due punti non contiene dati e fornisce informazioni errate se viene mappato in un modulo successivo nello scenario.

+++

+++**[!DNL Workfront Fusion]- Aggiornamento di manutenzione del 18 marzo 2021**

**Le impostazioni dei modelli di progetto ora si applicano ai progetti creati tramite [!DNL Workfront Fusion] 2.0**

_[!DNL Workfront Fusion]2.0_

Quando un utente crea un progetto da un modello utilizzando [!DNL Workfront Fusion] 2.0, le impostazioni del modello vengono applicate al nuovo progetto. Questo comportamento è identico alla procedura di creazione di un progetto a partire da un modello nell’applicazione [!DNL Workfront].

+++

+++**Aggiornamento di manutenzione del 18 marzo 2021**

**Le impostazioni dei modelli di progetto ora si applicano ai progetti creati tramite l’API**

_[!DNL Workfront]API_

Quando un utente crea un progetto da un modello utilizzando l’API [!DNL Workfront], le impostazioni del modello vengono applicate al nuovo progetto. Questo comportamento è identico alla procedura di creazione di un progetto a partire da un modello nell’applicazione [!DNL Workfront].

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 15 marzo 2021**

**Il componente condiviso non funziona come previsto**

_[!DNL Workfront Proof]_

Se gli account [!DNL Workfront Proof] autonomi vengono spostati in un componente condiviso, possono verificarsi gli scenari seguenti quando un utente aggiunge una nuova versione di una bozza o di un documento:

* L’utente non è in grado di eliminare l’utente [!UICONTROL Studio Proof].
* Il messaggio predefinito non viene visualizzato nella nuova versione.

**La condivisione di collegamenti pubblici non è abilitata nella nuova versione di una bozza**

_Documenti_

Quando un utente abilita la condivisione di collegamenti pubblici su una bozza e successivamente ne carica una nuova versione, la condivisione di collegamenti pubblici non viene abilitata automaticamente sulla nuova versione.

**[!UICONTROL I pulsanti Approva], [!UICONTROL Modifiche], [!UICONTROL Rifiuta] non sono presenti nella bozza**

_[!DNL Workfront Proof]_

Quando un utente visualizza una bozza nel visualizzatore bozze, i pulsanti [!UICONTROL Approva], [!UICONTROL Modifiche] e [!UICONTROL Rifiuta] non sono presenti nella parte superiore dello schermo.

**Impossibile modificare l’ordinamento di un report**

_Report_

Quando un utente tenta di modificare l’ordinamento di un report nella nuova esperienza [!DNL Workfront], l’ordinamento non cambia rispetto a quello selezionato al momento della creazione del report.

**Il messaggio personalizzato di una bozza non viene trasferito nella nuova versione**

_[!DNL Workfront Proof]_

Quando un utente allega un messaggio personalizzato a una bozza e carica una nuova versione, il messaggio personalizzato non viene visualizzato nella nuova bozza.

**L’elenco utenti non viene visualizzato**

_Elenchi_

Quando un utente tenta di visualizzare un Elenco utenti e la visualizzazione include la colonna “[!UICONTROL Icone di stato]”, l’elenco non viene visualizzato.

**Opzione “[!UICONTROL Notifica i destinatari relativamente a questa bozza]” disabilitata indipendentemente dalle impostazioni del flusso di lavoro**

_[!DNL Workfront Proof]_

Quando un utente crea una nuova bozza e non abilita manualmente l’opzione “[!UICONTROL Notifica i destinatari relativamente a questa bozza]”, il destinatario non riceve alcuna notifica. Ciò avviene anche quando l’opzione è abilitata nelle impostazioni del flusso di lavoro.

**Impossibile modificare l’intervallo di date**

_[!UICONTROL Funzionalità di analisi avanzate]_

Quando un utente visualizza la [!UICONTROL Funzionalità di analisi avanzate] e fa clic sul calendario per modificare l’intervallo di date, le date non cambiano.

**Impossibile scaricare un documento condiviso pubblicamente**

_Documenti_

Quando un utente fa clic su un collegamento condiviso per scaricare un documento, l’operazione ha esito negativo e l’utente visualizza all’interno del browser un messaggio di errore dove si indica che la pagina non esiste.

+++

+++**Aggiornamento di manutenzione dell’11 marzo 2021**

**Esportazione di una sezione del modulo personalizzato consentita solo agli amministratori**

_Moduli personalizzati_

Se un modulo personalizzato allegato a un oggetto presenta un’interruzione di sezione che richiede un accesso superiore rispetto a “[!UICONTROL Visualizzazione]” per visualizzare il contenuto della sezione, tale contenuto può essere esportato soltanto dagli amministratori.

**Il nome del documento scaricato non è corretto**

_[!DNL Workfront Proof]_

Quando un utente scarica un documento da [!UICONTROL Visualizzatore bozze], il documento presenta il nome di una versione precedente, non di quella scaricata.

+++

+++**Aggiornamento di manutenzione del 4 marzo 2021**

**Errore durante l’accesso al modello di layout**

_Modelli di layout_

Quando un utente iscritto alla nuova esperienza [!DNL Workfront] passa a [!DNL Classic] e tenta di accedere a un modello di layout [!DNL Classic], visualizza l’errore “[!UICONTROL La pagina non esiste]”.

**Impossibile modificare i filtri nel [!UICONTROL Bilanciatore dei carichi di lavoro]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di modificare un filtro nel [!UICONTROL Bilanciatore dei carichi di lavoro], il generatore di filtri non si apre.

**Il collegamento “[!UICONTROL Visualizza tutte le notifiche]” in una notifica e-mail reindirizza l’utente a una pagina errata**

_Notifiche e-mail_

Quando un utente fa clic sul collegamento “[!UICONTROL Visualizza tutte le notifiche]” in una notifica e-mail, viene reindirizzato a una pagina contenente il messaggio seguente:

“[!UICONTROL L’utente non esiste più. L’indirizzo web potrebbe non essere digitato correttamente. Controllalo e prova di digitarlo di nuovo.]”

**L’utente non viene indirizzato al commento della bozza in cui è taggato**

_Notifiche e-mail_

Quando un utente viene taggato all’interno di un commento della bozza e fa clic sul collegamento [!UICONTROL Vai alla bozza] nella notifica e-mail, viene indirizzato alla bozza ma non al commento specifico. Se l’utente si trova in [!DNL Workfront Classic], viene indirizzato alla pagina [!UICONTROL Dettagli documento] e non al commento nella bozza.

**Gli utenti aggiunti alla fase [!DNL Workfront] ricevono notifiche e-mail**

_[!DNL Workfront Proof]_

Quando un utente che non fa parte del flusso di lavoro apre una bozza da [!DNL Workfront], il sistema crea automaticamente una fase, aggiunge l’utente alla bozza e invia la notifica e-mail [!UICONTROL Nuova bozza].

**Il pannello di riepilogo del documento si scurisce, rendendo le azioni non disponibili**

_Documenti_

Quando un utente si trova su una pagina del documento e passa il puntatore sul pannello di riepilogo, il pannello si scurisce e potrebbe mostrare altri pulsanti. L’utente non può selezionare le azioni del pannello di riepilogo.

**Modifica delle prestazioni del flusso di aggiornamento**

_Flusso di aggiornamento_

Il numero di aggiornamenti utente mostrati nella scheda [!UICONTROL Aggiornamenti] è stato ridotto da 50 a 25 alla volta per migliorare le prestazioni.

+++

+++**Aggiornamento di manutenzione (correzione rapida) del 1° marzo 2021**

**Le nuove e-mail di bozza non vengono inviate**

_[!DNL Workfront Proof]_

NOTA: questo problema è stato risolto nella nuova esperienza [!DNL Workfront] il 26 febbraio 2021.
È stato risolto in [!DNL Classic] il 1° marzo 2021.

Quando un utente crea una nuova bozza e abilita l’opzione [!UICONTROL Notifica i destinatari relativamente a questa bozza], non viene inviata alcuna e-mail di notifica al destinatario.

+++


## Aggiornamenti di febbraio 2021

+++**Aggiornamento di manutenzione del 25 febbraio 2021**

**[!UICONTROL Lo strumento Pianificazione] non si carica in nessuna area**

_Gestione risorse_

Quando un utente che presenta un apostrofo nel proprio nome utente tenta di accedere allo strumento [!UICONTROL Pianificazione] in [!DNL Workfront Classic], la pagina è vuota e lo strumento non si carica.

**Il nome non si aggiorna nelle nuove versioni di una bozza**

_Documenti_

Nella nuova esperienza [!DNL Workfront], quando un utente carica una nuova versione di un documento con un nome diverso, il nome non viene aggiornato in modo da corrispondere al nome della versione più recente.

**[!UICONTROL Errore Condivisione documento] durante l’eliminazione di progetti**

_Progetti_

Quando un amministratore di sistema ha accesso a un progetto che è stato copiato e tenta di eliminare tale progetto o un documento al suo interno, l’operazione ha esito negativo e viene visualizzato il messaggio di errore “[!UICONTROL Condivisione documento con valore/i di chiave primaria non trovato]”.

**Il report utente non applica tutti i filtri**

_Report_

Nella nuova esperienza di [!DNL Workfront], quando un utente crea un report utente con una regola di filtro che include il campo [!UICONTROL ID padre principale], le altre regole di filtro non vengono applicate.

**I campi calcolati non vengono ricalcolati dopo le modifiche**

_Moduli personalizzati_

Nella nuova esperienza [!DNL Workfront], quando un utente modifica e salva un modulo personalizzato contenente campi calcolati, questi campi non vengono aggiornati.

**Eliminazione di documenti durante la rimozione di un modulo personalizzato**

_Moduli personalizzati_

Nella nuova esperienza [!DNL Workfront], quando un utente elimina un modulo personalizzato Documenti allegato ai documenti, anche questi ultimi vengono eliminati.

+++

+++**Aggiornamento di manutenzione del 18 febbraio 2021**

**Casella di controllo non necessaria rimossa dall’area [!UICONTROL Richieste]**

_Richieste_

La casella di controllo a sinistra dei nomi delle richieste nell’elenco Inviato dell’area [!UICONTROL Richieste] è stata rimossa. Questa casella di controllo non era connessa ad alcuna funzionalità, pertanto la sua rimozione ha contribuito a migliorare l’esperienza dell’utente.

**Impossibile accedere ai documenti dai collegamenti**

_Documenti_

Nella nuova esperienza [!DNL Workfront], quando un utente fa clic su alcuni collegamenti all’interno del documento, non è in grado di accedere al documento e visualizza il messaggio di errore “[!UICONTROL Il documento non esiste più. È possibile che l’indirizzo web sia stato digitato in modo errato. Controllare l’indirizzo e digitarlo di nuovo.]”. Lo stesso errore si verifica con il collegamento [!UICONTROL Visualizza dettagli] delle notifiche e-mail relative alla bozza.

+++

+++**Workfront Fusion - Aggiornamento di manutenzione del 16 febbraio 2021**

**[!DNL Workfront Fusion] 2.0 mostra fusi orari imprecisi**

_Scenari_

Questo aggiornamento ha risolto un problema relativo alla visualizzazione non corretta dei fusi orari in [!DNL Fusion] 2.0. Gli utenti possono ora visualizzare il proprio fuso orario nei campi di input per le date.

+++

+++**Aggiornamento di manutenzione dell’11 febbraio 2021**

**Le bozze non vengono caricate nella cartella selezionata**

_[!DNL Workfront Proof]_

Quando un utente apre una cartella e aggiunge una nuova bozza, quest’ultima viene caricata nell’area [!UICONTROL Documenti] generale dell’oggetto anziché all’interno della cartella.

**Troppe pagine fissate provocano la scomparsa della barra di navigazione superiore**

_Navigazione_

Quando un utente ha fissato più di 60 pagine, la visualizzazione della barra di navigazione superiore si interrompe, impedendo all’utente di accedere alle sezioni [!UICONTROL Ricerca], [!UICONTROL Menu principale], [!UICONTROL Notifiche] e altro ancora.

**Impossibile digitare testo nel campo in formato Rich text**

_Elenchi_

Quando un utente tenta di modificare in linea un campo in formato Rich text, può digitare un solo carattere.

+++

+++**Aggiornamento di manutenzione del 4 febbraio 2021**

**Il report esportato mostra il [!DNL Workfront Classic] marchio**

_Report_

Quando un utente nella nuova esperienza Workfront esporta un report, il logo visualizzato nel report esportato corrisponde alle impostazioni di [!DNL Workfront Classic] presenti in [!UICONTROL Configurazione] > [!UICONTROL Sistema] > [!UICONTROL Marchio].

+++


## Aggiornamenti di gennaio 2021

+++**Aggiornamento di manutenzione del 28 gennaio 2021**

**Nei commenti non viene visualizzato “[!UICONTROL per conto di]”**

_Aggiornamenti_

Quando un amministratore [!DNL Workfront] effettua l’accesso come altro utente e risponde a un commento nella sezione [!UICONTROL Aggiornamenti] di un oggetto, il testo “[!UICONTROL per conto di]” non viene visualizzato prima del nome utente.

**Impossibile allegare un documento**

_Richieste_

Nella nuova esperienza [!DNL Workfront], quando un utente tenta di aggiungere un documento a una nuova richiesta di un provider di documenti esterno, l’elenco [!UICONTROL Documenti] non si carica, impedendo all’utente di selezionare il documento e completare la richiesta.

**La larghezza dello schermo si espande a destra, causando problemi di navigazione**

_[!UICONTROL Calendario Home]_

Nella nuova esperienza [!DNL Workfront], quando un utente apre la sezione [!UICONTROL Calendario predefinito] contenente voci in scadenza tra qualche settimana, lo schermo si espande a destra, impedendo all’utente di visualizzare tutta la settimana. Se l’utente seleziona un elemento per aprire il pannello [!UICONTROL Dettagli] in questo stato e desidera visualizzare i dettagli di un altro elemento, deve scorrere verso sinistra, chiudendo così il pannello [!UICONTROL Dettagli].

**L’etichetta del processo di approvazione a utente singolo è stata corretta**

_Progetti_

Nella nuova esperienza di [!DNL Workfront], il processo di approvazione a utente singolo per un progetto ora viene visualizzato come “[!UICONTROL Processo di approvazione per singolo utilizzo]” invece di “&lt;Personalizzato>” nella casella [!UICONTROL Modifica progetto]. Questo aggiornamento non è ancora disponibile per attività e problemi.

**È stato migliorato il look and feel dei moduli personalizzati**

_Progetti_

È stato migliorato il look and feel dei moduli personalizzati nella nuova esperienza [!DNL Workfront] per i progetti.

**La funzionalità API per la valuta del progetto ora corrisponde alla funzionalità in-app**

_Progetti_

Non è possibile modificare la valuta di un progetto se sono già presenti informazioni finanziarie. Con l’ultimo aggiornamento di manutenzione, la funzionalità API per questa circostanza corrisponde ora all’esperienza nell’interfaccia di [!DNL Workfront].

**Nessuna generazione automatica della settimana successiva**

_Schede orario_

Quando un utente passa alla sezione [!UICONTROL Schede orario], visualizza solo la scheda orario della settimana corrente. Le schede orario per le settimane successive non vengono generate automaticamente.

+++

+++**Aggiornamento di manutenzione del 21 gennaio 2021**

**L’ordinamento manuale per colonna mostra tutti i risultati**

_Report_

Nella nuova esperienza [!DNL Workfront], quando un utente fa clic su una barra nel grafico di un report e successivamente fa clic su un’intestazione di colonna per ordinare manualmente i risultati di tale raggruppamento, vengono visualizzati tutti i risultati del report e non solo i risultati del raggruppamento selezionato originariamente.

**Modifiche all’impostazione “[!UICONTROL Consenti condivisione bozze tramite URL o codice di incorporamento]”**

_[!DNL Workfront Proof]_

Quando un utente crea una bozza e deseleziona l’impostazione [!UICONTROL Consenti condivisione bozze tramite URL o codice di incorporamento], l’impostazione viene nuovamente selezionata dopo la generazione della bozza. Se l’utente lascia tale impostazione selezionata, dopo la generazione della bozza viene deselezionata.

Gli utenti **[!DNL Mac] non possono incollare nei campi di testo nel visualizzatore di bozze**

_[!DNL Workfront Proof]_

Quando un utente tenta di incollare del testo in determinati campi del visualizzatore di bozze, il testo non viene visualizzato.

+++

+++**Aggiornamento di manutenzione del 14 gennaio 2021**

**Impossibile aggiornare le impostazioni delle notifiche e-mail**

_Configura_

Quando un utente prova ad aggiornare le impostazioni delle notifiche e-mail, non può accedere alla sezione [!UICONTROL Notifiche e-mail] e visualizza il messaggio di errore “[!UICONTROL Riproviamo. Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

**[!UICONTROL Il Grafico di Gantt] causa il troncamento di alcuni campi**

_Elenchi_

In alcune aree dell’elenco, quando un utente apre il [!UICONTROL Grafico di Gantt], il testo all’interno di alcuni campi, ad esempio [!UICONTROL Descrizione], appare troncato. Per visualizzare il testo completo, l’utente deve fare doppio clic sul campo.

**Impossibile inviare file da [!UICONTROL Dettagli documento]**

_Documenti_

Nella nuova esperienza [!DNL Workfront], quando un utente tenta di inviare un documento dalla pagina [!UICONTROL Dettagli documento], visualizza il messaggio di errore “[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova ad aggiornare la pagina del browser]”.

+++

+++**Aggiornamento di manutenzione del 7 gennaio 2021**

**La finestra di dialogo Delega approvazioni si chiude**

_Home_

Quando un utente prova a delegare le approvazioni in [!UICONTROL Home] e fa clic su una data, la finestra di dialogo si chiude senza selezionare la data o consentire all’utente di completare il processo di delega utente.

**Problema relativo allo spostamento di un documento in un’attività**

_Documenti_

Quando un utente tenta di spostare un documento o una bozza nella nuova esperienza [!DNL Workfront], alcune attività esterne al progetto non elencano il progetto principale come previsto.

**Il nome del PDF scaricato non è corretto**

_[!DNL Workfront Proof]_

Quando un utente riceve un collegamento per il download tramite e-mail ([!UICONTROL Bozza] > [!UICONTROL Stampa commenti] > [!UICONTROL PDF]) ed esporta il file, al file scaricato viene assegnato un numero casuale e non l’ID bozza.

+++
