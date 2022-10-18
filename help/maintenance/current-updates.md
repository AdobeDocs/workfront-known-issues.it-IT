---
title: Aggiornamenti alla manutenzione di Workfront
description: Aggiornamenti di manutenzione per [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: efb3af8506cf73ac7a5fe7e9f756356fdb298158
workflow-type: tm+mt
source-wordcount: '14458'
ht-degree: 3%

---

# [!DNL Workfront] Aggiornamenti di manutenzione

Nel 2022 sono stati effettuati i seguenti aggiornamenti di manutenzione.

>[!NOTE]
>
>Questi aggiornamenti includono anche altre correzioni di bug minori o meno importanti. [!DNL Workfront] Il supporto ti avviserà quando un problema inviato verrà risolto.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Per gli aggiornamenti di manutenzione precedenti al 2022, vedi [Aggiornamenti precedenti alla manutenzione](#previous-maintenance-updates)

## Aggiornamenti a ottobre 2022

+++**Aggiornamento della manutenzione il 20 ottobre 2022**

**Errore durante l&#39;assegnazione in massa di un team**

*Assegnazioni*

Quando un utente modifica in serie attività o problemi e assegna un team dopo l&#39;assegnazione di un singolo utente, le assegnazioni non vengono salvate e l&#39;utente visualizza il seguente errore:

&quot;[!UICONTROL Proviamo di nuovo - Si è verificato il seguente errore: teamAssignments deve essere un elenco di oggetti o un elenco di ID]&quot;

**[!UICONTROL Impossibile caricare il file]&quot; Errore**

*Documenti*

Quando un utente tenta di caricare un file nel [!UICONTROL Documenti] area, il file non viene caricato e l&#39;utente visualizza l&#39;errore &quot;[!UICONTROL Impossibile caricare il file].&quot;

Questo è stato riportato durante il tentativo di caricare file MP4.

**Il conteggio dei problemi nella navigazione a sinistra dell&#39;attività non è corretto**

*problemi*

Quando un utente visualizza un&#39;attività, il numero visualizzato nella [!UICONTROL Problemi] la sezione della navigazione a sinistra non rappresenta con precisione il numero effettivo di problemi associati all&#39;attività.


**[!UICONTROL Predecessore] icona mancante nell&#39;intestazione dell&#39;attività**

*Attività*

Quando un utente visualizza un&#39;attività, l&#39;icona del predecessore attività risulta mancante nell&#39;intestazione.

+++

+++**Aggiornamento della manutenzione il 13 ottobre 2022**

**Impossibile ripetere il pin di una pagina dopo la rimozione del pin**

*Navigazione*

>[!NOTE]
>
>Questo problema verrà risolto in Anteprima il 13 ottobre 2022. Sarà fissato in Produzione il 27 ottobre 2022.

Quando un utente seleziona il &quot;[!UICONTROL Rimuovi perno]&quot; opzione su un pin, riceve un messaggio sulla rimozione e tenta di sostituire il pin facendo clic su &quot;[!UICONTROL Annulla]&quot; nel messaggio, il pin non viene sostituito nella navigazione superiore, né viene aggiunto all&#39;elenco dei pin sotto il [!UICONTROL Altri pin] (il menu a tre punti nel [!UICONTROL Pins] area).

Se un utente tenta di fissare nuovamente la pagina passando alla pagina e fissandola, il pin non viene creato e l’utente non può fissare la pagina.

**Impossibile assegnare un nome o salvare i filtri appena creati**

*[!UICONTROL Pianificazione risorse]*

Quando un utente tenta di denominare un nuovo filtro nel [!UICONTROL Planner risorse], la casella del nome rimane vuota. Inoltre, se l&#39;utente ha premuto la barra spaziatrice, la [!UICONTROL Salva] pulsante disattiva.

**Impossibile modificare il nome o la percentuale di completamento di un&#39;attività o di un problema**

*Attività e problemi*

Utenti con [!UICONTROL Collaborare] l&#39;accesso a un&#39;attività o a un problema non può modificare il nome dell&#39;attività o del problema nell&#39;intestazione. Inoltre, gli utenti con [!UICONTROL Collaborare] impossibile modificare la percentuale di completamento di un&#39;attività o di un problema.

**I richiedenti e i revisori contano per il numero di licenze di un&#39;organizzazione**

*[!DNL Workfront Proof]*

Quando un utente viene aggiunto a una bozza come revisore o richiedente, ottiene un &quot;[!UICONTROL Visitatore]&quot; profilo di autorizzazioni, che non deve utilizzare un [!DNL Workfront Proof] licenza. Tuttavia, quando l’utente viene aggiunto, il numero di [!DNL Workfront Proof] le licenze aumentano.

+++

+++**Aggiornamento della manutenzione l’11 ottobre 2022**

**Impossibile ripetere il pin di una pagina dopo la rimozione del pin**

*Navigazione*

>[!NOTE]
>
>Questo problema è stato risolto in Anteprima il 13 ottobre 2022. Sarà fissato in Produzione il 27 ottobre 2022.

Quando un utente seleziona il &quot;[!UICONTROL Rimuovi perno]&quot; opzione su un pin, riceve un messaggio sulla rimozione e tenta di sostituire il pin facendo clic su &quot;[!UICONTROL Annulla]&quot; nel messaggio, il pin non viene sostituito nella navigazione superiore, né viene aggiunto all&#39;elenco dei pin sotto il [!UICONTROL Altri pin] (il menu a tre punti nel [!UICONTROL Pins] area).

Se un utente tenta di fissare nuovamente la pagina passando alla pagina e fissandola, il pin non viene creato e l’utente non può fissare la pagina.

+++

+++**Aggiornamento della manutenzione il 6 ottobre 2022**

**Nuovo tipo di blueprint**

*Blueprint*

Il tipo di blueprint &quot;Dashboard&quot; è stato aggiunto al catalogo di blueprint. In precedenza erano disponibili solo i modelli Modello di progetto e Struttura organizzativa .

**Elementi che si sovrappongono nel pannello a sinistra**

*Moduli personalizzati nel mio gruppo*

Quando un utente lavora nel generatore di moduli e il modulo contiene più di 100 campi, il messaggio di notifica all’utente del limite di campi causa la sovrapposizione degli elementi nel pannello di sinistra.

**Il selettore data non si apre più automaticamente quando si attiva l&#39;input o si fa clic su**

*Navigazione*

Quando un utente naviga tramite tastiera, i selettori di date non vengono più aperti automaticamente alla data in cui l’input della tastiera riceve lo stato attivo. Al contrario, gli utenti di tastiera devono passare all’icona del selettore data e premere Invio per aprire il selettore data. Quando un utente naviga con il mouse, i selettori di date non vengono più aperti automaticamente quando si fa clic sull’input della data. Al contrario, gli utenti del mouse devono fare clic sull’icona del selettore data per aprire il selettore data.

Questa modifica è stata apportata per essere più conforme ai pattern UX del selettore data standard e per creare un’esperienza più accessibile per gli utenti di tastiera e assistenti vocali.

**L’assegnazione di più team comporta l’assegnazione di un solo team**

*Team*

>[!NOTE]
>
>Questo problema esiste solo nell&#39;ambiente Preview.

Quando un utente assegna più team a un&#39;attività o a un problema, nell&#39;elenco delle assegnazioni viene visualizzato un solo team. Questo problema influisce anche sul reporting. I rapporti che mostrano le assegnazioni del team non sono accurati perché viene visualizzato un solo team assegnato all&#39;attività o al problema.

**&quot;[!UICONTROL Le modifiche recenti non sono state salvate]&quot; errore durante il salvataggio automatico delle modifiche su una scheda attività**

*Schede orario*

Quando un utente tenta di modificare una scheda attività in modo da attivare un salvataggio automatico, le modifiche non vengono salvate e l&#39;utente visualizza il seguente messaggio:

&quot;[!UICONTROL Le modifiche recenti non sono state salvate. Aggiorna la pagina da visualizzare.]&quot;

Questo è stato riportato durante la modifica dei seguenti elementi:

* Ore
* Attività

**Le notifiche e-mail sono ritardate**

*Bozza Workfront*

Quando si verifica un evento in [!DNL Workfront Proof] che attiva una notifica e-mail, l’utente non riceve la notifica immediatamente. La notifica può essere ritardata di diverse ore.

+++

+++**Aggiornamento della manutenzione il 3 ottobre 2022**

**Salvataggio manuale della scheda attività quando i ruoli di lavoro precedenti sono cambiati**

*Schede orario*

Se un ruolo di lavoro per il quale hai effettuato l&#39;accesso è cambiato e [!UICONTROL Assegnare manualmente i ruoli del processo alle voci dell&#39;ora] è stata disabilitata, è necessario salvare manualmente le voci di tempo fino a quando non vengono più registrate ore per il ruolo di processo modificato.

+++

## Aggiornamenti a settembre 2022

+++**Aggiornamento della manutenzione il 29 settembre 2022**

**L&#39;utente non ritorna alla pagina precedente quando chiude la bozza**

*Bozze*

Quando un utente visualizza una bozza in [!DNL Workfront] chiude la bozza, non restituisce la pagina in cui si trovava prima dell’apertura della bozza. Vengono invece reindirizzati a un’altra pagina in [!DNL Workfront].

**Impossibile aprire la bozza in[!DNL Workfront]**

*Bozze*

Quando un utente visualizza un documento in [!DNL Workfront] e tenta di aprire la bozza, la bozza non si apre e l’utente viene restituito al [!UICONTROL Dettagli documento] pagina.

**Le ore non vengono salvate quando si utilizza [!UICONTROL Scheda] key**

*Schede orario*

Quando un utente compila un foglio temporale e naviga tra le celle con [!UICONTROL Scheda] le ore non vengono salvate. La [!UICONTROL Salvataggio automatico] la notifica non viene visualizzata nella parte inferiore della schermata e, se l’utente aggiorna la pagina, può vedere che le ore non sono state salvate.

**Pagine vuote quando si visualizza una bozza con più pagine**

*[!DNL Workfront Proof]*

Quando un utente visualizza una bozza con più pagine, può vedere le miniature delle pagine, ma le pagine non si aprono nel visualizzatore principale.



+++

+++**Aggiornamento della manutenzione il 22 settembre 2022**

**Impossibile chiudere la scheda utente nel flusso di aggiornamento**

*Aggiornamenti*

Quando un utente visualizza gli aggiornamenti e passa il mouse su un nome, viene visualizzata una scheda con i dettagli dell&#39;utente il cui nome viene aperto e non viene chiuso automaticamente. La pagina non risponde finché la scheda non viene chiusa manualmente facendo clic sulla X nell’angolo in alto a destra.

+++

+++**Aggiornamento della manutenzione il 15 settembre 2022**

**&quot;[!UICONTROL Qualcun altro ha tentato di salvare il progetto]&quot; errore durante l&#39;immissione delle ore**

*Schede orario*

Quando un utente tenta di registrare le ore in un&#39;attività sulla scheda attività, le ore non vengono salvate automaticamente e l&#39;utente visualizza il seguente errore:

&quot;[!UICONTROL Database error from concurrent edit on a locked row. Automatic retry failed. Try transaction later.]&quot;

**Impossibile chiudere la scheda utente nel flusso di aggiornamento**

*Aggiornamenti*

Quando un utente visualizza gli aggiornamenti e passa il mouse su un nome, viene visualizzata una scheda con i dettagli dell&#39;utente il cui nome viene aperto e non viene chiuso automaticamente. La pagina non risponde finché la scheda non viene chiusa manualmente facendo clic sulla X nell’angolo in alto a destra.

**&quot;[!UICONTROL Assegnazione ruolo attività]&quot; il campo è stato rinominato in &quot;[!UICONTROL Assegnazione ruolo]&quot; quando si assegna il lavoro in blocco utilizzando [!UICONTROL Bilanciamento del carico di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Per riflettere la nuova funzionalità di assegnazione di attività e problemi in blocco dal [!UICONTROL Lavoro non assegnato] zona, abbiamo rinominato &quot;[!UICONTROL Assegnazione ruolo attività]&quot; campo a &quot;[!UICONTROL Assegnazione ruolo]&quot; nel [!UICONTROL Bilanciamento del carico di lavoro]. Il campo si riferisce ai ruoli di lavoro assegnati a attività o problemi e viene visualizzato quando si assegnano gli utenti a elementi nel [!UICONTROL Assegnazioni in blocco] scatola.

+++

+++**[!DNL Workfront Scenario Planner]Aggiornamento della manutenzione il 15 settembre 2022**

**Il filtro condiviso con un gruppo ora viene visualizzato nella sezione [!DNL Scenario Planner]s  [!UICONTROL Importa progetti] elenco per i membri di tutti i sottogruppi**

*[!DNL Workfront Scenario Planner]*

Ora, quando condividi un filtro di progetto con un gruppo con sottogruppi aggiuntivi, il filtro è visibile a tutti i membri del gruppo e dei sottogruppi che visualizzano i progetti nel [!UICONTROL Importa progetti] di un piano [!DNL Scenario Planner].

+++

+++**Aggiornamento della manutenzione l’8 settembre 2022**

**Nomi aggiornati ripristinati per i campi assegnazione utente e ruolo**

*Assegnazioni*

I campi di assegnazione temporaneamente rinominati la settimana scorsa sono stati ripristinati ai nomi originali:

* [!UICONTROL Assegnazione Utente]
* [!UICONTROL Assegnazioni Ruoli]

**Errore durante la rimozione del proprietario del progetto dall&#39;intestazione**

*Progetti*

Quando un utente tenta di rimuovere un [!UICONTROL Proprietario progetto] dall’intestazione di un progetto, il [!UICONTROL Proprietario progetto] non viene rimosso e l&#39;utente visualizza il seguente messaggio di errore:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Ridimensionato [!UICONTROL Descrizione] torna alla dimensione originale**

*Progetti, attività e problemi*

Quando un utente ridimensiona [!UICONTROL Descrizione] casella nell&#39;area dettagli di un elemento di lavoro per ingrandirlo, quindi inizia a digitare nella casella, la casella ritorna alle dimensioni originali. L&#39;utente può ancora digitare la casella e il contenuto viene salvato come previsto

**Uscita involontaria durante la creazione di attività o problemi**

*Attività e problemi*

Quando un utente sta creando un&#39;attività o un problema in un progetto e fa clic all&#39;esterno del pop-up di creazione, il pop-up si chiude senza alcun avviso e tutte le informazioni immesse in precedenza vengono perse.

**È stata rimossa la possibilità di inviare una bozza a una zona di rilascio tramite e-mail**

*[!DNL Workfront Proof]*

A partire da giovedì 8 settembre 2022, abbiamo rimosso la possibilità di inviare una prova a una zona di siccità in stand alone [!DNL Workfront Proof] prodotto.

È comunque possibile utilizzare zone di rilascio in altri modi per inviare nuove bozze e nuove versioni di bozze al tuo account senza dover accedere al tuo account. Vedi [Zona di rilascio](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) per ulteriori informazioni.

+++

+++**Aggiornamento della manutenzione il 6 settembre 2022**

**Date previste aggiunte all’elenco dei campi per le intestazioni di progetto personalizzabili**

*Progetti*

Abbiamo aggiunto [!UICONTROL Data di inizio prevista] e [!UICONTROL Data di completamento prevista] all’elenco dei campi per le intestazioni di progetto personalizzabili quando si utilizza un modello di layout.

**Nuovo limite con un messaggio di conferma che visualizza il numero di elementi aggiunti a una scheda attività**

*Schede orario*

Quando si selezionano più di 50 elementi da aggiungere a una scheda attività, viene visualizzato un messaggio di conferma che visualizza il numero di elementi da aggiungere alla scheda attività e consente di modificare il corso e non aggiungere tutti gli elementi. Tutti gli elementi aggiunti vengono automaticamente bloccati nella scheda attività e dovranno essere rimossi manualmente dai fogli presenze correnti e da quelli futuri.

+++

+++**Aggiornamento della manutenzione il 2 settembre 2022**

Aggiungi il [!UICONTROL Integrazioni] all’intestazione personalizzata del progetto

*Integrazioni*

Ora puoi aggiungere la [!UICONTROL Integrazioni] all’intestazione personalizzata di un progetto quando si utilizza un modello di layout. Una volta aggiunto, il campo visualizza un collegamento a un elemento esterno collegato al progetto che si trova in [!DNL Salesforce] o [!DNL Anaplan], a seconda dell’integrazione.

>[!NOTE]
>
>Questo aggiornamento di manutenzione è stato rilasciato in precedenza nell’ambiente Anteprima il 25 agosto 2022 ed è ora in Produzione.

+++

+++**Aggiornamento della manutenzione il 1° settembre 2022**

**Elementi completati rimossi dalla delega**

*Deleghe*

Ora, solo gli elementi incompleti le cui date corrispondono alle date di una delega verranno delegati ad altri utenti quando inizia la delega degli elementi di lavoro. Se gli elementi sono stati completati prima dell’avvio della delega, non saranno delegati. Gli elementi che vengono completati durante l&#39;intervallo di tempo della delega rimarranno sull&#39;Elenco di lavoro dell&#39;area Home sia per il delegato che per il cessionario per due settimane prima della loro rimozione automatica, se la delega non è terminata durante queste settimane.

**Aggiornamenti dei metadati per [!DNL Adobe Workfront] per [!DNL Experience Manager Assets] e [!DNL Assets Essentials] integrazioni**

*Integrazioni*

I metadati vengono inviati automaticamente quando aggiungi una risorsa a una cartella collegata.

In precedenza, i metadati venivano inviati solo quando si aggiungeva una risorsa utilizzando [!UICONTROL Aggiungi nuovo] menu a discesa.

**Impossibile approvare o rifiutare le ore su un problema**

*problemi*

Quando un utente tenta di approvare o rifiutare ore nel [!UICONTROL Ore] scheda di un problema, [!UICONTROL Approva] e [!UICONTROL Rifiuta] mancano i pulsanti.

**Quando si converte un problema in un progetto utilizzando un modello, viene visualizzato un messaggio di errore non corretto**

*problemi*

Quando si converte un problema in un progetto utilizzando un modello e si verifica un errore, all&#39;utente viene visualizzata una pagina con il messaggio &quot;[!UICONTROL Il progetto non esiste più]&quot; invece del messaggio di errore corretto che spiega la causa della conversione non riuscita.

**Impossibile creare una bozza per file superiori a 1,5 GB**

*[!DNL Workfront Proof]*

Quando crei una nuova bozza, se un utente carica un file di dimensioni superiori a 1,5 GB, il nome del file diventa rosso e la bozza non viene creata.

+++

## Aggiornamenti ad agosto 2022

+++**Aggiornamento della manutenzione il 25 agosto 2022**

**I collegamenti di bilanciamento del carico di lavoro non vengono visualizzati correttamente nelle dashboard**

*Dashboard*

I collegamenti condivisibili del servizio di bilanciamento del carico di lavoro non vengono visualizzati correttamente se aggiunti a un dashboard come pagina esterna. Invece di utilizzare la visualizzazione/i filtri univoci associati al collegamento, il dashboard utilizza la visualizzazione/i filtri applicati più di recente al servizio di bilanciamento del carico di lavoro.

**Aggiungi il [!UICONTROL Integrazioni] all’intestazione personalizzata del progetto**

*Progetti*

Ora puoi aggiungere la [!UICONTROL Integrazioni] all’intestazione personalizzata di un progetto quando si utilizza un modello di layout. Una volta aggiunto, il campo visualizza un collegamento a un elemento esterno collegato al progetto che si trova in [!DNL Salesforce] o [!DNL Anaplan], a seconda dell’integrazione.

>[!NOTE]
>
>Questo aggiornamento di manutenzione è attualmente disponibile solo nell’ambiente Anteprima. Verrà rilasciato in produzione una settimana dopo il rilascio di Preview.

**I dati personalizzati non vengono mantenuti durante la conversione di un problema in un progetto vuoto**

*Progetti*

Quando un utente converte un problema in un progetto vuoto (senza un modello), i dati contenuti nei campi calcolati non vengono trasferiti al nuovo progetto.

**Errore &quot;Modalità di pianificazione temporale&quot; durante la modifica di una data in un progetto**

*Progetti*

Quando un utente tenta di modificare una data di un progetto con la [!UICONTROL Modalità piano] impostato su [!UICONTROL Salvataggio manuale] > [!UICONTROL Pianificazione temporale], la data non cambia e l’utente visualizza un errore.

&quot;[!UICONTROL La modalità di pianificazione della timeline è disponibile solo quando viene caricato timelineDate. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

**Coerenza quando si apre il servizio di bilanciamento del carico di lavoro utilizzando la visualizzazione Mese**

*Bilanciatore dei carichi di lavoro*

Ora, il servizio di bilanciamento del carico di lavoro visualizza gli elementi assegnati degli utenti espansi quando vengono visualizzati nel [!UICONTROL Giorno], [!UICONTROL Settimana]oppure [!UICONTROL Mese] visualizzazioni. Prima di questo aggiornamento, gli elementi assegnati venivano visualizzati espansi per [!UICONTROL Giorno] e [!UICONTROL Settimana] viste e compresso per [!UICONTROL Mese] visualizza.


+++

+++**Aggiornamento della manutenzione il 18 agosto 2022**

**&quot;[!UICONTROL Aggiungi a iterazione]&quot; e &quot;[!UICONTROL Aggiungi a bacheca kanban]&quot; opzioni non disponibili quando le attività di modifica in linea sono in un rapporto**

*Rapporti*

Quando un utente visualizza un elenco di attività in un rapporto e apre la [!UICONTROL Altro] (a tre punti), il menu &quot;[!UICONTROL Aggiungi a iterazione]&quot; e &quot;[!UICONTROL Aggiungi a bacheca kanban]&quot; non sono disponibili nel menu a discesa. Se il rapporto viene visualizzato in un dashboard, il valore &quot;[!UICONTROL Aggiungi a iterazione]&quot; e &quot;[!UICONTROL Aggiungi a bacheca kanban]&quot; sono disponibili nel menu a discesa .

**I rapporti sulle matrici non vengono visualizzati correttamente quando si esegue lo scorrimento**

*Rapporti*

Quando un utente visualizza un rapporto di matrice e lo scorre, alcuni elementi visivi del rapporto potrebbero sovrapporsi o essere duplicati.

**[!UICONTROL Milestone] vista rimossa dall’elenco dei progetti Timesheets**

*Schede orario*

La [!UICONTROL Milestone] la visualizzazione è stata rimossa dall&#39;elenco del progetto della scheda attività quando si aggiunge un progetto.

**I collegamenti ipertestuali in una bozza interattiva non sono attivi**

*[!DNL Workfront Proof]*

Quando un utente visualizza una bozza interattiva e fa clic su un collegamento o su un pulsante che contiene un collegamento, l’utente non viene portato alla pagina a cui il collegamento o il pulsante si collega.

**Nuovi campi di testo mancanti della pagina di prova**

*[!DNL Workfront Proof]*

Sulla [!DNL New Proof] pagina, molti campi di testo non vengono visualizzati (comprese le etichette dei campi, le opzioni a discesa e i nomi delle caselle di controllo).

**Gli utenti non ricevono notifiche quando vengono inseriti i tag in una bozza**

*[!DNL Workfront Proof]*

Quando un utente viene taggato in un commento di bozza, non riceve una notifica e-mail sul commento.

+++

+++**Aggiornamento della manutenzione il 12 agosto 2022**

**Nuovo campo intestazione personalizzabile aggiunto all’inizio dell’intestazione**

*Intestazioni*

Quando si aggiunge un nuovo campo a un’intestazione personalizzabile, il campo viene ora aggiunto come primo campo a sinistra nell’intestazione o subito dopo il [!UICONTROL Ricerca] all’interno della casella Modello di layout. Prima di questa modifica, il campo era stato aggiunto come ultimo campo nell’intestazione.

+++

+++**Aggiornamento della manutenzione l’11 agosto 2022**

**Impossibile modificare i moduli personalizzati a causa di un limite di caratteri errato nei campi di testo descrittivo**

*Moduli personalizzati nel mio gruppo*

Quando un utente tenta di modificare un modulo personalizzato e tale modulo personalizzato ha una [!UICONTROL Testo descrittivo] campo che attualmente contiene più di 512 caratteri, l’utente non può salvare le modifiche al modulo personalizzato e visualizza il seguente errore:

&quot;I campi seguenti non sono validi: (Campo) troppo lungo, max 512&quot;

Ciò influisce [!UICONTROL Testo descrittivo] campi che in precedenza hanno funzionato bene nonostante abbiano più di 512 caratteri.

**I dati nei campi nascosti dall’interruzione di sezione non vengono mantenuti durante la conversione di un problema in un progetto**

*Moduli personalizzati nel mio gruppo*

Quando un utente converte un problema in un progetto e il problema include un modulo personalizzato con dati in un’interruzione di sezione che possono essere nascosti utilizzando la logica di visualizzazione, i dati in tale sezione non vengono trasferiti al nuovo progetto.

**I dati nei campi nascosti dall’interruzione di sezione non vengono mantenuti durante la conversione di una richiesta in un progetto**

*Moduli personalizzati nel mio gruppo*

Quando un utente converte una richiesta in un progetto e la richiesta include un modulo personalizzato con i dati in un’interruzione di sezione che può essere nascosta utilizzando la logica di visualizzazione, i dati contenuti in tale sezione non vengono trasferiti al nuovo progetto.

**Impossibile modificare i moduli personalizzati a causa del campo Testo descrittivo**

*Moduli personalizzati nel mio gruppo*

Quando un utente tenta di modificare un modulo personalizzato che include un campo Testo descrittivo, l’etichetta del campo non viene compilata. L&#39;utente visualizza l&#39;errore &quot;[!UICONTROL Questo campo è obbligatorio]&quot; nel campo etichetta e l’utente non può modificare il modulo personalizzato a causa di questo errore.

**Impossibile rimuovere istruzioni da un campo personalizzato nel modulo builder personalizzato**

*Moduli personalizzati nel mio gruppo*

Quando un utente modifica un campo personalizzato e tenta di rimuovere il testo esistente nel campo [!UICONTROL Istruzioni] area, il testo non viene rimosso quando il campo viene salvato. L’utente può modificare il testo, ma non può rimuoverlo completamente.

**L&#39;assegnazione del team durante la creazione della richiesta non viene visualizzata su una nuova richiesta**

*Richieste*

Quando un utente crea una richiesta e assegna un team alla richiesta, quindi invia la richiesta, il team non viene assegnato alla richiesta creata. Ciò influisce solo sull&#39;assegnazione del team. Le assegnazioni utente funzionano come previsto.

+++

+++**Aggiornamento della manutenzione il 4 agosto 2022**

Questi problemi sono stati risolti solo nel nuovo [!DNL Workfront] esperienza.

Tutto [!DNL Workfront Classic] funzionalità rimossa il 14 luglio 2022.

**Errore durante la modifica della data di completamento pianificata nell&#39;intestazione di un&#39;attività o di un problema**

*Attività e problemi*

Quando un utente tenta di modificare il [!UICONTROL Data completamento pianificata] nell’intestazione di un’attività o di un problema, la data non cambia e l’utente visualizza un errore simile al seguente:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Aggiornamenti a luglio 2022

+++**Aggiornamento della manutenzione il 28 luglio 2022**

Questi problemi sono stati risolti solo nel nuovo [!DNL Workfront] esperienza.

Tutto [!DNL Workfront Classic] funzionalità rimossa il 14 luglio 2022.

**Errore durante l&#39;apertura di un elemento dal [!UICONTROL Elenco dei lavori domestici]**

*[!UICONTROL Home]*

Quando un utente tenta di aprire un elemento sul suo [!UICONTROL Elenco dei lavori domestici], l’elemento non si apre e l’utente visualizza il seguente messaggio:

&quot;[!UICONTROL Si è verificato un errore e stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro prova ad aggiornare questa pagina del browser.]&quot;

**Le attività e i problemi delegati a un utente non vengono visualizzati nell&#39;elenco Home Work dell&#39;utente**

*[!UICONTROL Pagina principale]*

Quando l’utente visualizza le [!UICONTROL Elenco dei lavori domestici], eventuali attività o problemi delegati all&#39;utente non compaiono nell&#39;elenco e l&#39;utente potrebbe non essere a conoscenza delle delegazioni.

**I report pianificati non vengono inviati a tutti i destinatari**

*Rapporti*

Quando viene inviato un rapporto pianificato, non viene inviato a tutti gli utenti nel[!UICONTROL Invia a]&quot; sezione. Gli utenti omessi sono casuali e possono variare ogni volta che il rapporto viene inviato.

**[!UICONTROL Impossibile deselezionare le attività durante l&#39;associazione del modello]**

*Modelli*

Quando un utente allega e personalizza un modello, viene richiesto di deselezionare le attività che non desidera includere. Tuttavia, nessuna delle attività viene visualizzata come selezionata e l&#39;utente non può deselezionarle.

**I campi &quot;Impostazioni internazionali&quot; ora dispongono di etichette più specifiche**

*Terminologia*

Per fare la funzione di &quot;[!UICONTROL Impostazioni internazionali]&quot; campi più chiari, abbiamo aggiornato le loro etichette.

* &quot;[!UICONTROL Impostazioni internazionali]&quot; sul profilo utente ora è etichettato &quot;[!UICONTROL Impostazioni internazionali e-mail]&quot;
* &quot;[!UICONTROL Impostazioni internazionali]&quot; campo trovato nel [!UICONTROL Configurazione] >[!UICONTROL Sistema] >[!UICONTROL Informazioni cliente] l&#39;area è ora etichettata &quot;[!UICONTROL Impostazioni internazionali e-mail predefinite]&quot;

La funzionalità di questi campi non è cambiata.

**Problemi durante la creazione dei fogli presenze**

*Schede orario*

Sono stati segnalati i seguenti problemi relativi alla creazione di fogli presenze:

* Quando un utente tenta di creare una scheda attività per un ruolo, la scheda attività non viene creata e l&#39;utente visualizza l&#39;errore &quot;[!UICONTROL Impossibile trovare l&#39;utente con valori di chiave primaria &#39;XXXXXXXXXXX&#39;.]&quot;
* Quando un utente tenta di creare una scheda attività per un team, il [!UICONTROL timone] il campo non viene compilato con i team e il [!UICONTROL Crea foglio presenze] pulsante disabilitato.


**Zone [!DNL Workfront Proof] non aggiornare quando viene creata, spostata o archiviata una bozza**

*[!DNL Workfront]Bozza*

La prova sta riscontrando ritardi nell&#39;indicizzazione. Questo può influenzare l’esperienza utente nei modi seguenti:

* Le dashboard non mostrano il numero corretto di bozze
* Le cartelle non vengono aggiornate quando si crea o si sposta una bozza
* Le bozze archiviate rimangono sugli elenchi di prove attivi.

+++

+++**Aggiornamento di manutenzione (Hotfix) il 26 luglio 2022**

Questi problemi sono stati risolti solo nel nuovo [!DNL Workfront] esperienza.

Tutto [!DNL Workfront Classic] funzionalità rimossa il 14 luglio 2022.

**Le ore visualizzate nella scheda attività sono diverse dall&#39;elenco dei fogli presenze**

*Schede orario*

Quando un utente apre una scheda attività per visualizzarla, le ore visualizzate sono diverse da quando l&#39;utente visualizza la stessa scheda attività in un elenco di schede attività.


**La richiesta convertita in progetto con modello mostra il gruppo dalla coda di richiesta, non il gruppo dal modello**

*Richieste*

Quando un utente converte una richiesta in un progetto utilizzando un modello, il progetto appena creato viene associato al gruppo proprietario della coda di richiesta, non al gruppo assegnato sul modello. Ciò si verifica anche se durante la creazione del progetto, il gruppo associato al modello viene popolato nel [!UICONTROL Gruppo] campo .

+++

+++**Aggiornamento della manutenzione il 21 luglio 2022**

Questi problemi sono stati risolti solo nel nuovo [!DNL Workfront] esperienza.

Tutto [!DNL Workfront Classic] funzionalità rimossa il 14 luglio 2022.

**Lo stato di rifiuto associato a un&#39;approvazione rispetta il flusso di lavoro di approvazione**

**NOTA: Questa funzionalità è stata rilasciata il 22 luglio 2022.**

*Approvazioni*

Se si seleziona uno stato associato a un processo di approvazione come stato di rifiuto per un percorso di approvazione, l&#39;oggetto rifiutato si sposta sullo stato selezionato e verrà contrassegnato come &quot;[!UICONTROL Approvazione in sospeso]&quot;. Ad esempio, se selezioni [!UICONTROL Bloccato] per lo stato di rifiuto e [!UICONTROL Bloccato] lo stato è associato a un processo di approvazione, l&#39;oggetto rifiutato viene posizionato nello stato di &quot;[!UICONTROL In attesa di approvazione]&quot;, che richiede l&#39;approvazione.

Prima di questo aggiornamento, l&#39;oggetto ignorava il processo di approvazione per lo stato di rifiuto e veniva posizionato nella [!UICONTROL Bloccato] stato.

**Configurare un URL di aiuto personalizzato**

*[!UICONTROL Menu principale]*

Se la tua organizzazione dispone di un sito di aiuto interno personalizzato, puoi configurare le [!UICONTROL Menu principale] [!UICONTROL Aiuto] per passare a quel sito. Questa opzione è utile se il sito della guida contiene informazioni sulle modalità di utilizzo dell’organizzazione [!DNL Workfront].
Questo URL personalizzato non influisce sul collegamento principale della Guida nell’area superiore di [!DNL Workfront], né i collegamenti di aiuto sensibili al contesto attraverso [!DNL Workfront], che porta gli utenti al [!DNL Workfront] Sito della Guida.

**Impossibile selezionare Tempo trascorso durante la modifica in linea [!UICONTROL Durata attività]**

*Attività*

Quando un utente visualizza un elenco di attività e tenta di modificare il [!UICONTROL Durata attività], le seguenti unità di durata non sono disponibili:

* [!UICONTROL Minuti trascorsi]
* [!UICONTROL Ore trascorse]
* [!UICONTROL Giorni trascorsi]
* [!UICONTROL Settimane trascorse]
* [!UICONTROL Mesi trascorsi]

**[!UICONTROL Aggiornamenti personali] pagina vuota**

*Aggiornamenti*

Quando un utente tenta di visualizzare la [!UICONTROL Aggiornamenti personali] la pagina non viene caricata. L’utente può visualizzare solo il [!DNL Workfront] intestazione di navigazione.

**&quot;[!UICONTROL Consenti solo autenticazione SAML 2.0]&quot; impostazione mancante durante la copia di un utente**

*Utenti*

Quando un amministratore di gruppo copia un utente e deseleziona &quot;[!UICONTROL Invia un messaggio e-mail di invito a questa persona]&quot;, opzione &quot;O[!UICONTROL Consenti solo autenticazione SAML 2.0]&quot; non viene visualizzata come previsto. Ciò può verificarsi anche quando tutti i requisiti di accesso e autorizzazione per questa azione sono soddisfatti.

+++

+++**Aggiornamento della manutenzione il 14 luglio 2022**

Questi problemi sono stati risolti solo nel nuovo [!DNL Workfront] esperienza.

Tutto [!DNL Workfront Classic] funzionalità rimossa il 14 luglio 2022.

**Errore durante il ripristino della password**

*Accedi*

Quando un utente tenta di reimpostare la propria password, non può reimpostarla e viene visualizzato un messaggio che informa che non ha accesso. L&#39;utente non può accedere a Workfront.

**Impossibile richiedere più accesso a un report**

*Rapporti*

Quando un utente con accesso limitato a un report tenta di richiedere più accesso a un report, l&#39;opzione per richiedere più accesso non è disponibile nella sezione [!UICONTROL azioni di report] menu.

**Messaggio di conferma aggiornato durante l’eliminazione di una bozza di richiesta**

*Richieste*

Quando scarti una richiesta di bozza, viene visualizzato il messaggio di conferma dopo aver fatto clic su &quot;[!UICONTROL Elimina bozza]&quot; visualizza quanto segue:

* [!UICONTROL Bozza scartata] (notifica per comunicare che la bozza è stata scartata)
* [!UICONTROL Annulla] Questo è un collegamento su cui potete fare clic per annullare l’azione di eliminazione della bozza. La bozza verrà mantenuta invece di essere eliminata.)

Prima di questa modifica, le opzioni erano:

* [!UICONTROL La bozza verrà eliminata]
* [!UICONTROL Annulla]

**I valori di data per i campi di immissione scritture contabili non sono corretti quando vi si accede tramite l&#39;API**

*Aggiornamenti*

Quando un utente modifica un valore di data in un oggetto e quindi l&#39;accesso tramite l&#39;API alla voce Journal che rappresenta tale modifica di data, i valori di data per [!UICONTROL oldDateVal] e [!UICONTROL newDateVal] restituito dall&#39;API non corretto.

**Errore durante il tentativo di annullare il commento**

*Aggiornamenti*

Quando un utente tenta di annullare un commento, questo non viene annullato e l’utente visualizza il seguente errore:

[!UICONTROL Errore 403: Accesso insufficiente per eliminare la nota /attask/api-internal/NOTE]

**Nuova limitazione al numero di caratteri in un aggiornamento in Anteprima**

*Aggiornamenti*

Per migliorare le prestazioni del [!UICONTROL Aggiornamenti] è stato introdotto un nuovo limite al numero di caratteri che è possibile immettere in un aggiornamento o in una risposta a un aggiornamento esistente. Il nuovo limite è di 15.000 caratteri. Questo aggiornamento non ha modificato il numero di caratteri consentiti quando si utilizza l’API. Il limite di caratteri API per gli aggiornamenti è 4.000.

**Errore durante il caricamento dell&#39;allegato da [!DNL Workfront] integrazione per Outlook**

*Integrazioni Workfront*

Quando un utente tenta di caricare un allegato utilizzando la variabile [!DNL Workfront for Outlook] integrazione, l&#39;allegato non viene caricato e l&#39;utente visualizza il seguente messaggio:

[!UICONTROL Alcuni allegati non sono stati caricati. Motivo: Si è verificato un errore durante il caricamento degli allegati.]

**Aggiornamento notifica e-mail di bozza**

*[!DNL Workfront]Bozza*

All’inizio di questo mese, come parte di una patch per [!DNL Workfront] Ambiente di produzione, abbiamo corretto alcuni bug nel sistema di notifica e-mail di bozza. Questa modifica non è stata comunicata nell&#39;aggiornamento di manutenzione al momento del rilascio. Abbiamo aggiunto le seguenti informazioni al [Aggiornamento della manutenzione il 2 giugno 2022](#maintenance-update-on-june-2-2022) :

A seguito di queste correzioni di bug, l’indirizzo e-mail utilizzato per inviare le notifiche di bozza è cambiato.

In precedenza, gli indirizzi e-mail di bozza contenevano il sottodominio dell’organizzazione. Ad esempio, notifiche@[dominio dell&#39;azienda].my.workfront.com

Ora, gli indirizzi e-mail di profilazione non contengono più un sottodominio organizzazione. Tutte le notifiche e-mail di bozza verranno inviate dal seguente indirizzo: notification@my.workfront.com

Di conseguenza, se non lo hai già fatto, ti consigliamo di effettuare le seguenti operazioni:

* Aggiorna i filtri anti-spam per accettare le e-mail da notification@my.workfront.com
* Aggiorna i tuoi inserire nell&#39;elenco Consentiti per accettare le e-mail da notification@my.workfront.com

**Le opzioni utente non possono essere modificate dopo la configurazione iniziale nei modelli di flusso di lavoro**

*[!DNL Workfront Proof]*

Quando un utente aggiunge un utente a un modello di flusso di lavoro, può configurare delle opzioni. Tuttavia, al termine della configurazione iniziale, l’utente non può più modificare quanto segue:

* &quot;[!UICONTROL Risolvere i commenti e applicare azioni]&quot; capacità
* [!UICONTROL &quot;Condividere le prove tramite assegnazione tag]&quot; capacità
* Ruolo di bozza ([!UICONTROL Revisore], [!UICONTROL Approvatore], ecc.)

**&quot;[!UICONTROL Elementi di lavoro di questo progetto]&quot; filtro ripristinato nel progetto [!UICONTROL Bilanciamento del carico di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Abbiamo ripristinato il filtro &quot;Elementi di lavoro di questo progetto&quot; nel [!UICONTROL Assegnato] quando si accede alla [!UICONTROL Bilanciamento del carico di lavoro] da un progetto.

Questo filtro è ora elencato nella sezione &quot;[!UICONTROL Suggerito]&quot; della sezione dei filtri per [!UICONTROL Lavoro assegnato] area di un progetto [!UICONTROL Bilanciamento del carico di lavoro].

+++

## Aggiornamenti a giugno 2022

+++**Aggiornamento della manutenzione il 30 giugno 2022**

**Visualizza la [!UICONTROL Bilanciamento del carico di lavoro] per una settimana**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

In base al feedback ricevuto da molti clienti, è stata aggiunta un’opzione per visualizzare il [!UICONTROL Bilanciamento del carico di lavoro] per una settimana. Prima di questo aggiornamento, era possibile visualizzare il [!UICONTROL Bilanciamento del carico di lavoro] per 4, 6 e 12 settimane. Con questo aggiornamento, abbiamo anche cambiato l&#39;opzione 12 settimane a 3 mesi.

**Il pannello Delega è ora disponibile dal servizio di bilanciamento del carico di lavoro**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

NOTA: Questo aggiornamento esiste solo nell&#39;ambiente di anteprima. La funzionalità associata a questo aggiornamento sarà disponibile in Produzione con la versione 22.3.

Ora puoi visualizzare i delegati di un&#39;attività o di un problema dal servizio di bilanciamento del carico di lavoro. Quando si assegna un&#39;attività o un problema dal servizio di bilanciamento del carico di lavoro, è possibile visualizzare un elenco di assegnazioni e un elenco di delegati per l&#39;attività o il problema, se sono attualmente delegati.

**Impossibile aprire le informazioni sull&#39;endpoint in API Explorer**

*API*

Quando un utente visualizza la variabile [!DNL API Explorer] e fa clic su un endpoint, le informazioni sull&#39;endpoint non vengono visualizzate.

**Problemi relativi [!UICONTROL Dettagli] quando si utilizza il pulsante [!UICONTROL Calendario Home]**

*Pagina principale*

Quando un utente utilizza la variabile [!UICONTROL Calendario Home] e i clic su un&#39;attività possono verificarsi uno dei seguenti casi:

* La [!UICONTROL Dettagli] viene visualizzato brevemente, quindi scompare. L&#39;utente non può accedere ai dettagli.
* La [!UICONTROL Dettagli] il pulsante non viene visualizzato. L&#39;utente non può accedere ai dettagli.
* La [!UICONTROL Dettagli] viene visualizzato il pulsante , ma non si trova nella posizione corretta. L’utente può fare clic sul pulsante per accedere ai dettagli.

+++

+++**Aggiornamento di manutenzione (Hotfix) il 24 giugno 2022**

**Il selettore data non si chiude quando si modifica un modulo personalizzato**

*Moduli personalizzati*

Quando un utente modifica un modulo personalizzato e tenta di modificare una data, il selettore data non si chiude quando viene selezionata la data. L’utente non può chiudere il selettore di date salvando, annullando o facendo clic in un altro punto lontano dal selettore di date.

Ciò è stato riferito nelle seguenti aree:

* [!UICONTROL Aggiornamenti] area
* [!UICONTROL Pagina principale]

**L&#39;utente non può spostarsi da solo in un&#39;altra fase di una bozza**

*Bozze*

Quando un utente visualizza la variabile [!UICONTROL Flusso di lavoro di prova] di una bozza e tenta di trascinarsi in un’altra fase della bozza, il nome dell’utente torna alla fase originale e non vengono aggiunti alla fase desiderata.

+++

+++**Aggiornamento della manutenzione il 23 giugno 2022**

**[!UICONTROL Impossibile aggiungere una nuova richiesta tramite il dashboard]**

*Dashboard*

Quando un utente visualizza un dashboard in un progetto e tenta di aggiungere una nuova richiesta facendo clic sul pulsante [!UICONTROL +Nuova richiesta] il pulsante non risponde e l’utente non può aggiungere una nuova richiesta.

**Errore durante la visualizzazione degli elementi nell&#39;elenco Home di lavoro**

*[!UICONTROL Pagina principale]*

Quando un utente visualizza la [!UICONTROL Elenco dei lavori domestici] e fa clic su un elemento nel [!UICONTROL Approvazioni inviate] nella pagina viene visualizzato il seguente errore:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

Se l’utente aggiorna la pagina, fa clic su qualsiasi elemento nel [!UICONTROL Elenco lavori], viene visualizzato l’errore . Il problema non influisce più solo sugli elementi nel [!UICONTROL Approvazioni inviate] sezione .

**La sezione personalizzata di un oggetto include i risultati non presenti in tale oggetto**

*Oggetti*

Quando un utente visualizza un [!UICONTROL personalizzato] in un oggetto, la sezione personalizzata visualizza gli elementi che non fanno parte di tale oggetto. Questo è stato riportato quando la sezione personalizzata viene aggiunta direttamente all’oggetto e quando una sezione personalizzata viene aggiunta tramite un modello di layout.

**Le attività vengono spostate in un progetto non corretto**

*Attività*

Quando un utente sposta le attività dal Progetto A al Progetto B e quindi sposta più attività dal Progetto A al Progetto C, le attività originariamente spostate al Progetto B vengono visualizzate nel Progetto C.

**Alcuni pulsanti/icone non funzionano quando si accede a [!UICONTROL Bilanciamento del carico di lavoro] da un collegamento o da un dashboard condiviso**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente accede alla pagina [!UICONTROL Bilanciamento del carico di lavoro] tramite un collegamento condiviso o un collegamento in un dashboard e tenta di utilizzare l’elemento nella parte superiore dello schermo, gli elementi non funzionano. Questo è stato segnalato per i seguenti elementi:

* [!UICONTROL Oggi]
* Frecce Indietro e Avanti
* [!UICONTROL Settimane]
* Icona Calendario (selezione data)

+++

+++**[!DNL Workfront]Aggiornamento sulla manutenzione del planner dello scenario il 23 giugno 2022**

**Utenti con [!UICONTROL Gestisci] i permessi di un piano possono condividerlo con altri**

Come utente con [!UICONTROL Gestisci] autorizzazioni per un piano nel [!DNL Scenario Planner], ora puoi condividerlo con altri utenti. Prima di questo aggiornamento, solo il creatore del piano poteva condividere il piano con altri utenti.

+++

+++**Aggiornamento della manutenzione il 16 giugno 2022**

**L&#39;amministratore del gruppo non può aggiungere membri al gruppo**

*Gruppi*

Quando un amministratore di gruppo tenta di aggiungere un utente a un gruppo, il menu a discesa per selezionare l&#39;utente non viene compilato. L&#39;amministratore del gruppo non può selezionare alcun utente e pertanto non può aggiungere alcun utente al gruppo.

**I quarti personalizzati non vengono visualizzati quando si imposta un filtro**

*Filtri*

Quando un utente crea un filtro e filtra in base a un campo data, il menu a discesa degli operatori disponibili per il campo data non include i trimestri personalizzati aggiunti di recente.

**Errore &quot;Whoops&quot; durante la conversione di un problema in un progetto tramite un modello**

*Progetti*

Quando un utente tenta di convertire un problema in un progetto tramite un modello e il problema ha un modulo personalizzato che contiene una sezione di sola amministrazione, il problema non viene convertito e l&#39;utente visualizza il seguente errore:

&quot;[!UICONTROL Riproviamo. Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

**Le richieste vengono inviate senza campi obbligatori compilati**

*Richieste*

Quando un utente crea una richiesta e non compila i campi obbligatori, quindi invia la richiesta, la richiesta viene inviata senza dati nei campi richiesti. Si prevede che la richiesta non venga inviata e che all’utente venga notificato che deve compilare i campi obbligatori prima di inviare la richiesta.

**I nuovi trimestri personalizzati non vengono salvati**

*Configura*

Quando un utente aggiunge un nuovo trimestre personalizzato dall’area Progetti di installazione e fa clic su [!UICONTROL Salva], non vi è alcuna indicazione visiva del salvataggio. L&#39;utente non visualizza un messaggio di successo e il [!UICONTROL Salva] pulsante presente e attivo. Tuttavia, se l’utente aggiorna la pagina, può vedere che i nuovi trimestri compaiono nell’elenco dei trimestri personalizzati.

Se l&#39;utente aggiunge un nuovo trimestre, fa clic su [!UICONTROL Salva], non riceve alcuna indicazione del salvataggio, aggiunge un altro trimestre senza aggiornare la pagina e fa clic su [!UICONTROL Salva] di nuovo, il secondo trimestre aggiunto potrebbe non essere salvato.

**[!UICONTROL Richieste di lavoro del team] pagina vuota**

*Team*

NOTA: Questo problema esiste solo nell&#39;ambiente Preview.

Quando un utente tenta di aprire il [!UICONTROL Richieste di lavoro] in una pagina del team, la pagina è vuota. L’utente può visualizzare la barra di navigazione superiore, ma non il contenuto della pagina.

+++

+++**Aggiornamento della manutenzione il 9 giugno 2022**

**Impossibile selezionare gli oggetti da filtrare in [!UICONTROL Ottimizzatore Portfolio] preferenze**

*Portfolio*

Quando un utente si trova nella [!UICONTROL Ottimizzatore Portfolio] e visualizza [!UICONTROL Filtri di progetto] nella scheda [!UICONTROL Preferenze] le caselle accanto agli oggetti sono assenti. L&#39;utente non può selezionare o deselezionare le caselle di controllo e quindi non può selezionare oggetti da filtrare.

**Impossibile modificare [!UICONTROL Data di inizio prevista] o [!UICONTROL Data completamento pianificata] quando &quot;[!UICONTROL Pianificazione da]&quot; non è selezionato**

*Progetti*

Quando un utente tenta di modificare il [!UICONTROL Data di inizio prevista] o [!UICONTROL Data completamento pianificata] di un progetto e[!UICONTROL Pianificazione da]&quot; non è selezionata l&#39;opzione per quel progetto, il [!UICONTROL Data di inizio prevista] e [!UICONTROL Data completamento pianificata] le aree sono disattivate e l’utente non può modificare tali date.

**Impossibile modificare il livello di accesso degli utenti**

*Utenti*

Quando un utente con accesso a Planner che include l&#39;accesso Amministratore utenti (Utenti di gruppo) tenta di modificare gli utenti del gruppo di cui è amministratore, il [!UICONTROL Accesso] il campo livello è disabilitato e l&#39;utente non è in grado di modificare il livello di accesso.

+++

+++**[!DNL Workfront Scenario Planner]Aggiornamento della manutenzione il 9 giugno 2022**

**Pannello a sinistra ridimensionabile nel[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Ora è possibile ridimensionare il pannello di sinistra in un piano, nella [!DNL Scenario Planner]. Questo consente di visualizzare completamente i nomi delle iniziative più lunghi. Prima di questo aggiornamento, i nomi delle iniziative più lunghi venivano troncati.

+++

+++**[!DNL Workfront Fusion]Aggiornamento della manutenzione il 9 giugno 2022**

**Dati da moduli personalizzati non disponibili in [!DNL Workfront Fusion] [!DNL Workfront] moduli**

*[!DNL Workfront Fusion]*

Quando un utente configura un [!DNL Workfront] modulo in [!DNL Workfront Fusion]e tenta di selezionare gli output per il modulo, i campi dei moduli personalizzati non sono visibili. Ciò si verifica quando il modulo personalizzato è stato creato per un tipo di [!DNL Workfront] e un altro tipo è stato aggiunto ad esso. [!DNL Workfront Fusion] visualizza solo i campi dei moduli personalizzati originariamente creati per il tipo di oggetto selezionato.

**Impossibile scorrere per visualizzare tutte le esecuzioni dello scenario**

*[!DNL Workfront Fusion]*

Quando un utente visualizza la cronologia di esecuzione di uno scenario e tenta di scorrere verso il basso per visualizzare più esecuzioni, le esecuzioni smettono di caricarsi e l&#39;utente non è in grado di visualizzarle. Inoltre, l’utente non può scorrere fino alle esecuzioni più recenti.

+++

+++**Aggiornamento della manutenzione il 2 giugno 2022**

**[!UICONTROL Ottimizzatore Portfolio] mostra un punteggio pari a 0 quando si utilizza una lingua diversa dall’inglese**

*Portfolio*

Quando un utente utilizza [!DNL Workfront] in una lingua diversa dall&#39;inglese e visualizza il [!UICONTROL Ottimizzatore Portfolio], il punteggio viene visualizzato come 0. Ciò può verificarsi anche quando il business case non è completo.

**Valori dei campi calcolati non corretti durante la creazione di un progetto da un modello**

*Progetti*

Quando un utente crea un progetto da un modello che include campi calcolati, i valori dei campi visualizzati nel nuovo progetto non sono corretti.

**Impossibile modificare [!UICONTROL Condizioni] in [!UICONTROL Preferenze del progetto] area [!UICONTROL Configurazione]**

*[!UICONTROL Configura]*

Quando un utente tenta di modificare [!UICONTROL Condizioni] in [!UICONTROL Preferenze del progetto] area [!UICONTROL Configurazione], la pagina è vuota.

**Nuova limitazione al numero di caratteri in un aggiornamento in Anteprima**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

>[!NOTE]
>
>Questo aggiornamento si applica solo all’ambiente Preview.

Per migliorare le prestazioni dell’area Aggiornamenti, è stato introdotto un nuovo limite al numero di caratteri che è possibile immettere in un aggiornamento o una risposta a un aggiornamento esistente. Il nuovo limite è di 15.000 caratteri. Questo aggiornamento non ha modificato il numero di caratteri consentiti quando si utilizza l’API. Il limite di caratteri API per gli aggiornamenti è 4.000. Aggiorna il supporto per i campi personalizzati di tipo Typehead nei filtri di bilanciamento del carico di lavoro

È in corso il supporto dei filtri basati su [!UICONTROL Tipo] digita campi personalizzati nel servizio di bilanciamento del carico di lavoro. Prima di questa patch, il filtro per questo tipo di campi personalizzati non era possibile nel load Balancer.

**Impossibile modificare le autorizzazioni per il ruolo di un utente**

*[!DNL Workfront Proof]*

Quando un utente tenta di modificare il &quot;[!UICONTROL Risolvere i commenti e applicare azioni]&quot; o &quot;[!UICONTROL Condividere una bozza tagging]&quot; autorizzazioni sul ruolo di un utente in [!DNL Workfront Proof], le modifiche non vengono salvate. L’utente riceve una notifica dell’aggiornamento del modello, ma se riapre le autorizzazioni per il ruolo può vedere che le modifiche non sono state salvate.

+++


## Aggiornamenti a maggio 2022

+++**Aggiornamento della manutenzione il 26 maggio 2022**

Questi problemi sono stati risolti solo nel nuovo [!DNL Workfront] esperienza. [!DNL Adobe Workfront Classic] non è più supportato.

Tutto [!DNL Workfront Classic] La funzionalità verrà rimossa a luglio 2022. Passa alla nuova esperienza il prima possibile.

**Separatori di breadcrumb aggiornati**

*[!DNL Workfront]*

NOTA: Questo aggiornamento è stato rilasciato il 24 maggio 2022.

Sono stati aggiornati i separatori delle breadcrumb in tutte le aree in cui sono disponibili le breadcrumb. Ora, gli oggetti nelle breadcrumb sono separati da tubi (|). Prima di questo aggiornamento, erano separati da barre (/).

**Impossibile modificare i moduli personalizzati con interruzioni di sezione**

*Moduli personalizzati*

Quando un utente tenta di modificare un modulo personalizzato con un’interruzione di sezione, non può modificare il modulo e viene visualizzato il seguente messaggio:

[!UICONTROL La sicurezza specificata per l’interruzione di sezione non può essere applicata a tutti i tipi di oggetto]

**Problemi relativi alla stampa di dashboard in PDF**

*Dashboard*

Durante la stampa di un dashboard in un PDF sono stati segnalati i seguenti problemi: PDF non stampa tutte le righe del rapporto. Se mancano le righe, viene visualizzato solo uno spazio vuoto.
PDF include spazi vuoti tra le intestazioni di colonna e la prima riga del rapporto.

**[!DNL Portfolio Optimizer]mostra un punteggio pari a 0 quando si utilizza una lingua diversa dall’inglese**

*Portfolio*

Quando un utente utilizza [!DNL Workfront] in una lingua diversa dall&#39;inglese e visualizza il [!UICONTROL Ottimizzatore Portfolio], il punteggio viene visualizzato come 0. Ciò può verificarsi anche quando il business case non è completo.

**Alcuni moduli personalizzati non vengono visualizzati durante la modifica di un modello**

*Modelli*

Quando un utente tenta di modificare i moduli personalizzati su un modello facendo clic su [!UICONTROL Modifica] nell’intestazione del modello, il [!UICONTROL Modifica modello] in questa finestra viene visualizzato solo uno dei moduli personalizzati collegati al modello.

**Il collegamento condiviso al servizio di bilanciamento del carico di lavoro visualizza il funzionamento assegnato in modo errato**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente visualizza il [!UICONTROL Bilanciamento del carico di lavoro] utilizzando un collegamento condiviso, la variabile [!DNL Workload Balancer] include [!UICONTROL Lavoro assegnato] in [!UICONTROL Lavoro non assegnato] sezione . [!UICONTROL Lavoro assegnato] non dispone di una sezione separata. Quando l’utente visualizza il [!UICONTROL Bilanciamento del carico di lavoro] senza utilizzare il collegamento condiviso, [!UICONTROL Lavoro assegnato] viene visualizzato come previsto.

+++

+++**Aggiornamento della manutenzione il 19 maggio 2022**

**Impossibile creare una bozza da un[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Quando un utente tenta di creare una bozza da un [!DNL PowerPoint] che include un grafico, la creazione della bozza non riesce.

**Impossibile creare una bozza da un [!UICONTROL Parola] documento**

*[!DNL Workfront Proof]*

Quando un utente tenta di creare una bozza da un [!DNL Word] documento che include un grafico, la creazione della bozza non riesce.

**Impossibile aggiungere un messaggio personalizzato durante la condivisione di una bozza**

*[!DNL Workfront Proof]*

Quando un utente visualizza una bozza, apre la [!UICONTROL Condividi bozza] e seleziona la [!UICONTROL Aggiungi messaggio personalizzato] l&#39;utente non può digitare nella casella di testo che si apre. Quando l’utente tenta di digitare la casella, questa scompare immediatamente.

**Impossibile chiudere la bozza**

*[!DNL Workfront Proof]*

Quando un utente visualizza una bozza e tenta di chiuderla, la X per chiuderla manca nell’angolo in alto a destra della bozza.

**Impossibile aggiungere o rimuovere l&#39;amministratore del gruppo**

*Gruppi*

Se un utente visualizza un [!UICONTROL Gruppo] e tenta di aggiungere o rimuovere un amministratore di gruppo utilizzando il [!UICONTROL Amministratori di gruppo] nell’intestazione, le modifiche non vengono salvate e l’utente visualizza il seguente errore:

[!UICONTROL Errore Whops! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]

**Opzione di blocco della barra di scorrimento orizzontale alla fine dell’elenco**

*Progetti*

Quando un utente visualizza un elenco utilizzando una vista che si estende oltre il lato dello schermo, la barra di scorrimento orizzontale blocca la visualizzazione dell’ultimo elemento dell’elenco da parte dell’utente.

**&quot;[!UICONTROL Errore imprevisto]&quot; durante la conversione di un problema in un progetto utilizzando un modello**

*Elenchi*

Quando un utente tenta di convertire un problema in un progetto utilizzando un modello, il problema non viene convertito e l&#39;utente visualizza il seguente messaggio:

[!UICONTROL Si è verificato un errore inatteso]

**La [!UICONTROL Stato] Il campo in una visualizzazione scheda attività è ora di sola lettura**

*Schede orario*

Abbiamo cambiato il [!UICONTROL Stato] in una visualizzazione scheda attività per essere di sola lettura. Prima di questa modifica, gli utenti potevano modificare in linea lo stato di una scheda attività che consentiva loro di ignorare la decisione degli approvatori della scheda attività.

+++

+++**Aggiornamento della manutenzione il 12 maggio 2022**

**[!UICONTROL Salva] il pulsante non smette di caricare quando si modifica un progetto**

*Progetti*

Quando un utente modifica un progetto e tenta di salvarlo, osserva che [!UICONTROL Salva] visualizza la parola &quot;[!UICONTROL Caricamento].&quot; Se l’utente fa clic su questo pulsante per salvare le modifiche apportate al progetto, il pulsante non risponde e le modifiche non vengono salvate.

**Le etichette dei campi non vengono visualizzate quando un oggetto è visualizzato in [!UICONTROL Pagina principale]**

*Pagina principale*

Quando un utente seleziona un oggetto dal proprio [!UICONTROL Elenco dei lavori domestici]la zona a destra [!UICONTROL Elenco dei lavori domestici] che visualizza l’oggetto senza le etichette dei campi. I valori dei campi sono presenti.

**Il filtro rapido non si attiva automaticamente sulla barra di ricerca**

*Elenchi*

Quando un utente si trova in un elenco e fa clic sulla lente di ingrandimento per filtrare rapidamente, quindi inizia a digitare, il testo non viene visualizzato. Questo perché la messa a fuoco rimane sull&#39;icona della lente d&#39;ingrandimento, invece di passare alla barra di ricerca.

Facendo clic sulla barra di ricerca, lo stato attivo viene trasferito e l’utente può immettere il testo della ricerca.

**Gli utenti non possono inserire campi di modifica in linea in un rapporto**

*Rapporti*

Quando un utente tenta di modificare un campo in un rapporto e tale campo viene estratto da un modulo personalizzato, l’utente non è in grado di modificare il campo. Ciò si verifica quando il modulo personalizzato è stato creato originariamente per un tipo di oggetto diverso dall’oggetto a cui è associato.

**Testo etichetta e pulsante non visibile durante la creazione di una bozza**

*[!DNL Workfront Proof]*

NOTA: Questo problema esiste solo nell&#39;ambiente Preview.

Quando un utente tenta di creare una bozza, il testo non è visibile per le opzioni o i pulsanti. Pertanto, l’utente non sa cosa rappresentano ciascuna opzione o pulsante e non può configurare la bozza.

+++

+++**Aggiornamento della manutenzione il 5 maggio 2022**

**Impossibile aggiungere un nuovo record di fatturazione**

*Progetti*

Quando un utente si trova nella [!UICONTROL Record di fatturazione] area di un progetto e utilizza [!UICONTROL Nuovo record di fatturazione] Visualizza, se l&#39;utente tenta di aggiungere un nuovo record di fatturazione, i campi per un nuovo record di fatturazione non vengono visualizzati e non è possibile creare il record di fatturazione.

**Errore durante l&#39;assegnazione in blocco in [!UICONTROL Bilanciamento del carico di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente tenta di effettuare assegnazioni nel [!DNL Workload Balancer] di un progetto, l’utente viene reindirizzato a una pagina con il seguente messaggio:

&quot;[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]&quot;

L’utente non può spostarsi da questa pagina finché non aggiorna la pagina.

**È stata aggiornata la navigazione per aprire la [!UICONTROL Riepilogo] pannello per le attività e i problemi [!UICONTROL Bilanciamento del carico di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Ora, è sufficiente fare clic su un&#39;attività o su una barra dei problemi nel [!UICONTROL Bilanciamento del carico di lavoro] apre il pannello Riepilogo . Prima di questo aggiornamento, era necessario fare clic sul pulsante [!UICONTROL Apri riepilogo] nella barra degli strumenti, quindi fare clic sull&#39;attività o sul problema. Ciò ha dimostrato un’esperienza confusa che ora viene corretta. In alternativa, puoi fare clic sul pulsante [!UICONTROL Altro] accanto al nome dell&#39;attività o del problema, quindi fare clic su [!UICONTROL Apri riepilogo].

**L&#39;amministratore del gruppo non può visualizzare i dettagli degli utenti del gruppo**

*Utenti*

Quando un utente viene assegnato a un livello di accesso che include [!UICONTROL Amministratore utente (utenti del gruppo)] l’impostazione di accesso tenta di visualizzare i dettagli di un utente del proprio gruppo, visualizzano il seguente errore:

&quot;[!UICONTROL Riproviamo. Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

**Impossibile eliminare lo stato del gruppo personalizzato**

*Gruppi*

Quando un utente tenta di eliminare uno stato di gruppo personalizzato dalla [!UICONTROL Gruppo] la pagina diventa vuota e lo stato non viene eliminato.

**Le impostazioni degli avvisi e-mail non sono coerenti tra l&#39;area Contatti e i Dettagli utente**

*[!DNL Workfront Proof]*

Impostazioni degli avvisi e-mail visualizzate nella [!UICONTROL Contatti] area [!DNL Workfront Proof] per un determinato utente sono diverse dall&#39;impostazione di avviso e-mail impostata nel [!UICONTROL Dettagli utente].

**Impossibile utilizzare lo strumento Testo quando si crea un commento su una bozza**

*[!DNL Workfront Proof]*

Quando un utente commenta una bozza e tenta di aprire la [!UICONTROL Testo] strumento, lo strumento non si apre e l&#39;utente visualizza il seguente messaggio:

&quot;[!UICONTROL È ancora in corso il download dei dati di testo per questa pagina. Per piacere, aspetti.]&quot;

**Le e-mail di prova verranno inviate all’e-mail principale dell’utente**

*[!DNL Workfront Proof]*

Stiamo modificando il modo in cui vengono inviate le notifiche e-mail di bozza. Ora, le notifiche passano all’indirizzo e-mail principale dell’utente anziché all’alias generato dal sistema.

Per ulteriori informazioni sul motivo per cui il sistema genera e-mail di alias, consulta Sincronizzazione degli utenti tra Adobe [!DNL Workfront] e [!DNL Workfront Proof].

+++

## Aggiornamenti nell’aprile 2022

+++**Aggiornamento della manutenzione il 28 aprile 2022**

**Impossibile scorrere fino a [!UICONTROL Salva] pulsante durante la modifica di una scheda attività**

*Schede orario*

Quando un utente sta modificando una scheda attività, non può scorrere la finestra di modifica in modo sufficientemente ampio da visualizzare il [!UICONTROL Salva] e quindi non può modificare la scheda attività.

**La firma elettronica ora controlla l&#39;ID federativo**

*Bozze*

Quando si firma una bozza elettronicamente, il sistema ora controlla l&#39;ID federazione, se l&#39;SSO è configurato in [!DNL Workfront Proof], oltre alla tua e-mail in [!DNL Workfront].

In precedenza, il sistema controllava solo l’e-mail in Workfront.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 25 aprile 2022**

**[!UICONTROL Bilanciamento del carico di lavoro] non viene caricato**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente tenta di aprire il [!UICONTROL Bilanciamento del carico di lavoro], l’intestazione e il caricamento di navigazione a sinistra, ma il contenuto del servizio di bilanciamento del carico di lavoro non viene caricato. L’utente visualizza quadrati grigi lampeggianti invece dei dati. A volte, parte del contenuto viene caricata, ma l’utente continua a vedere quadrati grigi lampeggianti dove sarebbero presenti i dati mancanti.

+++

+++**Aggiornamento della manutenzione il 21 aprile 2022**

**L&#39;aggiunta di un&#39;attività fa sì che la pagina salti verso il basso**

*Attività*

Quando un utente aggiunge un’attività sotto un’attività esistente in un elenco, la pagina si sposta verso il basso nell’elenco. Anche se la nuova attività si trova nella posizione corretta, l’utente deve scorrere indietro per individuarla.

**Gli utenti aggiunti a una bozza non possono accedere all’elemento di lavoro della bozza in[!DNL Workfront]**

*Bozze*

Se un utente viene aggiunto a un&#39;area di lavoro nel flusso di lavoro di una bozza, l&#39;utente non viene aggiunto alla condivisione del documento e non ottiene le autorizzazioni per l&#39;elemento di lavoro della bozza in [!DNL Workfront]. Quando l’utente è in [!DNL Workfront] e tenta di aprire l&#39;elemento di lavoro a cui è associata la bozza, visualizzano il seguente messaggio:

&quot;[!UICONTROL Accesso insufficiente per visualizzare l&#39;oggetto]&quot;

Questo problema è specifico per le bozze già create e gli utenti che vengono aggiunti dopo il fatto. L’aggiunta di utenti al flusso di lavoro prima della creazione della bozza funziona come previsto.

**Impossibile inviare l&#39;e-mail di reimpostazione password da[!DNL Workfront]**

*Utenti*

Quando un utente tenta di inviare un messaggio e-mail di reimpostazione della password da un elenco di utenti in [!DNL Workfront], l’opzione per inviare l’e-mail non è disponibile.

**Il pulsante visualizza &quot;[!UICONTROL Problema iniziale]&quot; anziché &quot;[!UICONTROL Richiesta di avvio]&quot;**

*Richieste*

Quando un utente visualizza una richiesta assegnata al proprio team, visualizza un &quot;[!UICONTROL Problema iniziale]&quot; nell&#39;intestazione anziché &quot;[!UICONTROL Richiesta di avvio]&quot; pulsante.

**&quot;[!UICONTROL Annulla commento]&quot; opzione rimuove gli utenti con tag**

*Aggiornamenti*

Quando un utente assegna un tag a un altro utente in un commento, lo pubblica e quindi seleziona il &quot;[!UICONTROL Annulla commento]&quot;, il commento viene visualizzato come di consueto in una casella di aggiornamento, ma l’utente con tag non è incluso [!UICONTROL Utenti con tag] scatola.

**Impossibile scorrere quando si utilizza [!UICONTROL Milestone] visualizzare in un report**

*Rapporti*

Quando un utente visualizza un rapporto e seleziona la [!UICONTROL Milestone] La pagina visualizza la vista Milestone ma non scorre più e l’utente non può visualizzare i Milestone che si troverebbero più in basso nella pagina.

**Valuta errata quando il report viene visualizzato nel dashboard**

*Rapporti*

Quando un utente visualizza un rapporto in un dashboard, la valuta utilizzata nel rapporto non è corretta. Quando l’utente visualizza il rapporto all’esterno del dashboard, la valuta è corretta.

**Il filtro completato non visualizza l&#39;elemento di lavoro completato**&#x200B;

*[!UICONTROL Pagina principale]*

Quando un utente visualizza la sua [!UICONTROL Elenco dei lavori domestici] con [!UICONTROL Completato] filtro selezionato, gli elementi di lavoro completati non vengono visualizzati nell&#39;elenco. Quando il [!UICONTROL Tutto] Il filtro è selezionato, gli elementi completati sono inclusi nell’elenco, mostrando l’esistenza degli elementi completati.

**[!DNL Workfront]non viene caricato**

*[!DNL Workfront]*

Quando un utente tenta di accedere a [!DNL Workfront], la pagina sembra essere bloccata in un ciclo di reindirizzamenti o aggiornamenti e non viene caricata.

+++

+++**Aggiornamento della manutenzione il 14 aprile 2022**

**Impossibile aggiungere un&#39;attività da un report su una sezione personalizzata su un&#39;attività**

*Attività*

Quando un utente visualizza una sezione personalizzata di un&#39;attività e la sezione contiene un rapporto di attività, non può aggiungere un&#39;attività da tale rapporto. La [!UICONTROL Aggiungi attività] il pulsante evidenzia il rapporto, ma non apre una finestra in cui l’utente può aggiungere un’attività.

**Pulsante Fine in posizione sbagliata durante la modifica di una visualizzazione**

*Viste*

Quando un utente sta modificando una visualizzazione, la [!UICONTROL Fine] il pulsante appare più in alto sullo schermo e potrebbe sovrapporsi al testo.

L’utente può modificare la visualizzazione come di consueto. Funzionalità non interessata.

**Impossibile scorrere quando si utilizza [!UICONTROL Milestone] visualizzare in un report**

*Rapporti*

Quando un utente visualizza un rapporto e seleziona la [!UICONTROL Milestone] La pagina visualizza la vista Milestone ma non scorre più e l’utente non può visualizzare i Milestone che si troverebbero più in basso nella pagina.

**Schermata vuota durante la visualizzazione degli aggiornamenti**

*Aggiornamenti*

Quando un utente visualizza gli aggiornamenti e scorre la schermata per visualizzare gli aggiornamenti più in basso, la schermata diventa vuota e l&#39;utente non può vedere alcun aggiornamento.

**Errore durante l&#39;assegnazione in massa dell&#39;utente a un&#39;attività non assegnata al ruolo dell&#39;utente**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente nella [!UICONTROL Bilanciamento del carico di lavoro] tenta di assegnare attività a un utente il cui ruolo di lavoro non corrisponde al ruolo di processo assegnato alle attività, l&#39;utente visualizza un messaggio che indica che l&#39;attività verrà assegnata utilizzando il ruolo di lavoro principale dell&#39;utente assegnato. Tuttavia, quando l&#39;utente fa clic su &quot;[!UICONTROL Assegna],&quot; le attività non sono assegnate e l&#39;utente visualizza il seguente errore:

&quot;[!UICONTROL Errore. Si è verificato un errore sconosciuto del server.]&quot;

+++

+++**Aggiornamento della manutenzione il 7 aprile 2022**

**Gli utenti aggiunti alle bozze hanno ruoli errati**

*Bozze*

Quando un utente aggiunge un altro utente a una bozza, il suo ruolo sulla bozza viene impostato come &quot;[!UICONTROL Sola lettura]&quot; nonostante il ruolo di bozza effettivo dell&#39;utente.

**Impossibile inviare l&#39;e-mail di reimpostazione della password all&#39;utente**

*Utenti*

Quando un utente tenta di inviare una reimpostazione della password a un altro utente, vede che [!UICONTROL Invia e-mail Password dimenticata] non è disponibile nella [!UICONTROL Altro] menu.

**[!UICONTROL Aggiorna tutto] invia aggiornamenti ai profili utente anziché al progetto**

*Aggiornamenti*

Quando un utente visualizza la variabile [!UICONTROL Persone] area di un progetto e seleziona la [!UICONTROL Aggiorna tutto] , quindi immette un aggiornamento, l’aggiornamento non viene inviato al progetto stesso. Viene invece pubblicato sui singoli profili utente di ogni utente del progetto.

**Numero eccessivo di pagine durante la stampa degli aggiornamenti**

*Aggiornamenti*

Quando un utente visualizza un flusso di aggiornamento che sarebbe più di una pagina stampata e tenta di stampare la pagina, la schermata di stampa mostra che il numero di pagine è molto superiore al numero effettivo di pagine necessarie per stampare gli aggiornamenti. Se l’utente tenta di stampare su PDF, la creazione di PDF non riesce.

**Gli utenti non possono visualizzare l&#39;intero elenco di entità condivise con un report quando &quot;[!UICONTROL Visibile a livello di sistema]&quot; l&#39;impostazione è abilitata**

*Rapporti*

Quando si condividono rapporti con più entità visualizzate nel [!UICONTROL Accesso ai rapporti] Gli utenti non possono scorrere fino alla parte inferiore dell&#39;elenco per visualizzare l&#39;intero elenco quando &quot;[!UICONTROL Visibile a livello di sistema]&quot; impostazione abilitata.

**Valuta errata utilizzata nei rapporti**

*Rapporti*

Se un utente imposta la valuta di un progetto in modo che sia diversa da quella predefinita, visualizza un rapporto sul progetto, la valuta verrà visualizzata come valuta predefinita al posto della valuta del progetto.

**Ultime informazioni visualizzate non aggiornate in [!UICONTROL Utilizzo dei rapporti] rapporti**

*Rapporti*

Quando un utente visualizza un rapporto che visualizza informazioni relative all’ultima visualizzazione del rapporto, tali informazioni potrebbero essere vuote o essere dati obsoleti. Questo problema riguarda i campi, tra cui:

* [!UICONTROL Ultima visualizzazione di]
* [!UICONTROL Ultimi dati visualizzati]
* [!UICONTROL Ultimi visualizzatori X]
* [!UICONTROL Visualizzazioni Questo Mese / Trimestre / Anno]

**Attività completate visualizzate in [!UICONTROL Elenco dei lavori domestici]**

*[!UICONTROL Pagina principale]*

Quando un utente visualizza la [!UICONTROL Elenco dei lavori domestici], nell’elenco vengono visualizzate le attività complete, anche quando l’opzione per visualizzare le attività completate non è selezionata.

**Pulsante Pianificazione non visibile per la pianificazione dell&#39;aggiornamento della sandbox**

*Ambiente sandbox*

La [!UICONTROL Pianificazione] il pulsante utilizzato per pianificare l’aggiornamento di una sandbox non è visibile nel banner superiore dell’ambiente sandbox.

**Le modifiche a un campo calcolato hanno effetto su tutti i campi calcolati di un modulo**

*Moduli personalizzati*

Quando un utente si trova nel Generatore di moduli personalizzato e modifica il valore di un modulo calcolato, tutti i campi calcolati del modulo visualizzano il nuovo valore. Questo può influenzare i campi calcolati nuovi o esistenti.

**Colori che sfarfallano nel generatore di moduli personalizzato**

*Moduli personalizzati*

Quando un utente lavora con campi calcolati nel generatore di moduli personalizzato, i colori dei campi e delle espressioni vengono visualizzati momentaneamente.

**[!UICONTROL Impossibile rifiutare un&#39;approvazione]**

*Approvazioni*

Quando un utente tenta di rifiutare un&#39;approvazione, il [!UICONTROL Rifiuta] Il pulsante non risponde e l&#39;approvazione non viene rifiutata.

**[!UICONTROL Progetti] la scheda viene impostata automaticamente su Tutti i progetti nonostante la selezione precedente**

*Progetti*

Quando un utente passa a una pagina Progetti tramite una scheda che è stata bloccata come parte del modello di layout, per impostazione predefinita la pagina [!UICONTROL Tutti i progetti] area della navigazione a sinistra. Ciò si verifica anche quando l’utente sceglie un’altra area della navigazione a sinistra, quindi si sposta dalla pagina Progetti e torna indietro.

+++


## Aggiornamenti a marzo 2022

+++**Aggiornamento della manutenzione il 31 marzo 2022**

**Fusi orari non coerenti tra [!DNL Workfront] e[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando il profilo di un utente è impostato su un fuso orario specifico in [!DNL Workfront], il fuso orario dell&#39;utente in [!DNL Workfront Proof] è impostato su un fuso orario diverso.

**Il collegamento per l&#39;invio di un documento richiesto porta a una pagina vuota**

*Documenti*

Quando un utente riceve una richiesta di invio di un documento e fa clic sul collegamento all&#39;oggetto in cui è stato richiesto il documento, il collegamento porta a una pagina vuota. Questo può verificarsi quando si fa clic su un collegamento in un’e-mail o in una notifica in-app.

**Il gruppo viene assegnato in modo errato durante la conversione del problema in progetto**

Gruppi

Quando un utente converte un problema in un progetto utilizzando un modello, la funzionalità è:

* Se al modello è assegnato un gruppo, tale gruppo viene visualizzato nella finestra di conversione del problema come gruppo per il nuovo progetto.
* Se al modello non è assegnato alcun gruppo, il gruppo predefinito dell’utente che sta convertendo il problema viene visualizzato nella finestra di conversione del problema come gruppo per il nuovo progetto.
* Se il modello non ha un gruppo, il nuovo progetto deve ereditare il gruppo dal progetto del problema.

**Impossibile associare il modulo personalizzato tra oggetti alla coda di richiesta**

Richieste

Quando un utente tenta di aggiungere un modulo personalizzato con più oggetti alla pagina dei dettagli di una coda, il modulo con più oggetti non viene visualizzato nell’elenco a discesa dei moduli disponibili e l’utente non può selezionarlo per aggiungerlo ai dettagli della coda.

**Gli utenti non possono essere assegnati con un ruolo secondario su [!UICONTROL Bilanciamento del carico di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente tenta di assegnare un altro utente a un&#39;attività nella [!UICONTROL Bilanciamento del carico di lavoro]e l&#39;attività viene assegnata a un ruolo di lavoro diverso dal ruolo di lavoro principale dell&#39;utente assegnato, l&#39;utente viene assegnato all&#39;attività in base al ruolo di lavoro principale e viene visualizzato il seguente messaggio:

&quot;\&lt;name> non corrisponde al ruolo di \&lt;task role=&quot;&quot; assignment=&quot;&quot;>. 1 elemento di lavoro attualmente assegnato al ruolo di &lt;\Task role Assignment\> verrà assegnato a \&lt;name> nel ruolo di \&lt;primary job=&quot;&quot; role=&quot;&quot;>.&quot;

Ciò si verifica anche se l&#39;utente ha il ruolo di lavoro dell&#39;assegnazione del ruolo Attività come ruolo secondario.

**Problema con Scrum Board &quot;Show more work items&quot; b**&#x200B;

*Agile*

Quando un utente fa clic sul pulsante [!UICONTROL Mostra altri elementi di lavoro] barra su una bacheca scrum, quindi scorre per vedere i nuovi elementi, il [!UICONTROL Mostra altri elementi di lavoro] barra si attacca alla Scrum Board e si muove con esso quando scorrevole. Questo può rendere le carte difficili da leggere.

**I punti rossi vengono visualizzati sui campi obbligatori nei moduli personalizzati**

Moduli personalizzati

Quando un utente visualizza un campo obbligatorio in un modulo personalizzato, sotto l’asterisco vengono visualizzati due punti rossi che indicano che il campo è obbligatorio.

**Taglio a discesa del tempo nei prompt**

*Rapporti*

Quando un utente compila le richieste di un report e rileva un selettore di date, il selettore di ora nella parte inferiore del selettore di date non visualizza ore oltre 2 e l&#39;utente non può selezionare valori orari oltre 1 o 2.

+++

+++**Aggiornamento di manutenzione (Hotfix) il 29 marzo 2022**

**Impossibile modificare o salvare i calcoli nel generatore di moduli personalizzati**

*Moduli personalizzati nel mio gruppo*

Se un utente immette manualmente un calcolo in un campo di calcolo nel generatore di moduli personalizzati e salva il modulo, il calcolo non viene salvato. Se l’utente riapre il modulo personalizzato, tale campo è vuoto.

Se un utente immette un calcolo in un campo di calcolo nel generatore di moduli personalizzati utilizzando i menu a discesa e salva il modulo, tale valore viene salvato. Tuttavia, se l’utente riapre il modulo personalizzato, non può modificare questo campo o rimuovere il valore, manualmente o con il menu a discesa.

NOTA: Questo problema è stato risolto includendo funzionalità aggiuntive. Ora, quando inizi a digitare in un campo calcolato, le espressioni o i calcoli possibili vengono visualizzati in un elenco a discesa sottostante, come nell&#39;Editor di calcolo. Fai clic su un elemento nel menu a discesa per aggiungerlo al campo calcolato.

+++

+++**Aggiornamento della manutenzione il 24 marzo 2022**

**Fusi orari non coerenti tra [!DNL Workfront] e[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando il profilo di un utente è impostato su un fuso orario specifico in [!DNL Workfront], il fuso orario dell&#39;utente in [!DNL Workfront Proof] è impostato su un fuso orario diverso.

**Errore campo richiesto per i campi personalizzati compilati durante l&#39;associazione a un modello**

*Progetti*

Quando si allega un modello con campi personalizzati obbligatori a un progetto in cui il campo esiste già ed è compilato, gli utenti visualizzano il seguente errore: &quot;[!UICONTROL Ci sono campi incompleti. Immetti i valori per i campi obbligatori prima di continuare.]&quot; Clic su &quot;[!UICONTROL Portami lì]&quot; consente loro di vedere che i campi sono compilati e possono allegare il modello con successo.

**La [!UICONTROL Bilanciamento del carico di lavoro] lampeggia quando si alternano date diverse**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Le ore dell’utente elencate per prime nella [!UICONTROL Bilanciamento del carico di lavoro] non visualizzare quando si aggiorna la timeline. L&#39;utente e le loro ore mostrano tutte le scatole grigie che lampeggiano. Questo accade se ci si sposta avanti e indietro sulla timeline.

L’aggiornamento del filtro sembra reimpostare la visualizzazione. Tuttavia, se si sposta avanti e indietro sulla timeline, il display lampeggia nuovamente e le ore dell&#39;utente non vengono visualizzate.

**La terminologia personalizzata non è coerente**

*Modelli di layout*

Gli utenti segnalano che quando [!DNL Workfront] l’amministratore personalizza la terminologia di alcuni oggetti utilizzando un modello di layout; il nuovo nome oggetto viene visualizzato in modo incoerente nell’interfaccia.

Ad esempio, nella [!UICONTROL Progetti] è comunque possibile visualizzare il titolo della pagina come &quot;[!UICONTROL Progetti]&quot;, anche se [!DNL Workfront] l&#39;amministratore ha cambiato il nome per &quot;[!UICONTROL Progetti]&quot; a qualcos&#39;altro.

Questo crea confusione per gli utenti finali.

+++

+++**Aggiornamento della manutenzione il 17 marzo 2022**

**Le immagini principali e miniature sono vuote quando si visualizzano file con più pagine utilizzando [!DNL Safari] browser**

*[!DNL Workfront Proof]*

Quando un utente tenta di visualizzare un file con più pagine nel [!DNL Safari] nel browser, le immagini delle miniature delle pagine sono vuote. A volte, anche l&#39;immagine principale può essere vuota.

**Elenco utenti errato durante l&#39;esecuzione di assegnazioni in serie nel [!UICONTROL Bilanciamento del carico di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente effettua un&#39;assegnazione in blocco nel [!UICONTROL Bilanciamento del carico di lavoro] e seleziona un Ruolo progetto e processo, l’elenco degli utenti disponibili non è corretto. Può mostrare gli utenti senza le autorizzazioni Ruolo lavoro o Progetto e gli utenti con le autorizzazioni Ruolo lavoro e Progetto non vengono visualizzati nell’elenco.

**[!UICONTROL L&#39;ordinamento non funziona nei rapporti]**

*Rapporti*

Quando un utente fa clic su una colonna per ordinare in base a essa, l’ordinamento sembra funzionare ma i risultati vengono immediatamente ripristinati nell’ordinamento originale visualizzato prima di fare clic sulla colonna. L’ordinamento su una colonna non viene mantenuto.

**Selezione di &quot;[!UICONTROL Niente]&quot; ritorna al [!UICONTROL Predefinito rapporto] raggruppamento**

*Rapporti*

Quando un report ha un raggruppamento integrato e l&#39;utente tenta di selezionare &quot;[!UICONTROL Niente]&quot; nel [!UICONTROL Raggruppamento] menu a discesa, il rapporto viene visualizzato a breve senza raggruppamenti e quindi viene ripristinato il [!UICONTROL Predefinito rapporto] raggruppamento.

**Rimosso &quot;[!UICONTROL Accesso alle blueprint]&quot; scheda dalle preferenze Blueprint**

*Blueprint*

NOTA: Questo problema esiste solo nell&#39;ambiente Preview.

La [!UICONTROL Accesso alle blueprint] La scheda è stata rimossa dalla finestra modale delle preferenze Blueprint. Nessuna funzionalità è stata rimossa dalle preferenze Blueprint.

+++

+++**Aggiornamento della manutenzione (Hotfix) il 14 marzo 2022**

**Impossibile scorrere l&#39;elenco utenti in basso quando si esegue un&#39;assegnazione su una bacheca kanban**

*Agile*

Quando un utente visualizza un [!DNL Kanban] bacheca e tenta di eseguire un&#39;assegnazione, l&#39;elenco di utenti visualizzato quando digitano continua a saltare all&#39;inizio mentre scorrono verso il basso. L&#39;utente non è in grado di selezionare un utente non vicino alla parte superiore dell&#39;elenco e non può salvare la modifica dell&#39;assegnazione.

**[!UICONTROL Milestone] La visualizzazione nel rapporto del progetto causa un errore**

*Rapporti*

Quando visualizzi un rapporto di progetto utilizzando [!UICONTROL Milestone] Visualizza, gli utenti ricevono un &quot;[!UICONTROL APIModel INTERNAL non supporta denominatoQuery TILE:milestone-view (UIVW)]&quot; errore.

**La terminologia personalizzata non è coerente**

*Modelli di layout*

Gli utenti segnalano che quando [!DNL Workfront] l’amministratore personalizza la terminologia di alcuni oggetti utilizzando un modello di layout; il nuovo nome oggetto viene visualizzato in modo incoerente nell’interfaccia.

Ad esempio, nella [!UICONTROL Progetti] è comunque possibile visualizzare il titolo della pagina come &quot;[!UICONTROL Progetti]&quot;, anche se [!DNL Workfront] l&#39;amministratore ha cambiato il nome per &quot;[!UICONTROL Progetti]&quot; a qualcos&#39;altro.

Questo crea confusione per gli utenti finali.

**Impossibile aggiornare i calcoli per i campi calcolati esistenti**

*Moduli personalizzati*

Gli utenti non possono aggiornare/modificare i calcoli nei campi calcolati. Se il campo è stato creato e salvato con senza un calcolo, ogni volta che si tenta di aggiungere un&#39;espressione e di salvare/applicare, il generatore torna a essere vuoto.

Se si crea un campo calcolato con una determinata espressione e lo si salva, ogni volta che si tenta di modificare il calcolo viene ripristinato il valore precedente.

**[!UICONTROL Parametro non valido] errore durante il ripristino delle password**

*Accedi*

Gli utenti non possono reimpostare le password in alcun ambiente. Quando inseriscono l’e-mail e tentano di procedere, viene visualizzato un errore.

[!UICONTROL Errore: Parametro non valido: Valore del parametro di ricerca &quot;domain&quot;].

+++

+++**Aggiornamento della manutenzione il 10 marzo 2022**

**Problemi di accesso all&#39;ambiente di anteprima**

*Accedi*

Sono stati segnalati i seguenti problemi relativi all’accesso all’ambiente Preview.

Quando un utente tenta di accedere all&#39;ambiente di anteprima, viene visualizzato un messaggio che indica che l&#39;ID o la password immessi è errata.

Quando un utente tenta di reimpostare la propria password, visualizza l&#39;errore &quot;[!UICONTROL ?Sono stati trovati più utenti con l&#39;indirizzo e-mail <example@example.com>?]&quot;

**I moduli personalizzati vengono caricati lentamente [!UICONTROL Dettagli progetto] area**

*Progetti*

Quando un utente tenta di visualizzare un [!UICONTROL Dettagli progetto] area, i moduli personalizzati allegati al progetto vengono caricati solo dopo un ritardo di 15 secondi o più. La [!UICONTROL Aggiungi moduli personalizzati] Anche questo ritardo influisce sull’opzione .

**I valori dei campi modulo personalizzati non vengono salvati nel pannello di riepilogo dei documenti**

*Documenti*

Quando un utente aggiorna i campi modulo personalizzati nel pannello di riepilogo del documento e uno o più di essi sono campi tipo, salva le modifiche e si allontana dal pannello di riepilogo, gli aggiornamenti non vengono salvati. Ciò si verifica solo quando viene modificato un campo typeahead, anche se tutti i campi sono interessati.

**I dati non vengono conservati durante la conversione dei modelli a causa della condivisione dei livelli di accesso**

*Progetti*

Quando un utente con accesso Visualizza su un modello condiviso tenta di convertire un problema in un progetto, tutti i dati contenuti nelle sezioni del modulo personalizzato che richiedono [!UICONTROL Contributo] o un accesso più elevato alla visualizzazione non viene trasferito al progetto creato.

**Errore durante il caricamento della nuova versione del documento**

*Documenti*

Quando un utente tenta di caricare una nuova versione di un documento dall&#39;elenco dei documenti, il documento non viene caricato e l&#39;utente visualizza il seguente errore:

[!UICONTROL Errore Impossibile richiamare &quot;com.attask.boz.Document.getCurrentVersion()&quot; perché &quot;document&quot; è null]

**Impossibile modificare le tariffe di fatturazione**

*Progetti*

Quando un utente tenta di modificare un tasso di fatturazione sul [!UICONTROL Tassi di fatturazione] scheda di un progetto, facendo clic sul pulsante [!UICONTROL Modifica] apre [!UICONTROL Modifica] per un breve periodo, ma si chiude prima che l&#39;utente possa modificare il tasso di fatturazione. Facendo nuovamente clic sul pulsante non si apre la finestra di modifica.

**Il link pubblico per il documento porta alla pagina vuota**

*Documenti*

Quando un utente tenta di aprire un documento utilizzando un collegamento pubblico, il collegamento porta a una pagina vuota. Ciò si verifica quando il collegamento viene aperto in una finestra in cui è attiva una [!DNL Workfront] sessione aperta.

**Errore durante l&#39;aggiunta di attività o problemi all&#39;elenco**

*Attività e problemi*

Quando un utente che non è un amministratore tenta di aggiungere un’attività o un problema a un elenco e compila campi personalizzati, l’attività o il problema non viene creato e l’utente visualizza il seguente errore:

[!UICONTROL Errore Whops! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]

**Se si lascia un aggiornamento dopo una modifica dello stato, l’oggetto viene ripristinato in uno stato precedente**

Progetti, attività e problemi

Se si modifica lo stato di un progetto, un&#39;attività o un problema e si inizia immediatamente a digitare un aggiornamento senza aggiornare la pagina, nella casella di aggiornamento viene visualizzato lo stato precedente. Se l&#39;aggiornamento viene pubblicato, l&#39;oggetto viene ripristinato allo stato precedente.

**Gli utenti aggiunti alle bozze hanno ruoli errati**

*Bozze*

Quando un utente aggiunge un altro utente a una bozza, il suo ruolo sulla bozza viene impostato come &quot;[!UICONTROL Sola lettura]&quot; nonostante il ruolo di bozza effettivo dell&#39;utente.

Soluzione: Imposta il ruolo di bozza dell&#39;utente nel suo profilo su qualcos&#39;altro, quindi reimposta il ruolo corretto.

**Il modulo personalizzato non viene caricato durante la conversione del problema in progetto utilizzando il modello**

*Moduli personalizzati nel mio gruppo*

Quando un utente tenta di convertire un problema in un progetto utilizzando un modello, uno o più moduli personalizzati allegati al modello potrebbero non essere caricati. Quando l’utente configura il modello per il nuovo progetto, invece dei moduli personalizzati viene visualizzato il seguente messaggio:

&quot;[!UICONTROL Errore durante il caricamento del modulo].&quot;

**L&#39;utente non è in grado di aggiungere il problema in linea con il campo a discesa personalizzato visualizzato nella visualizzazione**

*Elenchi*

Quando un utente aggiunge un problema dal menu in linea ed è presente una visualizzazione personalizzata con campi a discesa personalizzati applicati all’elenco, si verifica un errore quando compila solo il campo a discesa. L’utente dispone dell’accesso per modificare il modulo personalizzato ed è il proprietario del progetto con diritti di gestione per il progetto.

[!UICONTROL Errore: Wow! Si è verificato un errore. Contattare [!DNL Workfront] così possiamo capire cosa è andato storto e ripararlo!]

**Le autorizzazioni per aggiungere attività a un progetto non sono necessarie per spostare o copiare un&#39;attività nel progetto**

*Attività*

È ora possibile spostare o copiare un&#39;attività in un&#39;altra attività di un progetto senza disporre delle autorizzazioni necessarie per aggiungere attività al progetto di destinazione. È necessario disporre delle autorizzazioni per aggiungere attività ad almeno una delle attività del progetto di destinazione. Prima di questo aggiornamento, era necessario disporre delle autorizzazioni necessarie per aggiungere attività al progetto per spostare o copiare un&#39;attività nel progetto o in una delle relative attività.  Questo aggiornamento è ora disponibile nell’ambiente di produzione. È disponibile nell’ambiente Anteprima a partire dall’aggiornamento di manutenzione del 24 marzo 2022.

NOTA: Questo aggiornamento sarà disponibile nell’ambiente di produzione quando si copiano o si spostano i problemi dopo la versione 22.2 di Produzione. Per ulteriori informazioni sulla versione corrente, consulta workfront.com/release.

**Menu a discesa Prompt disattivato**

*Rapporti*

Quando in un rapporto viene visualizzato un prompt, i menu a discesa che consentono di selezionare i criteri di filtro per il rapporto vengono disattivati. Di conseguenza, i criteri nella parte inferiore del menu a discesa di selezione non vengono visualizzati.

**L&#39;elemento di lavoro torna allo stato precedente quando viene effettuato un aggiornamento**

*Aggiornamenti*

Quando un utente modifica lo stato di un elemento di lavoro nell’intestazione, lo stato non viene aggiornato nella [!UICONTROL Aggiorna] area. Se l’utente effettua un aggiornamento, il menu a discesa mostra ancora lo stato precedente. Quando l’aggiornamento viene salvato, questo stato precedente e errato sovrascrive lo stato impostato nell’intestazione.

+++

+++**Aggiornamento della manutenzione il 3 marzo 2022**

**Impossibile aggiungere il documento da[!DNL Google Drive]**

*Documenti*

Quando un utente tenta di aggiungere un documento da [!DNL Google Drive], la selezione non risponde e l&#39;utente non è in grado di selezionare i documenti da aggiungere.

**Gli utenti con tag non vengono aggiunti per aggiornare il thread**

*Aggiornamenti*

Quando un utente ha i tag in un aggiornamento, non viene visualizzato in &quot;[!UICONTROL A]&quot; area dell&#39;aggiornamento o delle relative risposte.

**L&#39;utente della bozza ha due account di correzione separati**

*[!DNL Workfront Proof]*

Indirizzo e-mail di un utente in [!DNL Workfront Proof] possono trovarsi in due account separati con ID separati, dando all&#39;utente due account. Questo può rendere difficile individuare l’account corretto.

**Errore durante la visualizzazione nelle intestazioni del report**

*Rapporti*

Quando un utente visualizza un rapporto, nell&#39;intestazione del rapporto viene visualizzato il seguente errore:

&quot;[!UICONTROL Riproviamo. Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]&quot;

Se l’utente sta visualizzando una dashboard, l’errore potrebbe comparire nell’intestazione di tutti i report sul dashboard.

**I dati nei campi di sola modifica dell’amministratore del modulo personalizzato non vengono mantenuti durante la conversione dei problemi in progetti**

*Progetti*

Quando un utente non amministratore tenta di convertire un problema in un progetto utilizzando un modello e il problema contiene dati in campi che possono essere modificati solo da un amministratore, i dati contenuti in tali campi non vengono trasferiti al nuovo progetto.

Quando un amministratore converte il problema, i dati vengono trasferiti al nuovo progetto come previsto.

**[!DNL XLS]e [!DNL XLSX] il limite di dimensione del file è temporaneamente diminuito a 100 MB per le bozze**

*Verifica*

Per risolvere un problema di sicurezza, abbiamo temporaneamente limitato la dimensione massima del file per [!DNL XLS] e [!DNL XLSX] a 100 MB durante la creazione di una bozza.

NOTA: Questo aggiornamento si trovava nell’ambiente Anteprima il 24 febbraio e sarà disponibile nell’ambiente Produzione il 3 marzo.

**Aggiornamento a Workfront Search**

Ricerca

Questa settimana è iniziato un rollout graduale per aggiornare l&#39;infrastruttura per [!DNL Workfront] Funzionalità di ricerca. L&#39;aggiornamento renderà i miglioramenti futuri alla ricerca più semplici e affidabili. Con queste modifiche, gli elementi aggiunti a [!DNL Workfront] verrà indicizzato più rapidamente e quindi restituirà i risultati della ricerca prima.

Il rollout graduale continuerà per 2 settimane.

**Sono state aggiornate le barre degli strumenti per i rapporti nelle dashboard**

Rapporti

I rapporti nelle dashboard ora mostrano una nuova barra degli strumenti. Questa barra degli strumenti fa parte degli aggiornamenti agli elenchi e ai rapporti che si verificano in tutto il mondo [!DNL Workfront].

+++


## Aggiornamenti a febbraio 2022

+++**Aggiornamento della manutenzione (Hotfix) il 24 febbraio 2022**

**I dati non vengono conservati durante la conversione dei problemi in progetti se il campo è nascosto nel modello**

*Progetti*

Quando un utente converte un problema in un modello e il modello include un modulo personalizzato che visualizza o nasconde campi basati sui valori di altri campi, tutti i dati contenuti nei campi nascosti nel modello (dati) al momento della conversione non vengono inseriti nel nuovo progetto.

**Impossibile esportare il planner risorse per ruolo**

*Pianificazione risorse*

Quando un utente tenta di esportare il [!DNL Resource Planner] quando si utilizza [!UICONTROL Visualizza per ruolo] l’esportazione non ha esito positivo e l’utente riceve un messaggio e-mail con il seguente messaggio:

Errore durante l&#39;esportazione del [!DNL Resource Planner] dati.

**Il pulsante Copia richiesta non funziona**

*Richieste*

Quando un utente tenta di copiare una richiesta, la [!UICONTROL Copia richiesta] Il pulsante non funziona se l’utente non dispone dell’accesso Visualizza all’argomento della coda.

+++

+++**Aggiornamento della manutenzione il 24 febbraio 2022**

**I dati del modulo personalizzato scompaiono quando vengono compilati altri campi del modulo**

*Moduli personalizzati nel mio gruppo*

Quando un utente compila un modulo personalizzato nell’ambito della conversione di un problema in un progetto, la compilazione di un campo personalizzato potrebbe causare la scomparsa dei dati in un altro campo personalizzato. Se l’utente immette nuovamente i dati mancanti, quando tenta di creare il progetto, visualizza il seguente messaggio di errore:

&quot;[!UICONTROL Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema]&quot;

**&quot;[!UICONTROL Questo processo di approvazione può essere utilizzato da...]&quot; campo mancante**

*Approvazioni*

Quando un utente crea o modifica un processo di approvazione in [!UICONTROL Configurazione] area, &quot;[!UICONTROL Questo processo di approvazione può essere utilizzato da...]&quot; campo mancante. Questo può verificarsi durante la creazione di un processo di approvazione o la modifica di uno esistente.

**L&#39;amministratore di sistema non può riassegnare gli utenti quando si elimina un gruppo**

*Gruppi*

Quando un amministratore di sistema elimina un gruppo, avrà solo la possibilità di riassegnare gli utenti del gruppo ai gruppi per i quali l&#39;amministratore di sistema è un amministratore di gruppo. Gli altri gruppi non vengono visualizzati nel menu a discesa e l’amministratore non può selezionarli.

**Whops error durante la conversione del problema in progetto**

*Progetti*

Quando un utente tenta di convertire un problema in un progetto utilizzando un modello e aggiunge o rimuove moduli personalizzati dal modello, il problema non viene convertito e l&#39;utente visualizza il seguente messaggio:

[!UICONTROL Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]

**Impossibile aprire la bozza; aggiornamento della pagina**

*Bozze*

Quando un utente tenta di aprire una bozza, questa non può essere aperta. Alla fine, la pagina viene aggiornata.

**[!DNL XLS]e [!DNL XLSX] il limite di dimensione del file è temporaneamente diminuito a 100 MB per le bozze**

*Verifica*

Per risolvere un problema di sicurezza, abbiamo temporaneamente limitato la dimensione massima del file per [!DNL XLS] e [!DNL XLSX] a 100 MB durante la creazione di una bozza.

NOTA: Questo aggiornamento sarà disponibile nell’ambiente Anteprima il 24 febbraio e nell’ambiente Produzione il 3 marzo.

**Le autorizzazioni per aggiungere attività o problemi a un progetto non sono necessarie per spostare o copiare un&#39;attività o un problema nel progetto**

*Progetti*

È ora possibile spostare o copiare un&#39;attività o un problema in un&#39;altra attività di un progetto senza disporre delle autorizzazioni necessarie per aggiungere attività o problemi al progetto di destinazione. È necessario disporre delle autorizzazioni per aggiungere attività o problemi ad almeno una delle attività del progetto di destinazione. Prima di questo aggiornamento, era necessario disporre delle autorizzazioni necessarie per aggiungere attività o problemi al progetto per spostare o copiare un&#39;attività o un problema nel progetto o in una delle relative attività. Questo aggiornamento è disponibile solo nell’ambiente di anteprima.

NOTA: Questo aggiornamento sarà disponibile nell’ambiente di produzione quando si esegue il ping o lo spostamento delle attività il 10 marzo. Questo aggiornamento sarà disponibile nell’ambiente di produzione quando si copiano o si spostano i problemi con la versione di produzione 22.2. Per ulteriori informazioni sulla versione corrente, consulta workfront.com/release.

**Aggiornamento a Workfront Search**

*Ricerca*

Questa settimana è iniziato un rollout graduale per aggiornare l&#39;infrastruttura per [!DNL Workfront] Funzionalità di ricerca. L&#39;aggiornamento renderà i miglioramenti futuri alla ricerca più semplici e affidabili. Con queste modifiche, gli elementi aggiunti a [!DNL Workfront] verrà indicizzato più rapidamente e quindi restituirà i risultati della ricerca prima.

Il rollout graduale continuerà per 2 settimane.

+++

+++**[!DNL Workfront Fusion]Aggiornamento della manutenzione il 18 febbraio 2022**

**Aggiunta convalida del tipo di valore campo a [!DNL Anaplan] proprietà degli elementi elenco**

*[!DNL Adobe Workfront Fusion]*

È stato risolto un problema che consentiva agli utenti di inserire il tipo di dati errato nei campi per le proprietà dell’elemento elenco. La convalida del tipo di proprietà consente [!DNL Fusion] per garantire che venga inviato ad Anaplan il tipo di dati corretto, eliminando gli errori causati da tipi di dati errati.

+++

+++**Aggiornamento della manutenzione il 17 febbraio 2022**

**Errore durante l&#39;eliminazione del predecessore dalla scheda Predecessori**

*Attività*

Quando un utente tenta di eliminare un predecessore dal [!UICONTROL Predecessori] su un&#39;attività, l&#39;attività non viene eliminata e l&#39;utente visualizza il seguente errore:

[!UICONTROL Attività con valori chiave primaria &quot;&quot; non trovata]

**Whops error all&#39;apertura della pagina degli utenti**

*Utenti*

Quando un utente tenta di aprire il [!UICONTROL Utenti] la pagina non si apre e l’utente visualizza il seguente errore:

[!UICONTROL Wow! Si è verificato un errore. Contattare [!DNL Workfront] quindi possiamo capire cosa è andato storto e ripararlo.]

**Sovrapposizione di elementi nell’intestazione di un rapporto su una dashboard**

*Dashboard*

Quando un utente visualizza un rapporto su un dashboard, noterà che l’icona e l’etichetta dei raggruppamenti si sovrappongono ai collegamenti a [!UICONTROL Dettagli] e [!UICONTROL Riepilogo].

**Problemi relativi a &quot;[!UICONTROL Altro]&quot; menu per documenti e bozze**

*Documenti*

Quando un utente seleziona un documento o una bozza su un [!DNL Workfront Classic] elenco documenti, quindi fare clic su &quot;[!UICONTROL Altro],&quot; possono riscontrare uno dei seguenti problemi: Il pulsante non risponde Tutte le opzioni sotto il pulsante sono etichettate &quot;[!UICONTROL oggetto]&quot; e non può essere utilizzato.

**Errore &quot;Devi essere un amministratore di sistema&quot; durante la creazione di un progetto**

*Progetti*

Quando un utente non amministratore tenta di creare un progetto e allega un modulo personalizzato con una sezione disponibile solo per gli amministratori, non può creare il progetto e viene visualizzato il seguente errore:

&quot;Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema&quot;

**I dati nella sezione di sola amministrazione del modulo personalizzato non vengono conservati durante la conversione dei problemi in progetti**

*Progetti*

Quando un utente converte un problema in un progetto utilizzando un modello con un modulo personalizzato con una sezione di sola amministrazione, tutti i dati della sezione di sola amministrazione non vengono trasferiti al nuovo progetto. Ciò si verifica anche se un amministratore sta convertendo il problema.

+++

+++**Aggiornamento della manutenzione il 10 febbraio 2022**

**&quot;[!UICONTROL Devi essere un amministratore di sistema]&quot; errore durante la creazione di un progetto**

*Progetti*

Quando un utente non amministratore tenta di creare un progetto e allega un modulo personalizzato con una sezione disponibile solo per gli amministratori, non può creare il progetto e viene visualizzato il seguente errore:

&quot;[!UICONTROL Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema]&quot;

**Gli utenti disattivati e riattivati non vengono visualizzati in [!UICONTROL Contatti di prova]**

*[!DNL Workfront Proof]*

Quando un utente visualizza l&#39;elenco dei contatti in [!DNL Workfront Proof], gli utenti disattivati e riattivati non vengono visualizzati nell’elenco.

**Messaggio &quot;Qualcosa è andato storto&quot; durante la conversione di un problema in un progetto utilizzando un modello**

*Progetti*

Quando un utente non amministratore tenta di convertire un problema in un progetto utilizzando un modello, i campi modulo personalizzati visibili solo agli amministratori mostrano il seguente messaggio:

&quot;[!UICONTROL Errore durante il caricamento del modulo]&quot;

**Errore &quot;Impossibile caricare il contenuto della pagina&quot; durante la visualizzazione delle preferenze del progetto**

*Configura*

Quando un utente amministratore tenta di visualizzare progetti, attività o problemi in [!UICONTROL Preferenze del progetto] in [!UICONTROL Configurazione] area, la pagina non viene caricata e l’utente visualizza il seguente errore:

&quot;[!UICONTROL Impossibile caricare il contenuto della pagina. Provare a riaggiornare la pagina.]&quot;

+++

+++**Aggiornamento della manutenzione il 3 febbraio 2022**

**[!UICONTROL BizContext] errore durante l&#39;accesso**

*Accedi*

Quando un utente sta tentando di accedere a [!DNL Workfront], l&#39;accesso non ha esito positivo e viene visualizzato il seguente messaggio:

&quot;[!UICONTROL Riproviamo. Errore del database: commit BizContext non riuscito.]&quot;

Questo è stato riportato nell’ambiente Anteprima.

**Il flusso di aggiornamento del problema scompare se il problema è in attesa di approvazione**

*Aggiornamenti*

Quando un utente fa clic in [!UICONTROL Nuovo aggiornamento] nel flusso di aggiornamento di un problema in attesa di approvazione, l&#39;intero flusso di aggiornamento scompare.

**Errore durante il caricamento della nuova versione di un documento**

*Documenti*

Quando un utente tenta di caricare una nuova versione di un documento, la nuova versione non viene caricata e l&#39;utente visualizza uno dei seguenti errori:

* [!UICONTROL documentID non può essere null]
* [!UICONTROL Errore: Parametro non valido: valore documentID &quot;undefined&quot;]

**Il link pubblico per il documento porta alla pagina vuota**

*Documenti*

Quando un utente tenta di aprire un documento utilizzando un collegamento pubblico, il collegamento porta a una pagina vuota. Ciò si verifica quando il collegamento viene aperto in una finestra in cui è attiva una [!DNL Workfront] sessione aperta.

**I controlli elenco non funzionano sui rapporti nelle dashboard**

*Dashboard*

Quando un utente visualizza un rapporto in una dashboard e tenta di modificare il filtro, il raggruppamento o la visualizzazione del rapporto, il filtro, il raggruppamento o la visualizzazione non cambiano.

**&quot;[!UICONTROL Devi essere un amministratore di sistema]&quot; errore durante la creazione di un progetto**

*Progetti*

Quando un utente non amministratore tenta di creare un progetto e allega un modulo personalizzato con una sezione disponibile solo per gli amministratori, non può creare il progetto e viene visualizzato il seguente errore:

&quot;[!UICONTROL Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema]&quot;

**I dati personalizzati non vengono mantenuti durante la conversione del problema in progetto**

*Progetti*

Quando un utente converte un problema in un progetto utilizzando un modello, i dati di un modulo personalizzato relativo al problema non vengono trasferiti nel modulo personalizzato comparabile del progetto. Ciò si verifica per i dati contenuti in campi personalizzati che possono essere nascosti in base ai valori di altri campi personalizzati.

**Errore durante la conversione del problema nel progetto**

*Progetti*

Quando un utente tenta di convertire un problema in un progetto, il problema non viene convertito e viene visualizzato il seguente errore:

&quot;[!UICONTROL Un errore inaspettato si è verificato]&quot;

+++


## Aggiornamenti a gennaio 2022

+++**Aggiornamento della manutenzione il 27 gennaio 2022**

**I dati personalizzati non vengono mantenuti durante la conversione del problema in progetto**

*Progetti*

Quando un utente converte un problema in un progetto utilizzando un modello, i dati di un modulo personalizzato relativo al problema non vengono trasferiti nel modulo personalizzato comparabile del progetto. Ciò si verifica per i dati contenuti in campi personalizzati che possono essere nascosti in base ai valori di altri campi personalizzati.

**L&#39;elenco degli utenti sulla bacheca di agile non è alfabetico**

*Agile*

Quando un utente visualizza l&#39;elenco degli utenti su una bacheca mobile, gli utenti non vengono visualizzati in ordine alfabetico. Vengono invece elencati per primi gli utenti con il maggior numero di assegnazioni.

**Collegamenti aggiornati per copiare e spostare i problemi**

*problemi*

Nell’ambiente Anteprima, i collegamenti per copiare e spostare i problemi sono stati aggiornati a &quot;[!UICONTROL Copia in]&quot; e &quot;[!UICONTROL Sposta a]&quot; sia nella pagina del problema che in un elenco di problemi.

**Aggiungi fino a 45 indirizzi IP al tuo [!DNL Workfront] inserire nell&#39;elenco Consentiti**

*Configura*

Limite per gli indirizzi IP aggiunti al tuo [!DNL Workfront] inserire nell&#39;elenco Consentiti&#39; è aumentato da 30 a 45.

+++

+++**Aggiornamento della manutenzione il 20 gennaio 2022**

**&quot;[!UICONTROL Parametro non valido]&quot; errore durante la creazione di un progetto dal modello**

*Progetti*

Quando un utente tenta di creare un progetto da un modello e rimuove un modulo personalizzato dal modello durante la creazione del progetto, il progetto non viene creato e l&#39;utente visualizza un &quot;[!UICONTROL Parametro non valido]&quot; messaggio di errore che fa riferimento a un campo obbligatorio nel modulo personalizzato rimosso.

**L&#39;elenco utenti non viene caricato [!DNL Safari] browser**

*Utenti*

Quando un utente accede alla pagina [!UICONTROL Utenti] area, l&#39;intestazione viene visualizzata ma l&#39;elenco degli utenti non viene caricato.

**Ritardo durante il trascinamento di attività in un elenco causa lo spostamento dell&#39;attività in una posizione errata**

*Elenchi*

Quando un utente tenta di spostare un’attività in un elenco trascinandola, la linea blu che indica dove verrà spostata l’attività si sposta molto più lentamente del cursore. Quando l’utente rilascia l’attività, questa si sposterà nel punto in cui si trova la linea blu, anche se il cursore punta a una posizione diversa nell’elenco.

+++

+++**[!DNL Workfront Fusion]Aggiornamento della manutenzione il 14 gennaio 2022**

**Alcuni campi mappati vengono reimpostati quando si selezionano [!UICONTROL nuovo campo da mappare]**

*[!DNL Workfront Fusion]*

Se almeno un campo nel [!DNL Workfront] [!UICONTROL Crea] o [!UICONTROL Aggiorna] i moduli hanno la mappatura abilitata e un utente seleziona un nuovo campo da mappare, i campi mappati in precedenza abilitati per la mappatura perdono i valori di mappatura.

+++

+++**Aggiornamento della manutenzione il 13 gennaio 2022**

**Impossibile aggiungere un collegamento ipertestuale a un commento nel pannello Riepilogo**

*Attività*

Quando un utente fa un commento nel pannello di riepilogo di un&#39;attività e tenta di aggiungere un collegamento ipertestuale al commento, viene visualizzata la finestra del collegamento ipertestuale, ma non appena l&#39;utente fa clic nella finestra si chiude e l&#39;utente non può aggiungere un collegamento ipertestuale. Se un utente si sposta con il tasto Tab nella finestra, può digitare o incollare un collegamento nel campo, ma il collegamento ipertestuale non viene salvato. In entrambi i casi, l’attività viene deselezionata.

**La pagina Modifica team non viene chiusa**

*Team*

Quando un utente tenta di modificare un team, la [!DNL Edit team] la pagina non si chiude. L’utente non può chiudere la pagina facendo clic su un pulsante, facendo clic sulla X o allontanandosi dalla pagina.

**Le notifiche e-mail e in-app non vengono inviate**

*Notifiche*

Quando si verifica un evento che deve attivare una notifica, la notifica non viene inviata. Questo può verificarsi per le notifiche e-mail o in-app e anche se vengono inviate altre notifiche.

**[!UICONTROL Il mio lavoro] elenco vuoto**

*[!UICONTROL Il mio lavoro]*

Quando un utente visualizza la sua [!UICONTROL Il mio lavoro] e il modello di layout [!UICONTROL Il mio lavoro] l’elenco include un valore numerico quale [!UICONTROL Percentuale completata], [!UICONTROL Il mio lavoro] elenco non visualizzato.

**[!UICONTROL Percentuale completata] e [!UICONTROL Ore complete] non può essere modificato su Agile Board**

*Agile*

Quando un utente seleziona &quot;[!UICONTROL Mostra altri elementi di lavoro]&quot; sulla bacheca di Agile, cerca quindi di cambiare il [!UICONTROL Percentuale completata] o [!UICONTROL Ore complete] in uno degli elementi di lavoro appena caricati, non è possibile modificare la percentuale di completamento o la percentuale di completamento ore. La [!UICONTROL Percentuale completata] Il pulsante è inoltre grigio e indica che è inattivo.

+++

+++**Aggiornamento della manutenzione il 6 gennaio 2022**

**&quot;[!UICONTROL Parametro non valido]&quot; errore durante l&#39;associazione di modelli o moduli personalizzati ai progetti**

*Progetti*

Quando un utente tenta di allegare un modulo personalizzato o un modello a un progetto esistente, compila i campi obbligatori nel modulo o modello personalizzato e salva le modifiche al progetto, le modifiche non vengono salvate e l&#39;utente visualizza un &quot;[!UICONTROL Parametro non valido]&quot; errore nella parte superiore della pagina dei dettagli del progetto.

**I commenti della bozza non vengono visualizzati negli aggiornamenti del documento**

*Bozze*

Quando un utente visualizza una bozza nel [!UICONTROL Documenti] area, le eventuali osservazioni sulla prova stessa non vengono visualizzate nel [!UICONTROL aggiornamenti] area del documento.

**[!UICONTROL Bilanciatore dei carichi di lavoro]: &quot;[!UICONTROL ?[oggetto]?]&quot; viene visualizzato nelle informazioni sulla sovrallocazione**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Se un utente viene visualizzato come sovrapassegnato nel [!UICONTROL Bilanciamento del carico di lavoro] a causa di un&#39;attività che si sovrappone al tempo libero dell&#39;utente e un altro utente visualizza la sua sovrallocazione, il &quot;[!UICONTROL Capacità]&quot; viene visualizzata l&#39;area delle informazioni sulla sovrallocazione &quot;[!UICONTROL ?[oggetto]?]&quot; invece della capacità effettiva dell&#39;utente.

+++

## Aggiornamenti precedenti alla manutenzione

Le informazioni sui precedenti aggiornamenti di manutenzione sono disponibili qui:

* [[!DNL Workfront] Archivio aggiornamenti manutenzione - 2021](2021-updates.md)
