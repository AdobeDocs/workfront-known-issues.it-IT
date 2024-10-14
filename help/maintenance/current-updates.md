---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 8e095890454b39f046eb8ea2ee9505bdf25c8237
workflow-type: tm+mt
source-wordcount: '6157'
ht-degree: 98%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

>[!NOTE]
>
>Per informazioni sulle interruzioni di manutenzione per tutti i prodotti Adobe, incluso Workfront, consulta la [pagina di stato Adobe](https://status.adobe.com/it).

Questa pagina descrive i problemi risolti negli aggiornamenti settimanali di Workfront.

Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2024, consulta [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2024.

## Aggiornamenti di ottobre 2024

+++**Aggiornamento di manutenzione del venerdì 10 ottobre 2024**

### Aggiornamento di manutenzione del venerdì 10 ottobre 2024

#### Bacheche

**Errore durante lo spostamento delle schede o l&#39;assegnazione di utenti**

A volte, durante lo spostamento delle schede o l’assegnazione degli utenti, l’azione non viene eseguita e genera l’errore “Risposta non riuscita: ricevuto il codice di stato 502” dopo un ritardo.

**Errore durante il caricamento di una bacheca**

Quando un utente cerca di caricare una bacheca, questa non viene caricata e l’utente visualizza il seguente messaggio:

&quot;Errore durante il caricamento della bacheca&quot;

&quot;Si è verificato un errore durante il caricamento di questa bacheca. Aggiorna la pagina e riprova; se il problema persiste, contatta il supporto con l’ID errore seguente.&quot;

#### Pagina Home

**&quot;Contrassegna come completato&quot; chiude il riquadro di riepilogo per il widget Problemi personali**

Quando si tenta di utilizzare il pulsante “Contrassegna come completato” nel riquadro di riepilogo di un problema aperto tramite il widget I miei problemi, il riquadro di riepilogo si chiude in modo imprevisto.

**Impossibile aggiungere la colonna** nelle impostazioni del widget del modello di layout

Quando si seleziona un campo da aggiungere a un widget tramite le impostazioni del widget Modello di layout, è possibile selezionare un campo ma la colonna corrispondente non viene visualizzata nel widget.

#### Attività

**Problemi con il ricalcolo della sequenza temporale**

I seguenti problemi sono stati segnalati in relazione al ricalcolo della timeline:

* Durante l’aggiornamento della durata di un’attività della timeline, il sistema impiega molto tempo per ricalcolare.
* Al termine del ricalcolo, le date possono rimanere disabilitate o diventare disabilitate, come se la timeline fosse ancora in fase di ricalcolo.

**Spese attività non visualizzate**

Dopo aver aggiunto una spesa a un&#39;attività, la spesa non viene visualizzata nelle informazioni sull&#39;attività nonostante la conferma API che è stata immessa.

+++

+++**Aggiornamento di manutenzione del venerdì 3 ottobre 2024**

### Aggiornamento di manutenzione del 3 ottobre 2024

#### Bacheche

**Schede connesse archiviate non sincronizzate**

Per risolvere i problemi di prestazioni, le schede connesse archiviate non vengono più sincronizzate. Le modifiche apportate all’attività o al problema di Workfront non vengono riportate sulle schede archiviate. Se una scheda viene ripristinata, questa verrà nuovamente sincronizzata.

#### Moduli personalizzati

**Errore di conversione del tipo di visualizzazione nei moduli personalizzati**

Nei moduli personalizzati, i campi RTF causano la visualizzazione del seguente errore:

“Errore: le conversioni dei tipi di visualizzazione tra testo e RTF non sono consentite.”

Ciò può verificarsi nelle seguenti condizioni:

* L’utente inizia a modificare i moduli, ma fa clic su Applica senza apportare alcuna modifica.
* L’utente sta creando un modulo personalizzato.

In entrambi i casi, i problemi sono causati dai campi RTF.

#### Notifiche

**Gli utenti collaboratori non ricevono notifiche e-mail**

Gli utenti con una licenza Collaboratore non ricevono le e-mail di notifica. Questo può interessare sia le e-mail di notifica istantanea che le e-mail del Riepilogo giornaliero.

#### Bozze

**Impossibile aggiungere firme elettroniche quando si utilizza SSO per la bozza**

Quando si utilizza l’SSO per accedere alla bozza, gli utenti non possono impostare una bozza per richiedere firme elettroniche.

+++

## Aggiornamenti di settembre 2024

+++**Aggiornamento di manutenzione del venerdì 26 settembre 2024**

### Aggiornamento di manutenzione del venerdì 26 settembre 2024

#### Agile

**Opzione Aggiungi all’iterazione elencata due volte durante l’assegnazione del team Scrum**

Quando si assegna un’attività o un problema a un team agile Scrum, l’opzione “Aggiungi all’iterazione” viene visualizzata due volte nel menu Altro. Questo non influisce sulla possibilità di effettuare assegnazioni al team e non viene visualizzato per i team agile non Scrum.

#### Moduli personalizzati

**Elenco dei campi dell’Editor di calcolo limitato a 200 elementi**

Nell’Editor di calcolo per i campi calcolati nei moduli personalizzati, l’elenco dei campi per un oggetto ora è limitato a 200 elementi per migliorare le prestazioni del sistema. Se conosci il nome del campo, puoi cercarlo utilizzando l’opzione Automatico invece di scorrere l’elenco.

#### Report

**Consegne dei rapporti ritardate o mancanti**

I rapporti con consegne pianificate non vengono consegnati come previsto. Possono essere in ritardo o non essere consegnati affatto.

+++

+++**Aggiornamento di manutenzione del venerdì 19 settembre 2024**

### Aggiornamento di manutenzione del venerdì 19 settembre 2024

#### Dashboard

**Selezionando il pulsante Esporta in un rapporto, si scorre verso l’inizio della pagina**

Quando si fa clic sul pulsante Esporta per un report in un dashboard, la finestra scorre fino alla parte superiore della pagina e richiede lo scorrimento verso il basso per trovare il menu delle opzioni di esportazione aperto.

+++

+++**Aggiornamento di manutenzione del venerdì 12 settembre 2024**

### Aggiornamento di manutenzione del venerdì 12 settembre 2024

#### Integrazioni

**Errore durante la creazione di una richiesta da Outlook**

Quando un utente tenta di creare una richiesta dall’integrazione di Workfront per Outlook e aggiunge un allegato, visualizza il messaggio “Si è verificato un errore. Riprova più tardi.”

La richiesta viene creata e contiene una cartella per gli allegati e-mail, ma la cartella è vuota e l’allegato non è stato aggiunto alla richiesta.

+++

+++**Aggiornamento di manutenzione del venerdì 5 settembre 2024**

### Aggiornamento di manutenzione del 5 settembre 2024

#### Gruppi

**I sottogruppi non vengono visualizzati correttamente**

Quando un utente visualizza l’elenco Gruppi nell’area Configura, nota che i sottogruppi non sono elencati correttamente nel gruppo principale. Il sottogruppo viene salvato correttamente nel gruppo principale, ma l’elenco può causare confusione.

Se l’utente apre il sottogruppo, nelle breadcrumb può visualizzare che il sottogruppo viene salvato correttamente nel gruppo principale.

#### Utenti

**Non si riesce a riattivare un utente**

Quando un utente tenta di riattivare un utente utilizzando l’opzione “Riattiva utente” nel menu Altro, può selezionare un livello di accesso, ma la modifica non viene salvata. Invece, l’utente visualizza il seguente errore:

“homeGroupID non può essere nullo”

+++

## Aggiornamenti di agosto 2024

+++**Aggiornamento di manutenzione del venerdì 29 agosto 2024**

### Aggiornamento di manutenzione dell’venerdì 29 agosto 2024

#### Moduli personalizzati

**Per impostazione predefinita, la sezione Moduli utilizza i moduli di progetto**

Quando un utente crea un modulo personalizzato e seleziona un tipo di oggetto per il modulo, il tipo di oggetto viene ignorato e il modulo viene creato come modulo personalizzato di Progetto.

#### Documenti

**Cliccando su un nome di un documento, si arriva a una pagina vuota**

Quando un utente tenta di visualizzare i dettagli del documento facendo clic sul relativo nome in un elenco di documenti, l’elenco scompare e l’utente non viene indirizzato ai dettagli del documento.

#### Pagina Home

**Il widget delle approvazioni in sospeso mostra i documenti eliminati**

Quando un utente visualizza il widget Approvazioni in sospeso su Home, i documenti mostrati sono quelli eliminati. Se l’utente fa clic su uno di questi documenti, viene visualizzata una pagina vuota.

#### Utenti

**Il campo Impostazioni internazionali e-mail del profilo utente è stato disabilitato**

Per le organizzazioni su IMS, le preferenze di lingua sono memorizzate nel profilo Adobe Experience Cloud di ciascun utente. Il campo Impostazioni internazionali e-mail nel profilo utente di Workfront è stato disabilitato (solo per le organizzazioni IMS) e una descrizione su tale campo fornisce istruzioni su come accedere alle impostazioni della lingua nel profilo di Adobe.

Questo risolvere il problema che si verifica quando un amministratore tenta di modificare le impostazioni internazionali dell’e-mail di un utente, viene ripristinata la lingua inglese.

+++

+++**Aggiornamento di manutenzione del venerdì 22 agosto 2024**

### Aggiornamento di manutenzione dell’venerdì 22 agosto 2024

#### Report

**Impossibile fare clic su un rapporto dall’area Campi personalizzati della configurazione**

Quando un utente visualizza l’area Moduli personalizzati > Campi della configurazione e la vista include il campo Rapporti nativi, i collegamenti ai rapporti non funzionano. L’utente dovrebbe essere in grado di fare clic sul nome di un rapporto ed essere portato al rapporto, ma cliccare nome del rapporto non ha alcun effetto.

+++

+++**Aggiornamento di manutenzione del venerdì 15 agosto 2024**

### Aggiornamento di manutenzione dell’venerdì 15 agosto 2024

#### Bacheche

**Problemi relativi alle schede duplicate**

Sono stati segnalati i seguenti problemi relativi alle schede duplicate in Bacheche:

* Una scheda viene visualizzata due volte. Per risolvere questo problema, aggiorna la pagina.
* Se un utente elimina una delle schede duplicate, vengono eliminate tutte le relative istanze.

#### Notifiche

**Errore durante l’impostazione delle preferenze di notifica**

Quando un utente tenta di visualizzare le preferenze di notifica, visualizza il seguente errore:

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.]”

Questo problema è stato segnalato nelle seguenti aree:

* Impostazioni di notifica su un profilo utente
* Area Notifiche degli eventi in configurazione

#### Progetti

**Il simbolo valuta non è corretto durante l’esportazione**

Quando un utente esporta un problema, il simbolo di valuta nell’esportazione non corrisponde alla valuta impostata nel progetto o nel problema.

#### Bozze

**I markup di bozza non sono accurati**

I markup della bozza non sono allineati sulle stampe PDF ricevute tramite e-mail dalla funzione Stampa bozza.


+++

+++**Aggiornamento di manutenzione del venerdì 8 agosto 2024**

### Aggiornamento di manutenzione dell’8 agosto 2024

#### Bacheche

**La scheda non include le attività secondarie**

Quando un utente visualizza una scheda per un’attività che è un’attività principale, le attività secondarie di tale attività principale non vengono visualizzate sulla scheda. Invece, la scheda mostra che ci sono 0 attività secondarie.

### Report

**Consegne dei rapporti ritardate o mancanti**

I rapporti con consegne pianificate non vengono consegnati come previsto. Possono essere in ritardo o non essere consegnati affatto.

#### Configura

**“Accedi come” porta a una schermata vuota**

Quando un amministratore effettua l’accesso come un altro utente, invece di visualizzare l’account dell’utente, visualizza una schermata vuota.

+++

+++**Aggiornamento di manutenzione del venerdì 1 agosto 2024**

### Aggiornamento di manutenzione del 1° agosto 2024

#### Documenti

**Impossibile creare la vista per l’elenco dei documenti**

Quando un utente tenta di creare una nuova vista in un elenco dei documenti, la schermata diventa vuota e l’utente non può crearla.

Le viste esistenti funzionano come previsto.

#### Integrazioni

**Problemi relativi all’integrazione con Dropbox**

I seguenti problemi sono stati riscontrati in relazione all’integrazione con Dropbox:

* Quando un utente prova a cercare un file nel selettore di file di Dropbox, visualizza un messaggio di errore di autorizzazione e il file desiderato non viene recuperato dal selettore.
* Quando un utente cerca di aprire una cartella collegata, visualizza un errore che indica che in Dropbox i file o la cartella non esistono più.

Questi problemi sono dovuti a problemi con Dropbox, non con Workfront.

+++

## Aggiornamenti di luglio 2024

+++**Aggiornamento di manutenzione del venerdì 25 luglio 2024**

### Aggiornamento di manutenzione del venerdì 25 luglio 2024

#### Moduli personalizzati

**Il menu a discesa si chiude quando si selezionano più valori**

Quando un utente cerca di selezionare più valori in un campo modulo personalizzato, il menu a discesa si chiude dopo aver selezionato il primo valore.

Ciò si verifica quando il campo è associato a una logica di visualizzazione nel modulo personalizzato.

#### Notifiche

**Le miniature non sono visibili nelle notifiche e-mail**

Quando un utente visualizza una notifica e-mail relativa all’approvazione di un documento, la miniatura del documento non è visibile nell’e-mail.

Questo problema è stato segnalato in Gmail.

+++

+++**Aggiornamento di manutenzione del venerdì 18 luglio 2024**

### Aggiornamento di manutenzione del venerdì 18 luglio 2024

#### Agile

**Lo storyboard diventa vuoto quando si aggiunge un’attività secondaria**

Quando un utente tenta di aggiungere un’attività secondaria a uno storyboard mentre è selezionato un filtro, la schermata diventa vuota e l’utente non può aggiungerla.

#### Pagina Home

**Impossibile aprire gli elementi dal [!UICONTROL Calendario della Home] o dall’[!UICONTROL Elenco lavori]**

Quando un utente cerca di aprire un elemento di lavoro o una bozza dal proprio [!UICONTROL calendario della Home] o dall’[!UICONTROL Elenco lavori della Home], l’elemento non si apre.

**La Home dell’amministratore viene visualizzata quando si accede come altro utente**

Quando un amministratore effettua l’accesso come altro utente e visualizza la Home dell’utente, viene visualizzata la Home dell’amministratore.

#### Bozze

**La chiusura di una bozza porta alla pagina Documenti del prodotto**

Quando un utente visualizza una bozza e la chiude, viene indirizzato alla pagina Documenti del progetto e non a quella da cui la bozza è stata aperta.

#### Workfront

**La terminologia personalizzata non viene applicata**

La terminologia personalizzata impostata nel modello di layout non viene visualizzata in alcune aree di Workfront. Viene invece visualizzata la terminologia non personalizzata predefinita.

Questo problema è stato segnalato nelle seguenti aree:

* Schede del menu
* Intestazioni pagina
* Descrizioni in cui sono elencati i progetti


+++

+++**Aggiornamento di manutenzione del venerdì 11 luglio 2024**

### Aggiornamento di manutenzione dell’11 luglio 2024

#### Problemi

**Errore quando effettuando l’assegnazione avanzata di un problema**

Quando un utente cerca di effettuare un’assegnazione avanzata di un problema in Workfront, il problema non viene assegnato e l’utente visualizza il messaggio di errore seguente:

“[!UICONTROL APIModel INTERNAL non supporta la durata del campo (OpTask)]”

#### Report

**Errore Ops quando si configurano le impostazioni della matrice nel report delle ore**

Quando un utente tenta di configurare le impostazioni della matrice in un report delle ore, non le può configurare e viene visualizzato il seguente errore:

* “[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.]”


+++

+++**Aggiornamento di manutenzione del venerdì 4 luglio 2024**

### Aggiornamento di manutenzione del 4 luglio 2024

#### Pagina Home

**Il menu a tre punti non ha alcun effetto**

Quando un utente fa clic sul menu a tre punti Altro nell’elenco lavori della Home precedente, non viene attivata alcuna azione.

#### Report

**“Nessun dato da visualizzare” quando il nome del raggruppamento ha una barra dritta o rovesciata**

Quando un utente visualizza un grafico in un rapporto e fa clic su un raggruppamento nel grafico, che presenta una / o \ nel nome, i dettagli aperti non mostrano gli elementi nel raggruppamento e l’utente visualizza il messaggio “Nessun dato da visualizzare”.

#### Attività

**La mansione non scompare dall’elenco quando l’utente viene assegnato all’attività**

Quando una mansione viene assegnata a un’attività e tale attività assegnata a un utente che dispone della mansione, quest’ultima non scompare dall’elenco delle assegnazioni.


+++

## Aggiornamenti di giugno 2024

+++**Aggiornamento di manutenzione il venerdì 27 giugno 2024**

### Aggiornamento di manutenzione il venerdì 27 giugno 2024

#### Bacheche

**Solo il proprietario della bacheca può aggiornare i filtri di configurazione**

Per motivi di sicurezza, solo il proprietario di una bacheca può modificarne i filtri nel pannello Configura.

#### Report

**Il rapporto non viene caricato quando la valuta predefinita è USD**

Quando un utente cerca di visualizzare un rapporto la cui valuta predefinita è USD, il rapporto non viene caricato.

#### Aggiornamenti

**Il collegamento copiato non viene incollato correttamente**

Se un utente copia un collegamento da un aggiornamento facendo clic con il pulsante destro del mouse e seleziona “[!UICONTROL Copia indirizzo collegamento]”, quindi lo incolla in un aggiornamento, il collegamento non viene incollato correttamente. Solo la prima parte del collegamento è un collegamento e il resto dell’URL viene ignorato.

Copiare il collegamento utilizzando un metodo diverso da “[!UICONTROL Copia indirizzo collegamento]” consente di incollare il collegamento come previsto.

+++

+++**Aggiornamento di manutenzione il venerdì 20 giugno 2024**

### Aggiornamento di manutenzione il venerdì 20 giugno 2024

#### Navigazione

**Il pulsante Indietro non torna alla pagina precedente**

Quando un utente in Workfront fa clic sul pulsante Indietro del browser, può verificarsi una delle seguenti situazioni.

* Il nome della scheda del browser cambia, ma la pagina non cambia. Se si fa nuovamente clic sul pulsante Indietro, il problema potrebbe risolversi.
* L’utente viene indirizzato alla pagina di destinazione del browser.

#### Bozze

**Impossibile chiudere il visualizzatore bozza**

Quando si visualizza una bozza nel visualizzatore di bozze e si tenta di chiuderla facendo clic sul pulsante X in alto a destra, la bozza non si chiude.

+++

+++**Aggiornamento di manutenzione il venerdì 13 giugno 2024**

### **Aggiornamento di manutenzione il venerdì 13 giugno 2024**

#### Gruppi

**Impossibile aggiungere un sottogruppo**

Quando un utente tenta di aggiungere un sottogruppo esistente a un gruppo, il pulsante Salva non funziona e il sottogruppo non viene aggiunto.

+++

+++ **Aggiornamento di manutenzione il 6 giugno 2024**

### Aggiornamento di manutenzione il 6 giugno 2024

#### Moduli personalizzati

**Limitazione dei campi nativi nel designer di moduli**

Nei moduli personalizzati creati nel designer di moduli ora sono supportati più campi nativi. In precedenza il limite era un campo nativo per modulo.

+++

## Aggiornamenti di maggio 2024

+++ **Aggiornamento di manutenzione il 30 maggio 2024**

### Aggiornamento di manutenzione il 30 maggio 2024

#### Moduli personalizzati

Errore durante la modifica dei campi di testo descrittivo

Quando un utente tenta di modificare il testo descrittivo in un modulo personalizzato, il testo non viene salvato e viene visualizzato il seguente errore:

“Un valore chiave duplicato viola il vincolo di univocità”

Questo problema è stato segnalato per il generatore di moduli precedente.

#### Aggiornamenti

**Quando si copia e incolla una menzione, l’utente menzionato non riceve una notifica**

Quando un utente copia un commento che include una menzione in formato @ e lo incolla nell’area Aggiornamenti di un altro oggetto, l’utente a cui si fa riferimento non riceve alcuna notifica del commento incollato.

+++

+++ **Aggiornamento di manutenzione il 23 maggio 2024**

### Aggiornamento di manutenzione il 23 maggio 2024

#### Report

Quando un utente visualizza un rapporto e fa clic sul pulsante Indietro del browser, può verificarsi una delle seguenti situazioni:

* L’utente rimane nella pagina Report.
* L’utente viene indirizzato alla pagina di destinazione del browser.
* L’utente viene indirizzato alla pagina di accesso.

Questo problema è stato segnalato con il browser Chrome.

#### Aggiornamenti

**L’utente taggato non può vedere chi ha messo il tag**

Quando un utente viene taggato all’interno di un aggiornamento, non può vedere chi gli ha messo il tag. Ciò si verifica quando l’impostazione “Le persone in altre società dovranno solo visualizzare gli utenti da...” è impostata su “La loro società”.

**L’assegnazione di tag a un utente con @ nel pannello Riepilogo non funziona**

Quando un utente tenta di assegnare un tag a un altro utente utilizzando @ nella sezione Aggiornamenti di un pannello Riepilogo, fare clic sul nome dell’utente nel menu a discesa non ha alcun effetto. Il tentativo di assegnare un tag all’utente una seconda volta funziona come previsto.

+++

+++**Aggiornamento di manutenzione il 16 maggio 2024**

### Aggiornamento di manutenzione il 16 maggio 2024

#### Configura

**Stati dei problemi predefiniti mancanti da alcuni tipi di problemi in Configurazione**

Quando un utente visualizza gli stati dei problemi in Configurazione, nota che in alcuni tipi di problemi mancano gli stati predefiniti (Nuovo, In corso e Completato). Gli stati predefiniti non dispongono della possibilità di modificare il tipo di problema, pertanto l’utente non può configurare nuovamente gli stati da visualizzare per i tipi di problema interessati.

#### Utenti

**Impossibile eliminare gli utenti**

Quando un utente tenta di eliminare gli utenti, l’operazione non riesce. Questo problema è stato segnalato nelle organizzazioni che sono migrate ad Adobe Admin Console.

+++

+++**Aggiornamento di manutenzione il 9 maggio 2024**

### Aggiornamento di manutenzione il 9 maggio 2024

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione il 2 maggio 2024**

### Aggiornamento di manutenzione il 2 maggio 2024

#### Registrazione dell’ora

**Impossibile modificare le ore su attività o problem**

Quando un utente cerca di modificare le ore su un’attività o un problema, le modifiche non vengono salvate.

+++

## Aggiornamenti di aprile 2024

+++**Aggiornamento di manutenzione il 25 aprile 2024**

### Aggiornamento di manutenzione il 25 aprile 2024

#### Aggiornamenti

**Gli elenchi numerati non vengono numerati correttamente**

Quando un utente invia un commento che include un elenco numerato, quest’ultimo mostra una numerazione errata nell’aggiornamento.

Questo problema è stato segnalato nella nuova esperienza di commento.

**Il testo non viene mantenuto quando si cambia pagina e si torna al commento**

Quando un utente scrive un commento che include un @mention, quindi cambia pagina da e torna al commento prima di inviarlo, qualsiasi testo immesso dopo il @mention non viene incluso nella bozza del commento.

Questo problema è stato segnalato nella nuova esperienza di commento.

+++

+++**Aggiornamento di manutenzione il 18 aprile 2024**

### Aggiornamento di manutenzione il 18 aprile 2024

#### Agile

**Nelle schede Kanban non vengono visualizzati i campi personalizzati**

Quando un utente visualizza una bacheca Kanban configurata per includere campi personalizzati, tali campi personalizzati potrebbero non essere visualizzati.

#### Calendari

**Errore durante l’aggiornamento del calendario**

Quando un utente visualizza un calendario e aggiorna la pagina, viene visualizzato un errore “Ops”. I dati nel calendario vengono visualizzati come previsto, ma possono essere oscurati dal messaggio di errore.

#### Moduli personalizzati

**I campi di ricerca esterni non restituiscono risultati**

Quando un campo di ricerca esterno fa riferimento a un campo a selezione multipla in cui è selezionato un solo valore, il campo non restituisce il valore.

Ad esempio, se un campo di ricerca esterno fa riferimento a un campo a selezione multipla in cui sono selezionati sia i valori “rosso” che quelli “blu”, il campo funziona come previsto. Se nel campo è selezionato solo “rosso”, il campo di ricerca esterno non restituisce alcun valore.

#### Progetti

**Non si riesce a convertire il problema in progetto se è allegata una bozza web**

Quando a un problema è allegata una bozza web (una bozza URL che utilizza un collegamento di un provider di documenti esterno come SharePoint) e un utente tenta di convertire tale problema in un progetto, la conversione non riesce e il progetto non viene creato. L’utente visualizza il seguente errore:

“Si è verificato un problema durante la copia del file (GUID file). Rimuovi il file o contatta l’assistenza e riprova.”

+++

+++**Aggiornamento di manutenzione il 11 aprile 2024**

### Aggiornamento di manutenzione il 11 aprile 2024

#### Ricerca

**Impossibile modificare dalla ricerca**

Quando un utente utilizza la Ricerca avanzata e tenta di modificare o modificare in blocco i risultati della ricerca, l’icona Modifica non risponde.

#### Aggiornamenti

**L’anteprima dell’immagine negli aggiornamenti è sfocata**

Quando un utente visualizza gli aggiornamenti e fa clic con la lente di ingrandimento su un’immagine per visualizzarla in anteprima, l’anteprima che si apre è estremamente sfocata e pixelata.

Se l’utente scarica l’immagine, questa viene visualizzata alla risoluzione prevista.

**Messaggio “[!UICONTROL Impossibile pubblicare il commento]” quando si risponde**

Quando un utente tanta di rispondere a un messaggio nella nuova esperienza di commento, la risposta non viene salvata e l’utente visualizza il seguente messaggio:

“[!UICONTROL Impossibile pubblicare il commento in questo momento. Riprova tra qualche istante.]”

+++

+++**Aggiornamento di manutenzione il 4 aprile 2024**

### Aggiornamento di manutenzione il 4 aprile 2024

#### Ricerca

**Impossibile modificare dalla ricerca**

Quando un utente utilizza la Ricerca avanzata e tenta di modificare o modificare in blocco i risultati della ricerca, l’icona Modifica non risponde.

#### Aggiornamenti

**L’anteprima dell’immagine negli aggiornamenti è sfocata**

Quando un utente visualizza gli aggiornamenti e fa clic con la lente di ingrandimento su un’immagine per visualizzarla in anteprima, l’anteprima che si apre è estremamente sfocata e pixelata.

Se l’utente scarica l’immagine, questa viene visualizzata alla risoluzione prevista.

**Messaggio “[!UICONTROL Impossibile pubblicare il commento]” quando si risponde**

Quando un utente tanta di rispondere a un messaggio nella nuova esperienza di commento, la risposta non viene salvata e l’utente visualizza il seguente messaggio:

“[!UICONTROL Impossibile pubblicare il commento in questo momento. Riprova tra qualche istante.]”

+++

+++**Aggiornamento di manutenzione il 4 aprile 2024**

### Aggiornamento di manutenzione il 4 aprile 2024

#### Integrazioni

**Documenti non allegati durante la creazione di una richiesta da[!DNL Outlook]**

Quando un utente crea una richiesta da [!DNL Outlook], i documenti allegati all’e-mail non vengono allegati alla richiesta.

Questo problema è stato segnalato per le seguenti tipologie di allegati:

XLS
PDF

#### Registrazione dell’ora

**Registrazione di ore: l’utente non può registrare l’ora per il giorno corrente**

Quando un utente cerca di registrare l’ora nell’area Aggiornamenti, il giorno corrente è disattivato e l’utente non può registrare l’ora per il giorno corrente.

#### Aggiornamenti

<!--no article-->

**Errore durante la visualizzazione dei commenti**

Quando un utente tenta di visualizzare i commenti nella nuova esperienza di commento, l’operazione ha esito negativo e viene visualizzato il seguente errore:

“Si è verificato un errore. Riprova più tardi.”

L’esperienza di commento precedente funziona come previsto.

+++

## Aggiornamenti di marzo 2024

+++**Aggiornamento di manutenzione il 28 marzo 2024**

### Aggiornamento di manutenzione il 28 marzo 2024

#### Integrazioni

**Documenti non allegati durante la creazione di una richiesta da[!DNL Outlook]**

Quando un utente crea una richiesta da [!DNL Outlook], i documenti allegati all’e-mail non vengono allegati alla richiesta.

Questo problema è stato segnalato per le seguenti tipologie di allegati:

XLS
PDF

#### Bozze

**Le bozze rimangono nel widget Le mie approvazioni**

Una bozza che dovrebbe scomparire dal widget Le mie approvazioni rimane sul widget. Ciò può verificarsi quando più utenti prendono decisioni su una bozza contemporaneamente oppure un utente prende una decisione e la modifica rapidamente.

#### Gestione risorse

**Discrepanza nelle ore preventivate**

Le ore preventivate visualizzate in una delle seguenti aree potrebbero non corrispondere a quelle visualizzate in un’altra area tra queste:

* Caso di business
* Report
* Strumento Budget di risorse

#### Attività

**La descrizione del predecessore non visualizza il nome dell’attività**

Quando un utente visualizza un elenco di attività e passa il puntatore sull’icona di un predecessore per ottenere ulteriori informazioni, nella descrizione non viene visualizzato il nome dell’attività predecessore.

#### Aggiornamenti

**I commenti al documento non vengono visualizzati negli aggiornamenti dell’oggetto principale**

Quando un utente aggiunge un commento a un documento, tale commento non viene visualizzato immediatamente nell’area Aggiornamenti dell’oggetto principale del documento.

Questo problema è stato segnalato nella nuova esperienza di commento. I commenti vengono visualizzati come previsto nell’esperienza di commento precedente.

**Assegnare tag a un utente non ha alcun effetto**

Quando un utente viene taggato all’interno di un commento, quest’ultimo non è visibile all’utente taggato. Inoltre, l’utente taggato non riceve alcuna notifica relativa al commento, né tramite e-mail e né tramite una notifica in-app.

Questo problema è stato segnalato nell’esperienza di commento precedente.

+++

+++**Workfront Fusion - Aggiornamento di manutenzione il 28 marzo 2024**

### Workfront Fusion - Aggiornamento di manutenzione il 28 marzo 2024

**RuntimeError con risposta 200 dal modulo Workfront**

Un modulo Workfront può restituire una risposta `RuntimeError [200]`. Il valore 200 implica una risposta corretta, ma l’errore mostra che la richiesta non è riuscita.

Ciò può verificarsi se la risposta è estremamente lunga. I dati vengono restituiti a Fusion, ma non possono essere elaborati.

+++

+++**Aggiornamento di manutenzione il 21 marzo 2024**

### Aggiornamento di manutenzione il 21 marzo 2024

#### Aggiornamenti

**Spazi di grandi dimensioni tra le linee**

Quando un utente digita un aggiornamento con più righe utilizzando il tasto Invio o A capo, o incolla più righe in un aggiornamento, l’aggiornamento viene visualizzato come previsto. Tuttavia, se un utente visualizza tale aggiornamento in un rapporto, ci sono ampi spazi tra le righe.

Questo problema è stato segnalato nella nuova esperienza di commento.

**Assegnare tag a un utente con @ non ha alcun effetto**

Quando un utente assegna un tag a un altro utente inserendo @ in un commento, l’utente non viene aggiunto all’area utenti taggati e non riceve una notifica relativa al commento.

Questa correzione si applica solo alla nuova esperienza di commento.

+++

+++**Aggiornamento di manutenzione il 14 marzo 2024**

### Aggiornamento di manutenzione il 14 marzo 2024

#### Bozze

**Alle bozze create da documenti collegati non è applicato il modello di bozza**

Quando un utente crea una bozza da un documento collegato, il modello di bozza non viene applicato correttamente e potrebbero mancare informazioni come il flusso di lavoro.

Questo vale anche per le bozze create tramite l’API e tramite Workfront Fusion.

#### Utenti

**Livelli di accesso inferiori non disponibili durante la creazione di un utente**

Quando un utente crea un altro utente, al nuovo utente è disponibile solo il livello di accesso del primo utente. Tutti i livelli di accesso con autorizzazioni inferiori rispetto a quelli dell’utente che crea devono essere disponibili per l’assegnazione al nuovo utente.

+++

+++**Aggiornamento di manutenzione il 7 marzo 2024**

### Aggiornamento di manutenzione il 7 marzo 2024

#### Bacheche

**Errore 400 durante l’aggiunta di un’attività a una bacheca**

Quando un utente visualizza un progetto e tenta di aggiungere un’attività a una bacheca, questa non viene aggiunta e l’utente visualizza il seguente errore:

Errore: “400: undefined /boards-service/graphql”

#### Pagina Home

**Errore durante la modifica in linea di un’attività nel widget Le mie attività**

Quando un utente cerca di modificare in linea un’attività nel widget Le mie attività, viene visualizzato il seguente errore:

“Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova ad aggiornare la pagina del browser.”


#### Bilanciatore dei carichi di lavoro

**Le ore pianificate non vengono aggiornate nel Bilanciatore dei carichi di lavoro**

“Quando le ore pianificate su un progetto vengono aggiornate, non vengono aggiornate nel Bilanciatore dei carichi di lavoro. Ciò può verificarsi anche se la modifica viene riflessa accuratamente nel progetto.

+++

+++**Aggiornamento di manutenzione di Workfront Fusion il 7 marzo 2024

**Workfront Proof > timeout del modulo Watch Proof**

Gli scenari che utilizzano Workfront Proof > modulo Watch Proof possono disattivarsi a causa del timeout del modulo Watch Proof.

+++

## Aggiornamenti di febbraio 2024

+++**Aggiornamento di manutenzione il 29 febbraio 2024**

### Aggiornamento di manutenzione il 29 febbraio 2024

#### Aggiornamenti

**Aggiornamenti: la schermata diventa vuota quando si risponde a un utente di un’altra azienda**

Quando un utente cerca di rispondere a un commento di un utente di un’altra azienda, la schermata diventa vuota.

Questo avviene perché l’utente non dispone dell’autorizzazione per visualizzare gli utenti di altre aziende.

+++

+++**Aggiornamento di manutenzione il 22 febbraio 2024**

### Aggiornamento di manutenzione il 22 febbraio 2024

#### Pagina Home

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

+++**Aggiornamento di manutenzione il 15 febbraio 2024**

### Aggiornamento di manutenzione il 15 febbraio 2024

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

+++**Aggiornamento di manutenzione il 8 febbraio 2024**

### Aggiornamento di manutenzione il 8 febbraio 2024

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

+++**Aggiornamento di manutenzione il 1 febbraio 2024**

### Aggiornamento di manutenzione il 1° febbraio 2024

#### Accedi

**Gli utenti che utilizzano SSO non vengono reindirizzati alla posizione originale durante l’accesso**

Quando un utente si trova su una pagina in [!DNL Workfront] e accede con SSO; una volta completato l’accesso, viene indirizzato alla pagina [!UICONTROL Home] invece che a quella in cui si trovava prima dell’accesso.

#### Modelli

**Errore durante la copia dei modelli**

Quando un utente tenta di copiare un modello nuovo o esistente, l’operazione ha esito negativo e l’utente visualizza il seguente messaggio di errore:

“[!UICONTROL L’ID non può essere nullo]”

+++

## Aggiornamenti di gennaio 2024

+++**Aggiornamento di manutenzione (Hot Fix) il 30 gennaio 2024**

### Aggiornamento di manutenzione (Hot Fix) il 30 gennaio 2024

#### Report

**Il campo API esterna non mostra tutti i valori disponibili negli elenchi e nei rapporti**

In precedenza, gli utenti potevano visualizzare il valore selezionato (e modificarlo) per un campo di ricerca esterno negli elenchi e nei rapporti, ma non visualizzavano il menu a discesa con le opzioni provenienti dall’API.

Ora, quando un campo personalizzato di ricerca esterna viene utilizzato in un elenco o in un rapporto, è disponibile il menu a discesa con tutte le opzioni dell’API esterna.

+++

+++**Aggiornamento di manutenzione il 25 gennaio 2024**

### Aggiornamento di manutenzione il 25 gennaio 2024

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

+++**Aggiornamento di manutenzione il 18 gennaio 2024**

### Aggiornamento di manutenzione il 18 gennaio 2024

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

#### Moduli personalizzati

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

+++**Aggiornamento di manutenzione il 11 gennaio 2024**

### Aggiornamento di manutenzione il 11 gennaio 2024

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
