---
title: Aggiornamenti alla manutenzione di Workfront per il 2021
description: Cronologia degli aggiornamenti di manutenzione del 2021 per [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
source-git-commit: 7fa90198186a7b0f392683d432a7da0424943da2
workflow-type: tm+mt
source-wordcount: '10019'
ht-degree: 3%

---

# 2021 [!DNL Workfront] Aggiornamenti di manutenzione

Nel 2021 sono stati effettuati i seguenti aggiornamenti di manutenzione:

## Aggiornamenti a dicembre 2021

+++**Aggiornamento della manutenzione il 23 dicembre 2021**

**Nuove attività predefinite per un vincolo di attività non corretto**

_Attività_

Quando un utente crea una nuova attività utilizzando il pulsante &quot;[!UICONTROL Nuova attività]&quot; e [!UICONTROL Inizio predefinito nuova attività] L&#39;opzione Data è impostata su &quot;[!UICONTROL Oggi],&quot; il vincolo dell&#39;attività creata è impostato su &quot;[!UICONTROL Non appena possibile]&quot; anziché &quot;[!UICONTROL Inizia non prima di].&quot; Ciò può verificarsi anche quando si utilizzano modelli di progetto.

**Orario di apertura in [!UICONTROL Gruppi] Area porta a pagina vuota**

_Configura_

Quando un utente visualizza i gruppi nel [!UICONTROL Configurazione] e tenta di aprire, modificare o copiare una pianificazione, la pianificazione non si apre e l’utente visualizza una pagina vuota.

**Le modifiche non vengono visualizzate quando si riordina la navigazione a sinistra**

_Navigazione_

Quando un utente tenta di riordinare il pannello di navigazione a sinistra trascinando un elemento, questo viene visualizzato nella posizione precedente quando l’utente lo rilascia. Se l’utente aggiorna la pagina, nel pannello a sinistra viene visualizzato il nuovo ordine.

**Il collegamento per inviare un documento richiesto porta a una pagina vuota.**

_Documenti_

Quando un utente riceve una richiesta di invio di un documento e fa clic sul collegamento all&#39;oggetto in cui è stato richiesto il documento, il collegamento porta a una pagina vuota. Questo può verificarsi quando si fa clic su un collegamento in un’e-mail o in una notifica in-app.

**[!UICONTROL Bilanciamento del carico di lavoro] mostra 0 ore assegnate**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente visualizza la variabile [!UICONTROL Bilanciamento del carico di lavoro] e ha &quot;[!UICONTROL Mostra date previste]&quot; impostazione abilitata, tutte le date future vengono visualizzate 0 ore allocate.

**Le bozze scompaiono a intermittenza dalle cartelle**

_[!DNL Workfront Proof]_

Quando un utente ha effettuato l&#39;accesso a [!DNL Workfront Proof] visualizza una cartella, la cartella appare vuota. Se l’utente esegue il check-indietro in un secondo momento, le bozze sono visibili.

+++

+++**Aggiornamento della manutenzione il 16 dicembre 2021**

**Facendo clic sull&#39;annuncio nell&#39;elenco delle notifiche si arriva alla pagina vuota**

_Notifiche_

Quando un utente apre il proprio elenco di notifiche da [!UICONTROL Notifiche] quindi fa clic su un annuncio, viene visualizzata una pagina vuota e l’annuncio non viene visualizzato.

**Il pannello di riepilogo mostra &quot;[!UICONTROL Nessuna selezione]&quot; quando l&#39;attività è selezionata**

_Attività_

Quando un utente apre un riepilogo del documento nel [!UICONTROL Documenti] area di un progetto, quindi passa all&#39;elenco attività, seleziona un&#39;attività e tenta di aprire il riepilogo attività, il riepilogo attività non viene visualizzato e l&#39;utente visualizza il seguente messaggio:

[!UICONTROL Nessuna selezione. Selezionare un documento nell&#39;elenco per visualizzare i dettagli.]

Il messaggio fa riferimento ai documenti anche se l’utente si trova nell’elenco delle attività.

**[!UICONTROL Lavoro non assegnato] non viene caricato**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente nella [!UICONTROL Bilanciamento del carico di lavoro] crea un filtro utilizzando [!UICONTROL Assegnazione:ID ruolo] campo [!UICONTROL Lavoro non assegnato] l&#39;area non viene caricata.

**Collegamento di un modello utilizzando &quot;[!UICONTROL Personalizza e allega]&quot; cancella i valori dei campi personalizzati**

_Progetti_

Se un utente allega un modello a un progetto utilizzando &quot;[!UICONTROL Personalizza e allega]&quot; e al progetto è già associato un modulo personalizzato, i valori dei campi personalizzati non vengono riportati e devono essere immessi manualmente. Ciò si verifica anche quando il modello include lo stesso modulo personalizzato.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 10 dicembre 2021**

**[!UICONTROL Whops] errore durante l&#39;associazione del modello al progetto esistente**

_Progetti_

Quando un utente tenta di allegare un modello a un progetto esistente, il modello non viene allegato e l&#39;utente visualizza il seguente errore:

&quot;[!UICONTROL Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

+++

+++**Aggiornamento della manutenzione il 9 dicembre 2021**


**Il pannello di navigazione a sinistra compresso si espande al caricamento della pagina**

_Navigazione_

Quando un utente imposta la propria navigazione a sinistra per comprimere e quindi aggiorna una pagina, la navigazione a sinistra viene espansa sulla pagina ricaricata. La navigazione a sinistra viene espansa anche se l’utente apre una pagina in una nuova scheda.

**[!UICONTROL Bilanciamento del carico di lavoro] mostra 0 ore assegnate**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente visualizza la variabile [!UICONTROL Bilanciamento del carico di lavoro] e ha &quot;[!UICONTROL Mostra date previste]&quot; impostazione abilitata, tutte le date future vengono visualizzate 0 ore allocate.

+++

+++**Aggiornamento della manutenzione l’8 dicembre 2021**

**L&#39;approvazione viene ripristinata quando viene effettuato un aggiornamento**

_Approvazioni_

Se un utente prende una decisione su un&#39;approvazione utilizzando l&#39;intestazione dell&#39;oggetto, quindi esegue immediatamente un aggiornamento sull&#39;oggetto, le icone di approvazione vengono nuovamente visualizzate nell&#39;intestazione e la decisione di approvazione non viene salvata.

**[!UICONTROL Impossibile modificare in linea un&#39;assegnazione in un report]**

_Rapporti_

Quando un utente tenta di modificare in linea un&#39;assegnazione in un rapporto, il valore del campo non cambia e la modifica non viene salvata.


+++

+++**Aggiornamento della manutenzione il 2 dicembre 2021**

**Aggiunta di una barra aggiuntiva durante la digitazione manuale dell’URL**

_Richieste_

Quando un utente compila una richiesta e inizia a digitare manualmente un URL, ad un certo punto viene aggiunta una barra in più vicino all’inizio dell’URL. L&#39;utente non può eliminare la barra.

**Impossibile rimuovere le sezioni personalizzate dal pannello di navigazione a sinistra**

_Navigazione_

Quando un utente tenta di rimuovere una sezione personalizzata dal pannello di navigazione a sinistra facendo clic sulla X accanto alla sezione, la sezione non viene rimossa.

**Il lavoro non assegnato non viene caricato**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente nella [!UICONTROL Bilanciamento del carico di lavoro] crea un filtro utilizzando [!UICONTROL Assegnazione:ID ruolo] campo [!UICONTROL Lavoro non assegnato] l&#39;area non viene caricata.

**Pagine che non vengono caricate in alcuni browser**

_[!DNL Workfront]_

Quando un utente lavora in [!DNL Workfront], le pagine non vengono caricate e l’utente visualizza il seguente messaggio di errore:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

Questo è stato segnalato in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Questo errore si verifica in modo casuale e può influenzare qualsiasi area di [!DNL Workfront].

+++


## Aggiornamenti a novembre 2021

+++**Aggiornamento della manutenzione il 18 novembre 2021**

**[!DNL Workfront]per [!DNL Jira] &quot;[!UICONTROL ClientID o clientSecret non valido]&quot; errore all&#39;accesso**

_Integrazioni Workfront_

Gli utenti sono stati disconnessi da [!DNL Jira] per l’integrazione con Workfront. Quando un utente tenta di accedere al [!DNL Workfront for Jira] integrazione, non possono effettuare l&#39;accesso e viene visualizzato il seguente errore:

&quot;[!UICONTROL ClientID o clientSecret non valido]&quot;

**Il modulo personalizzato allegato alla richiesta non viene aggiornato quando viene selezionato un nuovo argomento della coda**

_Richieste_

Quando un utente crea una richiesta e seleziona un argomento della coda che allega automaticamente un modulo personalizzato alla richiesta e quindi seleziona un argomento della coda diverso, il modulo personalizzato del primo argomento della coda rimane allegato alla richiesta.

**Le icone non vengono visualizzate correttamente**

_[!DNL Workfront]_

Le immagini a icona non vengono visualizzate correttamente. Questo è stato riportato in molte aree in [!UICONTROL Workfront].

**Le attività non vengono esportate in PDF quando è selezionata l’opzione &quot;Altre dimensioni&quot;.**

_Attività_

Se un utente tenta di esportare un elenco di attività in PDF e seleziona il[!UICONTROL Altre dimensioni]&quot;, possono selezionare una dimensione e fare clic su [!UICONTROL Esporta], ma l’elenco non viene esportato. Nessun messaggio di errore e nessun&#39;altra indicazione che l&#39;esportazione sia stata eseguita correttamente.

**L’indicatore immagine non viene visualizzato nelle notifiche e-mail**

_Notifiche_

Quando un utente aggiunge un&#39;immagine a un aggiornamento e viene inviata una notifica e-mail al destinatario dell&#39;aggiornamento, l&#39;e-mail non include un indicatore dell&#39;esistenza di un&#39;immagine nell&#39;aggiornamento.

**Pagine che non vengono caricate in alcuni browser**

_[!DNL Workfront]_

Quando un utente lavora in [!DNL Workfront], le pagine non vengono caricate e l’utente visualizza il seguente messaggio di errore:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

Questo è stato segnalato in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Questo errore si verifica in modo casuale e può influenzare qualsiasi area di Workfront.

+++

+++**Aggiornamento della manutenzione l’11 novembre 2021**

**Problema con le integrazioni dei documenti, pagina vuota nella finestra a comparsa di caricamento dei documenti da[!DNL Google Drive*]*

_Documenti_

Quando un utente tenta di aggiungere un nuovo documento a [!DNL Workfront] da [!DNL Google Drive] utilizzando [!UICONTROL Aggiungi nuovo] >[!UICONTROL Da [!DNL Google Drive]], la schermata a comparsa per il caricamento rimane vuota.

**Impossibile utilizzare più di un filtro nel load balancer di carico di lavoro**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente sta tentando di utilizzare più di un filtro nel [!UICONTROL Bilanciamento del carico di lavoro], i seguenti problemi:

* Se l’utente seleziona due filtri, viene applicato solo il filtro inferiore.
* Se l’utente seleziona più di due filtri, non viene visualizzato alcun risultato.

**&quot;[!UICONTROL Cartelle di progetto]&quot; intestazione documento mancante nell&#39;area documenti del progetto**

_Progetti_

Quando un utente si trova in un progetto e visualizza i documenti del progetto, l’intestazione &quot;[!UICONTROL Cartelle di progetto]&quot; manca nel menu di navigazione a sinistra. La freccia a discesa è ancora presente e l&#39;utente può selezionare una cartella.

**Le colonne sulla scheda Kanban sono troppo grandi e non possono essere regolate**

_Agile_

Quando un utente visualizza una bacheca Kanban con più colonne, le colonne sono troppo grandi e l&#39;utente deve scorrere per visualizzare o spostare le schede nelle colonne più a destra. Le larghezze delle colonne non sono regolabili, pertanto l’utente non può ridurre le colonne in modo che siano tutte visibili sullo schermo contemporaneamente.

**Interfaccia migliorata per la creazione di un nuovo team**

_Team_

La creazione di team è ora più intuitiva grazie ai nuovi suggerimenti visivi. Quando selezioni la [!UICONTROL Cambia team] su qualsiasi pagina del team, la [!UICONTROL Crea nuovo team] il link ha un&#39;icona per indicare &quot;[!UICONTROL nuovo],&quot; e il collegamento è separato dal resto dell’elenco in modo che non sembri un nome di team. Questa interfaccia è la stessa per i team agili e non-agili.

+++

+++**Aggiornamento della manutenzione il 4 novembre 2021**

**Nuove attività predefinite per un vincolo di attività non corretto**

_Attività_

Quando un utente crea una nuova attività utilizzando il pulsante &quot;[!UICONTROL Nuova attività]&quot; e l&#39;opzione Nuova data di inizio predefinita attività è impostata su &quot;[!UICONTROL Oggi],&quot; il vincolo dell&#39;attività creata è impostato su &quot;[!UICONTROL Non appena possibile]&quot; anziché &quot;[!UICONTROL Inizia non prima di].&quot;

**I campi non vengono visualizzati sulle schede dei racconti Agile**

_Agile_

Quando un utente visualizza uno storyboard di Agile, le schede visualizzano solo il [!UICONTROL Descrizione] e [!UICONTROL Stato] campi. Eventuali altri campi, compresi quelli personalizzati, non vengono visualizzati.

**Le schede ritornano alla colonna originale prima di passare alla nuova colonna**

_Agile_

Quando un utente trascina una scheda in una nuova colonna dello storyboard, l&#39;utente può vedere la scheda che sta trascinando. Tuttavia, quando l&#39;utente rilascia la scheda nella nuova colonna, questa viene visualizzata brevemente nella colonna originale prima che venga visualizzata nella nuova colonna.

**Valori non disponibili per il campo personalizzato nel filtro**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di creare un filtro utilizzando un campo personalizzato, il valore del campo personalizzato non viene visualizzato e non può essere inserito nel filtro.

**Pagine non caricate [!DNL Firefox] browser**

_[!DNL Workfront]_

Quando un utente lavora in [!DNL Workfront] utilizzando [!DNL Firefox] browser, le pagine non vengono caricate e l&#39;utente visualizza il seguente messaggio di errore:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

Questo errore si verifica in modo casuale e può influenzare qualsiasi area di [!DNL Workfront].

**Errore relativo alla data durante la creazione di un progetto dal modello.**

_Modelli_

Se un utente crea un progetto da un modello e imposta la modalità di pianificazione su [!UICONTROL Data di inizio], quindi seleziona un vincolo di attività quando l’utente tenta di creare il progetto, il progetto non viene creato e l’utente visualizza un messaggio di errore basato sul vincolo di attività.

**[!UICONTROL Esporta diagramma di Gantt] la finestra di dialogo non risponde**

_Diagramma di Gantt_

Se un utente nel nuovo [!DNL Workfront] tenta di esportare il [!UICONTROL Diagramma di Gantt] e seleziona il[!UICONTROL Cosa vedo]&quot;, l&#39;opzione [!UICONTROL Diagramma di Gantt] non esporta e la finestra di dialogo non risponde. L&#39;utente non è in grado di chiudere o fare clic fuori dalla finestra di dialogo.

**Le icone non vengono visualizzate correttamente**

_[!DNL Workfront]_

Le immagini a icona non vengono visualizzate correttamente. Sono state segnalate situazioni che includono, tra l’altro:

* Immagini per ruoli o gruppi di lavoro durante la condivisione di un oggetto
* Icone a sinistra e a destra nei rapporti sul calendario
* Ordinare le icone nelle colonne dei rapporti

**Aggiungi le caselle di controllo alle richieste nel [!UICONTROL Inviato] della sezione [!UICONTROL Richieste] area**

_Richieste_

Sono state aggiunte delle caselle di controllo a sinistra dei nomi delle richieste nel [!UICONTROL Elenco inviato] del [!UICONTROL Richieste] area. Questo semplifica la selezione di una richiesta e la visualizzazione di informazioni aggiuntive.

**I trimestri personalizzati sono ora supportati nei filtri di bilanciamento del carico di lavoro**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

I filtri nel [!UICONTROL Bilanciamento del carico di lavoro] ora supporta i trimestri personalizzati.

**Operatore filtro aggiornato per il campo Durata nei filtri di bilanciamento del carico di lavoro**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Gli operatori di filtro sono stati aggiornati quando si filtra il[!UICONTROL  Bilanciamento del carico di lavoro] zone [!UICONTROL Durata].

+++


## Aggiornamenti a ottobre 2021

+++**Aggiornamento della manutenzione il 28 ottobre 2021**

**[!UICONTROL Pagina principale] e [!UICONTROL Il mio lavoro] visualizzazione di una pagina vuota**

_[!UICONTROL Pagina principale] / [!UICONTROL Il mio lavoro]_

Quando un utente accede a [!UICONTROL Pagina principale] Per Lavoro personale, la pagina viene visualizzata come vuota.

**Impossibile visualizzare o modificare [!UICONTROL Gruppo argomenti] dettagli**

_Richieste_

Quando un utente tenta di visualizzare o modificare i dettagli di un gruppo di argomenti, la pagina visualizzata mostra &quot;[!UICONTROL Dettagli gruppo argomenti]&quot; nell&#39;intestazione ma altrimenti è vuoto

**I pulsanti di scelta vuoti richiesti vengono compilati automaticamente**

_Richieste_

Quando un utente invia una richiesta con un campo pulsante di scelta obbligatorio e l’utente non ha selezionato un valore per quel campo prima di inviare la richiesta, il primo valore viene selezionato automaticamente all’invio della richiesta.

+++

+++**Aggiornamento della manutenzione il 21 ottobre 2021**

**Impossibile aggiungere un filtro in [!UICONTROL Bilanciamento del carico di lavoro]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente nella [!UICONTROL Bilanciamento del carico di lavoro] tenta di aggiungere un filtro, il [!UICONTROL Aggiungi filtro] Il pannello si apre, ma il contenuto del pannello non viene caricato e l’utente non può aggiungere il filtro.

**La scheda Agile Scrum non visualizza storie**

_Agile_

Quando un utente tenta di visualizzare la bacheca di Scrum nell&#39;iterazione di un team, la bacheca di script viene visualizzata come vuota.

**Scrum story board vuoto quando si utilizzano i filtri**

_Agile_

Quando un utente tenta di visualizzare una bacheca della storia di Scrum utilizzando un filtro qualsiasi ma il &quot;[!UICONTROL Tutto il team]&quot;, viene visualizzata una schermata vuota. L&#39;utente non è in grado di tornare al &quot;[!UICONTROL Tutto il team]&quot; filtro.

**Gli elenchi sono visibili solo in una piccola area dello schermo**

_Elenchi_

Quando un utente tenta di visualizzare un elenco mentre utilizza un [!DNL Safari] browser su [!DNL Mac] utilizzando [!DNL Big Sur OS], l’elenco viene visualizzato solo in una piccola area dello schermo. L’utente può scorrere l’elenco, ma l’area potrebbe essere così piccola da rendere difficile o impossibile la lettura dell’elenco.

**I pulsanti di scelta vuoti richiesti vengono compilati automaticamente**

_Richieste_

Quando un utente invia una richiesta con un campo pulsante di scelta obbligatorio e l’utente non ha selezionato un valore per quel campo prima di inviare la richiesta, il primo valore viene selezionato automaticamente all’invio della richiesta.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 21 ottobre 2021**

**[!UICONTROL Pagina principale] e [!UICONTROL Il mio lavoro] visualizzazione di una pagina vuota**

_[!UICONTROL Pagina principale] / [!UICONTROL Il mio lavoro]_

Quando un utente accede a [!UICONTROL Pagina principale] o [!UICONTROL Il mio lavoro], la pagina viene visualizzata come vuota.

+++

+++**Aggiornamento della manutenzione il 20 ottobre 2021**

**[!UICONTROL Bilanciamento del carico di lavoro] impostato come opzione di programmazione predefinita**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Se un utente ha [!UICONTROL Scheduler] impostato come predefinito andrà ad usarlo, vedono che il [!UICONTROL Bilanciamento del carico di lavoro] è stato impostato come predefinito.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 19 ottobre 2021**

**Impossibile assegnare una richiesta durante la creazione**

_Richieste_

Quando un utente entra nel nuovo [!DNL Workfront] l&#39;esperienza sta creando una richiesta e tenta di assegnare un utente digitandone il nome nel [!UICONTROL Assegnazioni] il campo non visualizza l&#39;elenco a discesa e l&#39;utente non può selezionare il nome dell&#39;assegnatario.

**Scrum story board vuoto quando si utilizzano i filtri**

_Agile_

Quando un utente tenta di visualizzare una bacheca della storia di Scrum utilizzando un filtro qualsiasi ma il &quot;[!UICONTROL Tutto il team]&quot;, viene visualizzata una schermata vuota. L&#39;utente non è in grado di tornare al &quot;[!UICONTROL Tutto il team]&quot; filtro.

+++

+++**Aggiornamento della manutenzione il 14 ottobre 2021**

**I modelli condivisi a livello di sistema non sono visibili**

_Modelli_

Quando un utente crea un progetto e tenta di utilizzare un modello condiviso a livello di sistema, non può visualizzare il modello nell’elenco dei modelli disponibili e non può utilizzarlo.

**Errore durante la creazione di progetti da modelli**

_Modelli_

Quando un utente tenta di creare un progetto da un modello che include un modulo personalizzato con una sezione visibile solo agli amministratori, non può creare il progetto e viene visualizzato il seguente messaggio:

&quot;[!UICONTROL Categoria con valore/i chiave primaria &quot;xxxxxxxxxxxxxxxxxx&quot; non trovata]&quot;

**Collegamenti aggiornati per copiare e spostare attività**

_Attività_

I collegamenti per copiare e spostare le attività sono stati aggiornati a &quot;[!UICONTROL Copia in]&quot; e &quot;[!UICONTROL Sposta a]&quot; sia nella pagina attività che in un elenco di attività.

**Rimuovi il limite alla ricerca di ruoli di lavoro durante l&#39;override delle tariffe di fatturazione per un progetto**

Ruoli

NOTA: Questo aggiornamento si trova attualmente nell’ambiente di anteprima e sarà in produzione con la versione 22.1 Production . Per ulteriori informazioni, consulta &quot;Panoramica sulla versione 22.1&quot;.

L&#39;override dei tassi di fatturazione per i ruoli di lavoro in un progetto ora cerca tutti i ruoli di lavoro nel sistema.

Precedentemente, [!DNL Workfront] ricerca di ruoli di lavoro nei primi ruoli 2000 in ordine alfabetico.

+++

+++**Aggiornamento della manutenzione il 7 ottobre 2021**

**[!UICONTROL Le notifiche in-app scompaiono] centro notifiche**

_Notifiche_

Quando un utente visualizza il Centro notifiche, alcune notifiche precedentemente visibili non sono più visibili. In alcuni casi, la notifica potrebbe scomparire prima che l’utente la veda.

**Gli annunci non sono visibili nella sezione [!UICONTROL Tutti gli annunci] page**

_Notifiche_

Quando un utente apre la [!UICONTROL Tutti gli annunci] dalla pagina [!UICONTROL Notifiche] non sono visibili annunci nelle seguenti aree:

* [!UICONTROL Posta in arrivo]
* [!UICONTROL Preferiti]
* [!UICONTROL Bozze]
* [!UICONTROL Eliminato]

**Errore durante l&#39;assegnazione in [!UICONTROL Bilanciamento del carico di lavoro]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di effettuare un&#39;assegnazione dal [!UICONTROL Bilanciamento del carico di lavoro], il lavoro non viene assegnato e l&#39;utente visualizza il seguente errore:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

+++


## Aggiornamenti a settembre 2021

+++**Aggiornamento della manutenzione il 30 settembre 2021**

**Errore durante la navigazione rapida da o verso l&#39;esterno [!UICONTROL Pagina principale]**

_Home_

Quando un utente si sposta rapidamente verso o da [!UICONTROL Pagina principale], la pagina non viene caricata e l’utente visualizza il seguente errore:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

Questo può verificarsi anche quando si passa a [!UICONTROL Pagina principale] tramite un pin.

+++

+++**Aggiornamento della manutenzione il 23 settembre 2021**

**[!UICONTROL Accesso negato] errore durante la visualizzazione dei ticket inviati a[!DNL Workfront]**

_problemi_

Quando un utente ha inviato un ticket a [!DNL Workfront] e tenta di visualizzare il ticket, visualizzano il seguente errore:

&quot;[!UICONTROL Accesso negato: Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

**Riepilogo del caso aziendale mostra valori errati**

_Progetti_

Quando un utente visualizza il [!UICONTROL Business case] pannello di riepilogo, i valori visualizzati non riflettono i valori nel singolo [!UICONTROL Business case] sezioni.

**Le intestazioni di colonna non sono allineate alle colonne negli elenchi**

_Configura_

Quando un utente si trova nella [!UICONTROL Configurazione] visualizza un&#39;area e un elenco, ad esempio [!UICONTROL Forms personalizzato] o [!UICONTROL Livelli di accesso], le intestazioni di colonna per tale elenco non sono allineate alle colonne dell’elenco.

**Gli utenti che non dispongono delle autorizzazioni di condivisione appropriate possono allegare moduli personalizzati agli oggetti**

_Moduli personalizzati_

Quando un modulo personalizzato è incluso nel nuovo [!DNL Adobe Workfront] l’esperienza è impostata per essere visibile a livello di sistema, tutti gli utenti possono allegare il modulo personalizzato a un oggetto. Tuttavia, gli utenti dovrebbero essere in grado di visualizzare il modulo personalizzato e non di allegarlo a un oggetto, a meno che non sia stato condiviso specificatamente con loro.

+++

+++**Aggiornamento della manutenzione il 16 settembre 2021**

**Impossibile modificare i gruppi**

_Gruppi_

Quando un utente tenta di modificare o eliminare un gruppo, questo non viene modificato o eliminato e l&#39;utente visualizza il seguente messaggio:

&quot;[!UICONTROL Riproviamo. Gruppo con valori di chiave primaria &quot;(ID del gruppo)&quot; non trovato]&quot;

**[!UICONTROL Ottimizzatore Portfolio] non visualizzare i progetti**

_Portfolio_

Quando un utente tenta di visualizzare i progetti nel [!UICONTROL Ottimizzatore Portfolio], l’elenco dei progetti non viene visualizzato e l’utente non è quindi in grado di interagire con i progetti.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 10 settembre 2021**

**Data e ora contrassegnate come UTC durante la modifica in linea**

_Elenchi_

Quando un utente modifica una data o un’ora in linea (in un elenco di oggetti), la data e l’ora sono contrassegnate come UTC. La data e l’ora non sono impostate in UTC in [!DNL Workfront]. Questo problema interessa solo la visualizzazione, non i dati effettivi.

**Il colore del testo non viene visualizzato correttamente quando viene applicata la formattazione condizionale**

_Rapporti_

Quando un utente visualizza un rapporto con una formattazione condizionale che modifica il colore del testo, il colore del testo viene visualizzato come non modificato.

+++

+++**Aggiornamento della manutenzione il 9 settembre 2021**

**Problemi relativi alla mancata visualizzazione dei dettagli dei problemi**

_Pagina principale_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] seleziona un problema dal [!UICONTROL Elenco lavori], l’anteprima nel pannello di destra mostra alcuni campi privi di valori immessi. Tuttavia, se accedi al problema e visualizzi il [!UICONTROL Dettagli del problema], in questi campi sono stati inseriti dei valori.

**Per visualizzare gli utenti è necessario disporre delle autorizzazioni di Contribute [!UICONTROL Approvazioni] nella nuova esperienza Workfront**

_Approvazioni_

Utenti [!UICONTROL Collaborare] autorizzazioni per un oggetto per visualizzare [!UICONTROL Approvazioni] nella nuova sezione [!DNL Workfront] Esperienza. Dovrebbero avere solo bisogno di [!UICONTROL Visualizza] autorizzazioni per visualizzare [!UICONTROL Approvazioni] quando è presente un processo di approvazione sull&#39;oggetto.

**[!UICONTROL Whops] errore durante l’utilizzo dei filtri**

_Elenchi_

Quando un utente tenta di utilizzare uno dei seguenti filtri:

* [!UICONTROL Tutti i progetti]
* [!UICONTROL Progetti ai quali collaboro]
* [!UICONTROL Le Mie Attività Correnti]

l’elenco diventa vuoto e l’utente visualizza il seguente errore:

&quot;[!UICONTROL Riproviamo.]&quot;

**[!UICONTROL Attività] la sezione diventa vuota durante la modifica in linea**

_Modelli_

Quando un utente tenta di inline modificare le attività in un modello utilizzando una visualizzazione che include il[!UICONTROL Assegna a: Nome]&quot; e l&#39;assegnazione contiene un utente, il [!UICONTROL Attività] la sezione diventa vuota e l&#39;utente non è in grado di modificare le attività del modello.

**Impossibile esportare [!UICONTROL Ottimizzatore Portfolio]**

_Portfolio_

Quando un utente tenta di esportare il [!UICONTROL Ottimizzatore Portfolio] e fai clic su una delle opzioni di esportazione, [!UICONTROL Ottimizzatore Portfolio] non esporta.

**Le notifiche non vengono inviate per le risposte**

_Notifiche_

Quando un utente risponde a un aggiornamento in [!DNL Workfront], altri utenti nel thread di commento non ricevono notifiche.

**Le modifiche ai dati personalizzati causano un ritardo**

_Campi personalizzati_

Quando un utente modifica dati personalizzati che attivano le modifiche ad altri dati visualizzati, le modifiche vengono caricate lentamente.

**Raggruppamento &quot;[!UICONTROL Comprimi o espandi tutto]&quot; l&#39;icona non viene visualizzata**

_Reporting_

&quot;[!UICONTROL Comprimi o espandi tutto]&quot; non viene visualizzata nell’intestazione di un elenco o di un rapporto quando i raggruppamenti vengono applicati all’elenco o al rapporto.

**[!UICONTROL Controlla] e [!UICONTROL Annulla] opzioni non visibili durante la modifica delle allocazioni delle attività**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di modificare l&#39;allocazione delle attività per un&#39;attività e l&#39;intervallo di tempo di tale attività si estende fino o oltre il bordo della pagina visibile, la [!UICONTROL Controlla] e [!UICONTROL Annulla] i pulsanti non sono visibili e l’utente non può salvare o annullare le modifiche di allocazione.

**Aggiunta di un campo personalizzato a [!UICONTROL Pagina principale] causa la mancanza di dati sul campo**

_[!UICONTROL Pagina principale]_

Quando viene aggiunto un campo personalizzato a [!UICONTROL Pagina principale], altri campi iniziano a perdere dati e a essere visualizzati in modo errato.

**Impossibile visualizzare gli elementi collegati quando si è effettuato l&#39;accesso come un altro utente**

_Integrazioni_

Se un amministratore ha tentato di visualizzare gli elementi collegati da un provider esterno durante l&#39;accesso come altro utente, non è stato in grado di aprire le cartelle collegate e non è stato possibile visualizzare gli elementi.

+++

+++**Aggiornamento della manutenzione il 2 settembre 2021**

**Impossibile fissare il dashboard personalizzato**

_Dashboard_

Quando un utente tenta di fissare un dashboard personalizzato, il dashboard non si blocca e l’utente visualizza il seguente errore:

&quot;[!UICONTROL Si è verificato un errore durante il pinning. Contattare [!DNL Workfront] quindi possiamo riparare questo.]&quot;

**[!DNL Workfront Proof]riepilogo di stampa vuoto**

[!DNL Workfront Proof]

Quando un utente apre il riepilogo di stampa per stampare una bozza, l&#39;intestazione viene visualizzata ma il riepilogo stesso è vuoto.

+++


## Aggiornamenti in agosto 2021

+++**Aggiornamento della manutenzione il 26 agosto 2021**

**In [!DNL Safari] è presente uno sfondo grigio scuro nel testo delle intestazioni di colonna**

_Elenchi_

In [!DNL Safari] nelle intestazioni delle colonne è presente uno sfondo grigio scuro che evidenzia il testo. Questo non è un problema con altri browser supportati.

**Errore imprevisto durante l&#39;impostazione dei predecessori**

_Attività_

Quando un utente tenta di impostare un&#39;attività come predecessore utilizzando la modifica in linea, il predecessore non è impostato e l&#39;utente visualizza il seguente messaggio:

&quot;[!UICONTROL Si è verificato un errore inatteso]&quot;

+++

+++**Aggiornamento della manutenzione il 19 agosto 2021**

**Filtri salvati mancanti dopo la selezione di un filtro senza problemi**

_Elenchi_

I filtri salvati mancano in un elenco di problemi dopo aver selezionato un filtro che non visualizza risultati.

**Problemi relativi alla mancata visualizzazione dei dettagli dei problemi**

_[!UICONTROL Pagina principale] sommario_

Quando un utente effettua un [!DNL Adobe Workfront Classic] seleziona un problema dal [!UICONTROL Elenco lavori], l’anteprima nel pannello di destra mostra alcuni campi privi di valori immessi. Tuttavia, se accedi al problema e visualizzi il [!UICONTROL Dettagli del problema], in questi campi sono stati inseriti dei valori.

+++

+++**Aggiornamento della manutenzione il 12 agosto 2021**

**Impossibile personalizzare la visualizzazione agile nel progetto**

_Agile_

Quando un utente tenta di personalizzare una visualizzazione agile esistente in precedenza su un progetto, la finestra si chiude e l&#39;utente non è in grado di modificare la visualizzazione.

**Il nome non cambia nelle nuove versioni del documento**

_Documenti_

Quando un utente carica una nuova versione di un documento, il nome del documento non viene aggiornato in modo che corrisponda al nome della versione più recente.

**L&#39;icona Predecessore non diventa verde quando il predecessore è completato.**

_Attività_

Quando un&#39;attività ha un&#39;attività predecessore e l&#39;attività predecessore è completa, l&#39;icona predecessore nell&#39;attività dipendente non diventa verde.

Quando un modulo personalizzato è incluso nel nuovo [!DNL Adobe Workfront] l’esperienza è impostata per essere visibile a livello di sistema, tutti gli utenti possono allegare il modulo personalizzato a un oggetto. Tuttavia, gli utenti dovrebbero essere in grado di visualizzare il modulo personalizzato e non di allegarlo a un oggetto, a meno che non sia stato condiviso specificatamente con loro.

+++

+++**Aggiornamento di manutenzione (Hotfix) il 6 agosto 2021**

**Impossibile selezionare i calendari in [!DNL Outloo]k Impostazioni del calendario**

_Pagina principale_

Quando un utente entra nel nuovo [!DNL Workfront] esperienza di visualizzazione [!DNL Outlook] Calendario in home e apre le impostazioni, mancano le caselle di controllo per selezionare i calendari. Se l&#39;utente fa clic sul punto in cui si trova la casella di controllo, il calendario risponde come se la casella di controllo fosse presente.

**Impossibile riautorizzare o verificare la connessione a [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] utenti con scenari di connessione [!UICONTROL Webdam] devono essere consapevoli che [!UICONTROL Webdam] le connessioni richiedono la riautenticazione manuale ogni 14 giorni. La [!UICONTROL Webdam] Al momento l’API non supporta la riautorizzazione automatica.

+++

+++**Aggiornamento della manutenzione il 5 agosto 2021**

**Impossibile interagire con il documento in [!UICONTROL Pannello di riepilogo] o [!UICONTROL Altro] menu**

_Documenti_

Quando un utente entra nel nuovo [!DNL Workfront] l&#39;esperienza sta visualizzando un documento e tenta di effettuare una selezione nel [!UICONTROL Pannello di riepilogo] o [!UICONTROL Altro] il documento è deselezionato, causando la [!UICONTROL Pannello di riepilogo] o [!UICONTROL Altro] per lasciare vuoto il menu.

**[!UICONTROL Nuova richiesta] pulsante mancante**

_Richieste_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l&#39;esperienza va al [!UICONTROL Richieste] pagina, [!UICONTROL Nuova richiesta] non viene visualizzato e non è possibile inviare una richiesta.

**Gli utenti che non dispongono delle autorizzazioni di condivisione appropriate possono allegare moduli personalizzati agli oggetti**

_Moduli personalizzati_

Quando un modulo personalizzato è incluso nel nuovo [!DNL Adobe Workfront] l’esperienza è impostata per essere visibile a livello di sistema, tutti gli utenti possono allegare il modulo personalizzato a un oggetto. Tuttavia, gli utenti dovrebbero essere in grado di visualizzare il modulo personalizzato e non di allegarlo a un oggetto, a meno che non sia stato condiviso specificatamente con loro.

**Impossibile modificare le impostazioni della bozza quando si crea una nuova bozza**

_[!DNL Workfront Proof]_

Quando un utente crea una nuova bozza e tenta di modificare le impostazioni, questa viene ripristinata in un’impostazione precedente.

**[!UICONTROL Scheda Storia] non caricato correttamente**

_Agile_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] esperienza passa a un [!UICONTROL Scheda Storia], il caricamento della bacheca può richiedere fino a 10 secondi. Il ritardo nel caricamento è dovuto al caricamento del sistema di tutte le schede quando dovrebbe essere solo caricare 50 schede alla volta.

+++


## Aggiornamenti a luglio 2021

+++**Aggiornamento di manutenzione (Hotfix) il 29 luglio 2021**

**Impossibile caricare una nuova bozza o una nuova versione di prova**

_[!DNL Workfront Proof]_

Quando un utente tenta di caricare una nuova bozza o una nuova versione di una bozza nel Classic [!DNL Workfront] esperienza, la nuova pagina di bozza o nuova versione è vuota e l&#39;utente non è in grado di caricare la bozza o la versione.

+++

+++**Aggiornamento della manutenzione il 29 luglio 2021**

**[!UICONTROL Attività di bozza] e [!UICONTROL Impostazioni del visualizzatore delle prove] pagine sempre disponibili**

_[!DNL Workfront Proof]_

La [!UICONTROL Attività di bozza] e [!UICONTROL Visualizzatore di prove] Le pagine delle impostazioni sono sempre visibili, anche se l’utente non ha accesso per aggiornare tali pagine.

Precedentemente, quando un utente con un profilo di autorizzazione di prova personalizzato passava a un documento, la [!UICONTROL Attività di bozza] e [!UICONTROL Impostazioni del visualizzatore delle prove] le pagine a sinistra non erano sempre visibili.

**Messaggio di errore durante l&#39;utilizzo [!UICONTROL Percentuale] opzione per [!UICONTROL Ore assegnate]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente seleziona la [!UICONTROL Percentuale] opzione per [!UICONTROL Ore assegnate]e sono presenti i lavori elencati nel [!UICONTROL Lavoro non assegnato] l&#39;utente visualizza il seguente errore:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

+++

+++**Aggiornamento della manutenzione il 22 luglio 2021**

**Eliminazione dei nomi delle nuove versioni di bozza**

_[!DNL Workfront Proof]_

Quando un utente effettua un [!DNL Adobe Workfront Classic] carica una nuova versione di una bozza che contiene un punto nel nome file, il nome del file viene tagliato alla fine.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 19 luglio 2021**

**Errore durante il tentativo di passare a progetti, fogli presenze, attività o programmi**

Nella nuova [!DNL Adobe Workfront] esperienza: quando un utente cerca di passare a progetti, fogli ore, attività o programmi, viene visualizzato il messaggio di errore &quot;[!UICONTROL Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

+++

+++**Aggiornamento della manutenzione il 15 luglio 2021**

**La priorità predefinita nelle nuove richieste non è corretta**

_Richieste_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] esperienza crea una richiesta, la richiesta non rispetta la priorità predefinita impostata in [!UICONTROL Preferenze del progetto] e non sono in grado di modificare la priorità prima di inviare la richiesta.

**[!UICONTROL Vai alla bozza] il collegamento non indirizza al commento**

_Notifiche e-mail_

Quando un utente riceve una notifica e-mail per un commento a prova e fa clic su [!UICONTROL Vai alla bozza], sono indirizzati al commento sbagliato nella bozza o non sono diretti ad alcun commento.

**I valori dei campi RTF non vengono riportati dopo la conversione di un problema in un’attività**

_Moduli personalizzati_

Quando un utente converte un problema in un’attività e il problema presenta un modulo personalizzato allegato con un valore inserito in un campo di testo con formattazione RTF, il valore nel campo di testo non viene riportato dopo la conversione.

**I valori dei campi personalizzati vengono modificati dopo la selezione**

_[!DNL Workfront Proof]_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l’esperienza sta creando una nuova bozza e in alcuni campi personalizzati di una bozza viene immesso un valore. il valore di alcuni campi precedenti viene ripristinato ai valori predefiniti anziché al valore immesso dall’utente.

**[!UICONTROL Assegna a] typeahead non funziona**

_[!UICONTROL Pagina principale]_

Quando un utente effettua un [!DNL Adobe Workfront Classic] crea un progetto, un&#39;attività o una richiesta da [!UICONTROL Pagina principale] la zona [!UICONTROL Assegna a] il campo typeahead non compila i nomi utente.

**Arrotondamento delle ore in modo errato**

_Schede orario_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] experience naviga in [!UICONTROL Schede temporali] > [!UICONTROL Tutti i fogli presenze], i numeri delle ore totali per alcuni fogli presenze vengono arrotondati a un decimale anziché a incrementi di 0,25, ma le ore totali vengono visualizzate correttamente nella scheda attività individuale. Ad esempio, nell&#39;area Tutti i fogli presenze, una scheda attività mostra 44,8 ore totali, ma all&#39;apertura della scheda attività mostra 44,75 ore totali.

**Impossibile delegare le approvazioni**

_[!UICONTROL Pagina principale]_

Quando un utente effettua un [!DNL Adobe Workfront Classic] click [!UICONTROL Delega le mie approvazioni] in [!UICONTROL Pagina principale] e iniziano a digitare il nome dell&#39;utente a cui stanno tentando di delegare, nessun risultato viene visualizzato nel [!UICONTROL timone] e non possono selezionare un utente.

**[!UICONTROL Diagramma di Gantt] visualizzazione non disponibile per i rapporti attività**

_Rapporti_

NOTA: Questo fenomeno interessa anche i rapporti sui progetti.

Quando un utente entra nel nuovo [!DNL Adobe Workfront] viene aperto un rapporto di attività, con l’opzione per selezionare un [!UICONTROL Diagramma di Gantt] visualizzazione mancante nella barra degli strumenti del rapporto. Se la [!UICONTROL Diagramma di Gantt] per impostazione predefinita, la visualizzazione è selezionata per essere visualizzata nel rapporto. Viene invece visualizzato un formato di elenco.

**Clic [!UICONTROL Altro] nel rapporto non viene caricato nulla**

_Dashboard_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l&#39;esperienza sta visualizzando un rapporto su un dashboard e fanno clic sul pulsante [!UICONTROL Altro] non accade nulla e non possono visualizzare tutti gli elementi del rapporto.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento della manutenzione il 1° luglio 2021**

**La copia dei moduli non funziona**

_[!DNL Adobe Workfront Fusion]_

Quando un utente seleziona più moduli e tenta di copiarli e incollarli, i moduli non vengono incollati.

+++

+++**Aggiornamento della manutenzione il 1° luglio 2021**

**Set di colori per le carte non rispettate**

_Kanban_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l&#39;esperienza imposta i colori specifici della scheda nelle impostazioni del team; tali colori non vengono riflessi sulle schede Kanban.

**Impossibile incollare testo nel campo messaggio personalizzato**

_[!DNL Workfront Proof]_

Quando un utente crea una nuova bozza nel [!UICONTROL Visualizzatore per correzione web] e tentano di incollare testo nella [!UICONTROL Messaggio] nel campo [!UICONTROL Notifica e-mail] impossibile incollare il testo. Questo sembra accadere solo quando il testo ha la formattazione del paragrafo ed è presente un’interruzione di paragrafo.

**Le richieste vengono inviate con campi obbligatori vuoti**

_Richieste_

Quando un utente effettua una richiesta e la invia, le informazioni nei campi obbligatori non vengono inviate insieme alla richiesta.

**[!UICONTROL Nuova richiesta] pulsante mancante**

_Richieste_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l&#39;esperienza va al [!UICONTROL Richieste] pagina, [!UICONTROL Nuova richiesta] non viene visualizzato e non è possibile inviare una richiesta.

**Errore durante l’espansione di un modulo personalizzato**

_Progetti_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l’esperienza tenta di espandere un modulo personalizzato allegato a un progetto, non è in grado di aprire il modulo personalizzato e viene visualizzato il messaggio di errore &quot;[!UICONTROL Si è verificato un errore e stiamo lavorando per risolvere il problema. Per continuare il lavoro, prova ad aggiornare la pagina del browser.]&quot; L&#39;aggiornamento della pagina non risolve il problema.

**[!DNL Adobe Workfront]il branding viene ora visualizzato nelle e-mail del centro annunci**

E-mail

Come [!DNL Adobe Workfront] Il branding viene implementato in tutta l’applicazione, i seguenti aggiornamenti sono stati apportati alle e-mail del centro annunci:

* La [!DNL Adobe Workfront] il leone è stato aggiunto all&#39;area contenuto principale.
* La [!DNL Adobe Workfront] è stato aggiunto il logo al piè di pagina.

In futuro, questo marchio verrà visualizzato su ulteriori tipi di e-mail provenienti da Workfront.

+++


## Aggiornamenti a giugno 2021

+++**Aggiornamento della manutenzione il 24 giugno 2021**

**Impossibile modificare un team**

_Agile_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] clic esperienza [!UICONTROL Modifica] per aprire [!DNL Edit] Pagina del team di Agile, la pagina viene caricata inizialmente, le impostazioni scompaiono e diventa vuota.

**Dati rimossi dalla richiesta inviata**

_Richieste_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l’esperienza compila una richiesta; nella richiesta inviata mancano i valori immessi per alcuni campi personalizzati, alcuni dei quali includono campi obbligatori.

**Le colonne non vengono visualizzate**

_Kanban_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l&#39;esperienza aggiunge un [!UICONTROL Campi aggiuntivi] su una bacheca Kanban, tutte le intestazioni di colonna smettono di essere visualizzate sulla bacheca.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento della manutenzione il 23 giugno 2021**

**Collegamento interrotto rimosso nelle e-mail di notifica**

_[!DNL Adobe Workfront Fusion]_

Il collegamento alle impostazioni di notifica è stato rimosso da [!DNL Adobe Workfront Fusion] e-mail di notifica.
Per informazioni sulla modifica delle impostazioni di notifica, consulta [!DNL Adobe Workfront Fusion] organizzazioni e team.

+++

+++**Aggiornamento della manutenzione il 17 giugno 2021**

**[!UICONTROL Diagramma di Gantt] visualizzazione non disponibile per il rapporto Attività**

_Rapporti_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] viene aperto un rapporto di attività, con l’opzione per selezionare un [!UICONTROL Diagramma di Gantt] visualizzazione mancante nella barra degli strumenti del rapporto. Se la [!UICONTROL Diagramma di Gantt] per impostazione predefinita, la visualizzazione è selezionata per essere visualizzata nel rapporto. Viene invece visualizzato un formato di elenco.

**Errore del limite di caratteri non presente nelle richieste inviate**

_Richieste_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l’esperienza tenta di inviare una richiesta e supera il limite di caratteri per un campo, non è in grado di inviare la richiesta e non viene visualizzato alcun messaggio di errore. In [!DNL Adobe Workfront Classic], l&#39;utente visualizza l&#39;avviso &quot;[!UICONTROL [numero] caratteri in eccesso&quot; e quando tentano di inviare la richiesta, visualizzano il messaggio di errore &quot;Controlla quanto segue: Inserisci non più di 2000 caratteri (hai inserito [numero] caratteri).]&quot;

+++

+++**Aggiornamento della manutenzione il 10 giugno 2021**

**Le attività dei modelli riordinati non vengono spostate**

_Modelli_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] esperienza trascina un&#39;attività modello in una nuova posizione in un elenco, il numero di aggiornamenti dell&#39;attività modello, ma non riordina.

**Attività figlio non selezionate con le attività padre**

_Modelli_

Quando un utente seleziona un&#39;attività padre in un progetto creato da un modello, le attività secondarie non vengono selezionate automaticamente.

**Le fasi di modifica in linea di un elenco di attività visualizzano tutte le fasi cardine**

_Progetti_

Quando un progetto ha aggiunto un percorso cardine e un utente nel nuovo [!DNL Adobe Workfront] modifica in linea dell&#39;esperienza [!UICONTROL Milestone: Nome] nell’elenco delle attività, nel menu a discesa vengono visualizzati tutti i percorsi delle attività cardine, anziché solo i percorsi delle attività associate al progetto.

+++

+++**Aggiornamento della manutenzione il 3 giugno 2021**

**Il prompt causa l&#39;agitazione della pagina**

_Rapporti_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] esperienza esegue un rapporto con un prompt, le colonne del rapporto si spostano rapidamente da sinistra a destra.

**Alcune frasi sul [!UICONTROL Nuova prova] la pagina non viene tradotta correttamente**

_[!DNL Workfront Proof]_

Quando un utente passa alla [!UICONTROL Creazione di nuove prove] in [!DNL Workfront Proof] e il contenuto è tradotto in una lingua diversa dall&#39;inglese, alcune frasi sono ancora visualizzate in inglese.

**Etichette disattivate ed eliminate aggiunte agli utenti[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Disattivato] e [!UICONTROL Eliminato] le etichette utente sono state aggiunte alle seguenti aree in [!DNL Workfront] Prova:

* [!UICONTROL Dettagli della bozza] page
* [!UICONTROL Visualizzazione di correzione]
* [!UICONTROL Visualizzatore di bozze]
* [!UICONTROL Flussi di lavoro di correzione]
* [!UICONTROL Stampa commenti] page
* [!UICONTROL Utente] page

+++


## Aggiornamenti a maggio 2021

+++**Aggiornamento della manutenzione il 27 maggio 2021**

**[!UICONTROL Data impegno] viene visualizzato il calendario per gli aggiornamenti**

_Attività_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] è in corso l&#39;immissione di un aggiornamento su un&#39;attività, [!UICONTROL Data impegno] il calendario viene visualizzato senza che l&#39;utente selezioni [!UICONTROL Data impegno] campo .

**[!UICONTROL Altro] menu mancante da filtri, viste e raggruppamenti**

_Elenchi_

Quando un utente entra nel nuovo [!DNL Adobe Workfront] l’esperienza visualizza i filtri, le visualizzazioni o i raggruppamenti per un elenco, [!UICONTROL Altro] icona del menu mancante, che impedisce la condivisione o, se dispongono dell’accesso, la rimozione di filtri, visualizzazioni o raggruppamenti.

**Copiare e incollare un progetto [!UICONTROL Numero di riferimento] aggiunge &quot;[!UICONTROL Questo]&quot;**

_Progetti_

Quando un utente entra nel nuovo [!DNL Workfront] esperienza: passa a un progetto, copia il [!UICONTROL Numero di riferimento] dal [!UICONTROL Panoramica] area, quindi incolla, la parola &quot;[!UICONTROL Questo]&quot; viene aggiunto alla fine del numero.

**[!UICONTROL Digest giornaliero] Le e-mail vengono inviate quando sono disabilitate**

_Notifiche e-mail_

Alcuni utenti ricevono [!UICONTROL Digest giornaliero] notifiche e-mail quando non sono state abilitate nelle impostazioni utente.

**Errore non più presente nell&#39;oggetto**

_Oggetti_

Quando un utente entra nel nuovo [!DNL Workfront] esperienza tenta di aprire alcuni oggetti, vedono il messaggio di errore &quot;[!UICONTROL Il (oggetto) non esiste più: Potrebbe aver digitato l&#39;indirizzo web per errore. Verificare e riprovare a immettere l&#39;indirizzo.]&quot; Il collegamento oggetto viene comunque visualizzato in elenchi, recenti, preferiti, risultati della ricerca, ecc., ma non è possibile accedervi e non viene visualizzato nel Cestino con oggetti eliminati.



+++

+++**Aggiornamento della manutenzione il 20 maggio 2021**

**Opzioni di prova mancanti**

_Bozze_

Quando un utente carica un&#39;altra versione di una bozza in [!DNL Workfront], [!UICONTROL Prova aperta] e [!UICONTROL Flusso di lavoro di correzione] Mancano collegamenti, facendo sembrare che si tratti di un documento invece di una prova. Se mancano questi collegamenti, l’etichetta [!UICONTROL In sospeso] visualizza e altri utenti non sono in grado di generare la bozza mentre è in questo [!UICONTROL In sospeso] stato.

**Utenti che non ricevono consegne di report pianificati**

_Rapporti_

Quando alcuni rapporti sono pianificati per la consegna dei rapporti, a volte gli utenti non ricevono i rapporti.

**Impossibile rimuovere l&#39;accesso per il modello di layout**

_Dashboard_

Quando un utente apre [!UICONTROL Condivisione] opzioni di una dashboard per rimuovere l’accesso a un modello di layout, no [!UICONTROL Elimina] accanto al modello di layout viene visualizzata l’icona che non è in grado di rimuovere l’accesso.

+++

+++**[!DNL Workfront Fusion]Aggiornamento della manutenzione il 17 maggio 2021**

**Il dashboard dell&#39;organizzazione ora visualizza correttamente il numero di scenari attivi**

_[!DNL Workfront Fusion]_

La [!UICONTROL Organizzazione] in precedenza, il dashboard mostrava un campo vuoto invece del numero di scenari utilizzati.

**La ricerca nell’archivio dati ora mostra le etichette delle colonne**

_[!DNL Workfront Fusion]_

Le strutture di dati che utilizzavano le etichette di colonna visualizzavano in precedenza il nome della colonna nel [!UICONTROL esplorazione archivio dati] visualizza.  Ora viene visualizzata l’etichetta della colonna.  Se non è identificata alcuna etichetta per la colonna, viene visualizzato il nome della colonna.

**L&#39;errore di inizializzazione dello scenario non influisce più sui dati del webhook**

_[!DNL Workfront Fusion]_

In precedenza, uno scenario avviato da un webhook (inclusi quelli che utilizzano eventi in tempo reale per attivare) che ha rilevato un errore durante l&#39;inizializzazione dello scenario potrebbe causare la perdita dell&#39;accesso ai dati del webhook.  Ora, se si verifica un errore durante l&#39;inizializzazione dello scenario (ad esempio non è possibile verificare una connessione), i dati del webhook verranno mantenuti nella coda del webhook e l&#39;esecuzione viene ritentata automaticamente.  Dopo tre tentativi non riusciti, lo scenario viene disattivato e le informazioni rimarranno comunque nella coda.

**I record nelle code del webhook vengono ora elaborati in batch più piccoli**

_[!DNL Workfront Fusion]_

Precedentemente, se un utente attivava uno scenario inattivo che aveva una coda di webhook associata di molti record, [!DNL Workfront Fusion] tenta di elaborare l&#39;intera coda in un&#39;unica esecuzione (anche se con più cicli).  A seconda della quantità di record elaborati, ciò potrebbe talvolta causare il superamento del tempo massimo di esecuzione della singola esecuzione (40 minuti).  Ora, quando si attiva uno scenario inattivo che ha una coda di record del webhook associata, Workfront Fusion elaborerà fino al numero massimo di record identificati in una singola esecuzione (di solito 2 record per esecuzione).

**Gli archivi dati ora visualizzano correttamente i valori &quot;0&quot;**

_[!DNL Workfront Fusion]_

In precedenza, i valori dell&#39;archivio dati pari a 0 venivano visualizzati come vuoti. &lt;...>

+++

+++**Aggiornamento della manutenzione il 13 maggio 2021**

**Il calendario a discesa viene visualizzato dietro la [!UICONTROL Lavoro non assegnato] header**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente passa alla [!UICONTROL Bilanciamento del carico di lavoro] in [!DNL Workfront Classic], la parte superiore del datepicker è nascosta dietro il [!UICONTROL Lavoro non assegnato] , che impedisce all’utente di passare a diversi mesi.

**Impossibile incollare testo nel campo messaggio personalizzato**

_[!DNL Workfront Proof]_

Nota: Questo problema sembra influenzare solo il [!DNL Google Chrome] browser web in questo momento.

Quando un utente crea una nuova bozza in [!DNL Workfront Proof] e tentano di incollare testo da un’e-mail all’interno di [!UICONTROL Messaggio] nel campo [!UICONTROL Notifica e-mail] impossibile incollare il testo.

**Campi non supportati visualizzati nel generatore**

_Moduli personalizzati_

Quando un utente crea un modulo personalizzato e tenta di creare un campo calcolato utilizzando un campo dinamico, ad esempio [!UICONTROL Numero di rischi aperti]- la casella di calcolo evidenzia il rosso e non consente di salvare le modifiche. I campi dinamici non devono essere visualizzati nel selettore per i campi calcolati.

**Anteprima delle attività in [!UICONTROL Elenco lavori] non si carica**

_Pagina principale_

Quando un utente entra nel nuovo [!DNL Workfront] l’esperienza viene assegnata a un modello di layout che include campi personalizzati in [!UICONTROL Pagina principale], la pagina non risponde e non carica le attività dal [!UICONTROL Elenco lavori] se gli utenti li selezionano.

**Oggetti in [!UICONTROL Elenco lavori] senza caricamento [!UICONTROL Pagina principale]**

_[!UICONTROL Pagina principale]_

Quando un utente fa clic su un oggetto nel [!UICONTROL Elenco dei lavori domestici], l’intestazione dell’oggetto viene visualizzata nel pannello di destra, ma i dettagli dell’oggetto non vengono visualizzati. Alla fine l&#39;utente visualizza il messaggio &quot;[!UICONTROL Pagine non reattive.]&quot;

**Problemi relativi ai campi RTF in[!DNL Microsoft Outlook]**

_Integrazioni Workfront_

Quando un utente aggiorna un campo di testo RTF con [!DNL Workfront for Outlook] non sono in grado di:

* Backspace
* Copia testo
* Incolla il testo
* Invia una richiesta quando tutti i campi sono compilati

+++

+++**Aggiornamento della manutenzione il 6 maggio 2021**

**[!UICONTROL Valuta] campo non funzionante come previsto**

_Elenchi_

Quando un utente prova a modificare in linea il CurrCampo di aggiornamento in un elenco, non sono in grado di salvare le modifiche a causa dei seguenti problemi:

* Elenco attività e problemi che non consentono l&#39;immissione di simboli di valuta
* Elenchi che non consentono l’immissione di abbreviazioni di valuta quando si utilizzano impostazioni internazionali diverse dall’inglese
* Elenchi di sottoattività ed emissioni che consentono solo l&#39;abbreviazione della valuta di USD, indipendentemente dalla divisa del progetto impostata

**Nome non aggiornato per corrispondere al nuovo nome della bozza**

_Documenti_

Quando un utente crea una nuova versione di una bozza e aggiorna il nome della bozza, l&#39;oggetto documento in [!DNL Workfront] Mantiene il nome originale invece di corrispondere al nuovo nome della bozza.

**[!UICONTROL Business case] i pulsanti non funzionano quando i moduli personalizzati sono collegati**

_Progetti_

Quando un progetto nel nuovo [!DNL Workfront] l&#39;esperienza viene creata a partire da un modello di progetto ed è presente un modulo personalizzato allegato, gli utenti non possono inviare, rifiutare o approvare un caso aziendale.

**Prove archiviate visualizzate su elenchi e rapporti**

_Bozze_

Quando un utente visualizza il proprio elenco di lavoro in [!UICONTROL Pagina principale] o [!UICONTROL Il mio lavoro], le bozze già archiviate vengono visualizzate nell’elenco. Le bozze archiviate vengono visualizzate anche nei rapporti e nelle dashboard.

**Il progetto creato dal modello presenta impostazioni di accesso errate**

_Progetti_

Quando un utente crea un progetto da un modello, le impostazioni di accesso del modello non vengono riportate nel nuovo progetto creato.

**Oggetti in [!UICONTROL Elenco lavori] senza caricamento [!UICONTROL Pagina principale]**

_[!UICONTROL Pagina principale]_

Quando un utente fa clic su un oggetto nel [!UICONTROL Elenco dei lavori domestici], l’intestazione dell’oggetto viene visualizzata nel pannello di destra, ma i dettagli dell’oggetto non vengono visualizzati. Alla fine l&#39;utente visualizza il messaggio &quot;[!UICONTROL Pagine non reattive.]&quot;

+++


## Aggiornamenti nell’aprile 2021

+++**Aggiornamento della manutenzione il 29 aprile 2021**

**[!DNL SharePoint]l&#39;integrazione si autentica utilizzando le credenziali di un&#39;integrazione separata**

_Integrazioni Workfront_

Quando un utente ne ha più di uno [!DNL SharePoint] integrazione, una [!DNL SharePoint] l&#39;autenticazione tenta di eseguire l&#39;autenticazione utilizzando le credenziali di un altro [!DNL SharePoint] integrazione.

**Impossibile caricare o esportare file da [!DNL Adobe] products**

_Integrazioni Workfront_

Quando un utente tenta di caricare o esportare i file utilizzando il [!DNL Workfront for Adobe Creative Cloud] integrazione, visualizzano il messaggio di errore &quot;[!UICONTROL Impossibile leggere la proprietà &#39;stage&#39; di undefined]&quot; e non sono in grado di caricare o esportare i file.

**I file non sono visibili in[!DNL Internet Explorer]**

_Documenti_

Quando un utente ha un [!DNL Internet Explorer] il browser passa alla [!UICONTROL Documenti] area di un oggetto [!UICONTROL Documenti] La schermata è vuota e non carica i file. Per alcuni utenti, la schermata carica alcuni file, ma il numero di file visualizzati non corrisponde al numero visualizzato accanto al [!UICONTROL Documenti] sezione .

+++

+++**Aggiornamento della manutenzione il 22 aprile 2021**

**Attività aggiunte nell’ordine errato**

_Modelli_

Quando un utente aggiunge un&#39;attività a un modello, l&#39;attività non riceve il numero di attività previsto e l&#39;attività viene aggiunta nel punto sbagliato.

**Le bozze vengono ora combinate in un’unica e-mail**

_Bozze_

[!DNL Workfront] ora invia un’e-mail per le bozze combinate anziché un’e-mail per ogni file incluso.
+++

+++**[!DNL Workfront Fusion]Aggiornamento della manutenzione il 15 aprile 2021**

**&quot;[!UICONTROL Scenario rifiutato]&quot; errore durante l&#39;esecuzione di uno scenario**

_[!DNL Workfront Fusion]_

Quando un utente tenta di eseguire uno scenario, lo scenario non viene eseguito e l&#39;utente riceve il messaggio &quot;[!UICONTROL Scenario rifiutato.]&quot;

+++

+++**Aggiornamento della manutenzione il 15 aprile 2021**

**[!UICONTROL Bilanciamento del carico di lavoro] visualizza ore pianificate non corrette**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente visualizza le ore pianificate di un&#39;attività nel [!UICONTROL Bilanciamento del carico di lavoro] il valore delle ore pianificate non corrisponde alle ore pianificate assegnate all&#39;attività.

**La barra di navigazione superiore non è visibile in[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Quando un utente passa a qualsiasi [!DNL Workfront Proof] pagina diversa dalla pagina Dashboard, la barra di navigazione superiore scompare. L’utente non è in grado di accedere alla funzionalità nella barra di navigazione, ad esempio le impostazioni dell’account o il profilo.

**Miglioramento dei moduli personalizzati**

_Moduli personalizzati nel mio gruppo_

Per una migliore esperienza durante la compilazione di un modulo personalizzato, è stato migliorato il modo in cui vengono visualizzate le etichette dei campi personalizzati di lunga data. Quando c&#39;è abbastanza spazio orizzontale per mostrarle tutte, queste etichette non vengono più troncate.

+++

+++**Aggiornamento della manutenzione l’8 aprile 2021**

**Impossibile creare bozze in [!DNL Adobe Creative Cloud] integrazione**

_Integrazioni Workfront_

Quando un utente tenta di creare una bozza direttamente dal [!DNL Adobe Creative Cloud], la bozza non viene generata.

+++

+++**Aggiornamento della manutenzione il 1 aprile 2021**

**Problemi relativi alla visualizzazione del pannello di riepilogo in[!DNL Chrome]**

_[!UICONTROL Riepilogo]_

Quando un utente apre la [!UICONTROL Riepilogo] quando si utilizza il pannello [!DNL Chrome] , l’interfaccia utente del pannello di riepilogo non si comporta come previsto. L’utente non è in grado di scorrere, le icone potrebbero scomparire e il contenuto potrebbe sovrapporsi ad altri contenuti.

**[!UICONTROL Team] area [!UICONTROL Configurazione] non visualizzare tutti i team**

_[!UICONTROL Configura]_

Quando un amministratore accede alla pagina [!UICONTROL Team] area [!UICONTROL Configurazione], possono visualizzare solo i team creati. I team creati da altri amministratori non sono visibili.

**Impossibile aggiungere aggiornamenti al progetto in [!UICONTROL Approvazione in sospeso] status**

_Progetti_

Se un utente tenta di aggiungere un aggiornamento a un progetto in [!UICONTROL Approvazione in sospeso] e non sono l’utente assegnato per l’approvazione del progetto, l’aggiornamento non viene aggiunto e viene visualizzato il seguente avviso:

Un progetto con &quot;[!DNL Pending Approval]Impossibile modificare lo stato di &quot;. Puoi modificare il progetto modificando lo stato.

+++


## Aggiornamenti a marzo 2021

+++**Aggiornamento della manutenzione il 26 marzo 2021**

**I pulsanti in un caso aziendale vengono visualizzati in modo errato**

_Progetti_

Quando un utente visualizza un business case e la finestra è in modalità a schermo intero, la [!UICONTROL Salva] e [!UICONTROL Annulla] i pulsanti vengono visualizzati vicino al centro dello schermo e si sovrappongono agli elementi del business case.

**Impossibile modificare l&#39;ordinamento di un report**

_Rapporti_

Quando un utente tenta di modificare l’ordinamento di un rapporto nel nuovo [!DNL Workfront] esperienza, l&#39;ordinamento non cambia dall&#39;ordinamento selezionato al momento della creazione del rapporto.

**Condivisione di elementi disabilitati su nuove prove**

_[!DNL Workfront Proof]_

Quando un utente ha [!UICONTROL Condivisione pubblica] se attivata nelle impostazioni di bozza predefinite, viene creata una bozza; la bozza viene creata con la condivisione disabilitata. Altri utenti non possono visualizzare il [!UICONTROL Condividi] o condividere la bozza.

**&quot;[!UICONTROL Impossibile generare la bozza]&quot; errore durante la creazione della bozza**

_[!DNL Workfront Proof]_

Quando un utente tenta di creare una bozza, la bozza non viene creata e l’utente visualizza il seguente messaggio di errore:

&quot;[!UICONTROL Impossibile generare la bozza. Errore interno]&quot;

+++

+++**[!DNL Workfront Fusion]Aggiornamento della manutenzione il 25 marzo 2021**

**Raccolta o campo di riferimento ridondanti rimosso dal pannello di mappatura**

_[!DNL Workfront Fusion]2,0_

Quando un utente utilizza un termine del [!DNL Workfront] API per selezionare una raccolta o un campo di riferimento da includere nell&#39;output di un [!DNL Workfront] modulo, l&#39;output per quel modulo mostra quel campo con due punti (ad esempio [!UICONTROL proprietario:nome]) e anche negli attributi (il nome è un campo in proprietario). Il campo contrassegnato con due punti non contiene dati e fornisce dati errati se mappato a un modulo in un secondo momento nello scenario.

+++

+++**[!DNL Workfront Fusion]Aggiornamento della manutenzione il 18 marzo 2021**

**Le impostazioni dei modelli di progetto ora si applicano ai progetti creati tramite [!DNL Workfront Fusion] 2,0**

_[!DNL Workfront Fusion]2,0_

Quando crei un progetto da un modello utilizzando [!DNL Workfront Fusion] 2.0, le impostazioni del modello vengono applicate al nuovo progetto. Questo comportamento è lo stesso quando si crea un progetto da un modello nel [!DNL Workfront] applicazione.

+++

+++**Aggiornamento della manutenzione il 18 marzo 2021**

**Le impostazioni dei modelli di progetto ora si applicano ai progetti creati tramite API**

_[!DNL Workfront]API_

Quando crei un progetto da un modello utilizzando [!DNL Workfront] API, le impostazioni del modello vengono applicate al nuovo progetto. Questo comportamento è lo stesso quando si crea un progetto da un modello nel [!DNL Workfront] applicazione.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 15 marzo 2021**

**Il componente condiviso non funziona come previsto**

_[!DNL Workfront Proof]_

Se indipendente [!DNL Workfront Proof] gli account vengono spostati in un componente condiviso, le seguenti funzionalità possono verificarsi quando un utente aggiunge una nuova versione di una bozza o di un documento:

* Impossibile eliminare l&#39;utente [!UICONTROL Prove da studio].
* Il messaggio predefinito non viene visualizzato nella nuova versione.

**La condivisione di collegamenti pubblici non è abilitata nella nuova versione di una bozza**

_Documenti_

Quando un utente abilita la condivisione di collegamenti pubblici su una bozza e successivamente carica una nuova versione della bozza, la condivisione di collegamenti pubblici non viene abilitata automaticamente sulla nuova versione della bozza.

**[!UICONTROL Approva], [!UICONTROL Modifiche], [!UICONTROL Rifiuta] pulsanti mancanti dalla bozza**

_[!DNL Workfront Proof]_

Quando un utente visualizza una bozza nel visualizzatore delle prove, il [!UICONTROL Approva], [!UICONTROL Modifiche]e [!UICONTROL Rifiuta] nella parte superiore dello schermo mancano i pulsanti.

**Impossibile modificare l&#39;ordinamento di un report**

_Rapporti_

Quando un utente tenta di modificare l’ordinamento di un rapporto nel nuovo [!DNL Workfront] esperienza, l&#39;ordinamento non cambia dall&#39;ordinamento selezionato al momento della creazione del rapporto.

**Messaggio personalizzato sulla prova che non ritorna alla nuova versione**

_[!DNL Workfront Proof]_

Quando un utente allega un messaggio personalizzato a una bozza e quindi carica una nuova versione della bozza, il messaggio personalizzato non viene visualizzato nella nuova bozza.

**L&#39;elenco utenti non viene visualizzato**

_Elenchi_

Quando un utente tenta di visualizzare un elenco di utenti e la visualizzazione include il[!UICONTROL Icone di stato]&quot;, l&#39;elenco non viene visualizzato.

**&quot;[!UICONTROL Notifica ai destinatari questa bozza]&quot; opzione disabilitata indipendentemente dalle impostazioni del flusso di lavoro**

_[!DNL Workfront Proof]_

Quando un utente crea una nuova bozza e non attiva manualmente il pulsante &quot;[!UICONTROL Notifica ai destinatari questa bozza]&quot;, il destinatario previsto non viene informato. Questo vale anche se l’opzione è abilitata nelle impostazioni del flusso di lavoro.

**Impossibile modificare l&#39;intervallo di tempo**

_[!UICONTROL Analisi avanzata]_

Quando un utente visualizza [!UICONTROL Analisi migliorata] e clicca sul calendario per regolare l&#39;intervallo di date, le date non cambiano.

**Impossibile scaricare il documento condiviso pubblicamente**

_Documenti_

Quando un utente fa clic su un collegamento condiviso per scaricare un documento, il documento non viene scaricato e l&#39;utente visualizza un errore dal browser che indica che la pagina non esiste.

+++

+++**Aggiornamento della manutenzione l’11 marzo 2021**

**Sezione del modulo personalizzato non esportata per non amministratori**

_Moduli personalizzati_

Se un modulo personalizzato allegato a un oggetto presenta un’interruzione di sezione che richiede qualcosa di precedente a &quot;[!UICONTROL Visualizza]&quot; accesso necessario per visualizzare il contenuto della sezione, il contenuto della sezione non può essere esportato da altri utenti che non siano amministratori.

**Il documento scaricato ha un nome non corretto**

_[!DNL Workfront Proof]_

Quando un utente scarica un documento dal [!UICONTROL Visualizzatore di prove], il del documento ha il nome di una versione precedente del documento, non la versione scaricata.

+++

+++**Aggiornamento della manutenzione il 4 marzo 2021**

**Errore durante l’accesso al modello di layout**

_Modelli di layout_

Quando un utente si è iscritto al nuovo [!DNL Workfront] passa a [!DNL Classic] esperienza e tentativi di accesso a un [!DNL Classic] modello layout, vedono l&#39;errore &quot;[!UICONTROL La pagina non esiste.]&quot;

**Impossibile modificare i filtri nel [!UICONTROL Bilanciamento del carico di lavoro]**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente tenta di modificare un filtro nel [!UICONTROL Bilanciamento del carico di lavoro], il generatore di filtri non si apre.

**&quot;[!UICONTROL Visualizza tutte le notifiche]&quot; link in email notification reindirizza a pagina errata**

_Notifiche e-mail_

Quando un utente fa clic su &quot;[!UICONTROL Visualizza tutte le notifiche]&quot; in una notifica e-mail, vengono reindirizzati a una pagina con il seguente messaggio:

&quot;[!UICONTROL L&#39;utente non esiste più. L’indirizzo web potrebbe non essere digitato correttamente. Controllalo e prova di digitarlo di nuovo.]&quot;

**L’utente non viene indirizzato al commento di bozza a cui è stato applicato il tag**

_Notifiche e-mail_

Quando un utente ha i tag in un commento di bozza e fa clic sul pulsante [!UICONTROL Vai a prova] in una notifica e-mail, sono indirizzati alla bozza ma non al commento specifico. Se l’utente è in [!DNL Workfront Classic], sono dirette al [!UICONTROL Dettagli documento] al posto del commento nella bozza.

**Utenti aggiunti a [!DNL Workfront] ricezione di notifiche e-mail**

_[!DNL Workfront Proof]_

Quando un utente che non è nel flusso di lavoro apre una bozza da [!DNL Workfront], il sistema crea automaticamente un&#39;area di visualizzazione, aggiunge l&#39;utente alla bozza e invia un [!UICONTROL Nuova bozza] notifica via e-mail.

**Il pannello di riepilogo del documento si oscura, rendendo le azioni non disponibili**

_Documenti_

Quando un utente si trova su una pagina del documento e passa il mouse sul pannello di riepilogo del documento, il pannello si oscura e può mostrare altri pulsanti. L’utente non può fare clic sulle azioni nel pannello di riepilogo.

**Modifica delle prestazioni del flusso di lavoro**

_Aggiorna flusso_

Abbiamo ridotto il numero di aggiornamenti utente visualizzati nella [!UICONTROL Aggiornamenti] da 50 a 25 alla volta per migliorare le prestazioni.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 1° marzo 2021**

**Le nuove e-mail di bozza non vengono inviate**

_[!DNL Workfront Proof]_

NOTA: Questo problema è stato risolto nel nuovo [!DNL Workfront] esperienza il 26 febbraio 2021.
È stato risolto nel [!DNL Classic] esperienza del 1° marzo 2021.

Quando un utente crea una nuova bozza e abilita l’opzione [!UICONTROL Notifica ai destinatari questa bozza], non viene inviata alcuna e-mail di notifica al destinatario.

+++


## Aggiornamenti a febbraio 2021

+++**Aggiornamento della manutenzione il 25 febbraio 2021**

**[!UICONTROL Pianificazione] lo strumento non viene caricato in nessuna area**

_Gestione risorse_

Quando un utente con un apostrofo nel suo nome utente tenta di accedere al [!UICONTROL Pianificazione] entrare nello strumento [!DNL Workfront Classic], la pagina è vuota e lo strumento non viene mai caricato.

**Il nome non cambia nelle nuove versioni della bozza**

_Documenti_

Quando un utente entra nel nuovo [!DNL Workfront] experience carica una nuova versione di un documento con un nome diverso. il nome non viene aggiornato per corrispondere al nome della versione più recente.

**[!UICONTROL Condivisione documenti] errore durante l’eliminazione di progetti**

_Progetti_

Quando un utente amministratore di sistema ha accesso a un progetto copiato e tenta di eliminarlo o di eliminarlo nel progetto, non è in grado di eliminare l&#39;oggetto e viene visualizzato l&#39;errore &quot;[!UICONTROL Condivisione documenti con valori chiave principali non trovata.]&quot;

**Il rapporto utente non applica tutti i filtri**

_Rapporti_

Quando un utente entra nel nuovo [!DNL Workfront] crea un rapporto utente con una regola di filtro che include [!UICONTROL ID principale] non vengono applicate altre regole di filtro nel rapporto.

**Campi calcolati non ricalcolati dopo le modifiche**

_Moduli personalizzati_

Quando un utente entra nel nuovo [!DNL Workfront] l’esperienza modifica e salva un modulo personalizzato contenente campi calcolati, questi campi non vengono aggiornati.

**Documenti che vengono eliminati quando il modulo personalizzato viene eliminato**

_Moduli personalizzati_

Quando un utente entra nel nuovo [!DNL Workfront] esperienza elimina un modulo personalizzato Documenti allegato ai documenti, nonché tali documenti vengono eliminati.

+++

+++**Aggiornamento della manutenzione il 18 febbraio 2021**

**Casella di controllo non necessaria rimossa [!UICONTROL Richieste] area**

_Richieste_

Abbiamo rimosso la casella di controllo a sinistra dei nomi delle richieste nell&#39;elenco Inviato della [!UICONTROL Richieste] area. Questa casella di controllo non era connessa ad alcuna funzionalità, pertanto l&#39;abbiamo rimossa per eliminare un&#39;esperienza confusa.

**Impossibile accedere ai documenti dai collegamenti**

_Documenti_

Quando un utente entra nel nuovo [!DNL Workfront] l&#39;esperienza fa clic su alcuni collegamenti ai documenti, non sono in grado di accedere al documento e visualizzano il messaggio di errore &quot;[!UICONTROL Il documento non esiste più: Potrebbe aver digitato l&#39;indirizzo web per errore. Verificare e riprovare a immettere l&#39;indirizzo.]&quot; Lo stesso errore si verifica con [!UICONTROL Visualizza dettagli] collegamento nelle notifiche e-mail a prova di .

+++

+++**Aggiornamento sulla manutenzione di Workfront Fusion il 16 febbraio 2021**

**[!DNL Workfront Fusion]2.0 mostra fusi orari non accurati**

_Scenari_

Questo aggiornamento ha risolto un problema in cui [!DNL Fusion] 2.0 visualizzava i fusi orari utente in modo non accurato. Gli utenti possono ora visualizzare il proprio fuso orario nei campi di input per le date.

+++

+++**Aggiornamento della manutenzione l’11 febbraio 2021**

**Le bozze non vengono caricate nella cartella selezionata**

_[!DNL Workfront Proof]_

Quando un utente apre una cartella e ne aggiunge una nuova, la bozza viene caricata nel generale [!UICONTROL Documenti] area dell’oggetto anziché all’interno della cartella.

**Troppe pagine bloccate causano la scomparsa della navigazione superiore**

_Navigazione_

Quando un utente ha più di 60 pagine bloccate, la navigazione in alto smette di essere visualizzata, impedendo all’utente di accedere [!UICONTROL Ricerca], [!UICONTROL Menu principale], [!UICONTROL Notifiche]e altro ancora.

**L&#39;utente non può digitare testo nel campo RTF**

_Elenchi_

Quando un utente tenta di modificare in linea un campo di testo RTF, può digitare un solo carattere.

+++

+++**Aggiornamento della manutenzione il 4 febbraio 2021**

**Mostra report esportati [!DNL Workfront Classic] branding**

_Rapporti_

Quando un utente nella nuova esperienza Workfront esporta un rapporto, il logo visualizzato nel rapporto esportato corrisponde al [!DNL Workfront Classic] impostazioni trovate in [!UICONTROL Configurazione] > [!UICONTROL Sistema] > [!UICONTROL Branding].

+++


## Aggiornamenti a gennaio 2021

+++**Aggiornamento della manutenzione il 28 gennaio 2021**

**Commenti non visualizzati &quot;[!UICONTROL a nome di]&quot;**

_Aggiornamenti_

Quando un [!DNL Workfront] l’amministratore effettua l’accesso come un altro utente e risponde a un commento nel [!UICONTROL Aggiornamenti] area di un oggetto, testo &quot;[!UICONTROL a nome di]&quot; non viene visualizzato prima del nome utente.

**Impossibile allegare un documento**

_Richieste_

Quando un utente entra nel nuovo [!DNL Workfront] esperienza tenta di aggiungere un documento a una nuova richiesta di un provider di documenti esterno, il [!UICONTROL Documenti] l&#39;elenco non viene caricato, il che impedisce all&#39;utente di selezionare il documento e completare la richiesta.

**La larghezza dello schermo si espande a destra, causando problemi di navigazione**

_[!UICONTROL Calendario Home]_

Quando un utente entra nel nuovo [!DNL Workfront] l&#39;esperienza apre [!UICONTROL Calendario Home] e hanno oggetti dovuti in alcune settimane, lo schermo si espande a destra, impedendo loro di visualizzare l&#39;intera settimana contemporaneamente. Se l&#39;utente seleziona un elemento per aprire il [!UICONTROL Dettagli] in questo stato e desiderano visualizzare i dettagli di un altro elemento, devono scorrere a sinistra, che chiude il [!UICONTROL Dettagli] pannello.

**Etichetta del processo di approvazione monouso corretta**

_Progetti_

Quando si utilizza un processo di approvazione a uso singolo per un progetto nel nuovo [!DNL Workfront] esperienza, ora viene visualizzato come &quot;[!UICONTROL Processo di approvazione a uso singolo]&quot; invece di &quot;\&lt;custom>&quot; nel [!UICONTROL Modifica progetto] scatola. Non è ancora disponibile per attività e problemi.

**Aspetto dei moduli personalizzati migliorato**

_Progetti_

È stato migliorato l’aspetto e l’aspetto dell’utilizzo dei moduli personalizzati nella nuova [!DNL Workfront] esperienza per i progetti.

**La funzionalità API per la valuta del progetto ora corrisponde alla funzionalità in-app**

_Progetti_

Non è possibile modificare la valuta di un progetto se nel progetto sono già presenti informazioni finanziarie. Con l’ultimo aggiornamento di manutenzione, la funzionalità API per questo caso ora corrisponde all’esperienza in [!DNL Workfront] interfaccia.

**Non genera automaticamente la settimana successiva**

_Schede orario_

Quando un utente passa alla [!UICONTROL Schede temporali] visualizza solo la scheda attività della settimana corrente. La scheda attività per le prossime settimane non viene generata automaticamente.

+++

+++**Aggiornamento della manutenzione il 21 gennaio 2021**

**L’ordinamento manuale in base a una colonna mostra tutti i risultati**

_Rapporti_

Quando un utente entra nel nuovo [!DNL Workfront] l’esperienza fa clic su una barra nel grafico di un rapporto, quindi fa clic su un’intestazione di colonna per ordinare manualmente i risultati di tale raggruppamento, vengono visualizzati tutti i risultati del rapporto e non solo i risultati del raggruppamento selezionato originariamente.

**&quot;[!UICONTROL Consenti condivisione di prove tramite URL o codice di incorporamento]&quot; modifica delle impostazioni**

_[!DNL Workfront Proof]_

Quando un utente crea una bozza e deseleziona l’impostazione [!UICONTROL Consenti condivisione di prove tramite URL o codice di incorporamento], l’impostazione viene nuovamente controllata dopo la generazione della bozza. Se l’utente lascia selezionata l’impostazione , questa viene deselezionata dopo la generazione della bozza.

**[!DNL Mac]gli utenti non possono incollare nei campi di testo nel visualizzatore di prove**

_[!DNL Workfront Proof]_

Quando un utente tenta di incollare del testo in determinati campi nel visualizzatore di prove, il testo non viene visualizzato nel campo.

+++

+++**Aggiornamento della manutenzione il 14 gennaio 2021**

**Impossibile aggiornare le impostazioni di Notifiche e-mail**

_Configura_

Quando un utente prova ad aggiornare le impostazioni per le notifiche e-mail, non può accedere al [!UICONTROL Notifiche e-mail] e visualizza il messaggio di errore &quot;[!UICONTROL Proviamolo ancora. Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

**[!UICONTROL Diagramma di Gantt] causa il troncamento di alcuni campi**

_Elenchi_

Quando un utente apre la [!UICONTROL Diagramma di Gantt] in alcune aree elenco, alcuni campi, ad esempio [!UICONTROL Descrizione]- tronca il testo. Per visualizzare il testo completo, l’utente deve fare doppio clic sul campo.

**Impossibile inviare file da [!UICONTROL Dettagli documento]**

_Documenti_

Quando un utente entra nel nuovo [!DNL Workfront] tenta di inviare un documento dal [!UICONTROL Dettagli documento] page, visualizzano il messaggio di errore &quot;[!UICONTROL Si è verificato un errore e stiamo lavorando per risolvere il problema. Per continuare il lavoro, prova ad aggiornare la pagina del browser.]&quot;

+++

+++**Aggiornamento della manutenzione il 7 gennaio 2021**

**Si chiude la finestra di dialogo Delega approvazioni**

_Pagina principale_

Quando un utente prova a delegare le approvazioni in [!UICONTROL Pagina principale] e fanno clic su una data, la finestra di dialogo viene chiusa senza selezionare la data o consentire all’utente di completare la delega dell’utente.

**Problema relativo allo spostamento di un documento in un&#39;attività**

_Documenti_

Quando un utente tenta di spostare un documento o una bozza nel nuovo [!DNL Workfront] esperienza, alcune attività al di fuori del progetto non elencano il progetto padre come previsto.

**Il nome di PDF scaricato non è corretto**

_[!DNL Workfront Proof]_

Quando un utente riceve un collegamento per il download tramite e-mail ([!UICONTROL Prova] > [!UICONTROL Stampa commenti] > [!UICONTROL PDF]) ed esportano il file, il file scaricato è denominato con numeri casuali anziché con l’ID bozza.

+++
