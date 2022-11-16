---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: ffd3cb1f7e355af7fd568a33c7ca205031633276
workflow-type: tm+mt
source-wordcount: '15307'
ht-degree: 99%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2022.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. L’assistenza [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Per gli aggiornamenti di manutenzione precedenti al 2022, vedi [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di novembre 2022

+++**(Pianificato) Aggiornamento di manutenzione del 17 novembre 2022**

**Nascondere un elemento nasconde l&#39;elemento non corretto**

*Modelli di layout*

Quando un utente cambia se un elemento è nascosto o visualizzato, tali modifiche vengono applicate a un elemento diverso nel modello di layout.


+++

+++**Aggiornamento di manutenzione del 10 novembre 2022**

**La modifica collettiva delle attività modifica le assegnazioni delle attività**

*Attività*

Quando un utente modifica in blocco un campo di un set di attività, le assegnazioni della prima attività vengono applicate a tutte le attività. Questo elimina le assegnazioni precedenti.

**Impossibile aprire una bozza interattiva**

*Bozza Workfront*

Quando un utente cerca di aprire una bozza interattiva, la bozza non si apre e viene visualizzato il seguente errore:

“[!UICONTROL Bozza non caricata (501) Riprova]”

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 4 novembre 2022**

**Problemi relativi alle attività aggiunte a un’iterazione**

*Agile*

Sono stati segnalati i seguenti problemi relativi ad attività aggiunte a un’iterazione:

* Alcune sotto attività di un’attività aggiunta a un’iterazione non vengono visualizzate nella pagina [!UICONTROL Iterazione].
* Quando un utente tenta di aggiungere un’attività mancante all’iterazione, l’attività non viene aggiunta e l’utente visualizza il seguente messaggio:

   “[!UICONTROL Si è verificato il seguente errore: impossibile spostare gli elementi selezionati perché non sono assegnati a un Team Agile o non sono elementi Agile]”

**Le attività assegnate tramite la modifica in blocco non vengono visualizzate nel backlog del team**

*Agile*

Quando un utente assegna attività a un team Scrum utilizzando la modifica in blocco, queste attività non vengono visualizzate nel backlog del team.

I team Kanban non sono interessati da questo problema.

**La casella di testo “[!UICONTROL Destinatari nuova bozza]” è troppo piccola**

*Bozze*

Quando un utente visualizza una bozza e tenta di condividerla dalla scheda [!UICONTROL Condivisione], la casella di testo “[!UICONTROL Destinatari nuova bozza]” è molto piccola. L’utente può digitare un nome, ma date le dimensioni ridotte della casella, il testo viene disposto in modo da rendere difficile lettura.

**Le informazioni sull’utilizzo del report non vengono aggiornate**

*Report*

Quando un utente visualizza un rapporto, le informazioni Ultima visualizzazione, come Ultima data di visualizzazione e Ultima visualizzazione di, non vengono aggiornate. Ciò significa che eventuali informazioni di utilizzo potrebbero essere errate.

Questo comportamento è stato segnalato quando l’utente accede al rapporto nei seguenti modi:

* Ricerca
* Pin
* Preferiti
* Recenti

L’accesso ai rapporti tramite una dashboard aggiorna le informazioni Ultima visualizzazione.

**[!DNL Workfront]: errore 500 quando si apportano modifiche a un oggetto [!DNL Workfront]**

*[!DNL Workfront]*

Quando un utente cerca di apportare modifiche a un oggetto [!DNL Workfront], le modifiche non vengono salvate e viene visualizzato il seguente errore:

“[!UICONTROL 500: Errore database a causa di dichiarazione SQL non valida.]”

Questo problema è stato segnalato nelle seguenti situazioni:

* Modifica dello stato di un oggetto
* Ricalcolo delle timeline
* Allegamento di un modello
* Registrazione dell’ora

+++

+++**[!DNL Workfront Fusion]Aggiornamento di manutenzione del 3 novembre 2022**

**Errore relativo a [!UICONTROL apiKey] nel modulo [!DNL Workfront] > [!UICONTROL Osserva eventi]**

*[!DNL Workfront Fusion]*

Quando un utente tenta di aggiungere un webhook nel modulo [!DNL Workfront] > [!UICONTROL Osserva eventi], riceve il seguente errore:

“[!UICONTROL La chiave apiKey fornita è vuota o ritenuta non valida.]”

+++

+++**Aggiornamento di manutenzione del 3 novembre 2022**

**Ridenominazione delle sezioni “Pianifica” e “Pianificazione” per team e progetti nel modello di layout**

*Modelli di layout*

Le schede “Pianifica” e ”Pianificazione” da aggiungere a un modello di layout nel pannello di sinistra di un team o di un progetto sono state rinominate “Bilanciatore dei carichi di lavoro”.

**Errori durante l’accesso alle impostazioni di notifica e-mail**

*Notifiche*

>[!NOTE]
>
>Questo problema esiste sia negli ambienti di Produzione che in quelli di Anteprima.

Quando un utente cerca di modificare le impostazioni delle notifiche e-mail, potrebbe visualizzare i seguenti errori:

* ”[!UICONTROL Riproviamo. Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

* “[!UICONTROL Impossibile recuperare la notifica e-mail]”

Ciò è stato segnalato nelle seguenti aree:

* [!UICONTROL Setup] (Configura) > [!UICONTROL Email notifications] (Notifiche e-mail)
* [!UICONTROL User] (Utente)> [!UICONTROL Edit user] (Modifica utente)
* [!UICONTROL Gruppi]

+++

## Aggiornamenti di ottobre 2022

+++**Aggiornamento di manutenzione del 27 ottobre 2022**

La funzione **[!UICONTROL ORA] nei campi calcolati utilizza valori UTC**

*Moduli personalizzati*

Quando un campo calcolato include la funzione [!UICONTROL ORA], questa restituisce valori basati su UTC anziché sul fuso orario previsto. Pertanto, eventuali calcoli basati sul valore ORA risultano errati.

**[!UICONTROL Filtro rapido] non restituisce alcun risultato durante la ricerca di team**

*Elenchi*

Quando un utente tenta di utilizzare il [!UICONTROL filtro rapido] in un elenco per cercare un team, l’immissione del nome del team non restituisce alcun risultato, anche quando il team è visibile nell’elenco (ad esempio nel campo [!UICONTROL Assegnato a]). La ricerca della parola [!UICONTROL “team”] non restituisce alcun risultato.

**Impossibile ripetere l’operazione di fissaggio di una pagina dopo la rimozione dello stesso**

*Navigazione*

>[!NOTE]
>
>Questo problema è stato risolto in Anteprima il 13 ottobre 2022. È stato risolto in Produzione il 27 ottobre 2022.

Quando un utente seleziona l’opzione “[!UICONTROL Rimuovi pin]” su un pin, riceve un messaggio sulla rimozione e tenta di sostituire il pin facendo clic su “[!UICONTROL Annulla]” nel messaggio, il pin non viene sostituito nella navigazione superiore, né viene aggiunto all’elenco dei pin sotto l’elenco [!UICONTROL Altri pin] (il menu con tre punti nell’area [!UICONTROL Pin]).

Se un utente tenta di fissare nuovamente la pagina andando alla pagina e fissandola, il pin non viene creato e l’utente non è in grado di completare l’operazione.

**Tutti gli utenti elencati in [!UICONTROL Bilanciatore dei carichi di lavoro] quando si utilizza un collegamento condivisibile nel [!DNL Safari] browser**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente segue un collegamento condivisibile nel [!UICONTROL Bilanciatore dei carichi di lavoro] mentre utilizza un browser [!DNL Safari], vengono visualizzati tutti gli utenti anziché solo i membri del team elencato.

+++

+++**Aggiornamento di manutenzione del 20 ottobre 2022**

**Errore durante l’assegnazione in blocco di un team**

*Assegnazioni*

Quando un utente modifica attività o problemi in blocco e assegna un team dopo l’assegnazione di un singolo utente, le assegnazioni non vengono salvate e l’utente visualizza il seguente errore:

“[!UICONTROL Riproviamo - Si è verificato il seguente errore: teamAssignments deve essere un elenco di oggetti o un elenco di ID]”

**Errore “[!UICONTROL Impossibile caricare il file]”**

*Documenti*

Quando un utente tenta di caricare un file nell’area [!UICONTROL Documenti], il file non viene caricato e l’utente visualizza l’errore “[!UICONTROL Impossibile caricare il file].”

Il problema è stato segnalato durante il caricamento di file MP4.

**Il conteggio dei problemi nella navigazione a sinistra dell’attività non è corretto**

*Problemi*

Quando un utente visualizza un’attività, il numero visualizzato nella sezione [!UICONTROL Problemi] della navigazione a sinistra non rappresenta con precisione il numero effettivo di problemi associati all’attività.


Icona **[!UICONTROL Predecessore] mancante nell’intestazione dell’attività**

*Attività*

Quando un utente visualizza un’attività, l’icona del predecessore attività risulta mancante nell’intestazione.

+++

+++**Aggiornamento di manutenzione del 13 ottobre 2022**

**Impossibile ripetere l’operazione di fissaggio di una pagina dopo la rimozione dello stesso**

*Navigazione*

>[!NOTE]
>
>Questo problema verrà risolto in Anteprima il 13 ottobre 2022. Sarà risolto in Produzione il 27 ottobre 2022.

Quando un utente seleziona l’opzione “[!UICONTROL Rimuovi pin]” su un pin, riceve un messaggio sulla rimozione e tenta di sostituire il pin facendo clic su “[!UICONTROL Annulla]” nel messaggio, il pin non viene sostituito nella navigazione superiore, né viene aggiunto all’elenco dei pin sotto l’elenco [!UICONTROL Altri pin] (il menu con tre punti nell’area [!UICONTROL Pin]).

Se un utente tenta di fissare nuovamente la pagina andando sulla pagina e fissandola, il pin non viene creato e l’utente non è in grado di completare l’operazione.

**Impossibile assegnare un nome o salvare i filtri appena creati**

*[!UICONTROL Pianificazione risorse]*

Quando un utente tenta di denominare un nuovo filtro nella [!UICONTROL Pianificazione risorse], la casella del nome rimane vuota. Inoltre, se l’utente ha premuto la barra spaziatrice, il pulsante [!UICONTROL Salva] si disattiva.

**Impossibile modificare il nome o la percentuale di completamento di un’attività o di un problema**

*Attività e problemi*

Utenti con l’accesso [!UICONTROL Contribuisci] a un’attività o a un problema non possono modificare il nome dell’attività o del problema nell’intestazione. Inoltre, gli utenti con l’accesso [!UICONTROL Contribuisci] non possono modificare la percentuale di completamento di un’attività o di un problema.

**i richiedenti e i revisori vengono conteggiati nel numero di licenze di un’organizzazione**

*[!DNL Workfront Proof]*

Quando un utente viene aggiunto a una bozza come revisore o richiedente, ottiene il profilo di autorizzazione “[!UICONTROL Visitatore]”, che non utilizza una licenza di [!DNL Workfront Proof]. Quando l’utente viene aggiunto, tuttavia, il numero di licenze di [!DNL Workfront Proof] utilizzate aumenta.

+++

+++**Aggiornamento di manutenzione dell’11 ottobre 2022**

**Impossibile ripetere il fissaggio di una pagina dopo la rimozione dello stesso**

*Navigazione*

>[!NOTE]
>
>Questo problema è stato risolto in Anteprima il 13 ottobre 2022. Sarà risolto in Produzione il 27 ottobre 2022.

Quando un utente seleziona l’opzione “[!UICONTROL Rimuovi pin]” su un pin, riceve un messaggio sulla rimozione e tenta di sostituire il pin facendo clic su “[!UICONTROL Annulla]” nel messaggio, il pin non viene sostituito nella navigazione superiore, né viene aggiunto all’elenco dei pin sotto l’elenco [!UICONTROL Altri pin] (il menu con tre punti nell’area [!UICONTROL Pin]).

Se un utente tenta di fissare nuovamente la pagina andando sulla pagina e fissandola, il pin non viene creato e l’utente non è in grado di completare l’operazione.

+++

+++**Aggiornamento di manutenzione del 6 ottobre 2022**

**Nuovo tipo di blueprint**

*Blueprint*

Il tipo di blueprint “Dashboard” è stato aggiunto al catalogo dei blueprint. In precedenza erano disponibili solo i modelli Modello di progetto e Struttura organizzativa.

**Elementi che si sovrappongono nel pannello a sinistra**

*Moduli personalizzati nel mio gruppo*

Il messaggio di notifica relativo al limite dei campi, che viene visualizzato nel caso in cui un utente utilizzi il generatore di moduli con un modulo contenente più di 100 campi, causa la sovrapposizione degli elementi nel pannello sinistro.

**La selezione della data non si apre più automaticamente quando si attiva l’input o si fa clic su**

*Navigazione*

Quando un utente naviga tramite tastiera, le selezioni della data non vengono più aperte automaticamente alla data in cui l’input della tastiera riceve lo stato attivo. Al contrario, gli utenti che utilizzano la tastiera devono passare all’icona della selezione data e premere Invio per aprire la selezione data. Quando un utente naviga usando il mouse, le selezioni della data non vengono più aperte automaticamente quando si fa clic sull’input della data. Al contrario, gli utenti che utilizzano il mouse devono fare clic sull’icona della selezione della data per aprire la selezione della data.

Questa modifica è stata apportata per conformarsi ai pattern UX standard della selezione di data e creare un’esperienza più accessibile per gli utenti che utilizzano tastiera e assistenti vocali.

**L’assegnazione di più team risulta nell’assegnazione di un unico team**

*Team*

>[!NOTE]
>
>Questo problema esiste solo nell’ambiente di anteprima.

Quando un utente assegna più team a un’attività o a un problema, nell’elenco delle assegnazioni viene visualizzato un solo team. Questo problema influisce anche sulla produzione di report. I report che mostrano le assegnazioni del team non sono accurati, poiché viene visualizzato un unico team assegnato all’attività o al problema.

Errore **“[!UICONTROL Le modifiche recenti non sono state salvate]” durante il salvataggio automatico delle modifiche su una scheda orario**

*Schede orario*

Quando un utente cerca di modificare una scheda orario in modo da attivare un salvataggio automatico, le modifiche non vengono salvate e l’utente visualizza il seguente messaggio:

“[!UICONTROL Le modifiche recenti non sono state salvate. Aggiorna la pagina da visualizzare.]”

Questo problema è stato segnalato durante la modifica dei seguenti elementi:

* Ore
* Attività

**le notifiche e-mail subiscono ritardi**

*Bozza Workfront*

In [!DNL Workfront Proof], quando si verifica un evento che attiva una notifica e-mail, l’utente non riceve immediatamente l’avviso. La notifica può subire un ritardo di diverse ore.

+++

+++**Aggiornamento di manutenzione del 3 ottobre 2022**

**Salvataggio manuale della scheda orario quando i ruoli di lavoro precedenti sono cambiati**

*Schede orario*

Se un ruolo di lavoro per il quale hai effettuato l’accesso è cambiato e l’impostazione [!UICONTROL Assegnare manualmente i ruoli del processo alle voci orarie] è stata disabilitata, è necessario salvare manualmente le voci orarie fino a quando non vengono più registrate ore per la mansione che è stata modificata.

+++

## Aggiornamenti di settembre 2022

+++**Aggiornamento di manutenzione del 29 settembre 2022**

**L’utente non ritorna alla pagina precedente quando chiude la bozza**

*Bozze*

Quando un utente che sta visualizzando una bozza in [!DNL Workfront] chiude la bozza, non viene reindirizzato alla pagina in cui si trovava prima di aprire la bozza. Viene invece reindirizzato a un’altra pagina in [!DNL Workfront].

**Impossibile aprire la bozza in[!DNL Workfront]**

*Bozze*

Quando un utente visualizza un documento in [!DNL Workfront] e prova ad aprire la bozza, la bozza non si apre e l’utente viene reindirizzato alla pagina [!UICONTROL Dettagli documento].

**Le ore non vengono salvate quando si utilizza il tasto [!UICONTROL TAB]**

*Schede orario*

Quando un utente compila una scheda orario e naviga tra le celle con il tasto [!UICONTROL TAB], le ore non vengono salvate. La notifica di [!UICONTROL salvataggio automatico] non viene visualizzata nella parte inferiore della schermata e, se l’utente aggiorna la pagina, può vedere che le ore non sono state salvate.

**Pagine vuote quando si visualizza una bozza con più pagine**

*[!DNL Workfront Proof]*

Quando un utente visualizza una bozza con più pagine, può vedere le miniature delle pagine, ma le pagine non si aprono nel visualizzatore principale.



+++

+++**Aggiornamento di manutenzione del 22 settembre 2022**

**Non è possibile chiudere la scheda utente nel flusso di aggiornamento**

*Aggiornamenti*

Quando un utente visualizza gli aggiornamenti e passa il mouse su un nome, si apre una scheda con i dettagli dell’utente che non si chiude automaticamente. La pagina non risponde finché la scheda non viene chiusa manualmente facendo clic sulla X nell’angolo in alto a destra.

+++

+++**Aggiornamento di manutenzione del 15 settembre 2022**

**Errore “[!UICONTROL Qualcun altro ha tentato di salvare questo progetto]” durante l‘immissione delle ore**

*Schede orario*

Quando un utente cerca di registrare le ore per un’attività sulla propria scheda orario, le ore non vengono salvate automaticamente e l’utente visualizza il seguente errore:

”[!UICONTROL Database error from concurrent edit on a locked row. Automatic retry failed. Try transaction later.]”

**Non è possibile chiudere la scheda utente nel flusso di aggiornamento**

*Aggiornamenti*

Quando un utente visualizza gli aggiornamenti e passa il mouse su un nome, si apre una scheda con i dettagli dell’utente che non si chiude automaticamente. La pagina non risponde finché la scheda non viene chiusa manualmente facendo clic sulla X nell’angolo in alto a destra.

**Il campo “[!UICONTROL Assegnazione ruolo attività]” è stato rinominato “[!UICONTROL Assegnazione ruolo]” quando è stato assegnato il lavoro in blocco utilizzando il [!UICONTROL Bilanciatore dei carichi di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Per rispecchiare la nuova funzionalità di assegnazione di attività e problemi in blocco dall’area [!UICONTROL Lavoro non assegnato], il campo “[!UICONTROL Assegnazione ruolo attività]” è stato rinominato “[!UICONTROL Assegnazione ruolo]” nel [!UICONTROL bilanciatore dei carichi di lavoro]. Il campo si riferisce alle mansioni che sono state assegnate ad attività o problemi e viene visualizzato quando si assegnano gli utenti agli elementi nella casella [!UICONTROL Assegnazioni in blocco].

+++

+++**[!DNL Workfront Scenario Planner]- Aggiornamento di manutenzione del 15 settembre 2022**

**Adesso il filtro condiviso con un gruppo viene visualizzato nell’elenco [!UICONTROL Importa progetti] di [!DNL Scenario Planner] per i membri di tutti i sottogruppi**

*[!DNL Workfront Scenario Planner]*

Adesso, quando si condivide un filtro di progetto con un gruppo che ha altri sottogruppi, il filtro è visibile a tutti i membri del gruppo e del sottogruppo che visualizzano i progetti nella casella [!UICONTROL Importa progetti] di un piano in [!DNL Scenario Planner].

+++

+++**Aggiornamento di manutenzione dell’8 settembre 2022**

**Nomi aggiornati ripristinati per i campi di assegnazione degli utenti e dei ruoli**

*Assegnazioni*

Sono stati ripristinati i nomi originali dei campi di assegnazione che erano stati temporaneamente rinominati la settimana scorsa:

* [!UICONTROL Assegnazione Utente]
* [!UICONTROL Assegnazioni Ruoli]

**Errore durante la rimozione del proprietario del progetto dall’intestazione**

*Progetti*

Quando un utente cerca di rimuovere un [!UICONTROL Proprietario del progetto] dall’intestazione di un progetto, il [!UICONTROL Proprietario del progetto] non viene rimosso e l’utente visualizza il seguente messaggio di errore:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**La casella [!UICONTROL Descrizione] ridimensionata torna alle dimensioni originali**

*Progetti, attività e problemi*

Quando un utente ridimensiona la casella [!UICONTROL Importa progetti] nell’area dei Dettagli di un elemento di lavoro per ingrandirlo e inizia a digitare nella casella, questa ritorna alle dimensioni originali. L’utente può ancora digitare nella casella e il contenuto viene salvato come previsto

**Uscita involontaria durante la creazione di attività o problemi**

*Attività e problemi*

Quando, durante la creazione di un’attività o un problema in un progetto, l’utente fa clic all’esterno del pop-up di creazione, il pop-up si chiude senza alcun preavviso e tutte le informazioni immesse in precedenza vengono perse.

**È stata rimossa la possibilità di inviare una bozza a una dropzone via e-mail**

*[!DNL Workfront Proof]*

A partire dall’8 settembre 2022, è stata rimossa la possibilità di inviare bozze via e-mail alle zone di rilascio nel prodotto autonomo [!DNL Workfront Proof].

È comunque possibile utilizzare le dropzone in altri modi per inviare nuove bozze e nuove versioni delle bozze al proprio account senza dovervi accedere. Vedi [Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html?lang=it) per ulteriori informazioni.

+++

+++**Aggiornamento di manutenzione del 6 settembre 2022**

**Sono state aggiunte date previste all’elenco dei campi per le intestazioni di progetto personalizzabili**

*Progetti*

Sono state aggiunte la [!UICONTROL Data di inizio prevista] e la [!UICONTROL Data di completamento prevista] all’elenco dei campi per le intestazioni di progetto personalizzabili quando si utilizza un modello di layout.

**Nuovo limite con un messaggio di conferma che visualizza il numero di elementi aggiunti a una scheda orario**

*Schede orario*

Quando si selezionano più di 50 elementi da aggiungere a una scheda orario, viene visualizzato un messaggio di conferma che mostra il numero di elementi da aggiungere alla scheda e consente di cambiare idea e non aggiungere tutti gli elementi. Tutti gli elementi aggiunti vengono automaticamente bloccati nella scheda orario e dovranno essere rimossi manualmente dalle schede attuali e da quelle future.

+++

+++**Aggiornamento di manutenzione del 2 settembre 2022**

È stato aggiunto il campo [!UICONTROL Integrazioni] all’intestazione personalizzata del progetto

*Integrazioni*

Ora è possibile aggiungere il campo [!UICONTROL Integrazioni] all’intestazione personalizzata di un progetto quando si utilizza un modello di layout. Una volta aggiunto, il campo mostra un collegamento a un elemento esterno collegato al progetto che si trova in [!DNL Salesforce] o [!DNL Anaplan], a seconda dell’integrazione.

>[!NOTE]
>
>Questo aggiornamento di manutenzione è stato rilasciato in precedenza nell’ambiente di anteprima il 25 agosto 2022 e adesso si trova in quello di produzione.

+++

+++**Aggiornamento di manutenzione del 1° settembre 2022**

**Elementi completati rimossi dalla delega**

*Deleghe*

Adesso, solo gli elementi incompleti le cui date corrispondono a quelle di una delega verranno delegati ad altri utenti quando inizia la delega degli elementi di lavoro. Se gli elementi sono stati completati prima dell’avvio della delega, non saranno delegati. Gli elementi che vengono completati durante il periodo di delega rimarranno sull’elenco di lavoro dell’area Home sia per il delegato sia per l’assegnatario per due settimane prima di essere rimossi automaticamente, se la delega non è terminata durante queste settimane.

**Aggiornamenti dei metadati per le integrazioni di [!DNL Adobe Workfront] per [!DNL Experience Manager Assets] e [!DNL Assets Essentials]**

*Integrazioni*

I metadati vengono inviati automaticamente quando aggiungi una risorsa a una cartella collegata.

In precedenza, i metadati venivano inviati solo quando si aggiungeva una risorsa utilizzando il menu a discesa [!UICONTROL Aggiungi nuovo].

**Impossibile approvare o rifiutare le ore su un problema**

*Problemi*

Quando un utente cerca di approvare o rifiutare ore nella scheda [!UICONTROL Ore] di un problema, mancano i pulsanti [!UICONTROL Approva] e [!UICONTROL Rifiuta].

**Messaggio di errore non corretto quando si converte un problema in un progetto utilizzando un modello**

*Problemi*

Quando si verifica un errore durante la conversione di un problema in un progetto mediante modello, l’utente visualizza una pagina con un messaggio di tipo “[!UICONTROL Il progetto non esiste più]” invece del messaggio di errore corretto che spiega la causa della conversione non riuscita.

**Impossibile creare una bozza per file superiori a 1,5 GB**

*[!DNL Workfront Proof]*

Durante la creazione di una nuova bozza, se un utente carica un file di dimensioni superiori a 1,5 GB, il nome del file diventa di colore rosso e la bozza non viene creata.

+++

## Aggiornamenti di agosto 2022

+++**Aggiornamento di manutenzione del 25 agosto 2022**

**I collegamenti del bilanciatore dei carichi di lavoro non vengono visualizzati correttamente nei dashboard**

*Dashboard*

I collegamenti condivisibili del Bilanciatore dei carichi di lavoro non vengono visualizzati correttamente se aggiunti a un dashboard come pagina esterna. Invece di utilizzare la visualizzazione o i filtri univoci associati al collegamento, il dashboard utilizza quelli applicati più di recente al bilanciatore dei carichi di lavoro.

**È stato aggiunto il campo [!UICONTROL Integrazioni] all’intestazione personalizzata del progetto**

*Progetti*

Ora è possibile aggiungere il campo [!UICONTROL Integrazioni] all’intestazione personalizzata di un progetto quando si utilizza un modello di layout. Una volta aggiunto, il campo mostra un collegamento a un elemento esterno collegato al progetto che si trova in [!DNL Salesforce] o [!DNL Anaplan], a seconda dell’integrazione.

>[!NOTE]
>
>Questo aggiornamento di manutenzione è attualmente disponibile solo nell’ambiente di anteprima. Verrà rilasciato in produzione una settimana dopo il lancio nell’ambiente di anteprima.

**I dati personalizzati non vengono conservati quando si converte un problema in un progetto vuoto**

*Progetti*

Quando un utente converte un problema in un progetto vuoto (senza un modello), i dati contenuti nei campi calcolati non vengono trasferiti al nuovo progetto.

**Errore “Modalità Pianificazione sequenza temporale” durante la modifica della data in un progetto**

*Progetti*

Quando un utente cerca di modificare una data in un progetto la cui [!UICONTROL Modalità pianificazione] è impostata su [!UICONTROL Salvataggio manuale] > [!UICONTROL Pianificazione sequenza temporale], la data non viene modificata e l’utente visualizza un errore.

“[!UICONTROL La modalità di pianificazione della sequenza temporale è disponibile solo quando timelineDate è caricata. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

**Coerenza quando si apre il bilanciatore dei carichi di lavoro utilizzando la visualizzazione Mese**

*Bilanciatore dei carichi di lavoro*

Adesso il bilanciatore dei carichi di lavoro mostra la visualizzazione espansa degli elementi assegnati dagli utenti quando compaiono nelle viste [!UICONTROL Giorno], [!UICONTROL Settimana] o [!UICONTROL Mese]. Prima di questo aggiornamento, gli elementi assegnati venivano mostrati nella visualizzazione espansa per le viste [!UICONTROL Giorno] e [!UICONTROL Settimana] e in quella ridotta per [!UICONTROL Mese].


+++

+++**Aggiornamento di manutenzione del 18 agosto 2022**

**Opzioni “[!UICONTROL Aggiungi a iterazione]” e “[!UICONTROL Aggiungi a bacheca Kanban]” non disponibili quando si modificano attività in linea in un report**

*Report*

Quando un utente visualizza un elenco di attività in un report e apre il menu [!UICONTROL Altro] (tre punti), le opzioni “[!UICONTROL Aggiungi a iterazione]” e “[!UICONTROL Aggiungi a bacheca Kanban]” non sono disponibili nel menu a discesa. Se il report viene visualizzato in un dashboard, le opzioni “[!UICONTROL Aggiungi a iterazione]” e “[!UICONTROL Aggiungi a bacheca Kanban]” sono disponibili nel menu a discesa.

**I report matrice non vengono visualizzati correttamente durante lo scorrimento**

*Report*

Quando un utente visualizza un report matrice e scorre, alcuni elementi visivi del report potrebbero sovrapporsi o risultare duplicati.

Vista **[!UICONTROL Milestone] rimossa dall’elenco dei progetti delle schede orario**

*Schede orario*

La vista [!UICONTROL Milestone] viene rimossa dall’elenco dei progetti della scheda orario quando si aggiunge un progetto.

**I collegamenti ipertestuali in una bozza interattiva non sono attivi**

*[!DNL Workfront Proof]*

Quando un utente visualizza una bozza interattiva e fa clic su un collegamento o su un pulsante che contiene un collegamento, non viene reindirizzato alla pagina a cui il collegamento o il pulsante si collega.

**Campi di testo mancanti nella pagina Nuova bozza**

*[!DNL Workfront Proof]*

Sulla pagina [!DNL New Proof] non vengono visualizzati molti campi di testo (comprese le etichette dei campi, le opzioni a discesa e i nomi delle caselle di controllo).

**Gli utenti non ricevono notifiche quando vengono taggati in una bozza**

*[!DNL Workfront Proof]*

Quando un utente viene taggato all’interno di un commento della bozza, non riceve la relativa notifica e-mail.

+++

+++**Aggiornamento di manutenzione del 12 agosto 2022**

**È stato aggiunto un nuovo campo intestazione personalizzabile all’inizio dell’intestazione**

*Intestazioni*

Adesso, quando si aggiunge un nuovo campo a un’intestazione personalizzabile, il campo viene aggiunto come primo campo a sinistra nell’intestazione o subito dopo la casella di [!UICONTROL Ricerca] all’interno del modello di layout. Prima di questa modifica, il campo veniva aggiunto come ultimo campo nell’intestazione.

+++

+++**Aggiornamento di manutenzione dell’11 agosto 2022**

**Impossibile modificare i moduli personalizzati a causa di un limite di caratteri errato nei campi di testo descrittivo**

*Moduli personalizzati nel mio gruppo*

Quando un utente tenta di modificare un modulo personalizzato con un campo [!UICONTROL Testo descrittivo] contenente più di 512 caratteri, non può salvare le modifiche all’interno di tale modulo e visualizza il messaggio di errore seguente:

“I campi seguenti non sono validi: (Campo) è troppo lungo, massimo 512 caratteri”

Questo problema riguarda anche i campi [!UICONTROL Testo descrittivo] con più di 512 caratteri che in precedenza funzionavano correttamente.

**I dati nei campi nascosti da un’interruzione di sezione non vengono mantenuti quando si converte un problema in un progetto**

*Moduli personalizzati nel mio gruppo*

Quando un utente converte un problema in un progetto e il problema include un modulo personalizzato con dati in un’interruzione di sezione che può essere nascosta utilizzando la logica di visualizzazione, i dati in tale sezione non vengono trasferiti al nuovo progetto.

**I dati nei campi nascosti dall’interruzione di sezione non vengono conservati quando si converte una richiesta in un progetto**

*Moduli personalizzati nel mio gruppo*

Quando un utente converte una richiesta in un progetto e la richiesta include un modulo personalizzato con dati in un’interruzione di sezione che può essere nascosta utilizzando la logica di visualizzazione, i dati in tale sezione non vengono trasferiti al nuovo progetto.

**Impossibile modificare i moduli personalizzati a causa del campo Testo descrittivo**

*Moduli personalizzati nel mio gruppo*

Quando un utente tenta di modificare un modulo personalizzato che include un campo Testo descrittivo, l’etichetta del campo non si popola. L’utente visualizza l’errore “[!UICONTROL Questo campo è obbligatorio]” nel campo etichetta e a causa di questo errore non può modificare il modulo personalizzato.

**Impossibile rimuovere istruzioni da un campo personalizzato nel sistema di creazione di moduli personalizzati**

*Moduli personalizzati nel mio gruppo*

Quando un utente modifica un campo personalizzato e tenta di rimuovere il testo esistente nella sezione [!UICONTROL Istruzioni], il testo non viene rimosso durante il salvataggio del campo. L’utente può modificare il testo, ma non può rimuoverlo completamente.

**L’assegnazione del team durante la creazione della richiesta non viene visualizzata nella nuova richiesta**

*Richieste*

Quando un utente crea una richiesta, vi assegna un team e poi la invia, il team non viene assegnato alla richiesta creata. Ciò influisce solo sull’assegnazione del team. Le assegnazioni degli utenti funzionano come previsto.

+++

+++**Aggiornamento di manutenzione del 4 agosto 2022**

Questi problemi sono stati risolti solo nella nuova esperienza [!DNL Workfront].

Tutte le funzionalità [!DNL Workfront Classic] sono state rimosse il 14 luglio 2022.

**Errore durante la modifica della data di completamento pianificata nell’intestazione di un’attività o di un problema**

*Attività e problemi*

Quando un utente tenta di modificare il campo [!UICONTROL Data di completamento pianificata] nell’intestazione di un’attività o di un problema, la data non cambia e l’utente visualizza un messaggio di errore simile al seguente:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Aggiornamenti di luglio 2022

+++**Aggiornamento di manutenzione del 28 luglio 2022**

Questi problemi sono stati risolti solo nella nuova esperienza [!DNL Workfront].

Tutte le funzionalità [!DNL Workfront Classic] sono state rimosse il 14 luglio 2022.

**Errore durante l’apertura di un elemento presente nella sezione [!UICONTROL Elenco lavori]** dell’area Home

*[!UICONTROL Home]*

Quando un utente cerca di aprire un elemento nella sezione [!UICONTROL Elenco lavori] dell’area Home, l’elemento non si apre e l’utente visualizza il seguente messaggio:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro prova ad aggiornare la pagina del browser.]”

**Le attività e i problemi delegati a un utente non vengono visualizzati nell’elenco di lavoro dell’area Home dell’utente**

*[!UICONTROL Pagina principale]*

Quando l’utente visualizza la sezione [!UICONTROL Elenco lavori] dell’area Home, eventuali attività o problemi delegati all’utente non compaiono nell’elenco e l’utente potrebbe non essere a conoscenza delle deleghe.

**I report pianificati non vengono inviati a tutti i destinatari**

*Report*

Quando viene inviato un report pianificato, non viene inviato a tutti gli utenti nella sezione “[!UICONTROL Invia a]”. Gli utenti omessi sono casuali e possono variare ogni volta che il report viene inviato.

**[!UICONTROL Impossibile deselezionare le attività quando si allega il modello]**

*Modelli*

Quando un utente allega e personalizza un modello, viene richiesto di deselezionare le attività che non desidera includere. Tuttavia, nessuna delle attività viene visualizzata come selezionata e l’utente non può deselezionarle.

**Adesso i campi “Locale” hanno etichette più specifiche**

*Terminologia*

Per rendere più chiara la funzione dei campi “[!UICONTROL Locale]” sono state aggiornate le relative etichette.

* Il campo “[!UICONTROL Locale]” sul profilo utente ora è etichettato come “[!UICONTROL Email Locale]”
* Il campo “[!UICONTROL Lingua]” presente nell’area [!UICONTROL Configura] > [!UICONTROL Sistema] > [!UICONTROL Informazioni cliente] adesso si chiama “[!UICONTROL Impostazioni internazionali e-mail predefinite]”

La funzionalità di questi campi non è cambiata.

**Problemi durante la creazione delle schede orario**

*Schede orario*

Sono stati segnalati i seguenti problemi relativi alla creazione delle schede orario:

* Quando un utente tenta di creare una scheda orario per una mansione, questa non viene creata e l’utente visualizza l’errore “[!UICONTROL Utente con valori della chiave primaria ‘XXXXXXXXXXX’ non trovato.]”
* Quando un utente cerca di creare una scheda orario per un team, nel campo [!UICONTROL Automatico] non vengono inseriti i team e il pulsante [!UICONTROL Crea scheda orario] è disabilitato.


**Alcune aree di [!DNL Workfront Proof] non si aggiornano quando viene creata, spostata o archiviata una bozza**

*[!DNL Workfront]Bozza*

Al momento Proof sta riscontrando ritardi nell’indicizzazione. Ciò può influire sull’esperienza dell’utente in vari modi, tra cui i seguenti:

* I dashboard non mostrano il numero corretto di bozze
* Le cartelle non vengono aggiornate quando si crea o si sposta una bozza
* Le bozze archiviate rimangono negli elenchi delle bozze attive.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 26 luglio 2022**

Questi problemi sono stati risolti solo nella nuova esperienza [!DNL Workfront].

Tutte le funzionalità [!DNL Workfront Classic] sono state rimosse il 14 luglio 2022.

**Le ore visualizzate nella scheda orario non corrispondono a quelle dell’elenco**

*Schede orario*

Quando un utente apre una scheda orario per visualizzarla, gli orari visualizzati sono diversi da quelli mostrati quando per la stessa scheda orario in un elenco delle schede orario.


**La richiesta convertita in progetto con modello mostra il gruppo della coda richieste e non quello del modello**

*Richieste*

Quando un utente converte una richiesta in un progetto utilizzando un modello, il progetto appena creato viene associato al gruppo proprietario della coda richieste, non al gruppo assegnato sul modello. Ciò si verifica anche se durante la creazione del progetto, il gruppo associato al modello viene inserito nel campo [!UICONTROL Gruppo].

+++

+++**Aggiornamento di manutenzione del 21 luglio 2022**

Questi problemi sono stati risolti solo nella nuova esperienza [!DNL Workfront].

Tutte le funzionalità [!DNL Workfront Classic] sono state rimosse il 14 luglio 2022.

**Lo stato di rifiuto associato a un’approvazione rispetta il flusso di lavoro di approvazione**

**NOTA: questa funzionalità è stata rilasciata il 22 luglio 2022.**

*Approvazioni*

Se si seleziona uno stato associato a un processo di approvazione come stato di rifiuto per un percorso di approvazione, l’oggetto rifiutato si sposta sullo stato selezionato e verrà contrassegnato come “[!UICONTROL In attesa di approvazione]”. Ad esempio, selezionando [!UICONTROL In sospeso] con lo stato [!UICONTROL In sospeso] associato a un processo di approvazione, l’oggetto rifiutato passa allo stato “[!UICONTROL In sospeso - In attesa di approvazione]” e richiede l’approvazione.

Prima di questo aggiornamento, l’oggetto ignorava il processo di approvazione per lo stato di rifiuto e passava allo stato [!UICONTROL In sospeso].

**Configurare un URL guida personalizzato**

*[!UICONTROL Menu principale]*

Se la tua organizzazione dispone di un sito di assistenza interno dedicato, puoi configurare l’icona [!UICONTROL Aiuto] del [!UICONTROL menu principale] per passare a quel sito. Questa opzione è utile se il sito di assistenza contiene informazioni sull’utilizzo di [!DNL Workfront] da parte dell’organizzazione.
Questo URL dedicato non influisce sul collegamento della Guida principale nell’area superiore di [!DNL Workfront], né sui collegamenti di assistenza sensibili al contesto presenti in [!DNL Workfront], che portano gli utenti al sito di assistenza di [!DNL Workfront].

**Impossibile selezionare il Tempo trascorso quando si modifica la [!UICONTROL Durata attività]** in linea

*Attività*

Quando un utente visualizza un elenco di attività e tenta di modificare la [!UICONTROL Durata attività], le seguenti unità di durata non sono disponibili:

* [!UICONTROL Minuti trascorsi]
* [!UICONTROL Ore trascorse]
* [!UICONTROL Giorni trascorsi]
* [!UICONTROL Settimane trascorse]
* [!UICONTROL Mesi trascorsi]

La pagina **[!UICONTROL I miei aggiornamenti] è vuota**

*Aggiornamenti*

Quando un utente cerca di visualizzare la pagina [!UICONTROL I miei aggiornamenti], la pagina non viene caricata. L’utente può vedere solo l’intestazione di navigazione di [!DNL Workfront].

**L’impostazione “[!UICONTROL Consenti solo autenticazione SAML 2.0]” non è visibile durante la copia di un utente**

*Utenti*

Quando un amministratore gruppo copia un utente e deseleziona l’opzione “[!UICONTROL Invia un’e-mail di invito a questa persona]”, la casella di controllo “[!UICONTROL Consenti solo autenticazione SAML 2.0]” non viene visualizzata come previsto. Ciò può verificarsi anche quando tutti i requisiti di accesso e autorizzazione per questa azione sono soddisfatti.

+++

+++**Aggiornamento di manutenzione del 14 luglio 2022**

Questi problemi sono stati risolti solo nella nuova esperienza [!DNL Workfront].

Tutte le funzionalità [!DNL Workfront Classic] sono state rimosse il 14 luglio 2022.

**Errore durante il ripristino della password**

*Accedi*

Quando un utente cerca di reimpostare la propria password, non può reimpostarla e compare un messaggio che informa che non può accedere. L’utente non ha accesso a Workfront.

**Impossibile richiedere accesso aggiuntivo a un report**

*Report*

Quando un utente con accesso limitato a un report tenta di richiedere un accesso aggiuntivo a un report, l’opzione per richiedere l’accesso aggiuntivo non è disponibile nel menu [!UICONTROL Azioni report].

**Messaggio di conferma durante l’eliminazione di una bozza di richiesta aggiornato**

*Richieste*

Quando si scarta una bozza di richiesta, il messaggio di conferma visualizzato dopo aver fatto clic su “[!UICONTROL Elimina bozza]” è il seguente:

* [!UICONTROL La bozza è stata rimossa] (una notifica per comunicare che la bozza è stata scartata)
* [!UICONTROL Annulla] (collegamento su cui si può fare clic per annullare l’eliminazione della bozza. La bozza verrà conservata invece di essere eliminata.)

Prima di questa modifica, le opzioni erano:

* [!UICONTROL La bozza verrà eliminata]
* [!UICONTROL Annulla]

**I valori della data per i campi della Voce diario non sono corretti quando si accede tramite l’API**

*Aggiornamenti*

Quando un utente modifica un valore di data su un oggetto e poi accede alla Voce diario che rappresenta tale modifica attraverso l’API, i valori della data per [!UICONTROL oldDateVal] e [!UICONTROL newDateVal] restituiti dall’API sono errati.

**Errore durante il tentativo di annullare il commento**

*Aggiornamenti*

Quando un utente cerca di annullare un commento, questo non viene annullato e l’utente visualizza il seguente errore:

[!UICONTROL Errore 403: Non hai un accesso sufficiente per cancellare questa nota /attask/api-internal/NOTE]

**Nuovo limite al numero di caratteri in un aggiornamento in Anteprima**

*Aggiornamenti*

Per migliorare le prestazioni dell’area [!UICONTROL Aggiornamenti], è stato introdotto un nuovo limite al numero di caratteri che è possibile inserire in un aggiornamento o in una risposta a un aggiornamento esistente. Il nuovo limite è di 15.000 caratteri. Questo aggiornamento non ha modificato il numero di caratteri consentiti quando si utilizza l’API. Per l’API, il limite per gli aggiornamenti è di 4.000 caratteri.

**Errore durante il caricamento di un allegato da [!DNL Workfront] per l’integrazione con Outlook**

*Integrazioni di Workfront*

Quando un utente cerca di caricare un allegato utilizzando l’integrazione di [!DNL Workfront for Outlook]per Outlook, l’allegato non viene caricato e l’utente visualizza il seguente messaggio:

[!UICONTROL Alcuni allegati non sono stati caricati. Motivo: si è verificato un errore nel caricamento degli allegati.]

**Aggiornamento delle notifiche e-mail delle bozze**

*[!DNL Workfront]Bozza*

All’inizio di questo mese, nell’ambito di una patch dell’ambiente di produzione di [!DNL Workfront], sono stati corretti alcuni bug del sistema di notifica e-mail delle bozze. Questa modifica non è stata comunicata nell’aggiornamento di manutenzione al momento del rilascio. Abbiamo aggiunto le seguenti informazioni all’[aggiornamento di manutenzione del 2 giugno 2022](#maintenance-update-on-june-2-2022) :

In seguito alla correzione di questi bug, l’indirizzo e-mail utilizzato per inviare le notifiche delle bozze è cambiato.

In precedenza, gli indirizzi e-mail per le bozze contenevano il sottodominio della tua organizzazione. Ad esempio, notifications@[dominio dell’azienda].my.workfront.com

Adesso, gli indirizzi e-mail per le bozze non contengono più il sottodominio delle organizzazioni, e tutte le notifiche e-mail delle bozze verranno inviate dal seguente indirizzo: notification@my.workfront.com

Per questo, se non lo hai già fatto, ti consigliamo di effettuare le seguenti operazioni:

* Aggiorna i filtri anti-spam per accettare le e-mail da notification@my.workfront.com
* Aggiorna il tuo elenco di indirizzi consentiti per accettare le e-mail da notification@my.workfront.com

**Non è possibile modificare le opzioni utente al termine della configurazione iniziale in Modelli del flusso di lavoro**

*[!DNL Workfront Proof]*

Quando un utente aggiunge un altro utente a un Modello del flusso di lavoro, può configurare diverse opzioni. Al termine della configurazione iniziale, tuttavia, l’utente non può più modificare gli elementi seguenti:

* Funzionalità “[!UICONTROL Risolvi commenti e applica azioni]”
* Funzionalità [!UICONTROL “Condividi bozza mediante tag]”
* Ruolo della bozza ([!UICONTROL Revisore], [!UICONTROL Approvatore], ecc.)

**Il filtro “[!UICONTROL Elementi di lavoro di questo progetto]” è stato ripristinato nel progetto [!UICONTROL Bilanciatore dei carichi di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

È stato ripristinato il filtro “Elementi di lavoro di questo progetto” nell’area [!UICONTROL Assegnato] quando si accede al [!UICONTROL Bilanciatore dei carichi di lavoro] da un progetto.

Questo filtro è ora elencato nella sezione “[!UICONTROL Consigliato]” dei filtri per l’area [!UICONTROL Lavoro assegnato] del [!UICONTROL Bilanciatore dei carichi di lavoro] di un progetto.

+++

## Aggiornamenti di giugno 2022

+++**Aggiornamento di manutenzione del 30 giugno 2022**

**Visualizzare il [!UICONTROL Bilanciatore dei carichi di lavoro] per una settimana**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Sulla base del feedback ricevuto da molti clienti, è stata aggiunta un’opzione per visualizzare il [!UICONTROL Bilanciatore dei carichi di lavoro per una settimana] per una settimana. Prima di questo aggiornamento, era possibile visualizzare il [!UICONTROL Bilanciatore dei carichi di lavoro] per 4, 6 e 12 settimane. Con questo aggiornamento abbiamo anche modificato l’opzione 12 settimane in 3 mesi.

**Il pannello Delega è ora disponibile dal Bilanciatore dei carichi di lavoro**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

NOTA: questo aggiornamento esiste solo nell’ambiente di anteprima. Le funzionalità associate a questo aggiornamento saranno disponibili in produzione con la versione 22.3.

Ora è possibile visualizzare i delegati di un’attività o di un problema dal bilanciatore dei carichi di lavoro. Quando si assegna un’attività o un problema dal bilanciatore dei carichi di lavoro, è possibile visualizzare un elenco di assegnazioni e un elenco di delegati per l’attività o il problema, se sono attualmente delegati.

**Impossibile aprire le informazioni sull’endpoint in API Explorer**

*API*

Quando un utente visualizza [!DNL API Explorer] e fa clic su un endpoint, le informazioni sull’endpoint non vengono visualizzate.

**Problemi con il pulsante [!UICONTROL Dettagli] quando si utilizza l’[!UICONTROL Calendario predefinito]**

*Pagina principale*

Quando un utente usa l’[!UICONTROL Home Calendar] e fa clic su un’attività, può verificarsi una delle seguenti situazioni:

* Il pulsante [!UICONTROL Dettagli] viene visualizzato brevemente e poi scompare. L’utente non può accedere ai dettagli.
* Il pulsante [!UICONTROL Dettagli] non viene visualizzato. L’utente non può accedere ai dettagli.
* Il pulsante [!UICONTROL Dettagli] viene visualizzato ma non si trova nella posizione corretta. L’utente può fare clic sul pulsante per accedere ai dettagli.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 24 giugno 2022**

**La selezione della data non si chiude quando si modifica un modulo personalizzato**

*Moduli personalizzati*

Quando un utente modifica un modulo personalizzato e tenta di modificare una data, la selezione della data non si chiude quando viene selezionata la data. L’utente non può chiudere la selezione della data salvando, annullando o facendo clic in un altro punto lontano dalla selezione.

Ciò è stato segnalato nelle seguenti aree:

* Area [!UICONTROL Aggiornamenti]
* [!UICONTROL Pagina principale]

**L’utente non può passare autonomamente a un’altra fase della bozza**

*Bozze*

Quando un utente visualizza il [!UICONTROL Flusso di lavoro bozze] di una bozza e tenta di spostarsi in un’altra fase della bozza, il nome dell’utente torna alla fase originale e non viene aggiunto alla fase desiderata.

+++

+++**Aggiornamento di manutenzione del 23 giugno 2022**

**[!UICONTROL Impossibile aggiungere una nuova richiesta tramite il dashboard]**

*Dashboard*

Quando un utente visualizza un dashboard in un progetto e tenta di aggiungere una nuova richiesta facendo clic sul pulsante [!UICONTROL +Nuova richiesta], il pulsante non risponde e l’utente non può aggiungere una nuova richiesta.

**Errore durante la visualizzazione degli elementi nell’elenco di lavoro della Home**

*[!UICONTROL Pagina principale]*

Quando un utente visualizza la sezione [!UICONTROL Elenco lavori] dell’area Home e fa clic su un elemento nella sezione [!UICONTROL Approvazioni inviate], la pagina mostra il seguente errore:

”[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

Se l’utente aggiorna la pagina e poi fa clic su qualsiasi elemento nella [!UICONTROL Elenco lavori], viene visualizzato l’errore. Il problema non riguarda più solo gli elementi nella sezione [!UICONTROL Approvazioni inviate].

**La sezione personalizzata di un oggetto include risultati non presenti in tale oggetto**

*Oggetti*

Quando un utente visualizza una sezione [!UICONTROL personalizzata] su un oggetto, la sezione personalizzata mostra elementi che non fanno parte di tale oggetto. Questo problema è stato segnalato quando la sezione personalizzata viene aggiunta direttamente all’oggetto e quando una sezione personalizzata viene aggiunta tramite un modello di layout.

**Le attività vengono spostate in un progetto non corretto**

*Attività*

Quando un utente sposta le attività dal Progetto A al Progetto B e poi sposta più attività dal Progetto A al Progetto C, le attività originariamente spostate al Progetto B vengono visualizzate nel Progetto C.

**Alcuni pulsanti/icone non funzionano quando si accede al [!UICONTROL Bilanciatore dei carichi di lavoro] da un collegamento o da un dashboard condivisi**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente accede al [!UICONTROL Bilanciatore dei carichi di lavoro] tramite un collegamento condiviso o un collegamento in un dashboard e tenta di utilizzare l’elemento nella parte superiore dello schermo, gli elementi non funzionano. Ciò è stato segnalato per i seguenti elementi:

* [!UICONTROL Oggi]
* Frecce Indietro e Avanti
* [!UICONTROL Settimane]
* Icona Calendario (selezione della data)

+++

+++**[!DNL Workfront], Pianificazione scenario - Aggiornamento di manutenzione del 23 giugno 2022**

**Gli utenti con i permessi [!UICONTROL Gestione] di un piano possono condividerlo con altri utenti**

In quanto utente con permessi [!UICONTROL Gestisci] di un piano in [!DNL Scenario Planner], adesso puoi condividerlo con altri utenti. Prima di questo aggiornamento, solo il creatore del piano poteva condividerlo con altri utenti.

+++

+++**Aggiornamento di manutenzione del 16 giugno 2022**

**L’amministratore del gruppo non può aggiungere membri al gruppo**

*Gruppi*

Quando l’amministratore di un gruppo tenta di aggiungere un utente a un gruppo, il menu a discesa per selezionare l’utente non compare. L’amministratore del gruppo non può selezionare alcun utente e pertanto non può aggiungere alcun utente al gruppo.

**I trimestri personalizzati non vengono visualizzati quando si imposta un filtro**

*Filtri*

Quando un utente crea un filtro e filtra in base a un campo data, il menu a discesa degli operatori disponibili per il campo data non include i trimestri personalizzati aggiunti di recente.

**Errore quando si converte un problema in un progetto tramite un modello**

*Progetti*

Quando un utente cerca di convertire un problema in un progetto tramite un modello e il problema ha un modulo personalizzato che contiene una sezione solo per amministratori, il problema non viene convertito e l’utente visualizza il seguente errore:

”[!UICONTROL Riproviamo. Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

**Le richieste vengono inviate senza i campi obbligatori compilati**

*Richieste*

Quando un utente crea una richiesta e la invia senza compilare i campi obbligatori, la richiesta viene inviata senza dati nei campi obbligatori. Sarebbe previsto che la richiesta non venisse inviata e che all’utente venisse notificato che deve compilare i campi obbligatori prima di inviare la richiesta.

**Il salvataggio dei nuovi trimestri personalizzati non viene mostrato**

*Configura*

Quando un utente aggiunge un nuovo trimestre personalizzato dall’area Progetti di Configura e fa clic su [!UICONTROL Salva], non vi è alcuna indicazione visiva del salvataggio. L’utente non visualizza un messaggio di successo e il pulsante [!UICONTROL Salva] resta presente e attivo. Tuttavia, se l’utente aggiorna la pagina, può vedere che i nuovi trimestri compaiono nell’elenco dei trimestri personalizzati.

Se l’utente aggiunge un nuovo trimestre, fa clic su [!UICONTROL Salva], non riceve alcuna indicazione del salvataggio, aggiunge un altro trimestre senza aggiornare la pagina e fa di nuovo clic su [!UICONTROL Salva], il secondo trimestre aggiunto potrebbe non essere salvato.

La pagina **[!UICONTROL Richieste di lavoro del team] è vuota**

*Team*

NOTA: questo problema esiste solo nell’ambiente di anteprima.

Quando un utente cerca di aprire l’area [!UICONTROL Richieste di lavoro] in una pagina del team, la pagina è vuota. L’utente può visualizzare la barra di navigazione superiore, ma non il contenuto della pagina.

+++

+++**Aggiornamento di manutenzione del 9 giugno 2022**

**Impossibile selezionare gli oggetti da filtrare nelle preferenze dell’[!UICONTROL Ottimizzatore portfolio]**

*Portfolio*

Quando un utente si trova nell’[!UICONTROL Ottimizzatore portfolio] e visualizza la scheda [!UICONTROL Filtri progetto] nell’area [!UICONTROL Preferenze], le caselle di controllo accanto agli oggetti sono assenti. L’utente non può selezionare o deselezionare le caselle di controllo e quindi non può selezionare oggetti da filtrare.

**Impossibile modificare la [!UICONTROL Data inizio pianificata] o la [!UICONTROL Data completamento pianificata] quando “[!UICONTROL Pianifica da]” non è selezionato**

*Progetti*

Quando un utente cerca di modificare la [!UICONTROL Data inizio pianificata] o [!UICONTROL Data completamento pianificata] di un progetto e l’opzione “[!UICONTROL Pianifica da]” per quel progetto non è selezionata, la [!UICONTROL Data inizio pianificata] e la [!UICONTROL Data completamento pianificata] sono disattivate e l’utente non può modificarle.

**Impossibile modificare il livello di accesso degli utenti**

*Utenti*

Quando un utente con un accesso a Planner che include l’accesso Amministratore utenti (Utenti gruppo) tenta di modificare gli utenti del gruppo di cui è amministratore, il campo Livello di [!UICONTROL Accesso] è disabilitato e l’utente non può modificare il livello di accesso.

+++

+++**[!DNL Workfront Scenario Planner]- Aggiornamento di manutenzione del 9 giugno 2022**

**Pannello sinistro ridimensionabile in [!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Ora in [!DNL Scenario Planner] è possibile ridimensionare il pannello sinistro di un piano. Ciò consente di visualizzare completamente i nomi delle iniziative più lunghi. Prima di questo aggiornamento, i nomi delle iniziative più lunghi venivano troncati.

+++

+++**[!DNL Workfront Fusion]- Aggiornamento di manutenzione del 9 giugno 2022**

**I dati dei moduli personalizzati non sono disponibili nei moduli [!DNL Workfront] di [!DNL Workfront Fusion]**

*[!DNL Workfront Fusion]*

Quando un utente configura un modulo [!DNL Workfront] in [!DNL Workfront Fusion]e tenta di selezionare i relativi output, i campi dei moduli personalizzati non sono visibili. Ciò si verifica quando il modulo personalizzato è stato creato per un tipo di oggetto [!DNL Workfront] e successivamente ne è stato aggiunto un altro tipo. [!DNL Workfront Fusion] visualizza solo i campi dei moduli personalizzati originariamente creati per il tipo di oggetto selezionato.

**Impossibile scorrere per visualizzare tutte le esecuzioni dello scenario**

*[!DNL Workfront Fusion]*

Quando un utente visualizza la cronologia dell’esecuzione di uno scenario e tenta di scorrere verso il basso per visualizzare più esecuzioni, il caricamento della pagina si interrompe, rendendo impossibile l’operazione. Inoltre, l’utente non è in grado di tornare alle esecuzioni più recenti.

+++

+++**Aggiornamento di manutenzione del 2 giugno 2022**

**[!UICONTROL Ottimizzatore portfolio] mostra un punteggio pari a 0 quando si utilizza una lingua diversa dall’inglese**

*Portfolio*

Quando un utente utilizza [!DNL Workfront] in una lingua diversa dall’inglese e visualizza l’[!UICONTROL Ottimizzatore portfolio], il punteggio mostrato è 0. Ciò può verificarsi anche quando il caso di business non è completo.

**Valori dei campi calcolati non corretti durante la creazione di un progetto da un modello**

*Progetti*

Quando un utente crea un progetto da un modello che include campi calcolati, i valori dei campi visualizzati nel nuovo progetto non sono corretti.

**Impossibile modificare le [!UICONTROL Condizioni] nell’area [!UICONTROL Preferenze progetto] di [!UICONTROL Configura]**

*[!UICONTROL Configura]*

Quando un utente cerca di modificare le [!UICONTROL Condizioni] nell’area [!UICONTROL Preferenze progetto] di [!UICONTROL Configura], la pagina è vuota.

**Nuovo limite al numero di caratteri in un aggiornamento in Anteprima**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

>[!NOTE]
>
>Questo aggiornamento si applica solo all’ambiente di anteprima.

Per migliorare le prestazioni dell’area Aggiornamenti, è stato introdotto un nuovo limite al numero di caratteri che è possibile inserire in un aggiornamento o in una risposta a un aggiornamento esistente. Il nuovo limite è di 15.000 caratteri. Questo aggiornamento non ha modificato il numero di caratteri consentiti quando si utilizza l’API. Per l’API, il limite per gli aggiornamenti è di 4.000 caratteri. Aggiornamenti
Supporto per i campi personalizzati di tipo Typehead nei filtri del Bilanciatore dei carichi di lavoro

I filtri basati sui campi personalizzati di tipo [!UICONTROL Typeahead] sono ora supportati nel bilanciatore dei carichi di lavoro. Prima di questa patch, il filtro per questo tipo di campi personalizzati nel bilanciatore dei carichi di lavoro non era possibile.

**Impossibile modificare le autorizzazioni per il ruolo di un utente**

*[!DNL Workfront Proof]*

Quando un utente cerca di modificare le autorizzazioni “[!UICONTROL Risolvi i commenti e applica le azioni]” o “[!UICONTROL Condividi bozza con tag]” sul ruolo di un utente in [!DNL Workfront Proof], le modifiche non vengono salvate. L’utente riceve una notifica che indica che il modello è stato aggiornato, ma se apre nuovamente le autorizzazioni del ruolo può vedere che le modifiche non sono state salvate.

+++


## Aggiornamenti di maggio 2022

+++**Aggiornamento di manutenzione del 26 maggio 2022**

Questi problemi sono stati risolti solo nella nuova esperienza [!DNL Workfront]. [!DNL Adobe Workfront Classic] non è più supportato.

Tutte le funzionalità di [!DNL Workfront Classic] verranno rimosse a luglio 2022. Passa alla nuova esperienza il prima possibile.

**Separatori delle breadcrumb aggiornati**

*[!DNL Workfront]*

NOTA: questo aggiornamento è stato rilasciato il 24 maggio 2022.

Sono stati aggiornati i separatori delle breadcrumb in tutte le aree in cui sono disponibili le breadcrumb. Ora, gli oggetti nelle breadcrumb sono separati da barre verticali (|). Prima di questo aggiornamento, erano separati da barre (/).

**Impossibile modificare i moduli personalizzati con interruzioni di sezione**

*Moduli personalizzati*

Quando un utente cerca di modificare un modulo personalizzato con un’interruzione di sezione, non può modificare il modulo e visualizza il seguente messaggio:

[!UICONTROL La sicurezza specificata per l’interruzione di sezione non può essere applicata a tutti i tipi di oggetto]

**Problemi durante la stampa dei dashboard in PDF**

*Dashboard*

Sono stati segnalati i seguenti problemi durante la stampa di un dashboard in PDF: il PDF non stampa tutte le righe del report. Se mancano le righe, viene visualizzato solo uno spazio vuoto.
Il PDF include spazi vuoti tra le intestazioni di colonna e la prima riga del report.

**[!DNL Portfolio Optimizer] mostra un punteggio pari a 0 quando si utilizza una lingua diversa dall’inglese**

*Portfolio*

Quando un utente utilizza [!DNL Workfront] in una lingua diversa dall’inglese e visualizza l’[!UICONTROL Ottimizzatore portfolio], il punteggio mostrato è 0. Ciò può verificarsi anche quando il caso di business non è completo.

**Alcuni moduli personalizzati non vengono visualizzati durante la modifica di un modello**

*Modelli*

Quando un utente cerca di modificare i moduli personalizzati su un modello facendo clic su [!UICONTROL Modifica] nell’intestazione del modello, la finestra [!UICONTROL Modifica modello] mostra solo uno dei moduli personalizzati collegati al modello.

**Il collegamento condiviso al Bilanciatore dei carichi di lavoro non mostra correttamente il lavoro assegnato**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente visualizza il [!UICONTROL Bilanciamento del carico di lavoro] utilizzando un collegamento condiviso, il [!DNL Workload Balancer] include il [!UICONTROL Lavoro assegnato] nella sezione [!UICONTROL Lavoro non assegnato]. Il [!UICONTROL Lavoro assegnato] non dispone di una sezione separata. Quando l’utente visualizza il [!UICONTROL Bilanciatore dei carichi di lavoro] senza utilizzare il collegamento condiviso, il [!UICONTROL Lavoro assegnato] viene visualizzato come previsto.

+++

+++**Aggiornamento di manutenzione del 19 maggio 2022**

**Impossibile creare una bozza da un [!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Quando un utente cerca di creare una bozza da un [!DNL PowerPoint] che include un grafico, la creazione della bozza non riesce.

**Impossibile creare una bozza da un documento [!UICONTROL Word]**

*[!DNL Workfront Proof]*

Quando un utente cerca di creare una bozza da un documento [!DNL Word] che include un grafico, la creazione della bozza non riesce.

**Impossibile aggiungere un messaggio personalizzato durante la condivisione di una bozza**

*[!DNL Workfront Proof]*

Quando, visualizzando una bozza, un utente apre l’area [!UICONTROL Condividi bozza] e seleziona il pulsante [!UICONTROL Aggiungi messaggio personalizzato], non può digitare nella casella di testo che si apre. Quando l’utente cerca di digitare nella casella, questa scompare immediatamente.

**Impossibile chiudere le bozze**

*[!DNL Workfront Proof]*

Quando un utente visualizza una bozza e tenta di chiuderla, nell’angolo in alto a destra della bozza manca la X per chiuderla.

**Impossibile aggiungere o rimuovere l’amministratore del gruppo**

*Gruppi*

Se un utente visualizza la pagina di un [!UICONTROL Gruppo] e tenta di aggiungere o rimuovere un amministratore utilizzando l’area [!UICONTROL Amministratori di gruppi] nell’intestazione, le modifiche non vengono salvate e l’utente visualizza il seguente errore:

[!UICONTROL Errore Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]

**La barra di scorrimento orizzontale blocca l’elemento alla fine dell’elenco**

*Progetti*

Quando un utente visualizza un elenco utilizzando una vista che si estende oltre il lato dello schermo, la barra di scorrimento orizzontale blocca la visualizzazione dell’ultimo elemento dell’elenco da parte dell’utente.

**“[!UICONTROL Errore inatteso]” quando si converte un problema in un progetto utilizzando un modello**

*Elenchi*

Quando un utente cerca di convertire un problema in un progetto utilizzando un modello, il problema non viene convertito e l’utente visualizza il seguente messaggio:

[!UICONTROL Si è verificato un errore inatteso]

**Adesso il campo [!UICONTROL Stato] in una vista Scheda orario è di sola lettura**

*Schede orario*

Il campo [!UICONTROL Stato] in una vista Scheda orario è stato cambiato in modo da essere di sola lettura. Prima di questa modifica, gli utenti potevano modificare in linea lo stato di una scheda orario e potevano così ignorare la decisione degli approvatori della scheda orario.

+++

+++**Aggiornamento di manutenzione del 12 maggio 2022**

Il pulsante **[!UICONTROL Salva] non smette di caricare quando durante la modifica di un progetto**

*Progetti*

Quando un utente modifica un progetto e tenta di salvarlo, il pulsante [!UICONTROL Salva] mostra la parola “[!UICONTROL Caricamento]”. Se l’utente fa clic su questo pulsante per salvare le modifiche apportate al progetto, il pulsante non risponde e le modifiche non vengono salvate.

**Le etichette dei campi non sono visibili durante la visualizzazione di un oggetto nella [!UICONTROL Home]**

*Pagina principale*

Quando un utente seleziona un oggetto dalla sezione [!UICONTROL Elenco lavori] dell’area Home, l’area a destra di [!UICONTROL Elenco lavori] mostra l’oggetto senza le etichette dei campi. I valori dei campi sono presenti.

**Il filtro rapido non si attiva automaticamente sulla barra di ricerca**

*Elenchi*

Quando un utente fa clic sulla lente di ingrandimento in un elenco per filtrare rapidamente e poi inizia a digitare, il testo non viene visualizzato. Questo perché l’elemento attivo è ancora l’icona della lente d’ingrandimento e non la barra di ricerca.

Facendo clic sulla barra di ricerca, questa diventa l’elemento attivo e l’utente può immettere il testo della ricerca.

**Gli utenti non possono modificare i campi in linea in un report**

*Report*

Quando un utente cerca di modificare un campo in un report e tale campo viene estratto da un modulo personalizzato, l’utente non è in grado di modificare il campo. Ciò si verifica quando il modulo personalizzato è stato creato originariamente per un tipo di oggetto diverso dall’oggetto a cui è associato.

**Testo di etichetta e pulsante non visibile durante la creazione di una bozza**

*[!DNL Workfront Proof]*

NOTA: questo problema esiste solo nell’ambiente di anteprima.

Quando un utente cerca di creare una bozza, il testo non è visibile per le opzioni o i pulsanti. Pertanto, l’utente non sa cosa rappresentano le opzioni o i pulsanti e non può configurare la bozza.

+++

+++**Aggiornamento di manutenzione del 5 maggio 2022**

**Impossibile aggiungere un nuovo record della fatturazione**

*Progetti*

Quando un utente cerca di aggiungere un nuovo record della fatturazione dall’area [!UICONTROL Record fatturazione] di un progetto utilizzando la vista [!UICONTROL Nuovo record fatturazione], non vengono visualizzati i campi per un nuovo record della fatturazione e non è possibile crearlo.

**Errore durante l’assegnazione in blocco nel [!UICONTROL Bilanciatore dei carichi di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente cerca di effettuare assegnazioni nel [!DNL Workload Balancer] di un progetto, viene reindirizzato a una pagina con il seguente messaggio:

”[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova a riaggiornare la pagina del browser.]”

L’utente non può spostarsi da questa pagina finché non aggiorna la pagina.

**Navigazione aggiornata per aprire il pannello [!UICONTROL Riepilogo] per le attività e i problemi nel [!UICONTROL Bilanciatore dei carichi di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Adesso è sufficiente fare clic su una barra dei problemi o delle attività nel [!UICONTROL Bilanciatore dei carichi di lavoro] per aprire il pannello Riepilogo. Prima di questo aggiornamento, era necessario fare clic sul pulsante [!UICONTROL Apri riepilogo] nella barra degli strumenti e poi fare clic sull’attività o sul problema. Si trattava di un’esperienza che creava confusione e ora è stata corretta. In alternativa, è possibile fare clic sul pulsante [!UICONTROL Altro] accanto al nome dell’attività o del problema e poi su [!UICONTROL Apri riepilogo].

**L’amministratore del gruppo non può visualizzare i dettagli degli utenti del gruppo**

*Utenti*

Quando un utente assegnato a un livello di accesso che include l’impostazione di accesso [!UICONTROL Amministratore utenti (utenti gruppo)] tenta di visualizzare i dettagli di un utente del proprio gruppo, viene visualizzato il seguente errore:

”[!UICONTROL Riproviamo. Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

**Impossibile eliminare lo stato dei gruppo personalizzati**

*Gruppi*

Quando un utente cerca di eliminare lo stato di un gruppo personalizzato dalla pagina [!UICONTROL Gruppo], la pagina diventa vuota e lo stato non viene eliminato.

**Le impostazioni degli avvisi e-mail non sono coerenti tra l’area Contatti e i Dettagli utente**

*[!DNL Workfront Proof]*

Le impostazioni degli avvisi e-mail visualizzate nell’area [!UICONTROL Contatti] di [!DNL Workfront Proof] per un determinato utente sono diverse dalle impostazioni degli avvisi e-mail impostate in [!UICONTROL Dettagli utente].

**Impossibile utilizzare lo strumento Testo quando si crea un commento su una bozza**

*[!DNL Workfront Proof]*

Quando un utente commenta una bozza e tenta di aprire lo strumento di [!UICONTROL Testo], lo strumento non si apre e l’utente visualizza il seguente messaggio:

“[!UICONTROL È ancora in corso il download dei dati di testo per questa pagina. Resta in attesa.]”

**Le e-mail delle bozze verranno inviate all’e-mail principale dell’utente**

*[!DNL Workfront Proof]*

Stiamo modificando il modo in cui vengono inviate le notifiche e-mail delle bozze. Adesso le notifiche arrivano all’indirizzo e-mail principale dell’utente anziché all’alias generato dal sistema.

Per ulteriori informazioni sul motivo per cui il sistema genera alias di posta elettronica, consulta Sincronizzazione degli utenti tra Adobe [!DNL Workfront] e [!DNL Workfront Proof].

+++

## Aggiornamenti di aprile 2022

+++**Aggiornamento di manutenzione del 28 aprile 2022**

**Impossibile scorrere fino al pulsante [!UICONTROL Salva] durante la modifica di una scheda orario**

*Schede orario*

Quando un utente modifica una scheda orario, non può scorrere la finestra di modifica abbastanza da visualizzare il pulsante [!UICONTROL Salva] e quindi non può modificare la scheda orario.

**La firma elettronica ora controlla il Federation ID**

*Bozze*

Adesso, quando si firma una bozza elettronicamente, il sistema controlla il Federation ID, se l’SSO è configurato in [!DNL Workfront Proof], oltre all’e-mail in [!DNL Workfront].

In precedenza, il sistema controllava solo l’e-mail in Workfront.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 25 aprile 2022**

Il **[!UICONTROL Bilanciatore dei carichi di lavoro] non viene caricato**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente cerca di aprire il [!UICONTROL Bilanciatore dei carichi di lavoro], l’intestazione e la navigazione sinistra vengono caricate, ma il contenuto del Bilanciatore dei carichi di lavoro non viene caricato. Al posto dei dati, l’utente vede dei quadrati grigi lampeggianti. A volte, parte del contenuto viene caricata, ma l’utente continua a vedere quadrati grigi lampeggianti dove sarebbero presenti i dati mancanti.

+++

+++**Aggiornamento di manutenzione del 21 aprile 2022**

**L’aggiunta di un’attività fa saltare la pagina verso il basso**

*Attività*

Quando un utente aggiunge un’attività sotto un’attività esistente in un elenco, la pagina si sposta verso il basso nell’elenco. Anche se la nuova attività si trova nella posizione corretta, l’utente deve scorrere di nuovo verso l’alto per individuarla.

**Gli utenti aggiunti a una bozza non possono accedere all’elemento di lavoro della bozza in [!DNL Workfront]**

*Bozze*

Se un utente viene aggiunto a una fase del flusso di lavoro di una bozza, non viene aggiunto alla condivisione del documento e non ottiene le autorizzazioni per l’elemento di lavoro della bozza in [!DNL Workfront]. Quando l’utente cerca di aprire l’elemento di lavoro a cui è allegata la bozza su [!DNL Workfront], viene visualizzato il seguente messaggio:

“[!UICONTROL Livello di accesso insufficiente per visualizzare questo (oggetto)]”

Si tratta di un problema specifico per le bozze già create e gli utenti che vengono aggiunti a posteriori. L’aggiunta di utenti al flusso di lavoro prima della creazione della bozza funziona come previsto.

**Impossibile inviare l’e-mail di reimpostazione password da [!DNL Workfront]**

*Utenti*

Quando un utente cerca di inviare un messaggio e-mail di reimpostazione della password da un elenco di utenti in [!DNL Workfront], l’opzione per inviare l’e-mail non è disponibile.

**Il pulsante mostra “[!UICONTROL Avvia problema]” anziché “[!UICONTROL Avvia richiesta]”**

*Richieste*

Quando un utente visualizza una richiesta assegnata al proprio team, visualizza un pulsante “[!UICONTROL Avvia problema]” nell’intestazione anziché il pulsante “[!UICONTROL Avvia richiesta]”.

**L’opzione “[!UICONTROL Annulla commento]” rimuove gli utenti taggati**

*Aggiornamenti*

Quando un utente assegna un tag a un altro utente in un commento, lo pubblica e poi seleziona l’opzione “[!UICONTROL Annulla commento]”, il commento viene visualizzato come di consueto in una casella di aggiornamento, ma l’utente taggato non è incluso nella casella [!UICONTROL Utenti taggati].

**Impossibile scorrere quando si utilizza la vista [!UICONTROL Milestone] in un report**

*Report*

Quando un utente visualizza un report e seleziona la vista [!UICONTROL Milestone], la pagina mostra la vista ma non è più possibile scorrere e l’utente non può visualizzare le attività cardine che si troverebbero più in basso nella pagina.

**Valuta errata quando il report viene visualizzato nel dashboard**

*Report*

Quando un utente visualizza un report in un dashboard, la valuta utilizzata nel report non è corretta. Quando l’utente visualizza il report all’esterno del dashboard, la valuta è corretta.

**Il filtro Completati non mostra gli elementi di lavoro completati**&#x200B;

*[!UICONTROL Pagina principale]*

Quando un utente visualizza la sezione [!UICONTROL Elenco lavori] dell’area Home con il filtro [!UICONTROL Completati] selezionato, gli elementi di lavoro completati non vengono visualizzati nell’elenco. Quando si seleziona il filtro [!UICONTROL Tutti], gli elementi completati vengono inclusi nell’elenco, mostrando che gli elementi completati esistono.

**[!DNL Workfront]non si carica**

*[!DNL Workfront]*

Quando un utente cerca di accedere a [!DNL Workfront], la pagina sembra essere bloccata in un ciclo continuo di reindirizzamenti o aggiornamenti e non si carica.

+++

+++**Aggiornamento di manutenzione del 14 aprile 2022**

**Impossibile aggiungere un’attività da un report su una sezione personalizzata di un’attività**

*Attività*

Quando un utente visualizza una sezione personalizzata di un’attività e la sezione contiene un report sull’attività, non può aggiungere un’attività da tale report. Il pulsante [!UICONTROL Aggiungi attività] evidenzia il report, ma non apre una finestra per l’aggiunta di un’attività.

**Pulsante Fine in posizione errata durante la modifica di una vista**

*Viste*

Quando un utente modifica una vista, il pulsante [!UICONTROL Fine] appare più in alto sullo schermo e potrebbe sovrapporsi al testo.

L’utente può modificare la vista come di consueto. La funzionalità non è compromessa.

**Impossibile scorrere quando si utilizza la vista [!UICONTROL Milestone] in un report**

*Report*

Quando un utente visualizza un report e seleziona la vista [!UICONTROL Milestone], la pagina mostra la vista ma non è più possibile scorrere e l’utente non può visualizzare le attività cardine che si troverebbero più in basso nella pagina.

**Schermata vuota durante la visualizzazione degli aggiornamenti**

*Aggiornamenti*

Quando un utente visualizza gli aggiornamenti e scorre la schermata per visualizzare quelli più in basso, la schermata diventa vuota e l’utente non può vedere alcun aggiornamento.

**Errore durante l’assegnazione in blocco dell’utente a un’attività non assegnata al ruolo dell’utente**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente nel [!UICONTROL Bilanciatore dei carichi di lavoro] tenta di assegnare delle attività a un utente la cui mansione non corrisponde a quella assegnata alle attività, l’utente visualizza un messaggio che indica che l’attività verrà assegnata utilizzando la mansione principale dell’utente assegnato. Tuttavia, quando l’utente fa clic su “[!UICONTROL Assegna]”, le attività non vengono assegnate e l’utente visualizza il seguente errore:

”[!UICONTROL Errore. Si è verificato un errore sconosciuto del server.]”

+++

+++**Aggiornamento di manutenzione del 7 aprile 2022**

**Gli utenti aggiunti alle bozze hanno ruoli errati**

*Bozze*

Quando un utente ne aggiunge un altro a una bozza, il ruolo del nuovo utente sulla bozza viene impostato come “[!UICONTROL Sola lettura]” indipendentemente dal suo ruolo effettivo.

**Impossibile inviare l’e-mail di reimpostazione della password all’utente**

*Utenti*

Quando un utente cerca di inviare un’e-mail di reimpostazione della password a un altro utente, l’opzione [!UICONTROL Invia e-mail Password dimenticata] non è disponibile nel menu [!UICONTROL Altro].

**[!UICONTROL Aggiorna tutti] invia aggiornamenti ai profili utente anziché al progetto**

*Aggiornamenti*

Quando un utente seleziona l’opzione [!UICONTROL Aggiorna tutti] nell’area [!UICONTROL Persone] di un progetto e poi inserisce un aggiornamento, l’aggiornamento non viene inviato al progetto, Viene invece pubblicato sui singoli profili di ogni utente del progetto.

**Numero eccessivo di pagine durante la stampa degli aggiornamenti**

*Aggiornamenti*

Quando un utente visualizza un flusso di aggiornamenti che sarebbe più di una pagina stampata e tenta di stampare la pagina, la schermata di stampa mostra che il numero di pagine è molto superiore al numero effettivo di pagine necessarie per stampare gli aggiornamenti. Se l’utente cerca di stampare in PDF, la creazione del PDF non riesce.

**Gli utenti non possono visualizzare l’intero elenco di entità condivise con un report quando è attiva l’impostazione “[!UICONTROL Visibile a livello di sistema]”**

*Report*

Quando si condividono report con più entità visualizzate nel riquadro [!UICONTROL Accesso ai report], gli utenti non sono in grado di scorrere fino alla fine per vedere l’intero elenco quando l’impostazione “[!UICONTROL Visibile a livello di sistema]“ è abilitata.

**Valuta errata nei report**

*Report*

Se un utente imposta la valuta di un progetto in modo che sia diversa da quella predefinita e poi visualizza un report sul progetto, viene visualizzata la valuta predefinita al posto della valuta del progetto.

**Le informazioni relative all’ultima visualizzazione non vengono aggiornate in [!UICONTROL Utilizzo report]**

*Report*

Quando un utente visualizza un report che mostra informazioni relative all’ultima visualizzazione del report, tali informazioni potrebbero essere vuote o riportare dati obsoleti. Questo problema riguarda diversi campi, tra cui:

* [!UICONTROL Ultima visualizzazione di]
* [!UICONTROL Ultimi dati visualizzati]
* [!UICONTROL Ultimi X visualizzatori]
* [!UICONTROL Visualizzazioni questo mese / trimestre / anno]

**Attività completate visualizzate nella sezione [!UICONTROL Elenco lavori]** dell’area Home

*[!UICONTROL Pagina principale]*

Quando un utente visualizza la sezione [!UICONTROL Elenco lavori] dell’area Home, vede le attività completate nell’elenco anche se l’opzione per visualizzare le attività completate non è selezionata.

**Il pulsante Pianifica non è visibile per la pianificazione dell’aggiornamento della sandbox**

*Ambiente sandbox*

Il pulsante [!UICONTROL Pianifica] utilizzato per pianificare l’aggiornamento di una sandbox non è visibile nel banner superiore dell’ambiente sandbox.

**Le modifiche a un campo calcolato hanno effetto su tutti i campi calcolati di un modulo**

*Moduli personalizzati*

Quando un utente si trova nel sistema di creazione di moduli personalizzati e modifica il valore di un modulo calcolato, tutti i campi calcolati del modulo visualizzano il nuovo valore. Questo può influenzare i campi calcolati nuovi o esistenti.

**Sfarfallio dei colori nel sistema di creazione di moduli personalizzati**

*Moduli personalizzati*

Quando un utente lavora con campi calcolati nel sistema di creazione di moduli personalizzati, i colori dei campi e delle espressioni presentano uno sfarfallio.

**[!UICONTROL Impossibile rifiutare un’approvazione]**

*Approvazioni*

Quando un utente cerca di rifiutare un’approvazione, il pulsante [!UICONTROL Rifiuta] non risponde e l’approvazione non viene rifiutata.

La scheda **[!UICONTROL Progetti] viene impostata come predefinita nella sezione Tutti i progetti nonostante la selezione precedente**

*Progetti*

Quando un utente accede a una pagina Progetti tramite una scheda che è stata bloccata come parte del modello di layout, la pagina si sposta di default nell’area [!UICONTROL Tutti i progetti] della navigazione sinistra. Ciò si verifica anche quando l’utente sceglie un’altra area della navigazione sinistra e poi si sposta dalla pagina Progetti e torna indietro.

+++


## Aggiornamenti di marzo 2022

+++**Aggiornamento di manutenzione del 31 marzo 2022**

**Fusi orari non coerenti tra [!DNL Workfront] e [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando il profilo di un utente è impostato su un fuso orario specifico in [!DNL Workfront], il fuso orario dell’utente in [!DNL Workfront Proof] è diverso.

**Il collegamento per l’invio di un documento richiesto porta a una pagina vuota**

*Documenti*

Quando un utente riceve una richiesta di invio di un documento e fa clic sul collegamento all’oggetto in cui è stato richiesto il documento, il collegamento conduce a una pagina vuota. Ciò può verificarsi quando si fa clic su un collegamento all’interno di un’e-mail o una notifica in-app.

**Il gruppo viene assegnato in modo errato durante la conversione del problema in progetto**

Gruppi

Quando un utente converte un problema in un progetto utilizzando un modello, la funzionalità è la seguente:

* Se al modello è assegnato un gruppo, tale gruppo viene visualizzato nella finestra di conversione del problema come gruppo per il nuovo progetto.
* Se al modello non è assegnato alcun gruppo, come gruppo per il nuovo progetto nella finestra di conversione del problema viene visualizzato il gruppo predefinito dell’utente che sta convertendo il problema.
* Se il modello non ha un gruppo, il nuovo progetto deve ereditare il gruppo dal progetto del problema.

**Impossibile associare il modulo personalizzato con più oggetti alla coda di richiesta**

Richieste

Quando un utente cerca di aggiungere un modulo personalizzato con più oggetti alla pagina dei dettagli di una coda, il modulo non viene visualizzato nell’elenco a discesa dei moduli disponibili e l’utente non può selezionarlo per aggiungerlo ai dettagli della coda.

**Gli utenti non possono essere assegnati con una mansione secondaria sul [!UICONTROL Bilanciatore dei carichi di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente cerca di assegnare un altro utente a un’attività nel [!UICONTROL Bilanciatore dei carichi di lavoro] assegnata a una mansione diversa dalla mansione principale dell’utente, l’utente viene assegnato all’attività in base alla sua mansione principale e viene visualizzato il seguente messaggio:

“&lt;Name> non corrisponde al ruolo di &lt;Task role assignment>. 1 elemento di lavoro attualmente assegnato al ruolo di &lt;Task role assignment> sarà assegnato a &lt;Name> nel ruolo di &lt;Primary job role>.”

Ciò si verifica anche se il ruolo dell’assegnazione della mansione è secondario per l’utente.

**Problema con la barra “Mostra più elementi di lavoro” sulla bacheca Scrum**

*Agile*

Quando un utente fa clic sulla barra [!UICONTROL Mostra altri elementi di lavoro] su una bacheca Scrum e poi scorre per vedere i nuovi elementi, la barra [!UICONTROL Mostra altri elementi di lavoro] si fissa alla bacheca Scrum e si sposta con essa durante lo scorrimento. Questo può rendere le schede difficili da leggere.

**Sui campi obbligatori nei moduli personalizzati compaiono dei punti rossi**

Moduli personalizzati

Quando un utente visualizza un campo obbligatorio in un modulo personalizzato, sotto l’asterisco vengono visualizzati due punti rossi che indicano che il campo è obbligatorio.

**Menu a discesa dell’ora tagliato nei prompt**

*Report*

Quando un utente compila le richieste di un report e incontra un selettore di date, il selettore dell’ora nella parte inferiore del selettore di date non mostra le ore oltre le 2 e l’utente non può selezionare valori orari oltre a 1 o 2.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 29 marzo 2022**

**Impossibile modificare o salvare i calcoli nel sistema di creazione dei moduli personalizzati**

*Moduli personalizzati nel mio gruppo*

Se un utente immette manualmente un calcolo in un campo di calcolo nel sistema di creazione dei moduli personalizzati e salva il modulo, il calcolo non viene salvato. Se l’utente riapre il modulo personalizzato, tale campo è vuoto.

Se un utente immette un calcolo in un campo di calcolo nel sistema di creazione dei moduli personalizzati utilizzando i menu a discesa e salva il modulo, tale valore viene salvato. Tuttavia, se l’utente riapre il modulo personalizzato, non può modificare questo campo o rimuovere il valore, né manualmente né con il menu a discesa.

NOTA: questo problema è stato risolto includendo funzionalità aggiuntive. Ora, quando si inizia a digitare in un campo calcolato, le espressioni o i calcoli possibili vengono visualizzati in un elenco a discesa sottostante, come nell’Editor di calcolo. Fai clic su un elemento nel menu a discesa per aggiungerlo al campo calcolato.

+++

+++**Aggiornamento di manutenzione del 24 marzo 2022**

**Fusi orari non coerenti tra [!DNL Workfront] e [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando il profilo di un utente è impostato su un fuso orario specifico in [!DNL Workfront], il fuso orario dell’utente in [!DNL Workfront Proof] è diverso.

**Errore del campo richiesto per i campi personalizzati compilati quando si allega il modello**

*Progetti*

Quando si allega un modello con campi personalizzati obbligatori a un progetto in cui il campo esiste già ed è compilato, gli utenti visualizzano il seguente errore: “[!UICONTROL Sono presenti campi incompleti. Inserire i valori dei campi obbligatori per continuare.]”
Fare clic su “[!UICONTROL Reindirizza]” consente di vedere che i campi sono compilati ed è possibile allegare il modello.

**Il [!UICONTROL Bilanciatore dei carichi di lavoro] lampeggia quando si passa da una data all’altra**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Le ore dell’utente elencato per primo nel [!UICONTROL Bilanciatore dei carichi di lavoro] non vengono visualizzate quando si aggiorna la timeline. L’utente e le sue ore vengono visualizzati con caselle grigie che lampeggiano. Questo accade se ci si sposta avanti e indietro sulla timeline.

L’aggiornamento del filtro sembra reimpostare la visualizzazione, ma se ci si sposta avanti e indietro sulla timeline, il display lampeggia nuovamente e le ore dell’utente non vengono visualizzate.

**La terminologia personalizzata non è coerente**

*Modelli di layout*

Gli utenti segnalano che quando l’amministratore di [!DNL Workfront] personalizza la terminologia di alcuni oggetti utilizzando un modello di layout, il nuovo nome dell’oggetto viene visualizzato in modo incoerente nell’interfaccia.

Ad esempio, nella pagina “[!UICONTROL Progetti]” è ancora possibile vedere il titolo della pagina visualizzato come “[!UICONTROL Progetti]” anche se l’amministratore di [!DNL Workfront] ha cambiato il nome di “[!UICONTROL Progetti]”.

Ciò crea confusione per gli utenti finali.

+++

+++**Aggiornamento di manutenzione del 17 marzo 2022**

**Le miniature e le immagini principali sono vuote quando si visualizzano file multipagina con il browser [!DNL Safari]**

*[!DNL Workfront Proof]*

Quando un utente cerca di visualizzare un file con più pagine nel browser [!DNL Safari], le immagini delle miniature delle pagine sono vuote. A volte, anche l’immagine principale può essere vuota.

**Elenco utenti errato quando si effettuano assegnazioni in blocco nel [!UICONTROL Bilanciatore dei carichi di lavoro]**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Quando un utente effettua un’assegnazione in blocco nel [!UICONTROL Bilanciatore dei carichi di lavoro] e seleziona un Progetto e una Mansione, l’elenco degli utenti disponibili non è corretto. Potrebbero essere mostrati gli utenti senza le autorizzazioni per il Ruolo o la Mansione, mentre gli utenti con le autorizzazioni per Mansione e Progetto non vengono visualizzati nell’elenco.

**[!UICONTROL Non è possibile ordinare i report]**

*Report*

Quando un utente fa clic su una colonna per ordinare il report in base a essa, sembra funzionare. Tuttavia, i risultati vengono immediatamente ripristinati nell’ordine originale visualizzato prima di fare clic sulla colonna. L’ordine in base a una colonna non viene mantenuto.

**Selezionando “[!UICONTROL Niente]” si ritorna al raggruppamento del [!UICONTROL Report predefinito]**

*Report*

Quando un report ha un raggruppamento integrato e l’utente cerca di selezionare “[!UICONTROL Niente]” nel menu a discesa [!UICONTROL Raggruppamento], il report viene visualizzato per poco tempo senza raggruppamenti, ma poi viene ripristinato il raggruppamento del [!UICONTROL Report predefinito].

**Scheda “[!UICONTROL Accesso ai blueprint]” rimossa dalle preferenze Blueprint**

*Blueprint*

NOTA: questo problema esiste solo nell’ambiente di anteprima.

La scheda [!UICONTROL Accesso ai blueprint] è stata rimossa dalle preferenze modali Blueprint. Nessuna funzionalità è stata rimossa dalle preferenze Blueprint.

+++

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 14 marzo 2022**

**Impossibile scorrere l’elenco utenti verso il basso quando si esegue un’assegnazione su una bacheca kanban**

*Agile*

Quando un utente visualizza una bacheca [!DNL Kanban] e tenta di effettuare un’assegnazione, l’elenco degli utenti che appare durante la digitazione continua a saltare all’inizio man mano che si scorre verso il basso. L’utente non può selezionare un utente che non sia in cima all’elenco e non può salvare la modifica dell’assegnazione.

La vista **[!UICONTROL Milestone] nel report del progetto causa un errore**

*Report*

Quando si visualizza il report di un progetto utilizzando la vista [!UICONTROL Milestone], gli utenti ricevono un errore “[!UICONTROL APIModel INTERNAL non supporta namedQuery TILE:milestone-view (UIVW)]”.

**La terminologia personalizzata non è coerente**

*Modelli di layout*

Gli utenti segnalano che quando l’amministratore di [!DNL Workfront] personalizza la terminologia di alcuni oggetti utilizzando un modello di layout, il nuovo nome dell’oggetto viene visualizzato in modo incoerente nell’interfaccia.

Ad esempio, nella pagina “[!UICONTROL Progetti]” è ancora possibile vedere il titolo della pagina visualizzato come “[!UICONTROL Progetti]” anche se l’amministratore di [!DNL Workfront] ha cambiato il nome di “[!UICONTROL Progetti]”.

Ciò crea confusione per gli utenti finali.

**Impossibile aggiornare i calcoli per i campi calcolati esistenti**

*Moduli personalizzati*

Gli utenti non possono aggiornare o modificare i calcoli nei campi calcolati. Se il campo è stato creato e salvato senza calcoli, ogni volta che si tenta di aggiungere un’espressione e di salvare/applicare, il generatore torna a essere vuoto.

Se si crea un campo calcolato con una determinata espressione e lo si salva, ogni volta che si tenta di modificare il calcolo viene ripristinato il valore precedente.

**[!UICONTROL Errore Parametro non valido] durante il ripristino delle password**

*Accedi*

Gli utenti non possono reimpostare le password in alcun ambiente. Quando viene inserita l’e-mail e si tenta di procedere, viene visualizzato un errore.

[!UICONTROL Errore: Parametro non valido: valore del parametro di ricerca “domain”].

+++

+++**Aggiornamento di manutenzione del 10 marzo 2022**

**Problemi di accesso all’ambiente di anteprima**

*Accedi*

Sono stati segnalati i seguenti problemi relativi all’accesso all’ambiente di anteprima.

Quando un utente cerca di accedere all’ambiente di anteprima, viene visualizzato un messaggio che indica che l’ID o la password immessi sono errati.

Quando un utente cerca di reimpostare la propria password, visualizza l’errore “[!UICONTROL Sono stati trovati più utenti con l’indirizzo e-mail <example@example.com>?]”

**I moduli personalizzati si caricano lentamente nell’area [!UICONTROL Dettagli progetto]**

*Progetti*

Quando un utente cerca di visualizzare l’area [!UICONTROL Dettagli progetto] di un progetto, gli eventuali moduli personalizzati allegati al progetto vengono caricati con un ritardo di 15 secondi o più. Anche l’opzione [!UICONTROL Aggiungi moduli personalizzati] subisce questo ritardo.

**I valori dei campi modulo personalizzato non vengono salvati nel pannello di riepilogo dei documenti**

*Documenti*

Quando, nel pannello di riepilogo del documento, un utente aggiorna dei campi modulo personalizzato di cui almeno uno è un campo di tipo typeahead e poi salva le modifiche ed esce dal pannello di riepilogo, gli aggiornamenti non vengono salvati. Ciò si verifica solo quando viene modificato un campo typeahead, anche se vengono interessati tutti i campi.

**I dati non vengono conservati durante la conversione dei modelli a causa dei livelli di accesso alla condivisione dei modelli**

*Progetti*

Quando un utente con accesso di visualizzazione su un modello condiviso tenta di convertire un problema in un progetto, tutti i dati nelle sezioni dei moduli personalizzati che richiedono un accesso di tipo [!UICONTROL Contributo] o più elevato per essere visualizzati non vengono trasferiti al progetto creato.

**Errore durante il caricamento di una nuova versione del documento**

*Documenti*

Quando un utente cerca di caricare una nuova versione di un documento dall’elenco dei documenti, il documento non viene caricato e l’utente visualizza il seguente errore:

[!UICONTROL Errore Impossibile richiamare “com.attask.boz.Document.getCurrentVersion()” perché “document” è null]

**Impossibile modificare le tariffe di fatturazione**

*Progetti*

Quando un utente cerca di modificare una tariffa di fatturazione nella scheda [!UICONTROL Tariffe di fatturazione] di un progetto, facendo clic sul pulsante [!UICONTROL Modifica], la finestra [!UICONTROL Modifica] si apre brevemente ma si chiude prima che l’utente possa modificare la tariffa di fatturazione. Facendo nuovamente clic sul pulsante, la finestra di modifica non si apre.

**Il collegamento pubblico per il documento porta a una pagina vuota**

*Documenti*

Quando un utente cerca di aprire un documento utilizzando un collegamento pubblico, si apre una pagina vuota. Ciò si verifica quando il collegamento viene aperto in una finestra in cui è aperta una sessione attiva di [!DNL Workfront].

**Errore durante l’aggiunta di attività o problemi a un elenco**

*Attività e problemi*

Quando un utente che non è un amministratore tenta di aggiungere un’attività o un problema a un elenco e compila i campi personalizzati, l’attività o il problema non viene creato e l’utente visualizza il seguente errore:

[!UICONTROL Errore Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]

**Se si abbandona un aggiornamento dopo un cambiamento di stato, l’oggetto torna allo stato precedente**

Progetti, attività e problemi

Se si modifica lo stato di un progetto, un’attività o un problema e si inizia immediatamente a digitare un aggiornamento senza ricaricare la pagina, nella casella di aggiornamento viene visualizzato lo stato precedente. Se l’aggiornamento viene pubblicato, l’oggetto viene ripristinato allo stato precedente.

**Gli utenti aggiunti alle bozze hanno ruoli errati**

*Bozze*

Quando un utente ne aggiunge un altro a una bozza, il ruolo del nuovo utente sulla bozza viene impostato come “[!UICONTROL Sola lettura]” indipendentemente dal suo ruolo effettivo.

Soluzione alternativa: impostare il ruolo di bozza dell’utente nel suo profilo su qualcos’altro, quindi reimpostare il ruolo corretto.

**Il modulo personalizzato non viene caricato durante la conversione del problema in progetto utilizzando un modello**

*Moduli personalizzati nel mio gruppo*

Quando un utente cerca di convertire un problema in un progetto utilizzando un modello, uno o più moduli personalizzati allegati al modello potrebbero non essere caricati. Quando l’utente configura il modello per il nuovo progetto, invece dei moduli personalizzati viene visualizzato il seguente messaggio:

“[!UICONTROL Errore durante il caricamento del modulo].”

**L’utente non è in grado di aggiungere il problema in linea con il campo a discesa personalizzato mostrato nella vista**

*Elenchi*

Quando un utente aggiunge un problema in linea ed è presente una vista personalizzata con campi a discesa personalizzati applicati all’elenco, se si compila solo il campo a discesa si verifica un errore. L’utente dispone dell’accesso per modificare il modulo personalizzato ed è il proprietario del progetto con diritti di gestione.

[!UICONTROL Errore: Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]

**Le autorizzazioni per aggiungere attività a un progetto non sono necessarie per spostare o copiare un’attività nel progetto**

*Attività*

Adesso è possibile spostare o copiare un’attività in un’altra attività di un progetto senza disporre delle autorizzazioni necessarie per aggiungere attività al progetto di destinazione. È necessario disporre delle autorizzazioni per aggiungere attività ad almeno una delle attività del progetto di destinazione. Prima di questo aggiornamento, per spostare o copiare un’attività nel progetto o in una delle relative attività era necessario disporre delle autorizzazioni necessarie per aggiungere attività al progetto.  Questo aggiornamento è ora disponibile nell’ambiente di produzione. È disponibile nell’ambiente di anteprima a partire dall’aggiornamento di manutenzione del 24 marzo 2022.

NOTA: questo aggiornamento sarà disponibile nell’ambiente di produzione per la copia o lo spostamento dei problemi dopo la versione di produzione 22.2. Per ulteriori informazioni sulla versione corrente, consulta workfront.com/release.

**Menu a discesa Prompt disattivato**

*Report*

Quando viene utilizzato un prompt in un report, i menu a discesa che consentono di selezionare i criteri di filtro per il report vengono disattivati. Di conseguenza, i criteri nella parte inferiore del menu a discesa non vengono visualizzati.

**L’elemento di lavoro torna allo stato precedente quando viene effettuato un aggiornamento**

*Aggiornamenti*

Quando un utente modifica lo stato di un elemento di lavoro nell’intestazione, lo stato non viene aggiornato nell’area [!UICONTROL Aggiornamento]. Se l’utente effettua un aggiornamento, il menu a discesa mostra ancora lo stato precedente. Quando l’aggiornamento viene salvato, lo stato precedente errato sovrascrive lo stato impostato nell’intestazione.

+++

+++**Aggiornamento di manutenzione del 3 marzo 2022**

**Impossibile aggiungere il documento da [!DNL Google Drive]**

*Documenti*

Quando un utente cerca di aggiungere un documento da [!DNL Google Drive], la selezione non risponde e l’utente non è in grado di selezionare i documenti da aggiungere.

**Gli utenti taggati non vengono aggiunti per aggiornare il thread**

*Aggiornamenti*

Quando un utente viene citato in un aggiornamento, non viene visualizzato nell’area “[!UICONTROL A]” dell’aggiornamento o delle relative risposte.

**L’utente della bozza ha due account di bozza separati**

*[!DNL Workfront Proof]*

L’indirizzo e-mail di un utente in [!DNL Workfront Proof] può essere presente in due account distinti con ID separati, così l’utente può avere due account. Ciò può rendere difficile individuare l’account corretto.

**Errore durante la visualizzazione nelle intestazioni del report**

*Report*

Quando un utente visualizza un report, nell’intestazione del report viene visualizzato il seguente errore:

”[!UICONTROL Riproviamo. Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]”

Se l’utente visualizza un dashboard, l’errore potrebbe comparire nell’intestazione di tutti i report nel dashboard.

**I dati nei campi di sola modifica dell’amministratore nel modulo personalizzato non vengono conservati durante la conversione dei problemi in progetti**

*Progetti*

Quando un utente che non è amministratore tenta di convertire un problema in un progetto utilizzando un modello e il problema contiene dati in campi che possono essere modificati solo da un amministratore, i dati contenuti in tali campi non vengono trasferiti al nuovo progetto.

Quando il problema viene convertito da un amministratore, i dati vengono trasferiti al nuovo progetto come previsto.

Il limite di dimensione per i file **[!DNL XLS] e [!DNL XLSX] è temporaneamente ridotto a 100 MB per le bozze**

*Verifica*

Per risolvere un problema di sicurezza, abbiamo temporaneamente limitato la dimensione massima per i file [!DNL XLS] e [!DNL XLSX] a 100 MB per la creazione delle bozze.

NOTA: questo aggiornamento era presente nell’ambiente di anteprima il 24 febbraio e sarà disponibile nell’ambiente di produzione il 3 marzo.

**Aggiornamento per lo strumento di ricerca di Workfront**

Ricerca

Questa settimana è iniziato un rollout graduale di aggiornamento dell’infrastruttura per la funzionalità di ricerca di [!DNL Workfront]. L’aggiornamento renderà i futuri miglioramenti dello strumento di ricerca più semplici e affidabili. Grazie a queste modifiche, gli elementi aggiunti a [!DNL Workfront] saranno indicizzati più rapidamente e quindi verranno visualizzati prima nei risultati di ricerca.

Il rollout graduale continuerà per 2 settimane.

**Sono state aggiornate le barre degli strumenti per i report nei dashboard**

Report

Nei report dei dashboard è ora visibile una nuova barra degli strumenti. Questa barra degli strumenti fa parte degli aggiornamenti agli elenchi e ai report che coinvolgono [!DNL Workfront] complessivamente.

+++


## Aggiornamenti di febbraio 2022

+++**Aggiornamento di manutenzione (aggiornamento rapido) del 24 febbraio 2022**

**I dati non vengono conservati durante la conversione dei problemi in progetti se il campo è nascosto nel modello**

*Progetti*

Quando un utente converte un problema in un modello che include un modulo personalizzato, se il modulo mostra o nasconde campi basati sui valori di altri campi, tutti i dati contenuti in campi nascosti nel modello (senza dati) al momento della conversione non vengono inseriti nel nuovo progetto.

**Impossibile esportare la pianificazione delle risorse per ruolo**

*Pianificazione risorse*

Quando un utente cerca di esportare la [!DNL Resource Planner] utilizzando l’opzione [!UICONTROL Visualizza per ruolo], l’esportazione non riesce e l’utente riceve un’e-mail con il seguente messaggio:

Si è verificato un errore durante l’esportazione del grafico[!DNL Resource Planner].

**Il pulsante Copia richiesta non funziona**

*Richieste*

Quando un utente cerca di copiare una richiesta, il pulsante [!UICONTROL Copia richiesta] non funziona se l’utente non ha accesso alla visualizzazione dell’argomento della coda.

+++

+++**Aggiornamento di manutenzione del 24 febbraio 2022**

**I dati del modulo personalizzato scompaiono quando vengono compilati altri campi del modulo**

*Moduli personalizzati nel mio gruppo*

Quando un utente compila un modulo personalizzato nell’ambito della conversione di un problema in un progetto, la compilazione di un campo personalizzato potrebbe causare la scomparsa dei dati in un altro campo personalizzato. Se l’utente immette nuovamente i dati mancanti, quando tenta di creare il progetto, visualizza il seguente messaggio di errore:

”[!UICONTROL Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema]”

**Il campo “[!UICONTROL Questa approvazione è utilizzabile da...]” non è visibile**

*Approvazioni*

Quando un utente crea o modifica un processo di approvazione nell’area [!UICONTROL Configura], manca il campo “[!UICONTROL Questa approvazione è utilizzabile da...]”. Ciò può verificarsi durante la creazione di un processo di approvazione o la modifica di un processo esistente.

**L’amministratore di sistema non può riassegnare gli utenti quando si elimina un gruppo**

*Gruppi*

Quando l’amministratore di sistema elimina un gruppo, ha la possibilità di riassegnare gli utenti di quel gruppo solo ai gruppi di cui è amministratore gruppo. Gli altri gruppi non vengono visualizzati nel menu a discesa e l’amministratore non può selezionarli.

**Errore durante la conversione del problema in progetto**

*Progetti*

Quando un utente cerca di convertire un problema in un progetto utilizzando un modello e aggiunge o rimuove moduli personalizzati dal modello, il problema non viene convertito e l’utente visualizza il seguente messaggio:

[!UICONTROL Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]

**Impossibile aprire la bozza; la pagina si aggiorna**

*Bozze*

Quando un utente cerca di aprire una bozza, non è possibile aprirla. Alla fine, la pagina si aggiorna.

Il limite di dimensione per i file **[!DNL XLS] e [!DNL XLSX] è temporaneamente ridotto a 100 MB per le bozze**

*Verifica*

Per risolvere un problema di sicurezza, abbiamo temporaneamente limitato la dimensione massima per i file [!DNL XLS] e [!DNL XLSX] a 100 MB per la creazione delle bozze.

NOTA: questo aggiornamento sarà presente nell’ambiente di anteprima il 24 febbraio e nell’ambiente di produzione il 3 marzo.

**Le autorizzazioni per aggiungere attività o problemi a un progetto non sono necessarie per spostare o copiare un’attività o un problema nel progetto**

*Progetti*

È ora possibile spostare o copiare un’attività o un problema in un’altra attività di un progetto senza disporre delle autorizzazioni necessarie per aggiungere attività o problemi al progetto di destinazione. È necessario disporre delle autorizzazioni per aggiungere attività o problemi ad almeno una delle attività del progetto di destinazione. Prima di questo aggiornamento, per spostare o copiare un’attività o un problema nel progetto o in una delle relative attività era necessario disporre delle autorizzazioni necessarie per aggiungere attività o problemi al progetto. Questo aggiornamento è disponibile solo nell’ambiente di anteprima.

NOTA: questo aggiornamento sarà disponibile nell’ambiente di produzione quando si copiano o si spostano le attività il 10 marzo. Questo aggiornamento sarà disponibile nell’ambiente di produzione per la copia o lo spostamento dei problemi con la versione di produzione 22.2. Per ulteriori informazioni sulla versione corrente, consulta workfront.com/release.

**Aggiornamento per lo strumento di ricerca di Workfront**

*Ricerca*

Questa settimana è iniziato un rollout graduale di aggiornamento dell’infrastruttura per la funzionalità di ricerca di [!DNL Workfront]. L’aggiornamento renderà i futuri miglioramenti dello strumento di ricerca più semplici e affidabili. Grazie a queste modifiche, gli elementi aggiunti a [!DNL Workfront] saranno indicizzati più rapidamente e quindi verranno visualizzati prima nei risultati di ricerca.

Il rollout graduale continuerà per 2 settimane.

+++

+++**[!DNL Workfront Fusion]- Aggiornamento di manutenzione del 18 febbraio 2022**

**Convalida del tipo di valore del campo aggiunta alle proprietà degli elementi dell’elenco di [!DNL Anaplan]**

*[!DNL Adobe Workfront Fusion]*

È stato risolto un problema che permetteva agli utenti di inserire il tipo di dati errato nei campi per le proprietà degli elementi dell’elenco. La convalida del tipo di proprietà consente a [!DNL Fusion] di garantire che venga inviato il tipo di dati corretto ad Anaplan, eliminando gli errori dovuti a tipi di dati errati.

+++

+++**Aggiornamento di manutenzione del 17 febbraio 2022**

**Errore durante l’eliminazione di un predecessore dalla scheda Predecessori**

*Attività*

Quando un utente cerca di eliminare un predecessore dalla scheda [!UICONTROL Predecessori] su un’attività, l’attività non viene eliminata e l’utente visualizza il seguente errore:

[!UICONTROL Attività con valore della chiave primaria &quot;&quot; non trovata]

**Errore all’apertura della pagina Utenti**

*Utenti*

Quando un utente cerca di aprire la pagina [!UICONTROL Utenti], la pagina non si apre e l’utente visualizza il seguente errore:

[!UICONTROL Ops! Si è verificato un errore. Contatta [!DNL Workfront] in modo che possiamo capire qual è stato il problema e risolverlo.]

**Sovrapposizione di elementi nell’intestazione di un report su un dashboard**

*Dashboard*

Quando un utente visualizza un report su un dashboard, l’etichetta e l’icona dei raggruppamenti si sovrappongono ai collegamenti a [!UICONTROL Dettagli] e [!UICONTROL Riepilogo].

**Problemi con il menu “[!UICONTROL altro]” per i documenti e le bozze**

*Documenti*

Quando un utente seleziona un documento o una bozza in un elenco di documenti di [!DNL Workfront Classic] e poi fa clic su “[!UICONTROL Altro]”, potrebbe riscontrare uno dei seguenti problemi:
Il pulsante non risponde
Tutte le opzioni sotto il pulsante sono etichettate come “[!UICONTROL Oggetto oggetto]” e non possono essere utilizzate.

**Errore “Devi essere un amministratore di sistema” durante la creazione di un progetto**

*Progetti*

Quando un utente che non è amministratore tenta di creare un progetto e allega un modulo personalizzato con una sezione disponibile solo per gli amministratori, non può creare il progetto e viene visualizzato il seguente errore:

”Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema”

**I dati nella sezione Solo Amministratore nel modulo personalizzato non vengono conservati durante la conversione dei problemi in progetti**

*Progetti*

Quando un utente converte un problema in un progetto utilizzando un modello che presenta un modulo personalizzato con una sezione Solo amministratore, nessun dato della sezione Solo amministratore viene trasferito al nuovo progetto. Ciò si verifica anche se è un amministratore a convertire il problema.

+++

+++**Aggiornamento di manutenzione del 10 febbraio 2022**

**Errore “[!UICONTROL Devi essere un amministratore di sistema]” durante la creazione di un progetto**

*Progetti*

Quando un utente che non è amministratore tenta di creare un progetto e allega un modulo personalizzato con una sezione disponibile solo per gli amministratori, non può creare il progetto e viene visualizzato il seguente errore:

”[!UICONTROL Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema]”

**Gli utenti che sono stati disattivati e poi riattivati non compaiono in [!UICONTROL Contatti bozza]**

*[!DNL Workfront Proof]*

Quando un utente visualizza l’elenco dei contatti in [!DNL Workfront Proof], gli utenti disattivati e poi riattivati non vengono visualizzati nell’elenco.

**Messaggio “Si è verificato un errore” quando si converte un problema in un progetto utilizzando un modello**

*Progetti*

Quando un utente che non è amministratore tenta di convertire un problema in un progetto utilizzando un modello, i campi dei moduli personalizzati visibili solo agli amministratori mostrano il seguente messaggio:

“[!UICONTROL Errore durante il caricamento del modulo]”

**Errore “Impossibile caricare il contenuto della pagina” durante la visualizzazione delle preferenze del progetto**

*Configura*

Quando un utente amministratore tenta di visualizzare progetti, attività o problemi in [!UICONTROL Preferenze progetto] nell’area [!UICONTROL Configura], la pagina non viene caricata e l’utente visualizza il seguente errore:

”[!UICONTROL Impossibile caricare il contenuto della pagina. Provare a riaggiornare la pagina.]”

+++

+++**Aggiornamento di manutenzione del 3 febbraio 2022**

**[!UICONTROL Errore BizContext] quando si esegue l’accesso**

*Accedi*

Quando un utente cerca di accedere a [!DNL Workfront], l’accesso non riesce e viene visualizzato il seguente messaggio:

”[!UICONTROL Riproviamo. Errore del database: commit BizContext non riuscito.]”

Questo problema è stato segnalato nell’ambiente di anteprima.

**Il flusso di aggiornamento del problema scompare se il problema è in attesa di approvazione**

*Aggiornamenti*

Quando un utente fa clic sulla casella [!UICONTROL Nuovo aggiornamento] nel flusso di aggiornamento di un problema in attesa di approvazione, l’intero flusso di aggiornamento scompare.

**Errore durante il caricamento della nuova versione di un documento**

*Documenti*

Quando un utente cerca di caricare una nuova versione di un documento, la nuova versione non viene caricata e l’utente visualizza uno dei seguenti errori:

* [!UICONTROL documentID non può essere null]
* [!UICONTROL Errore: Parametro non valido: valore documentID “undefined”]

**Il collegamento pubblico per il documento porta a una pagina vuota**

*Documenti*

Quando un utente cerca di aprire un documento utilizzando un collegamento pubblico, si apre una pagina vuota. Ciò si verifica quando il collegamento viene aperto in una finestra in cui è aperta una sessione attiva di [!DNL Workfront].

**I controlli elenco non funzionano sui report nei dashboard**

*Dashboard*

Quando un utente visualizza un report in un dashboard e tenta di modificare il filtro, il raggruppamento o la visualizzazione del report, questi non cambiano.

**Errore “[!UICONTROL Devi essere un amministratore di sistema]” durante la creazione di un progetto**

*Progetti*

Quando un utente che non è amministratore tenta di creare un progetto e allega un modulo personalizzato con una sezione disponibile solo per gli amministratori, non può creare il progetto e viene visualizzato il seguente errore:

”[!UICONTROL Per cambiare il valore dei parametri dei dati personalizzati è necessario essere amministratore di sistema]”

**I dati personalizzati non vengono conservati durante la conversione del problema in progetto**

*Progetti*

Quando un utente converte un problema in un progetto utilizzando un modello, i dati di un modulo personalizzato relativo al problema non vengono trasferiti al modulo personalizzato analogo del progetto. Ciò si verifica per i dati contenuti in campi personalizzati che possono essere nascosti in base ai valori di altri campi personalizzati.

**Errore durante la conversione del problema in progetto**

*Progetti*

Quando un utente cerca di convertire un problema in un progetto, il problema non viene convertito e l’utente visualizza il seguente errore:

”[!UICONTROL Un errore inaspettato si è verificato]”

+++


## Aggiornamenti di gennaio 2022

+++**Aggiornamento di manutenzione del 27 gennaio 2022**

**I dati personalizzati non vengono conservati durante la conversione del problema in progetto**

*Progetti*

Quando un utente converte un problema in un progetto utilizzando un modello, i dati di un modulo personalizzato relativo al problema non vengono trasferiti al modulo personalizzato analogo del progetto. Ciò si verifica per i dati contenuti in campi personalizzati che possono essere nascosti in base ai valori di altri campi personalizzati.

**L’elenco degli utenti sulla bacheca Agile non è in ordine alfabetico**

*Agile*

Quando un utente visualizza l’elenco degli utenti su una bacheca Agile, gli utenti non vengono mostrati in ordine alfabetico. Vengono invece elencati per primi gli utenti con il maggior numero di assegnazioni.

**Aggiornamento dei collegamenti per copiare e spostare i problemi**

*problemi*

Nell’ambiente di anteprima, i collegamenti per copiare e spostare i problemi sono stati aggiornati a “[!UICONTROL Copy in]” e “[!UICONTROL Sposta in]” sia nelle pagine dei problemi sia negli elenchi dei problemi.

**Si possono aggiungere fino a 45 indirizzi IP al proprio elenco di indirizzi consentiti di [!DNL Workfront]**

*Configura*

Il limite per gli indirizzi IP aggiunti al proprio elenco di indirizzi consentiti su [!DNL Workfront] è aumentato da 30 a 45.

+++

+++**Aggiornamento di manutenzione del 20 gennaio 2022**

**Errore “[!UICONTROL Parametro non valido]” durante la creazione di un progetto da un modello**

*Progetti*

Quando un utente cerca di creare un progetto da un modello e rimuove un modulo personalizzato dal modello, il progetto non viene creato e l’utente visualizza un messaggio di errore “[!UICONTROL Parametro non valido]” che fa riferimento a un campo obbligatorio nel modulo personalizzato rimosso.

**L’elenco degli utenti non viene caricato nel browser [!DNL Safari]**

*Utenti*

Quando un utente accede all’area [!UICONTROL Utenti], l’intestazione viene visualizzata ma l’elenco degli utenti non si carica.

**Il ritardo nel trascinamento delle attività in un elenco causa lo spostamento dell’attività nella posizione sbagliata**

*Elenchi*

Quando un utente cerca di spostare un’attività in un elenco trascinandola, la linea blu che indica dove verrà spostata l’attività si sposta molto più lentamente del cursore. Quando l’utente rilascia l’attività, questa si sposterà nel punto in cui si trova la linea blu, anche se il cursore indica una posizione diversa nell’elenco.

+++

+++**[!DNL Workfront Fusion]- Aggiornamento di manutenzione del 14 gennaio 2022**

**Alcuni campi mappati vengono reimpostati quando si seleziona un [!UICONTROL nuovo campo da mappare]**

*[!DNL Workfront Fusion]*

Se almeno un campo nei moduli [!UICONTROL Crea] o [!UICONTROL Aggiorna] di [!DNL Workfront] è abilitato alla mappatura e un utente seleziona un nuovo campo da mappare, i campi precedentemente mappati che sono abilitati alla mappatura perdono i valori di mappatura.

+++

+++**Aggiornamento di manutenzione del 13 gennaio 2022**

**Impossibile aggiungere un collegamento ipertestuale a un commento nel pannello Riepilogo**

*Attività*

Quando un utente fa un commento nel pannello di riepilogo di un’attività e tentando di aggiungere un collegamento ipertestuale, la finestra del collegamento ipertestuale viene visualizzata ma si chiude non appena l’utente fa clic al suo interno, e non è possibile aggiungere il collegamento ipertestuale. Se un utente si sposta con il tasto TAB nella finestra, può digitare o incollare un collegamento nel campo, ma il collegamento ipertestuale non viene salvato. In entrambi i casi, l’attività viene deselezionata.

**La pagina Modifica team non viene chiusa**

*Team*

Quando un utente cerca di modificare un team, la pagina [!DNL Edit team] non si chiude. L’utente non può chiudere la pagina facendo clic su un pulsante, facendo clic sulla X né uscendo dalla pagina.

**Le notifiche e-mail e in-app non vengono inviate**

*Notifiche*

Quando si verifica un evento che deve attivare una notifica, la notifica non viene inviata. Ciò può accadere per le notifiche e-mail o in-app e può verificarsi anche se vengono inviate altre notifiche.

**[!UICONTROL L’elenco Il mio lavoro] risulta vuoto**

*[!UICONTROL Il mio lavoro]*

Quando un utente visualizza il proprio elenco [!UICONTROL Il mio lavoro] e il modello di layout dell’elenco [!UICONTROL Il mio lavoro] include un valore numerico come [!UICONTROL Percentuale di completamento], l’elenco [!UICONTROL Il mio lavoro] non viene visualizzato.

Non è possibile modificare la **[!UICONTROL percentuale di completamento] e le [!UICONTROL ore di completamento] nella bacheca Agile**

*Agile*

Quando un utente seleziona “[!UICONTROL Mostra altri elementi di lavoro]” nella bacheca Agile, quindi tenta di modificare la “[!UICONTROL Percentuale completata]” o le “[!UICONTROL Ore completate]” su uno degli elementi di lavoro appena caricati, non può modificare la percentuale o le ore completate. Anche il pulsante [!UICONTROL Percentuale completata] è grigio, per indicare che è inattivo.

+++

+++**Aggiornamento di manutenzione del 6 gennaio 2022**

**Errore “[!UICONTROL Parametro non valido]” durante l’associazione di modelli o moduli personalizzati ai progetti**

*Progetti*

Quando un utente cerca di allegare un modulo personalizzato o un modello a un progetto esistente, compila i campi obbligatori nel modulo o modello personalizzato e salva le modifiche al progetto, le modifiche non vengono salvate e l’utente visualizza un errore “[!UICONTROL Parametro non valido]” nella parte superiore della pagina dei dettagli del progetto.

**I commenti della bozza non vengono visualizzati negli aggiornamenti del documento**

*Bozze*

Quando un utente visualizza una bozza nell’area [!UICONTROL Documenti], i commenti inseriti nella bozza non vengono visualizzati nell’area [!UICONTROL Aggiornamenti] del documento.

**[!UICONTROL Bilanciatore dei carichi di lavoro]: ”[!UICONTROL ?[object Object]?] compare nelle informazioni sulla sovrassegnazione**

*[!UICONTROL Bilanciatore dei carichi di lavoro]*

Se un utente risulta sovrassegnato nel [!UICONTROL Bilanciatore dei carichi di lavoro] a causa di un’attività che si sovrappone al tempo libero dell’utente e un altro utente visualizza la sua sovrassegnazione, l’area “[!UICONTROL Capacità]” delle informazioni sulla sovrassegnazione mostra “[!UICONTROL ?[Oggetto oggetto]?]” invece della capacità effettiva dell’utente.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sui precedenti aggiornamenti di manutenzione sono disponibili qui:

* [[!DNL Workfront] Archivio aggiornamenti di manutenzione - 2021](2021-updates.md)
