---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: f27dfd8dbe3e0c862f84edfe5b2deab5f139eb50
workflow-type: tm+mt
source-wordcount: '2223'
ht-degree: 85%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2023.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. L’assistenza [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, vedi [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di marzo 2023

+++**(Pianificato) Aggiornamento di manutenzione del 16 marzo 2023**

**Elementi dell’elenco di controllo non copiati durante la copia di una scheda**

_Bacheche_

Quando si copia una scheda ad hoc (le schede collegate non possono essere copiate), le voci dell’elenco di controllo non vengono copiate nella nuova scheda.

**[!UICONTROL Riepilogo] il contenuto del pannello è troppo ampio**

_Documenti_

Quando un utente visualizza [!UICONTROL Riepilogo] per un documento, il contenuto è troppo largo per essere visualizzato nel pannello. Il pannello ora dispone di una barra di scorrimento orizzontale e l’utente deve scorrere in orizzontale per visualizzare [!UICONTROL Riepilogo] contenuti del pannello. Ciò si verifica perché il nome del file del documento non viene racchiuso. Questo problema è limitato al file il cui nome file ha estensione HTML.

**Campo personalizzato mancante quando il problema viene convertito in progetto**

_Progetti_

Quando un utente converte un problema in un progetto utilizzando un modello, nel progetto non viene visualizzato un campo personalizzato corrispondente al problema. Questo problema riguarda solo i non amministratori.

**I messaggi personalizzati non vengono visualizzati nelle notifiche e-mail**

_Bozze_

Quando un utente condivide una bozza e aggiunge un messaggio personalizzato, questo non viene visualizzato nell’e-mail di notifica al destinatario. L’oggetto è il nome della bozza e il messaggio non viene visualizzato nell’e-mail.

+++

+++**Aggiornamento di manutenzione del 9 marzo 2023**

**Il livello di accesso non viene assegnato durante la riattivazione dell&#39;utente**

_Utenti_

Quando un utente riattiva un utente disattivato e tenta di assegnargli un livello di accesso nella finestra [!UICONTROL Riattiva utente], il menu a discesa del livello di accesso non viene compilato quando l’utente digita e l’utente non può selezionare un livello di accesso. Se l’utente digita il livello di accesso e lo salva, tale livello di accesso non viene assegnato all’utente riattivato.

**Salvare la bozza di un commento in [!DNL Goals] area**

_[!DNL Workfront Goals]_

Ora, quando ci si allontana dal [!UICONTROL Aggiornamenti] pagina di un obiettivo durante la composizione di un messaggio, il messaggio viene mantenuto quando si torna indietro. Prima di questo aggiornamento, il commento non inviato sarebbe stato eliminato.

+++

+++**Aggiornamento di manutenzione del 2 marzo 2023**

**Impossibile aggiungere schede quando viene applicato il raggruppamento**

_Bacheche_

Quando un utente visualizza una bacheca a cui si applica il raggruppamento e tenta di aggiungere una scheda, può inserire solo il nome della scheda. Gli altri campi della scheda sono disabilitati, compreso il pulsante [!UICONTROL Salva].

Se si cambia il raggruppamento in [!UICONTROL Nessuno], il problema rimane. Per ripristinare la possibilità di aggiungere una scheda, l’utente deve cambiare il raggruppamento in [!UICONTROL Nessuno] e quindi aggiornare la pagina.

**Schede collegate non aggiunte alle colonne in base allo stato**

_Bacheche_

Anche se i criteri di colonna vengono applicati per lo stato, le nuove schede collegate vengono visualizzate nella colonna più a sinistra e non nella colonna che corrisponde al relativo stato.


**Il collegamento a un commento reindirizzerà alla pagina [!UICONTROL Dettagli]**

_Aggiornamenti_

Quando un utente segue un collegamento a un commento su un oggetto in Workfront, il flusso di aggiornamento viene caricato brevemente e l’utente viene reindirizzato all’area [!UICONTROL Dettagli] dell’oggetto. Questo può verificarsi se l’utente fa clic sul collegamento da un’e-mail o lo incolla nel browser.

Attualmente, questa modifica interessa solo gli oggetti Documento.

**Stampa riepilogo non viene caricato**

_[!UICONTROL Bozza Workfront]_

Quando un utente cerca di caricare la pagina Stampa riepilogo sembra che la pagina sia in fase di caricamento, ma non si carica mai.

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

Campo **[!UICONTROL Punti della storia] aggiunto a elenchi di attività e di problemi e rapporti**

_Report_

Il campo [!UICONTROL Punti della storia] è ora disponibile per essere aggiunto a elenchi e report di attività o problemi. Si tratta di un campo modulo libero modificabile che non è legato alle ore pianificate o alle assegnazioni del team.

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
