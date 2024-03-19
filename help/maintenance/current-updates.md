---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: e399c45c2bb5782d8d25add9b097cce18205f994
workflow-type: tm+mt
source-wordcount: '2205'
ht-degree: 99%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2024.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, consulta [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di marzo 2024

+++**Aggiornamento di manutenzione del venerdì 14 marzo 2024**

### Aggiornamento di manutenzione del venerdì 14 marzo 2024

#### Bozze

**Alle bozze create da documenti collegati non è applicato il modello di bozza**

Quando un utente crea una bozza da un documento collegato, il modello di bozza non viene applicato correttamente e potrebbero mancare informazioni come il flusso di lavoro.

Questo vale anche per le bozze create tramite l’API e tramite Workfront Fusion.

#### Utenti

**Livelli di accesso inferiori non disponibili durante la creazione di un utente**

Quando un utente crea un altro utente, al nuovo utente è disponibile solo il livello di accesso del primo utente. Tutti i livelli di accesso con autorizzazioni inferiori rispetto a quelli dell’utente che crea devono essere disponibili per l’assegnazione al nuovo utente.

+++

+++**Aggiornamento di manutenzione del venerdì 7 marzo 2024**

### Aggiornamento di manutenzione del 7 marzo 2024

#### Bacheche

**Errore 400 durante l’aggiunta di un’attività a una bacheca**

Quando un utente visualizza un progetto e tenta di aggiungere un’attività a una bacheca, questa non viene aggiunta e l’utente visualizza il seguente errore:

Errore: “400: undefined /boards-service/graphql”.

#### Home

**Errore durante la modifica in linea di un’attività nel widget Le mie attività**

Quando un utente cerca di modificare in linea un’attività nel widget Le mie attività, viene visualizzato il seguente errore:

“Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova ad aggiornare la pagina del browser.”


#### Bilanciatore dei carichi di lavoro

**Le ore pianificate non vengono aggiornate nel Bilanciatore dei carichi di lavoro**

“Quando le ore pianificate su un progetto vengono aggiornate, non vengono aggiornate nel Bilanciatore dei carichi di lavoro. Ciò può verificarsi anche se la modifica viene riflessa accuratamente nel progetto.

+++

+++**Aggiornamento di manutenzione di Workfront Fusion del 7 marzo 2024

**Workfront Proof > timeout del modulo Watch Proof**

Gli scenari che utilizzano Workfront Proof > modulo Watch Proof possono disattivarsi a causa del timeout del modulo Watch Proof.

+++

## Aggiornamenti di febbraio 2024

+++**Aggiornamento di manutenzione dell’venerdì 29 febbraio 2024**

### Aggiornamento di manutenzione dell’venerdì 29 febbraio 2024

#### Aggiornamenti

**Aggiornamenti: la schermata diventa vuota quando si risponde a un utente di un’altra azienda**

Quando un utente cerca di rispondere a un commento di un utente di un’altra azienda, la schermata diventa vuota.

Questo avviene perché l’utente non dispone dell’autorizzazione per visualizzare gli utenti di altre aziende.

+++

+++**Aggiornamento di manutenzione dell’venerdì 22 febbraio 2024**

### Aggiornamento di manutenzione dell’venerdì 22 febbraio 2024

#### Home

**[!UICONTROL Home]: l’[!UICONTROL area di lavoro] e i pin non vengono caricati**

Quando un utente effettua l’accesso, può verificarsi quanto segue:

* La nuova [!UICONTROL area di lavoro della Home] dell’utente non si carica e viene visualizzato l’errore: [!UICONTROL Impossibile caricare le informazioni dell’area di lavoro. Contatta Workfront per consentirci di individuare e risolvere il problema.]”
* I pin dell’utente non vengono caricati e viene visualizzato l’errore: [!UICONTROL I pin non sono disponibili a causa di un errore di sistema. Prova ad aggiornare il browser per risolvere il problema.]”

#### Utenti

**L’amministratore del gruppo non può impostare o modificare il livello di accesso di un utente**

<!--no article-->

Quando un amministratore del gruppo tenta di modificare il livello di accesso di un utente, può verificarsi una delle seguenti situazioni:

* il campo del livello di accesso è disabilitato.
* L’amministratore del gruppo non può scegliere un livello di accesso inferiore.

#### Bilanciatore dei carichi di lavoro

**Etichetta per ore non lavorative**

Il Bilanciatore dei carichi di lavoro e il calendario personale delle ferie ora mostrano le “[!UICONTROL ore non lavorative]” in cui l’utente ha preso le ferie. Precedentemente la visualizzazione mostrava “[!UICONTROL Ore di lavoro]” per il tempo non lavorativo.

+++

+++**Aggiornamento di manutenzione dell’venerdì 15 febbraio 2024**

### Aggiornamento di manutenzione dell’venerdì 15 febbraio 2024

#### Problemi

**I campi orario consentono di salvare orari non corretti durante la modifica in blocco dei problemi**

Quando un utente modifica in blocco problemi e seleziona una data e un’ora per un campo data e salva, l’ora salvata in questo campo del problema non è l’ora selezionata dall’utente. Al contrario, l’ora sembra essere convertita in UTC quando l’utente salva.

#### Attività

**Una o più attività non sono più assegnate all’utente**

L’assegnazione di un’attività a un utente può essere annullata automaticamente. L&#39;annullamento può verificarsi per una o più attività. L&#39;annullamento dell&#39;assegnazione non viene visualizzato nell&#39;area Aggiornamenti di sistema delle attività, ma nella sezione Aggiorna feed del menu di configurazione.

#### Aggiornamenti

**L’opzione Immagine disabilitata è disponibile quando si modifica un commento**

Dopo che un amministratore di [!DNL Workfront] ha disattivato l’opzione per aggiungere immagini ai commenti, tale opzione non è disponibile durante la creazione di un commento. Tuttavia, se un utente modifica un commento esistente, l’opzione immagine è disponibile.

+++

+++**Aggiornamento di manutenzione dell’venerdì 8 febbraio 2024**

### Aggiornamento di manutenzione dell’8 febbraio 2024

#### Bacheche

**Impossibile spostare una scheda in una colonna utilizzando le opzioni [!UICONTROL Sposta]**

Quando un utente tenta di spostare una scheda in una colonna utilizzando le opzioni “[!UICONTROL Inizio colonna]” o “[!UICONTROL Fine colonna]” nel menu a tre punti, la scheda non si sposta.

**Le schede persistono quando si modifica l’iterazione**

Quando un utente visualizza un’iterazione su una bacheca e successivamente la modifica, le schede visualizzate per la nuova iterazione sono quelle di una che l’utente stava visualizzando in precedenza.

#### Report

**La colonna “Nessun valore” non mostra alcun risultato**

Quando un rapporto di un grafico dispone di una colonna “[!DNL No value]”, la colonna non mostra dati, anche se dovrebbero essere presenti.

#### Gestione risorse

**Calcoli finanziari errati a causa di problemi relativi alla mansione**

Le ore e i calcoli finanziari potrebbero non essere corretti, mostrando un costo pari a 0 anche se le ore sono registrate in una mansione che prevede un tasso di costo.

Questo perché le mansioni creano automaticamente tariffe duplicate senza date di inizio o di fine. Poiché non dispongono di date di inizio o di fine, le tariffe vengono considerate come valori pari a 0 quando vengono eseguiti i calcoli finanziari.

+++

+++**Aggiornamento di manutenzione dell’venerdì 1 febbraio 2024**

### Aggiornamento di manutenzione del 1° febbraio 2024

#### Accedi

**Gli utenti che utilizzano SSO non vengono reindirizzati alla posizione originale durante l’accesso**

Quando un utente si trova su una pagina in [!DNL Workfront] e accede con SSO; una volta completato l’accesso, viene indirizzato alla pagina [!UICONTROL Home] invece che a quella in cui si trovava prima dell’accesso.

#### Modelli

**Errore durante la copia dei modelli**

Quando un utente tenta di copiare un modello nuovo o esistente, l’operazione ha esito negativo e l’utente visualizza il seguente messaggio di errore:

“[!UICONTROL L’ID non può essere nullo]”

+++

## Aggiornamenti di gennaio 2024

+++**Aggiornamento di manutenzione (Hot Fix) del mercoledì 30 gennaio 2024**

### Aggiornamento di manutenzione (Hot Fix) del 30 gennaio 2024

#### Report

**Il campo API esterna non mostra tutti i valori disponibili negli elenchi e nei rapporti**

In precedenza, gli utenti potevano visualizzare il valore selezionato (e modificarlo) per un campo di ricerca esterno negli elenchi e nei rapporti, ma non visualizzavano il menu a discesa con le opzioni provenienti dall’API.

Ora, quando un campo personalizzato di ricerca esterna viene utilizzato in un elenco o in un rapporto, è disponibile il menu a discesa con tutte le opzioni dell’API esterna.

+++

+++**Aggiornamento di manutenzione del venerdì 25 gennaio 2024**

### Aggiornamento di manutenzione dell’venerdì 25 gennaio 2024

#### Bacheche

**Le schede non vengono spostate nella colonna appropriata quando lo stato viene modificato**

Quando lo stato di un oggetto collegato a una scheda viene modificato direttamente sull’oggetto, la scheda non viene spostata nella colonna appropriata. Se lo stato dell’oggetto viene modificato sulla scheda o questa viene trascinata nella nuova colonna, la scheda si comporta nel modo previsto.

#### Notifiche

**La contrassegnazione delle notifiche come visualizzate non persiste**

Quando un utente contrassegna le notifiche come visualizzate e quindi passa a una pagina diversa all’interno di [!DNL Workfront], l’icona delle notifiche mostra ancora il numero di notifiche non lette che esistevano prima che l’utente le contrassegnasse come visualizzate e rimangono elencate quando l’utente fa clic sull’icona. Questo continua se l’utente le contrassegna come visualizzate e passa a un’altra pagina o torna alla pagina originale.

#### Aggiornamenti

**Problemi relativi all’assegnazione di tag nell’esperienza di commento precedente**

Quando un utente viene taggato in un commento nell’esperienza di commento precedente, si verificano i seguenti problemi:

* nel commento è presente solo il nome utente
* il nome utente non è contrassegnato con il simbolo @
* il nome utente non è di colore blu
* il nome utente non è un collegamento al profilo utente

l’utente riceve una notifica e-mail relativa al tag, come previsto.

+++

+++**Aggiornamento di manutenzione del venerdì 18 gennaio 2024**

### Aggiornamento di manutenzione dell’venerdì 18 gennaio 2024

#### Bacheche

**Impossibile allegare un documento a una scheda**

Quando un utente tenta di allegare un documento a una scheda connessa, può selezionare il documento da allegare, ma il documento non viene visualizzato nell’area del documento della scheda e non è collegato all’oggetto a cui è connessa la scheda.

Questo problema è stato segnalato nelle schede collegate a problemi.

**La scheda appare su più sprint**

Quando un utente sta visualizzando uno sprint su una bacheca, le schede che si trovano in sprint diversi appaiono sulla bacheca. Questo problema è intermittente.

**La scheda non si chiude quando si utilizza la vista Bacheche in un progetto**

Quando un utente crea una scheda durante la vista Bacheche in un elenco di attività di un progetto, la scheda non viene chiusa né salvata. Questo impedisce all’utente di tornare al progetto.

Per chiudere la scheda, l’utente deve modificare l’URL per rimuovere “scheda” e tutto ciò che si trova a destra di “scheda”.

**Le schede persistono quando si modifica l’iterazione**

Quando un utente visualizza un’iterazione su una bacheca e successivamente la modifica, le schede visualizzate per la nuova iterazione sono quelle di una che l’utente stava visualizzando in precedenza.

**Errore nella sezione [!UICONTROL Commenti] delle schede**

Quando un utente visualizza una scheda e scorre fino alla sezione [!UICONTROL Commenti], i commenti non vengono visualizzati e l’utente visualizza il seguente errore:

&quot;[!UICONTROL Si è verificato un errore. Riprova più tardi.]&quot;

**Problemi durante la visualizzazione dello stato delle attività secondarie**

Sono stati segnalati i seguenti problemi relativi alla visualizzazione dello stato delle attività secondarie in una scheda in Bacheche:

* Lo stato viene visualizzato come “Seleziona stato” anche quando l’attività ha già uno stato. Questo stato può essere visualizzato quando si visualizza direttamente l’attività.
* Se l’utente cerca di selezionare uno stato, la schermata diventa vuota e deve essere aggiornata.

**“[!UICONTROL Non disponi del livello di accesso]” durante la visualizzazione dei commenti su una scheda**

Quando un utente tenta di visualizzare i commenti su una scheda non connessa a un oggetto di [!DNL Workfront], viene mostrato il messaggio seguente:

“[!UICONTROL Non disponi del livello di accesso per visualizzare i commenti su questo oggetto]”

Ciò può verificarsi anche quando l’utente poteva vedere i commenti sulla scheda in precedenza.

#### Moduli personalizzati nel mio gruppo

**Impossibile aggiungere o rimuovere in blocco moduli personalizzati nelle attività modello**

Se un utente cerca di aggiungere o rimuovere in blocco un modulo personalizzato in un’attività modello, il modulo non viene aggiunto o rimosso e l’utente visualizza il seguente errore:

[!UICONTROL Riproviamo. Parametro non valido: valore templateID “XXXXXXXXXXXXXXXX”]

Se l’utente individua il modello con il GUID specificato e cerca di aggiungere o rimuovere moduli personalizzati nelle altre attività modello, l’errore si verificherà nuovamente utilizzando un altro templateID.

I moduli personalizzati possono essere aggiunti o rimossi in un’unica attività modello. Questo errore vale solo per l’aggiunta o per la rimozione in blocco.

#### Portfolio

**La terminologia personalizzata non viene applicata alla pagina del gruppo**

Quando un utente imposta la terminologia personalizzata a livello di portfolio, la terminologia non viene applicata alla pagina del livello di gruppo.

#### Configura

**Impossibile nascondere gli stati facoltativi**

Quando un utente prova a nascondere gli stati facoltativi a livello di sistema e di gruppo, lo stato non viene nascosto. Se l’utente visualizza lo stato, l’opzione per nascondere lo stato non è abilitata, anche se l’utente l’ha abilitata e ha salvato le modifiche.

**Stati dei problemi predefiniti mancanti da alcuni tipi di problemi in Configurazione**

Quando un utente visualizza gli stati dei problemi in Configurazione, nota che in alcuni tipi di problemi mancano gli stati predefiniti (Nuovo, In corso e Completato). Gli stati predefiniti non dispongono della possibilità di modificare il tipo di problema, pertanto l’utente non può configurare nuovamente gli stati da visualizzare per i tipi di problema interessati.

#### Team

**Problemi relativi all’impostazione degli stati del team per il pulsante [!UICONTROL Fine]**

Sono stati segnalati i seguenti problemi relativi agli stati per il pulsante [!UICONTROL Fine] durante la modifica o la creazione di un team:

* Alcuni stati potrebbero non essere presenti nell’area del pulsante Fine della finestra [!UICONTROL Nuovo team] o nell’area [!UICONTROL Impostazioni team] di un team esistente.
* Se l’utente tenta di salvare il team, potrebbe visualizzare l’errore “È necessario selezionare almeno uno stato in ogni categoria.”

#### Modelli

**Errore quando si allega un modello a un progetto**

Quando un utente cerca di allegare un modello a un progetto, riceve il seguente errore:

“Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.”

Ciò si verifica quando l’utente non dispone dell’autorizzazione Visualizzazione per un modulo personalizzato allegato al modello.

#### Aggiornamenti

**I commenti non vengono trasferiti dalla esperienza precedente alla nuova**

Un commento creato nell’esperienza di commento precedente potrebbe non essere visibile in quella nuova. Può verificarsi anche il contrario.

+++

+++**Aggiornamento di manutenzione del venerdì 11 gennaio 2024**

### Aggiornamento di manutenzione dell’venerdì 11 gennaio 2024

#### Bacheche

**Le schede completate non vengono caricate correttamente sulle bacheche dinamiche**

In precedenza, l’unico modo per includere il lavoro completato su una bacheca dinamica era caricare le schede come schede archiviate. In caso contrario, le schede completate non venivano affatto caricate sulla bacheca. Questo causava problemi nella possibilità di individuare le schede.

Ora, quando crei una bacheca dinamica, le schede completate vengono caricate per impostazione predefinita come schede archiviate, ma puoi selezionare Non archiviare le schede completate per caricare tutte le schede completate sulla bacheca come schede visibili nella colonna Completate.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sugli aggiornamenti di manutenzione precedenti sono disponibili qui:

* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2023](2023-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2022](2022-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2021](2021-updates.md)
