---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: b8552cb4de3b5372b5b18d5891b490f22b9d803d
workflow-type: tm+mt
source-wordcount: '3912'
ht-degree: 99%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2023.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. L’assistenza [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, vedi [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di giugno 2023

+++**Aggiornamento di manutenzione dell’15 giugno 2023**

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione dell’8 giugno 2023**

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione dell’8 giugno 2023**

[!DNL Fusion] ha implementato una correzione che impedisce la rimozione delle connessioni di un utente quando questo viene rimosso o disattivato in [!UICONTROL Adobe Admin Console].

[!DNL Fusion] gli amministratori del team sono ancora in grado di rimuovere le connessioni non necessarie [!UICONTROL Connessioni] pagina in [!DNL Fusion].

+++

+++**Aggiornamento di manutenzione del 1 giugno 2023**

**Nessun messaggio di errore quando si cambia l’ordine di un’attività nello stato [!UICONTROL Approvazione in sospeso]**

_Attività_

Quando un utente tenta di riordinare, in un elenco di attività, un’attività in stato [!UICONTROL Approvazione in sospeso], questa sembra venire spostata nell’elenco delle attività. Dopo l’aggiornamento, l’utente vede che l’elemento non è stato spostato. L’elemento non può essere spostato perché è in stato [!UICONTROL Approvazione in sospeso], ma non è presente alcun messaggio che dà tale informazione all’utente e questo potrebbe causare confusione.

**Nessun messaggio di errore quando si sposta un’attività predecessore sotto un’attività dipendente**

_Attività_

Quando un utente tenta di riordinare, in un elenco di attività, un’attività in stato [!UICONTROL Approvazione in sospeso], questa sembra venire spostata nell’elenco delle attività. Dopo l’aggiornamento, l’utente vede che l’elemento non è stato spostato. L’elemento non può essere spostato perché un’attività predecessore non può essere spostata sotto un’attività di cui è predecessore; tuttavia l’utente non riceve alcun messaggio in merito e questo potrebbe creare confusione.

+++

## Aggiornamenti di maggio 2023

+++**Aggiornamento di manutenzione del 25 maggio 2023**

La bacheca **[!UICONTROL Kanban] rimane vuota durante la modifica delle schede**

_Agile_

Quando un utente cambia qualcosa in una scheda nella bacheca [!UICONTROL Kanban], la bacheca [!UICONTROL Kanban] diventa vuota invece di aggiornarsi con la modifica. Se l’utente ricarica la pagina manualmente, la bacheca [!UICONTROL Kanban] viene visualizzata con la modifica corretta.

Questo problema è stato segnalato nelle seguenti situazioni:

* Modifica di una scheda
* Spostamento di una scheda


+++

+++**Aggiornamento di manutenzione del 22 maggio 2023**

**Impossibile regolare la dimensione di un testo descrittivo**

_Moduli personalizzati_

Quando il Designer dei moduli personalizzati è stato rilasciato in versione beta, la la funzionalità per regolare le dimensioni del testo descrittivo non era disponibile. Questo problema è stato risolto e gli utenti possono ora regolare le dimensioni del testo descrittivo.

+++

+++**Aggiornamento di manutenzione del 18 maggio 2023**

**Se si ordina per un campo personalizzato, il rapporto non viene ordinato correttamente**

_Rapporti_
Quando un utente esegue un rapporto di attività, il rapporto sembra venire ordinato in modo corretto durante il caricamento, ma al termine dell’operazione l’utente visualizza che il rapporto non è ordinato correttamente.

Questo sembra accadere se sono soddisfatte tutte le seguenti circostanze:

* Il rapporto è un rapporto di attività
* Il rapporto è ordinato in base a un campo personalizzato
* Al rapporto è applicato un raggruppamento

+++

+++**Aggiornamento di manutenzione dell’11 maggio 2023**

**Impossibile cambiare versione della bozza durante la visualizzazione della bozza**

_Bozze_

Quando un utente visualizza una bozza nel [!UICONTROL Proofing Viewer] e passa a un’altra versione, il menu a discesa della versione viene disattivato e l&#39;utente non può tornare alla versione originale che stava visualizzando, oppure a un’altra versione della bozza.

**[!DNL Workfront]Timeout della ricerca**

_Ricerca_

Timeout della ricerca [!DNL Workfront]. La ricerca può restituire alcuni risultati o nessuno.

Questo problema influisce anche sulla funzionalità del modulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Ricerca].

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione dell’11 maggio 2023**

**Errori di timeout in[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Quando uno scenario è in esecuzione, potrebbe presentare un errore di timeout. Le informazioni del modulo con l’errore non raggiungono la relativa destinazione.

**[!DNL Workfront]Timeout della ricerca**

_Ricerca_

Timeout della ricerca [!DNL Workfront]. La ricerca può restituire alcuni risultati o nessuno.

Questo problema influisce anche sulla funzionalità del modulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Ricerca].

+++

+++**Aggiornamento di manutenzione del 9 maggio 2023**

**Filtri salvati disponibili nella colonna di acquisizione della bacheca**

_Bacheche_

Ora si può utilizzare l’attività Workfront esistente e distribuire filtri durante la configurazione della colonna di acquisizione per una bacheca. Tuttavia, i filtri delle colonne di acquisizione esistenti ora sono di sola lettura nel pannello di configurazione. I filtri esistenti vengono comunque applicati alla colonna di acquisizione, ma, se si desidera modificarli, è necessario ricrearli.

+++

+++**Aggiornamento di manutenzione del 4 maggio 2023**

**Impossibile selezionare il modello da [!UICONTROL Modelli preferiti]**

_Modelli_

Quando un utente tenta di selezionare un modello dal menu Azioni (tre punti), l’elenco dei modelli scompare se l’utente sposta il mouse sull’elenco e non è possibile selezionare un modello. Questo perché la barra di scorrimento si trova tra il menu e l’elenco dei modelli, e il mouse si concentra sulla barra di scorrimento mentre si sposta all’elenco dei modelli.

+++

## Aggiornamenti di aprile 2023

+++**Aggiornamento di manutenzione del 27 aprile 2023**

**Impossibile passare da una bozza all’altra in [!UICONTROL Proofing Viewer]**

_Bozze_

Quando un utente visualizza una bozza in [!UICONTROL Proofing Viewer] e passa a un’altra bozza, il pulsante Cambia bozza non risponde. L’utente non può tornare alla bozza originariamente visualizzata o a un’altra bozza.

**Modificare le immagini allegate durante la modifica di un commento**

_Aggiornamenti_

È ora possibile modificare l’immagine allegata a un commento mentre lo si modifica. Questa funzione è disponibile nella sezione Aggiornamenti per gli obiettivi Workfront e in quella dei problemi quando si abilita l’esperienza dei commenti in Beta.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione del 25 aprile 2023**

I collegamenti della Guida in-app **[!DNL Fusion]non conducono a pagine di aiuto specifiche**

_[!DNL Workfront Fusion]_

Quando un utente visualizza una bozza in [!UICONTROL Proofing Viewer] e passa a un’altra bozza, il pulsante Cambia bozza non risponde. L’utente non può tornare alla bozza originariamente visualizzata o a un’altra bozza.

+++

+++**Aggiornamento di manutenzione del 20 aprile 2023**

**Problemi nei campi a discesa personalizzati**

_Moduli personalizzati_

I campi a discesa personalizzati abilitati come campi con selezione multipla possono presentare i seguenti problemi:

* Il pulsante “+[!UICONTROL Aggiungi]” non è presente quando il modulo non è in modalità di modifica.
* I campi privi di valori presentano un’opzione “—[!UICONTROL nessuna etichetta]—”.

**Impossibile utilizzare lo strumento Polilinea quando si crea un commento su una bozza**

_Bozze_

Quando un utente visualizza una bozza nel Proofing Viewer e tenta di creare un commento utilizzando lo strumento Polilinea, lo strumento non contrassegna la bozza.

**La casella delle opzioni di testo mostra “textAnnotations”**

_Bozze_

Quando un utente visualizza una bozza, inizia ad aggiungere un commento e apre lo strumento Testo, accanto alle opzioni dello strumento viene visualizzata la dicitura “textAnnotation”. Lo strumento Testo continua a funzionare come previsto e “textAnnotation” scompare dopo la pubblicazione del commento.

**Mantieni le immagini come bozza quando ti sposti da un aggiornamento per gli obiettivi e per i problemi nell’esperienza beta dei commenti**

>[!NOTE]
>
>Questa funzione è stata rilasciata in anteprima il 19 aprile 2023 e in produzione il 20 aprile 2023.

_Aggiornamenti_

Ora, quando ti sposti dalla pagina Aggiornamenti mentre stai componendo un messaggio a cui è stata allegata un’immagine, il messaggio e l’immagine vengono conservati quando torni indietro. Prima di questo aggiornamento, il commento non inviato veniva mantenuto mentre l’immagine veniva eliminata. Questa funzione è disponibile nella sezione Aggiornamenti per gli obiettivi e in quella dei problemi quando si abilita l’esperienza beta dei commenti.

**Aggiornamenti in tempo reale e commenti eliminati nella sezione Aggiornamenti**

>[!NOTE]
>
>Questa funzione è stata rilasciata in anteprima il 19 aprile 2023 e in produzione il 20 aprile 2023.

_Aggiornamenti_

Ora, quando un utente aggiunge un commento o una risposta oppure elimina un commento dall’area Aggiornamenti, è possibile visualizzare il nuovo commento o un’indicazione che un commento è stato rimosso in tempo reale, senza alcun ritardo. Questa funzione è disponibile nella sezione Aggiornamenti per gli obiettivi e in quella dei problemi quando si abilita l’esperienza beta dei commenti.

**Livello di accesso modificato dal sistema senza record della modifica**

_Utenti_

Il livello di accesso di un utente può essere modificato in modo imprevedibile dal sistema. In questo caso, non vi è alcun aggiornamento visibile e la modifica non viene visualizzata nel registro di controllo.

+++

+++**Aggiornamento di manutenzione del 17 aprile 2023**

**Mostra nuovi commenti al di fuori dell’area visibile della schermata nella sezione [!UICONTROL Aggiornamenti] dei problemi (nuova esperienza beta dei commenti) e degli [!UICONTROL obiettivi]**

_Aggiornamenti_

È stato aggiunto un banner di notifica per la sezione [!UICONTROL Aggiornamenti] per informare gli utenti in caso di commenti più recenti su un elemento che potrebbe essere al di fuori dell’area visibile sulla schermata. Questo aggiornamento è attualmente disponibile nella sezione [!UICONTROL Aggiornamenti] degli obiettivi e in quella dei problemi quando la nuova esperienza beta dei commenti è stata abilitata per i problemi.

+++

+++**Aggiornamento di manutenzione del 13 aprile 2023**

**I filtri non vengono applicati all’elenco delle richieste**

_Richieste_

Quando un utente visualizza un elenco di richieste a cui è stato applicato un filtro, l’elenco include richieste che il filtro dovrebbe escludere.

**Impossibile selezionare [!UICONTROL Tipo di ora predefinito] o [!UICONTROL Tipi di ora disponibili]**

_Utenti_

Quando un amministratore sta modificando un utente e tenta di selezionare un [!UICONTROL Tipo di ora predefinito] o [!UICONTROL Tipo di ora disponibile], i menu a discesa per tali campi sono disattivati e non si possono effettuare selezioni.

+++

+++**Aggiornamento di manutenzione del 6 aprile 2023**

**I menu a discesa non si aprono quando un utente viene aggiunto a una bozza**

_Bozze_

Quando un utente aggiunge un altro utente a una bozza nel [!UICONTROL Proofing Viewer], è impossibile aprire i menu a discesa “[!UICONTROL Ruolo bozza]” e “[!UICONTROL Avvisi e-mail]”. L’utente non può assegnare un ruolo bozza o un avviso e-mail. Questo può verificarsi quando si aggiunge un utente tramite un commento o quando si condivide la bozza con l’utente.

+++

## Aggiornamenti di marzo 2023

+++**Aggiornamento di manutenzione del 30 marzo 2023**

**Impossibile cambiare versione della bozza durante la visualizzazione della bozza**

_Bozze_

Quando un utente visualizza una bozza nel [!UICONTROL Proofing Viewer] e passa a un’altra versione, il menu a discesa della versione viene disattivato e l&#39;utente non può tornare alla versione originale che stava visualizzando, oppure a un’altra versione della bozza.

**Errore 504 durante l’esportazione dei rapporti**

_Rapporti_

Quando un utente tenta di esportare un rapporto con un numero elevato di elementi, visualizzerà un errore 504 e non potrà esportare il rapporto.

**L’aggiornamento effettuato per conto di un utente viene visualizzato come effettuato direttamente dall’utente**

_Aggiornamenti_

Quando un amministratore effettua l’accesso come utente e crea un commento, il commento viene visualizzato come creato direttamente dall’utente, anziché dall’amministratore per conto dell’utente.

+++

+++**Aggiornamento di manutenzione del 23 marzo 2023**

I contenuti del pannello **[!UICONTROL Riepilogo] sono troppo ampi per il pannello**

_Documenti_

Quando un utente visualizza il pannello [!UICONTROL Riepilogo] per un documento, i contenuti sono troppo ampi per essere visualizzati nel pannello. Il pannello ora dispone di una barra di scorrimento orizzontale che l’utente deve utilizzare per visualizzare i contenuti del pannello [!UICONTROL Riepilogo]. Ciò si verifica perché il nome del file del documento non va a capo. Questo problema è limitato ai file con estensione HTML nel nome.

**Nuova versione di [!UICONTROL Desktop Proofing Viewer]**

_Bozza_

Per risolvere un problema relativo ai commenti in [!UICONTROL Desktop Proofing Viewer], ne è stata implementata una nuova versione.

Gli utenti che hanno già installato [!UICONTROL Desktop Proofing Viewer] riceveranno automaticamente questo aggiornamento.

Gli utenti possono anche scaricare manualmente la versione più recente. Per ulteriori informazioni, consulta [[!UICONTROL Installare Desktop Proofing Viewer]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=it).

* Versione precedente: 2.1.22
* Nuova versione: 2.1.23

+++

+++**Aggiornamento di manutenzione del 16 marzo 2023**

**Gli elementi di un elenco di controllo non vengono copiati quando si copia una scheda**

_Bacheche_

Quando si copia una scheda ad hoc (le schede collegate non possono essere copiate), gli elementi di un elenco di controllo non vengono copiati nella nuova scheda.

**Campo personalizzato mancante quando un problema viene convertito in progetto**

_Progetti_

Quando un utente converte un problema in un progetto utilizzando un modello, nel progetto non viene visualizzato un campo personalizzato presente nel problema. Questo problema riguarda solo gli utenti non amministratori.

**I messaggi personalizzati non vengono visualizzati nelle notifiche e-mail**

_Bozze_

Quando un utente condivide una bozza e aggiunge un messaggio personalizzato, questo non viene visualizzato nell’e-mail di notifica al destinatario. L’oggetto è il nome della bozza e il messaggio non viene visualizzato nell’e-mail.

+++

+++**Aggiornamento di manutenzione del 9 marzo 2023**

**Il livello di accesso non viene assegnato quando si riattiva l’utente**

_Utenti_

Quando un utente riattiva un utente disattivato e tenta di assegnargli un livello di accesso nella finestra [!UICONTROL Riattiva utente], il menu a discesa del livello di accesso non viene compilato quando l’utente digita e l’utente non può selezionare un livello di accesso. Se l’utente digita il livello di accesso e lo salva, tale livello di accesso non viene assegnato all’utente riattivato.

**Salvare la bozza di un commento nell’area [!DNL Goals]**

_[!DNL Workfront Goals]_

Ora, se esci dalla pagina [!UICONTROL Aggiornamenti] di un obiettivo mentre stai componendo un messaggio e quindi torni indietro, il messaggio viene mantenuto. Prima di questo aggiornamento, i commenti non inviati venivano eliminati.

+++

+++**Aggiornamento di manutenzione del 2 marzo 2023**

**Impossibile aggiungere schede quando viene applicato il raggruppamento**

_Bacheche_

Quando un utente visualizza una bacheca a cui si applica il raggruppamento e tenta di aggiungere una scheda, può inserire solo il nome della scheda. Gli altri campi della scheda sono disabilitati, compreso il pulsante [!UICONTROL Salva].

Se si cambia il raggruppamento in [!UICONTROL Nessuno], il problema rimane. Per ripristinare la possibilità di aggiungere una scheda, l’utente deve cambiare il raggruppamento in [!UICONTROL Nessuno] e quindi aggiornare la pagina.

**Schede collegate non aggiunte alle colonne in base allo stato**

_Bacheche_

Anche se vengono applicati i criteri di colonna per lo stato, le nuove schede collegate vengono visualizzate nella colonna più a sinistra e non in quella corrispondente allo stato.


**Il collegamento a un commento reindirizzerà alla pagina [!UICONTROL Dettagli]**

_Aggiornamenti_

Quando un utente segue un collegamento a un commento su un oggetto in Workfront, il flusso di aggiornamento viene caricato brevemente e l’utente viene reindirizzato all’area [!UICONTROL Dettagli] dell’oggetto. Questo può verificarsi se l’utente fa clic sul collegamento da un’e-mail o lo incolla nel browser.

Attualmente, questa modifica interessa solo gli oggetti Documento.

**Stampa riepilogo non si carica**

_[!UICONTROL Workfront Proof]_

Quando un utente cerca di caricare la pagina Stampa riepilogo, questa risulta sempre in caricamento, senza essere mai caricata.

+++

## Aggiornamenti di febbraio 2023

+++**Aggiornamento di manutenzione del 23 febbraio 2023**

**Il collegamento a un commento reindirizzerà alla pagina [!UICONTROL Dettagli]**

_Aggiornamenti_

Quando un utente segue un collegamento a un commento su un oggetto in Workfront, il flusso di aggiornamento viene caricato brevemente e l’utente viene reindirizzato all’area [!UICONTROL Dettagli] dell’oggetto. Questo può verificarsi se l’utente fa clic sul collegamento da un’e-mail o lo incolla nel browser.

Attualmente, questa modifica interessa solo gli oggetti Documento.

**L’utente non può modificare le proprie impostazioni di notifica**

_Utenti_

Quando un utente con licenza [!UICONTROL Lavoratore] tenta di modificare le proprie impostazioni di notifica, le opzioni di [!UICONTROL Notifica] non sono visibili nella finestra [!UICONTROL Modifica] e l’utente non può modificare le impostazioni.

+++

+++**Aggiornamento di manutenzione del 16 febbraio 2023**

**Più assegnazioni di team sulle bacheche**

_Bacheche_

Ora si possono assegnare più team a un’attività o a un problema su una bacheca e alla bacheca stessa.

**Aumento del limite di decadenza della scheda**

_Bacheche_

I limiti di tempo per la decadenza della scheda sono stati portati a 8 settimane / 60 giorni invece di 4 settimane / 30 giorni.

**La disattivazione pianificata non disattiva l’utente**

_Utenti_

Quando è pianificata la disattivazione di un utente e vengono superate la data e l’ora pianificate, l’utente non viene disattivato.

+++

+++**Aggiornamento di manutenzione del 9 febbraio 2023**

Campo **[!UICONTROL Punti storia] aggiunto a rapporti ed elenchi di attività e problemi**

_Report_

Il campo [!UICONTROL Punti storia] è ora disponibile per essere aggiunto a rapporti ed elenchi di attività o problemi. Si tratta di un campo modulo libero modificabile che non è legato alle ore pianificate o alle assegnazioni del team.

+++

+++**Aggiornamento di manutenzione del 8 febbraio 2023**

**Pulsante Filtro nella colonna di acquisizione**

_Bacheche_

La colonna di acquisizione su una bacheca ora include un pulsante **[!UICONTROL Aggiungi un filtro]** quando la colonna è vuota e non sono stati creati filtri. Il pulsante apre l’area di configurazione, in cui puoi aggiungere filtri per inserire attività e problemi nella colonna di acquisizione.

+++

+++**Aggiornamento di manutenzione del 2 febbraio 2023**

L’icona **[!UICONTROL Schede] viene visualizzata nel [!UICONTROL Menu principale] per impostazione predefinita**

_Bacheche_

L’icona [!UICONTROL Schede] ora appare nel [!UICONTROL Menu principale] per gli utenti che non dispongono di un modello di layout. Per impostazione predefinita, le schede sono incluse anche nel menu principale per tutti i nuovi modelli di layout creati. I modelli di layout esistenti non sono stati modificati.

**Impossibile salvare i modelli di e-mail**

_Configura_

Quando un utente tenta di creare o modificare un modello e-mail, il pulsante [!UICONTROL Salva] non risponde e l’utente non può salvare il modello.

+++

## Aggiornamenti di gennaio 2023

+++**Aggiornamento di manutenzione del 30 gennaio 2023**

**Sono state aggiunte scelte rapide da tastiera per le azioni comuni della scheda attività**

_Schede orario_

Sono state introdotte le seguenti scelte rapide da tastiera per le seguenti azioni frequenti all’interno di una scheda attività:

* Aggiungi riga (Comando+Opzione++ / Ctrl+Opzione++)
* Elimina riga (Comando+Opzione+- / Ctrl+Opzione+-)
* Fissa o sblocca un elemento di lavoro (Opzione+P / Opzione+P)
* Apri commento (Maiusc+F2 / Maiusc+F2)
* Salva commento (Comando+Invio / Ctrl+Invio)
* Espandi (Maiusc+Opzione+Freccia su/Maiusc+Alt+Freccia su)
* Comprimi (Maiusc+Opzione+Freccia giù/ Maiusc+Alt+Freccia giù)

L’area in cui vengono eseguite queste azioni deve essere evidenziata per poterle applicare.

**Icone nuove informazioni per schede orario, profili delle schede orario e preferenze della scheda orario**

_Schede orario_

>[!NOTE]
>
>Questo aggiornamento è stato rilasciato solo nell’ambiente Anteprima il 3 novembre 2022 ed è ora disponibile in Produzione.

Sono state aggiunte diverse icone di informazioni alle seguenti impostazioni:

* La casella di controllo “[!UICONTROL Can edit time]” (Può modificare l’ora) durante la creazione o la modifica di una scheda orario o di un profilo della scheda orario per indicare, se abilitata, che gli approvatori possono anche inviare, riaprire o modificare la scheda orario, a meno che l’amministratore non limiti queste azioni nell’area di [!UICONTROL Setup] (Configurazione) di [!UICONTROL Timesheet Preferences] (Preferenze della scheda orario).
* “[!UICONTROL Restrict timesheet editing to owners and admins]” (Limita la modifica della scheda orario a proprietari e amministratori) nell’area di [!UICONTROL Setup] (Configurazione) [!UICONTROL Timesheet &amp; Hour Preferences] (Preferenze scheda orario e ora) per indicare che, se disabilitata, i seguenti utenti possono anche modificare le schede orario: utenti con accesso amministrativo a schede orario e ore, approvatori di schede orario autorizzati a modificare l’ora e responsabili dei proprietari delle schede orario.

La funzionalità di queste impostazioni non è stata modificata e sono state aggiunte solo le icone delle informazioni per chiarire l’ambito delle impostazioni.

+++

+++**Aggiornamento di manutenzione del 26 gennaio 2023**

**Errore durante l’invio della richiesta da [!DNL Outlook]**

_Integrazioni_

Quando un utente cerca di inviare una richiesta con allegati da un indirizzo e-mail di [!DNL Outlook], uno o più allegati non vengono caricati e l’utente visualizza il seguente errore:

“[!UICONTROL Si è verificato il seguente errore: il file con handle xxxx non esiste.]”

Ciò si verifica solo quando viene eseguita un’assegnazione per la nuova richiesta, sia attraverso la coda di richieste che sia manualmente durante la creazione della richiesta.

**Nuova versione di Desktop Proofing Viewer**

_Verifica_

Per risolvere un problema di blocco in Desktop Proofing Viewer, ne è stata implementata una nuova versione. Gli utenti che hanno già installato Desktop Proofing Viewer riceveranno automaticamente questo aggiornamento.

Gli utenti possono anche scaricare manualmente la versione più recente. Per ulteriori informazioni, consulta [Installare Desktop Proofing Viewer](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=it).

* Versione precedente: 2.1.19
* Nuova versione: 2.1.20

**Gli utenti non possono modificare le proprie impostazioni**

_Utenti_

Quando un utente con una licenza Lavoro, Revisione oppure Richiesta tenta di modificare le proprie impostazioni, la finestra a comparsa visualizzata è vuota e l’utente non può apportare alcuna modifica. Per uscire dalla finestra a comparsa, l’utente deve aggiornare la pagina.

+++

+++**Aggiornamento di manutenzione del 19 gennaio 2023**

**È ora possibile condividere i filtri della colonna di acquisizione**

_Bacheche_

Quando la funzione della colonna di acquisizione è stata rilasciata in Bacheche, i filtri per la configurazione di tale colonna potevano essere visualizzati solo dall’utente che li aveva creati. Ora i filtri creati dall’utente possono essere condivisi con altri utenti o team.

**Funzionalità pin disponibile nel menu [!UICONTROL Altro]**

_Navigazione_

Le seguenti funzioni sono ora disponibili nel menu [!UICONTROL Altro] per i pin, nell’ambiente Produzione:

* Rinominazione dei pin
* Riordinamento dei pin all’interno del menu [!UICONTROL Altro]
* Spostamento di un pin dal menu [!UICONTROL Altro] (in questo modo, l’ultimo pin della barra di navigazione superiore viene spostato nel menu [!UICONTROL Altro])

+++

+++**Aggiornamento di manutenzione del 18 gennaio 2023**

**Espressioni con caratteri jolly non sono valide nei campi personalizzati**

_Moduli personalizzati_

Quando un utente utilizza un carattere jolly come \$$TODAY o $$NOW insieme a un modificatore (ad esempio “-30d”) in un campo personalizzato, la convalida non lo accetta come valido. I caratteri jolly senza modificatori sono considerati validi.

**[!UICONTROL Bilanciamento del carico di lavoro] mostra ore non associate a un/una progetto/attività/problema**

_[!UICONTROL Bilanciamento del carico di lavoro]_

Quando un utente visualizza il [!UICONTROL Bilanciamento del carico di lavoro], visualizza le ore registrate per un utente che non sono associate ad alcun progetto, alcuna attività o alcun problema, né vengono registrate come ore [!UICONTROL Generali]. Queste ore possono essere visualizzate solo nella visualizzazione a 4 settimane o a 6 settimane.

+++

+++Aggiornamento di manutenzione per **[!DNL Adobe Workfront Fusion] (Hot Fix) del 12 gennaio 2023**

**Errori 404 nei moduli [!DNL Workfront]**

_Workfront Fusion_

Quando è in esecuzione uno scenario, un modulo [!DNL Workfront] restituisce un errore 404.

Questo problema è stato segnalato nei seguenti moduli:

* [!UICONTROL Leggi un record]

+++

+++**Aggiornamento di manutenzione (Hot Fix) del 12 gennaio 2023**

**“[!UICONTROL Ops]”, si è verificato un errore durante la configurazione di un campo calcolato**

_Moduli personalizzati_

Quando un utente crea o modifica un campo calcolato in un modulo personalizzato e include un campo personalizzato nell’espressione del campo calcolato, l’espressione viene considerata non valida. Il pulsante [!UICONTROL Salva] è disattivato e l’utente non può spostarsi dal campo personalizzato. Inoltre, l’utente visualizza il seguente messaggio sotto il campo.

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront in modo che possiamo capire qual è stato il problema e risolverlo.]”

La rimozione del campo personalizzato dall’espressione consente all’utente di salvare e spostarsi dal campo.

**Impossibile impostare i livelli di accesso**

_Utenti_

Quando un utente tenta di modificare il livello di accesso di un altro utente, i livelli di accesso sono disattivati e non possono essere modificati. Ciò si verifica anche quando l’utente che tenta di apportare la modifica è un amministratore di sistema.

+++

+++**Aggiornamento di manutenzione del 12 gennaio 2023**

**Ctrl+F o Comando+F non funziona come previsto nei campi a discesa**

_Moduli personalizzati_

Quando si compila un modulo personalizzato e si cerca in un elenco a discesa utilizzando la scelta rapida Ctrl+F o Comando+F, quindi si tenta di passare all’istanza successiva della ricerca, l’elenco a discesa non passa a tale istanza ma ritorna all’inizio. Questo si verifica se il menu a discesa è impostato per consentire selezioni multiple.

La schermata **[!UICONTROL Edit Report] (Modifica report) è vuota**

_Report_

Quando un utente visualizza un report e tenta di modificarlo, viene visualizzata una schermata vuota e non può modificarlo.

**Le attività con rientro non mantengono il rientro**

_Attività_

Quando un utente visualizza un elenco di attività e fa rientrare un’attività, questa torna immediatamente al suo stato originale (non rientrato).

+++

+++**Aggiornamento di manutenzione del 5 gennaio 2023**

**Funzionalità pin disponibile nel menu [!UICONTROL Altro]**

_Navigazione_

Le seguenti funzioni sono ora disponibili nel menu [!UICONTROL Altro] per i pin, solo nell’ambiente Anteprima:

* Rinominazione dei pin
* Riordinamento dei pin all’interno del menu [!UICONTROL Altro]
* Spostamento di un pin dal menu [!UICONTROL Altro] (in questo modo, l’ultimo pin della barra di navigazione superiore viene spostato nel menu [!UICONTROL Altro])

**È stata rimossa la limitazione del Gruppo di progetti per l’aggiunta di utenti al team di progetto**

_Team_

Abbiamo rimosso la limitazione che richiedeva che gli utenti da aggiungere a un team di progetto fossero nel Gruppo associato al progetto. Ora puoi aggiungere qualsiasi utente attivo a un team di progetto, indipendentemente dai gruppi di appartenenza.

**Icone nuove informazioni per schede orario, profili delle schede orario e preferenze della scheda orario**

>[!NOTE]
>
>Questo aggiornamento è stato rilasciato nell’ambiente Anteprima il 3 novembre 2022 ed è ora disponibile in Produzione

_Workfront_

Sono state aggiunte diverse icone di informazioni alle seguenti impostazioni:

* Casella di controllo “Can edit time” (Può modificare l’ora) durante la creazione o la modifica di una scheda orario o di un profilo della scheda orario per indicare che, se abilitata, gli approvatori possono anche inviare, riaprire o modificare la scheda orario, a meno che l’amministratore non limiti queste azioni nell’area Timesheet Preferences (Preferenze della scheda orario) di Setup (Configurazione).
* “Restrict timesheet editing to owners and admins” (Limita la modifica della scheda orario a proprietari e amministratori) nell’area Timesheet &amp; Hour Preferences (Preferenze scheda orario e ora) di Setup (Configurazione) per indicare che, se disabilitata, anche i seguenti utenti possono modificare le schede orario: utenti con accesso amministrativo a schede orario e ore, approvatori di schede orario autorizzati a modificare l’ora e responsabili dei proprietari delle schede orario.

La funzionalità di queste impostazioni non è stata modificata e sono state aggiunte solo le icone delle informazioni per chiarire l’ambito delle impostazioni.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sui precedenti aggiornamenti di manutenzione sono disponibili qui:

* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2022](2022-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2021](2021-updates.md)
